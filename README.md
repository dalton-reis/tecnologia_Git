# tecnologia_Git

Estudando Versionador de Códigos (CVS/SVN/GIT).  

## Release: 0.0.1

## MarginNote

<marginnote3app://note/1467C880-2120-4578-8085-B9B94313CFE2>  

## VSCode Extensões

Mostra o uso de algumas extensões, entre elas o GitFlow:  
  Original: <https://www.youtube.com/watch?v=7B6AtSMvX9k>  
  Local: [VSCodeGIT_extensoes.mp4](VSCodeGIT_extensoes.mp4 "VSCodeGIT_extensoes.mp4")  
Indica um site que explica uma metodologia para criar Branches:  
  Original: <https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html>  
  Local: <marginnote3app://note/35D45FD0-0AD9-4D25-A781-E1CBDBF04EE4>

## Passos

- criar uma pasta com nome do repositório.  
- iniciar o GitLocal:  
    $ git init  
- abrir VSCode na pasta do projeto.  
- Command Palette: >GitFlow: Initialize repository for gitflow.  
- no Branch "develop"  
  - Command Palette: >GitFlow: Feature start.  
    - fazer os novos ajustes.  
  - Command Palette: >GitFlow: Feature finish.  
      vai trazer para branch developer os ajustes, e vai "matar" branch Feature.  
  - Command Palette: >GitFlow: Release start.  
    - registrar informações da nova Release.  
  - Command Palette: >GitFlow: Release finish.  
      vai trazer para branch developer e master todos os ajustes, e vai "matar" branch Release.  

Obs.: as branch Feature e Release ficam só no GitLocal, e as branch Develop e Master no GitLocal e GitRemoto.  
