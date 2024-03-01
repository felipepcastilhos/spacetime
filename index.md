# HTML

-imgs SVGs são vetorizadas

# CSS

-Keyframes para fazer leves animações

# GIT

No vscode: view > Terminal(ctrl+shift+´):

-Iniciando o git (repositorio) no projeto com: "git init";
-Adicionando todos os arquivos modificados ao stage: "git add name_file" ou "git add ." para todos arquivos na área de stage; (arquivos verdes com A);
-Criando um ponto na história: git commit -m “initial commit” // -m para adicionar flag de mensagem curta e objetiva no commit;

{
-Criando um novo repositório no Github e atribuindo commit pelo git:
--Cria repositorio online no Github, no campo "...or create a new repository on the command line" copia a linha "git remote add origin https://github.com/felipepcastilhos/spacetime.git" para salvar indicação diretório remoto e cola no terminal (-Adicionando origem do repositório remoto.);
--"git push -u origin main" (vai salvar no diretório remoto(origin) e vai deixar flag(-u) neste diretório remoto para futuros "git push", main é a minha branch) (-Enviando o projeto para o repositório remoto.);
}

-Para limpar o terminal no linux, usar comando "clear" no terminal, no mac seria o mesmo comando e no Windows "cls";

## Como atualizar o projeto pelo Git

{
-Fazendo modificação, criando um novo commit(ponto na história), neste caso criando um README:
--primeiro levar os arquivos para a area de stage, para preparar para o commit: "git add .";
--criar nosso commit(ponto na história): "git commit -m "add readme with project preview"; //ate então o ponto na história é apenas no computador local;
--bom verificar antes do push, para mostrar os pontos na histórias existentes no computador local pelo git: "git log"; Para sair do log, pressionar "q";
--agora será enviado para o github: "git push" //como o comando utilizado anteriormente com "git push -u origin main", o "-u" salvou diretório origin com flag
}

## Como atualizar o projeto pela interface VSCode

{
--"Ctrl+shift+g";
--no campo "Message ..." preencher com "Add project about" (exemplo);
--Clicar em Commit;
--Clicar em Syn Changes;
}
