# Treinamento
Repositório para treinamento de novos voluntários

## Formações

CC. Conhecimento Comum
  * Intro: [Introdução](introducao.md)
  * Markdown: [Sintaxe de Documentação](markdown.md)
  * VS Code - [Ambiente de Programação](vscode.md)
  * Git - [Versionamento de Código](git.md)
  * Github - Github
  * Docker - Docker

DB. Desenvolvedor Backend (DB)
  * IntroBack - [IntroBack: Instalação do Backend](instalacao_do_backend.md)
  * NodeJS - [Programação Javascript em NodeJS](nodejs.md)
  * Express - [Framework Express](express.md)

DF. Desenvolvedor Frontend (DF)
  * IntroFront - Instalação do Frontend
  * IntroJSWeb - Javascript no Navegador
  * React - React
  * ReactNative - React Native
 
GP. Gerência de Projetos
  * GithubProjects - Github Projects

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