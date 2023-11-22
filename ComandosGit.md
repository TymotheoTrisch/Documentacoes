# Manual de comandos Git

Este manual percorre uma pequena quantidade de códigos em Git para iniciar um projeto e subir ele para o GitHub.

# Tópicos
- [Tópico 1](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#texto)
+ Mudar o nome da branch
+ Criar uma nova branch
+ Mudar entre branch
+ Adiciona o conteúdo do arquivo ao índice
+ Registrar alterações no repositório

1. Comando para inicialização de um repositório
    
    ```
    git init
    ```
    
2. Mudar o nome da branch Maste para Main
    
    ```
    git branch -m master main
    ```
    
3. Comando par criar uma nova branch (se necessário)
    
    ```
    git branch <nome_da_nova_branch>
    git checkout -d <nome_da_nova_branch>
    
    # Para criar a nova branch a partir de uma branch especifica:
    git branch -c branchEspecifica MinhaNovaBrach
    
    # Para apagar uma branch
    git branch -d <nome_da_branch>
    ```
    
4. Comando para ir para uma outra branch 
    
    ```
    git checkout <nome_da_branch>
    ```

## Texto
5. Comando para adiciona o conteúdo do arquivo ao índice
    
    ```
    git add <nome_do_arquivo>
    git add .
    ```
    
6. Comando para registrar alterações no repositório (Obs: feito após o git add)
    
    ```
    git commit -m "mensagem de Commit"
    ```
    
7. Comando para verificar o status do repositório
    
    ```
    git status
    ```
    
8. Comando para criar a origem remota no GitHub
    
    ```
    git remote add origin <url>
    git remote -v
    ```
    
9. Comando para buscar e interar com  outro repositórioou branch local
    
    ```
    git pull
    ```
    
10. Comando para adicionar as alterações local para o repositório
    
    ```
    git push -u add origin <branch_local_atual>
    git push -u origin <nome_da_branch>
    ```
