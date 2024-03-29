# Treinamento

Seja bem vindo ao treinamento de novos voluntários para o projeto de desenvolvimento de software da Comunidade [Zen-Budista Daissen](https://daissen.org.br/).

## Formações

A Equipe de voluntários elaborou uma formação para desenvolvedores de software que desejam colaborar com o projeto. A formação é dividida em três áreas de conhecimento: Desenvolvedor Backend, Desenvolvedor Frontend e Gerência de Projetos.

### Conhecimento Comum
  * [Intro: Informações Gerais](introducao.md)
  * [Markdown: Sintaxe de Documentação](markdown.md) :constuction:
  * [VS Code: Ambiente de Programação](vscode.md) :constuction:
  * [Git: Versionamento de Código](git.md) :constuction:
  * [Github: Ambiente de Colaboração](github.md) :constuction:
  * [Docker: Distribuição de Software](docker.md) :constuction:

### Desenvolvedor Backend
  * [IntroBack: Instalação do Backend](instalacao_do_backend.md)
  * [NodeJS: Programação Javascript no Servidor](nodejs.md) :constuction: 
  * [Express: Framework para Aplicações Backend](express.md) :constuction:

### Desenvolvedor Frontend
  * [IntroFront: Instalação do Frontend](intro_frontend.md) :constuction:
  * [IntroJSWeb: Javascript no Navegador](intro_js_web.md) :constuction:
  * [React: Framework para Interface Web](react.md) :constuction:
  * [ReactNative: Framework para Interface Móvel](react_native.md)
 
### Gerência de Projetos
  * [GithubProjects: Gerência de Projetos no Github](github_projects.md) :constuction:

## Sugestão de Fluxo com Estimativa de Horas

```mermaid
flowchart LR
  Intro("Intro (1h)") --  "DB + DF"  --> IntroBack
  Intro -- "DB + DF + GP" --> Markdown
  IntroBack("IntroBack (2h) - ") -- "DB + DF + GP" --> VSCode 
  VSCode("VSCode (2h)") -- "DB + DF" --> Git("Git (2h)")
  VSCode -- "DB + DF + GP" --> Github("Github (2h)")
  VSCode -- "DB + DF" --> Docker("Docker (2h)")
  IntroBack -- "DB + DF" --> NodeJS
  NodeJS("NodeJS (20h)") -- "DB + DF" --> IntroFront("IntroFront (2h)")
  NodeJS -- "DF" --> IntroJSWeb
  IntroJSWeb("IntroJSWeb (10h)") -- "DF" --> React
  React("React (20h)") -- "DF" --> ReactNative("ReactNative (30h)")
  Markdown("Markdown (2h)") -- "GP" --> GithubProjects("GithubProjects (2h)")
  NodeJS -- "DB" --> Express("Express (10h)")
```