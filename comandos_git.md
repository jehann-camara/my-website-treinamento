# // By Jehann Câmara.

# Comandos Git no terminal Git Bash ( Windows) 

    dir
    clear
    git help
    git status
    git add --all
    git commit
    git commit - m "Mensagem ao comitar"
    git diff
    git restore
    git log
    git log --oneline

# Comandos de configuração do Git.

    git config --global user.name "Jehann Câmara" 
    git config --global user.email 	meuEmail@outlook.com
    git config --global init.default branch main <!-- Ou branch master  -->

# Inicializar diretótio Git, após estar dentro do diretório desejado.( criando um sub-diretório oculto e empty).

    git init

# Tracking dos arquivos no Git.
    git add index.html
    git add image.jpg

# Remover do Tracking (Exemplo).
    git rm --cached index.html

# add todos arquivos do diretório no Tracking. Adicionados, mas não comitados ainda (Staged=preparado - pré commit).
    git add --all
    git add .

# Primeiro Snapshot após commit.
    git commit
    git commit - m "Primeiro commit de todos os arquivos Staged."

# Mostra alterações feitas em arquivos commitados.
    git diff

# Pós versionamento, um arquivo pode estar em 3 status: Working - Staged - Commited   

# Verifica o Log de commits  
    git log

# Pulando o Staged - do status: Working para o Commited  
     git commit -a -m "Commit pulando o Staging."



    
    

    




