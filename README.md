<p align= "center">
  <img src=".github/preview.png" alt="Demonstração do projeto" width="100%" />
</p>
<!-- subindo imagem pro github no doc README, pelo git -->

## 🖥️ Projeto

<!-- ## comando markdown(.md) semelhante ao "h2", #="h1", etc -->

Esse é um projeto Web responsivo de uma cápsula do tempo para exibir memórias em uma linha do tempo.

## 🚀 Tecnologias

Esse projeto foi desenvolvido durante o NLW da Rocketseat com as seguintes tecnologias:

- HTML
- CSS
- Git e Github

## 🏷️ Layout

Você pode visualizar o layout do projeto através
[desse link](https://www.figma.com).

<!-- criando link genérico em um texto -->

## HTML

-imgs SVGs são vetorizadas

## CSS

-Keyframes para fazer leves animações

# GIT

## Iniciando New Repo

- No vscode: view > Terminal(ctrl+shift+´):
- Iniciando o git (repositorio) no projeto com: "git init";\
- Adicionando todos os arquivos modificados ao stage: "git add name_file" ou "git add ." para todos arquivos na área de stage; (arquivos verdes com A);\
- Criando um ponto na história: git commit -m “initial commit” // -m para adicionar flag de mensagem curta e objetiva no commit;\

{\

- Criando um novo repositório no Github e atribuindo commit pelo git:\
- Cria repositorio online no Github, no campo "...or create a new repository on the command line" copia a linha "git remote add origin https://github.com/felipepcastilhos/spacetime.git" para salvar indicação diretório remoto e cola no terminal (-Adicionando origem do repositório remoto.);\
- "git push -u origin main" (vai salvar no diretório remoto(origin) e vai deixar flag(-u) neste diretório remoto para futuros "git push", main é a minha branch) (-Enviando o projeto para o repositório remoto.);\  
  }\

- Para limpar o terminal no linux, usar comando "clear" no terminal, no mac seria o mesmo comando e no Windows "cls";\

## Como atualizar o projeto pelo Git

- Se precisar deletar um arquivo do repo: "git rm nameFile.txt"
- Se precisar definir default branch: "git config --global init.defaultBranch main"
- Fazendo modificação, criando um novo commit(ponto na história), neste caso criando um README:\
- OBS.: if it needs to change/update the "Remote Origin" use: "git remote set-url origin https://github.com/felipepcastilhos/spacetime.git

- Primeiro levar os arquivos para a area de stage, para preparar para o commit: "git add .";\
- Criar nosso commit(ponto na história): "git commit -m "add readme with project preview"; //ate então o ponto na história é apenas no computador local;\
- Bom verificar antes do push, para mostrar os pontos na histórias existentes no computador local pelo git: "git log"; Para sair do log, pressionar "q";\
- Agora será enviado para o github: "git push" //como o comando utilizado anteriormente com "git push -u origin main", o "-u" salvou diretório origin com flag\

## Como atualizar o projeto pela interface VSCode

- "Ctrl+shift+g";\
- No campo "Message ..." preencher com "Add project about" (exemplo);\
- Clicar em Commit;\
- Clicar em Syn Changes;\
