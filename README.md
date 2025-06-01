<p align="center">
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
- [Devops]
    -> Boards
    -> Repos


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
  A abordagem para a solução e apresentação é baseada em atividades, que serão descritas abaixo.

  <h3>Atividade 1 </h3>
  1) Aqui iremos fazer a configuração do Azure Devops, para tal precisamos definir algumas configurações, como organização
  , projeto, repositorio , branch, ou seja, precisamos definir a nossa estrutura de repositório. Abaixo iremos acompanhar a criação

  Imagens da criação da organização
  <p align="left">
    <img width="500" src="asset/imagens/01_Demonstracao_oragnizacao.JPG">
  </p>

  Logado na organização
  <p>&emsp;&nbsp; Vemos que já temos um projeto criado, que e o "dio azure devops projects"</p>
  <p align="left">
    <img width="500" src="asset/imagens/02_Logado_na_organizacao.JPG">
  </p>

  <p>&emsp;&nbsp; Vamos fazer um overview nas onfigurações da organização</p>
  <p align="left">
    <img width="500" src="asset/imagens/03_Area_setup_organizacao.JPG">
  </p>

  <p align="left">
    <img width="500" src="asset/imagens/04_Area_setup_org_ajuste_Reposositorio.JPG">
    Em Repos, podemos ver que podemos habilitar e definir o nome de uma branch inicial em cada repositorio, na imagem vemos o exemplo
    da troca de "main" para "master"
  </p>


  <h3>Atividade 2 </h3>
  1) Neste ponto vemos que o projeto já esta pronto para uso, iremos navegar em algumas funcionalidades.

  <p> &emsp;&nbsp; Projeto </p>

  <p align="left">
    <img width="600" src="asset/imagens/05_Projeto_Overview.JPG">
  </p>

   <p><pre> Overview do Projeto, como descrição, funcionalidades</pre></p>

  <p align="left">
    <img width="500" src="asset/imagens/06_Projeto_Setup_Overview.JPG">
  </p>

   <p> &emsp;&nbsp;&nbsp;&nbsp; Fizemos alguns experimentos na imagem vemos que podemos configurar funcionlidades do projeto, neste caso, desabilitamos : Pipelines, Test Plan, ArtFacts, pois não serão usados no projeto.  </p>
   
   <p align="left">
    <img width="500" src="asset/imagens/06_02_Projeto_Setup_Overview.JPG">
  </p>

  <h3>Atividade 3 </h3>
  1) Aqui iremos acompanhar a Configuracao do repositorio do projeto **Repos**

  <p><pre> &emsp;&nbsp;
    <b>Informações importantes:</b>
         Clone to your computer - Aqui vemos a url para poder colocar no git local no computador e trabalhar no projeto 
         Podemos ver que podemos gerar as credencias do git. Caso o projeto demanda esta ação

         Push an existing repository from comand line - Aqui vemos como podemos conectar 

         Import a repository - Temos a opção de importar um repositorio existente.

         Initialize master branck wiht REAME or gitignore - Aqui vemos que podemos criar tanto um arquivo README.md ou o arquivo gitignore, cabe ao usuario escolher.
  </pre></p>

  <p align="Left">
    <p> &emsp;&nbsp; Tela configuração Repos</p>
    <img width="600" src="asset/imagens/07_Projeto_Setup_Repos.JPG">
  </p>

2) Vamos agora acompanhar a criação de 2 issues  que estão na área de backlog.

  <p align="Left">
    <p> &emsp;&nbsp; Projeto e o Board apresentado, com 2 issues, que estão alocados na área de Backlog do projeto</p>
    <img width="600" src="asset/imagens/09_Projeto_Definindo_Backlog.JPG">
  </p>

  <p align="Left">
    <p> &emsp;&nbsp; Abrimos um Issue para verificar as informações pertinentes. Observamos que este Issue está atribuido a um usuário e agora já é um Work Item</p>
    <img width="600" src="asset/imagens/10_Projeto_Board_Criando_Workitems.JPG">
  </p> 

  <p align="Left">
    <p> &emsp;&nbsp; Abrimos outro  Issue para verificar as informações pertinentes. Observamos que este Issue está atribuido a um outro usuário e também é um Work Item</p>
    <img width="600" src="asset/imagens/11_Projeto_Board_Criando_Isue.JPG">
  </p>

3) Desenho da Sprint

  <p align="Left">
    <p> &emsp;&nbsp;Acompanhamos na imagen abaixo Sprint 1 com tasks em To Do e 2 issue fora da sprint </p>
    <img width="600" src="asset/imagens/12_Projeto_Verificando_Sprint.JPG">
  </p>

4) Querys 
    
    <p> &emsp;&nbsp;As querys são recursos bem importantes, com elas podemos selecionar uma gama de informações a respeito, dos Issues, Tasks e Epic.</p> 
    <p> &emsp;&nbsp; Gerando todo o suporte para a equipe do projeto e stakeholders.</p>

  <p align="Left">
    <p> &emsp;&nbsp; Área de criação e execução das Querys </p>
    <img width="600" src="asset/imagens/13_Projeto_Board_Criando_querys.JPG">
  </p>
  <p> &emsp;&nbsp; Temos ainda a parte de Delivery Plan e Analitics view, que neste momento não iremos aprofundar, pois o objetivo era ver a integração DEVOPS x Data Factory, vamos seguir então.</p>
    

  <h3>Atividade 4 </h3>
  1) Agora vamos começar a configuração do nosso Data Factory.
  
  <p> &emsp;&nbsp; Bem, antes queremos lembrar que temos 2 forma de configurar o git no Data factory, que são: </p>
 
  <p align="Left">
     <p> &emsp;&nbsp;&nbsp;&nbsp; 1) No momento da criação  </p>
    <img width="600" src="asset/imagens/20_01_Azure_Data_Factory_config_git_criacao.JPG">
   </p>

  <p align="Left">
     <p> &emsp;&nbsp;&nbsp;&nbsp; 2) Ou configurando o Data factory depois pelo Studio </p>
    <img width="600" src="asset/imagens/21_Azure_Data_Factory_Manage_Git_Config.JPG">
   </p>
   <p> &emsp;&nbsp;Em nosso projeto iremos por esta abordagem, visto que temos um Data Factory pronto : adf-DIO-HandsOn</p>

 2) Configurando o Git no Data Factory adf-DIO-HandsOn.

   <p align="Left">
     <p> &emsp;&nbsp;&nbsp;&nbsp; Vemos a tela de configuracao do Data factory  </p>
    <img width="600" src="asset/imagens/22_Azure_Data_Factory_Manage_Git_Config_selec_tipo_rep.JPG">
   </p>
   <p> &emsp;&nbsp; <pre>Informações necessárias: 
                         Escolha do tipo de repositorio, git ou azure devops git, no nosso caso iremos escolher o azure devops git.
                         Assinatura - Podemos escolher a assinatura que desejamos plugar o git.   
   </pre></p>

   <p align="Left">
     <p> &emsp;&nbsp;&nbsp;&nbsp; Detalhes da configuração.  </p>
    <img width="600" src="asset/imagens/23_Azure_Data_Factory_Manage_Git_Config_Rep_Project.JPG">
   </p>
   <p> &emsp;&nbsp; <pre>Informações necessárias: 
                         Precisamos pegar todas a informaçõe no Azure Devops Git para poder preencher os itens solicitados.
   </pre></p>

   <p align="Left">
     <p> &emsp;&nbsp;&nbsp;&nbsp; Sucesso na configuracao.  </p>
    <img width="600" src="asset/imagens/24_Azure_Data_Factory_Manage_Git_Config_Rep_Overview.JPG">
   </p>
   <p> &emsp;&nbsp; <pre> Confirmação de Sucesso na configuração: 
                         Precisamos pegar todas a informaçõe no Azure Devops Git para poder preencher os itens solicitados.
   </pre></p>
  
<h3>Atividade 5 </h3>

  1) Vamos agora em nosso Data Factory configurar um Pipeline
  <p> &emsp;&nbsp; O objetivo e depois verificar em no Devops Azure Git as pastas criadas dentro de nossa branch </p>
  <p align="Left">
    <img width="600" src="asset/imagens/30_Devops_Azure_Verificacao_branch_main.JPG">
  <p>

  <p> &emsp;&nbsp; <pre> Agora vamos em no Devops Azure Git 
                         Iremos observar em no repositorio do projeto a criação da pastas :
                         factory
                         pipeline
                         e ainda o arquivo Readme.md 
                        Com isto comprovamos que estamos controlando a versão de todos os ajustes e criações feitas em nosso Data Factory
   </pre></p>

  <p align="Left">
    <img width="600" src="asset/imagens/30_Azure_Data_Factory_Criacao_Pipeline_Atualizando_DEVOPS.JPG">
  <p>

  <p align="Left">
     <p> &emsp;&nbsp; <pre> Commits
                         Podemos aconpanhar os momentos de criação e ajustes de nosso pipeline no Data Factory, com isto provamos 
                         que estamos controlando as versões em nosso git do desenvolvimento no Data Factory
   </pre></p>
    <img width="600" src="asset/imagens/31_Devops_Azure_Verificacao_branch_main_commits.JPG">
  <p>


## Conclusão:
  <p><pre>&emsp;&nbsp; Aqui pudemos explorar um pouco do processo de criação e configuração do Devops Azure Git em um recurso do Microsodt Azure, que no caso foi o Data Factory . 
                       O nosso objetivo foi explorar o básico deste processo e demonstrar a viabilidade e praticidade.
                       Com isto concluimos o nosso objetivo de demonstrar estes recursos.
  </pre></p>

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