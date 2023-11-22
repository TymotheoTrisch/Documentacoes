# Manual de comandos Git

Este manual percorre uma pequena quantidade de códigos em Git para iniciar um projeto e subir ele para o GitHub.

# Tópicos
- [Inicialização de um repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-inicializacao-de-um-repositorio)
+ [Mudar o nome da branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#mudar-o-nome-da-branch)
+ [Criar uma nova branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-criar-uma-nova-branch)
+ [Mudar entre branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-ir-para-uma-outra-branch)
+ [Adiciona o conteúdo do arquivo ao índice](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-adiciona-o-conteudo-do-arquivo-ao-indice)
+ Registrar alterações no repositório
+ [Verificar o status do repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#Comando-para-verificar-o-status-do-repositorio)
+ [Criar a origem remota no GitHub](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-criar-a-origem-remota-no-github)
+ [Buscar e interar com  outro repositório ou branch local](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-buscar-e-interar-com-outro-repositório-ou-branch-local)


## Comando para inicialização de um repositório
    
    ```
    git init
    ```
    
## Mudar o nome da branch
    
    ```
    git branch -m master main
    ```
    
## Comando para criar uma nova branch
    
    ```
    git branch <nome_da_nova_branch>
    git checkout -d <nome_da_nova_branch>
    
    # Para criar a nova branch a partir de uma branch especifica:
    git branch -c branchEspecifica MinhaNovaBrach
    
    # Para apagar uma branch
    git branch -d <nome_da_branch>
    ```
    
## Comando para ir para uma outra branch 
    
    ```
    git checkout <nome_da_branch>
    ```
    
## Comando para adiciona o conteúdo do arquivo ao índice
    
    ```
    git add <nome_do_arquivo>
    git add .
    ```
    
## Comando para registrar alterações no repositório (Obs: feito após o git add)
    
    ```
    git commit -m "mensagem de Commit"
    ```
    
## Comando para verificar o status do repositório
    
    ```
    git status
    ```
    
## Comando para criar a origem remota no GitHub
    
    ```
    git remote add origin <url>
    git remote -v
    ```
    
## Comando para buscar e interar com  outro repositório ou branch local
    
    ```
    git pull
    ```
    
## Comando para adicionar as alterações local para o repositório
    
    ```
    git push -u add origin <branch_local_atual>
    git push -u origin <nome_da_branch>
    ```
