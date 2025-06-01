<p align="right">
    <img width="250" src="asset/imagens/iniciorapido.jpg">
</p>
<p align="left"><h1> # DIO-Azure-Devops  </h1></p>
<p align="center"><h1>BootCamp : Azure Databricks </h1></p>


# Projeto : Devops Azure


 > **Objetivo:** Este repositório foi desenvolvido durante o curso BootCamp Azure Databricks na plataforma da [DIO](https://dio.me)

Projeto com o objetivo de gerar evidência do conhecimento absorvido no treinamento de utilização da plataforma Azure Devops .

Iremos configurar um Devops Azure e a sequencia vamos criar um  Azure Data Factory e verificar todo o processo de versionamento no Azure Devops durante a configuração do Data Factory.
Iremos documentar neste repositorio os passos, para comprovação de entendimento e conhecimento.


## 💻 Tecnologias utilizadas no projeto

- [Github] 
- [Azure]
    -> Data Factory
    -> Storage 
- [Devops]

##    Desciption

Entendendo o Desafio
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎

Como entregar esse projeto?
Chegou a hora de você construir um portfólio ainda mais rico e impressionar futuros recrutadores, para isso é sempre importante mostrar os resultados do seu esforço
e como você os obteve deixando claro o seu racional, para isso faça da seguinte maneira:

1. Crie um novo repositório no github com um nome a sua preferência
2. Crie um arquivo chamado readme.md;
3.    Deixe alguns prints ;
4.    Descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo;
5.    Após a IA analisar suas sentenças
6. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

 
## ✨ Solution
  A abordagem para a solução e apresentação é baseada em 4 atividades, que serão descritas abaixo.

  <h3>Atividade 1 </h3>
  1) Aqui iremos fazer a configuração do Azure Devops, para tal iremos definir o Repos e ...., estes serão demosntrados nos próximos passos.
  
  </p><pre>Dados:
  Subscription: Azure subscription 1
  Workspace name : databircks_000001
  Managed Resource Group name: databricks-000001-managed
  Region: East US</pre></p>
  
  Imagens da criação
  <p align="left">
    <img width="500" src="asset/imagens/01_criacao workspace databricks.JPG">
  </p>

  <p align="left">
    <img width="500" src="asset/imagens/02_criacao workspace databricks_detalhes.JPG">
  </p>

  <p>&emsp;&nbsp; Agora navegando para o ambiente databricks para iniciar as configurações </p>
  <p align="center">
    <img width="500" src="asset/imagens/03_Ambiente Databricks.JPG">
  </p>

  <h3>Atividade 2 </h3>
  1) Neste desafio dentro do Databricks, iremos criar um cluster, neste teremos os nossos dados e notebooks para analise dos dados.
  <p> &emsp;&nbsp; CRIAÇÃO CLUSTER </p>

  <p align="left">
    <img width="600" src="asset/imagens/05_Create_Cluster_OK_Databricks01_Computer_21.JPG">
  </p>

   <p> &emsp;&nbsp;&nbsp;&nbsp; Fizemos experimentos criandos outros clusters em outra workspaces, a seguir veremos estas criações. </p>
   <p><pre> WorkSpace : databricks_000002
            Cluster: Alvaro Computer 4 Cluster
   </pre></p>
  <p align="right">
    <img width="500" src="asset/imagens/05_1_Create_Cluster_OK_Databricks02_Computer_4.JPG">
  </p>

   <p><pre> WorkSpace : databircks_000003
            Cluster: Alvaro Computer 5 Cluster
   </pre></p>
  <p align="right">
    <img width="500" src="asset/imagens/05_2_Create_Cluster_OK_Databricks03_Computer_5.JPG">
  </p>


  <h3>Atividade 3 </h3>
  1) Neste desafio iremos usar o Spark para fazer analise de dados.
  <p><pre> &emsp;&nbsp;
    <b>Ações:</b>
         Importar arquivo products.csv
         Inserir no Catalogo, com isto esta planilha será transformada em uma tabela no schema default do banco.
         No Catalogo, iremos criar um notebook.
         No notebook iremos:
         * Faremos uma alteração do nome da tabela
         * Faremos um comando SQL para visualizar o dados da tabela 
         * E usaremos o recurso de visualização para poder ver os dados da tabela recuperados</pre></p>

  <p align="Left">
    <img width="600" src="asset/imagens/06_Processo_upload_file_table_product.JPG">
    <p> &emsp;&nbsp; Tela para busca de opção de carga de dados</p>
  </p>

  <p align="Left">
    <img width="600" src="asset/imagens/07_Processo_upload_file_table_product_detail.JPG">
    <p> &emsp;&nbsp; Tela para seleção do arquivo a ser carregado, ação de drag and drop</p>
  </p>

  <p align="Left">
    <img width="600" src="asset/imagens/08_Processo_upload_table_products_details.JPG">
    <p> &emsp;&nbsp; Após arquivo selecionado e feita a demonstração do que foi carregado, podemos aqui corrigir, descartar ou seguir com a 
    criação.</p>
  </p>

  <p align="Left">
    <img width="600" src="asset/imagens/09_Processo_Create_Sucess_table_products.JPG">
    <p> &emsp;&nbsp; Aqui confirmamos a criação da tabela e vemos alguns detalhes da tabela criada</p>
  </p>

<p align="Left">
    <img width="600" src="asset/imagens/10_Processo_Create_Sucess_table_products_SampleData.JPG">
    <p> &emsp;&nbsp; Alguns detalhes da tabela products carregada</p>
  </p>

 <p align="Left">
    <img width="600" src="asset/imagens/11_Test_Conection_table_products_Sql_all_data.JPG">
    <p> &emsp;&nbsp; Aqui vemos no notebook criado um select para apresentar os dados da tabela products</p>
  </p>

 <p align="Left">
    <img width="600" src="asset/imagens/12_Usando_Sql_alterar_table_selecionar_data.JPG">
    <p> &emsp;&nbsp; Aqui constatamos que o nome da tabela estava incorreto e procedemos um comando de DDL para alterar o nome da tabela de procucts para products. <p> &emsp;&nbsp; Após fizemos um novo select para verificar se a tabela havia sido renomeada no schema default do banco.</p>
  </p>

 <p align="Left">
    <img width="600" src="asset/imagens/14_Usando_Sql_Visualizacao_Especifica.JPG">
    <p> &emsp;&nbsp; Agora vamos gerar uma visualização dos dados, para tal escolhemos a ação de "vizualization"</p>
  </p>

 <p align="Left">
    <img width="600" src="asset/imagens/15_Usando_Sql_Definindo_Visualizacao_Especifica.JPG">
    <p> &emsp;&nbsp; Agora vemos as propriedades dos dados que estão sendo visualizados, tais como: 
    <p> &emsp;&nbsp;&nbsp; Tipo, exio x e y, agrupamento</p>
  </p>

 <p align="Left">
    <img width="600" src="asset/imagens/16_Usando_Sql_Criada_Visualizacao.JPG">
    <p> &emsp;&nbsp; Ao final da configuracao da visualização, temos este resultado.: 
    <p> &emsp;&nbsp;&nbsp; Podemos ver que pode ainda filtrar e editar a visalização</p>
  </p>

  <h3>Atividade 4 </h3>
  1) Neste desafio iremos ver que no notebook podemos ter tanto codificação de SQL quanto um linguagem, que no caso usamos pyhton.
  <p> &emsp;&nbsp; Visualizando codigo python no notebook </p>

 <p align="Left">
    <img width="600" src="asset/imagens/13_Usando_Python_selecionar_visualizar_data.JPG">
    <p> &emsp;&nbsp; Vemos um codigo pyhton que foi gerado apartir de um prompt</p>
       <pre> &emsp;&nbsp; Neste vemos que foi feito seguido o seguinte prompt:
        &emsp;&nbsp;&nbsp;&nbsp; Importe a biblioteca pandas
        &emsp;&nbsp;&nbsp;&nbsp; Carregue a tabale products em um dataframe
        &emsp;&nbsp;&nbsp;&nbsp; Faça uma seleção no dataframe para apresentar registros que tenham no campo Category conteúdo "Mount"
        &emsp;&nbsp;&nbsp;&nbsp; Apresente a saida.
        </pre>
  </p>
  
  <h3>Atividade 5 </h3>
  1) Agora temos que fazer um CLEAR.
  <p> &emsp;&nbsp; CLEAR </p>
  <p> &emsp;&nbsp;&nbsp;&nbsp; Seria a parada do nosso cluster para evitar gerar gastos, pode serfeito ainda a deleção, para efetivamente não consuma recursos.</p>

   <p align="Left">
    <img width="600" src="asset/imagens/17_Clear_Cluster_Alvaro_Computer_21_Cluster_Workspace_databircks_000001.JPG">
    <p> &emsp;&nbsp; Verificamos o cluster parado
  </p>

  <p>2) Antes de paramos o cluster fizemos o exporte do json, para posterior necessidade de recriação do mesmo.
  abaixo vemos os detalhes do cluster e da criação.</p>

&emsp;&nbsp;&nbsp;&nbsp;[Create do Cluster pelo Json](asset/databricks_cluster/Create_databricks_000001.json)

&emsp;&nbsp;&nbsp;&nbsp;[Detalhes do Jso](asset/databricks_cluster/databricks_000001.json)

<p> 3) Por fim deixo aqui o notebook, para quem desejar olhar o codigo usado</p>
<p>&emsp;&nbsp; Esta no formato ipynb </p>

&emsp;&nbsp;&nbsp;&nbsp;[Notebook](asset/notebook/Notebook_analise_Products.ipynb)

## Conclusão:
  <p>Aqui tivemos uma pequena viagem entre o mundo Microsoft Azure e seus recursos e o recurso Databricks, pudemos ver a interface entre os produtos e a sua aplicação e exemplificação de uso.</p>

## 👨‍💻 Desenvolvedor

<p>
    <p>&nbsp&nbsp&nbspAlvaro Monteiro<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/Alvaro-MSJR">
    GitHub</a>&nbsp;|&nbsp;
    <a href="www.linkedin.com/in/alvaro-monteiro-silva">LinkedIn</a>
&nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>

---
⌨️ conteúdo por [Alvaro Monteiro](https://github.com/Alvaro-MSJR)