MEU PRIMEIRO SISTEMA NO GIT

1. CRIADA A PASTA "AWAX - B7WEB"

2. CRIADO O REPOSITÓRIO A PARTIR DO CMD. 
PELO COMANDO: git init

3. CRIANDO PRIMEIRO ARQUIVO README.md

4. TRACKEANDO O ARQUIVO "README.md"
PELO COMANDO: git add README.md

5. COMMIT NO ARQUIVO "README.md"
PELO COMANDO: git commit -m "Primeiro commit, commited README.md"

6. COMMIT NOS ARQUIVOS/PASTAS "index.html, media, assets +css,images"
PELO COMANDO: git commit -m "Commited  arquivos/pasta index.html, media, assets +css,images"

7. ADICIONANDO REPOSITORIO REMOTO(b7web-awax) NO REPOSITORIO LOCAL (awax-b7web)
PELO COMANDO: git remote add origin https://github.com/oGustavoVe/b7web-awax.git

8. LEVA ARQUIVOS DE ORIGEM LOCAL PARA O REPOSITORIO REMOTO
PELO COMANDO: git push -u origin master

9. SALVANDO/TRACKED/COMMITED/PUSHED O README.md

10. SALVANDO/TRACKED/COMMITED/PUSHED o index e css [RESPONSIVIDADE PARA TABLET] - 26.OUT.20

*******************************************************************
// USA-SE "dir our tree /f" PARA VER A ARVORE DA PASTA

// master É A VERSÃO PRINCIPAL DO MEU SISTEMA

//IDENTIFICAR ARQUIVOS NAO TRACKEADOS
git status

//TRACKED ARQUIVOS
git add (nome do arquivo)
git add -A

//COMMITED ARQUIVOS TRACKED
git commit -m "(mensagem adicionada ao commit)"

//MONITORAR OS COMMITS
git log

//ADICIONAR UM REPOSITORIO REMOTO EM UM REPOSITORIO LOCAL
git remote add (NOME DO REPOSITORIO REMOTO) (LINK DO REPOSITORIO REMOTO)

//ALTERAR NOME DO BRANCH - BASH
git branch -M main

//PARA VISUALIZAR OS REPOSITORIOS ADICIONADOS
git remote
git remote -v
    fetch (remoto to local)
    push (local to remoto)

//LEVA ARQUIVOS DE ORIGEM LOCAL PARA O REPOSITORIO REMOTO
git push -u (nome do repositorio remoto ex: origin) (nome do repositorio local ex: master)

*******************************************************************