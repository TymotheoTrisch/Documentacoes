# Manual de comandos Git

Este manual percorre uma pequena quantidade de códigos em Git para iniciar um projeto e subir ele para o GitHub.

# Tópicos
+ [Inicialização de um repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-inicialização-de-um-repositório)
+ [Mudar o nome da branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#mudar-o-nome-da-branch)
+ [Criar uma nova branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-criar-uma-nova-branch)
+ [Mudar entre branch](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-ir-para-uma-outra-branch)
+ [Adiciona o conteúdo do arquivo ao índice](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-adiciona-o-conteúdo-do-arquivo-ao-índice)
+ [Registrar alterações no repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-registrar-altera%C3%A7%C3%B5es-no-reposit%C3%B3rio-obs-feito-ap%C3%B3s-o-git-add)
+ [Verificar o status do repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#Comando-para-verificar-o-status-do-repositório)
+ [Criar a origem remota no GitHub](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-criar-a-origem-remota-no-github)
+ [Buscar e interar com  outro repositório ou branch local](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-buscar-e-interar-com--outro-reposit%C3%B3rio-ou-branch-local)
+ [Adicionar as alterações local para o repositório](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/ComandosGit.md#comando-para-adicionar-as-altera%C3%A7%C3%B5es-local-para-o-reposit%C3%B3rio)


## Comando para inicialização de um repositório

Este comando é usado quando se inicia um projeto.
    
```
git init
```
    
## Comando para mudar o nome da branch
Esse comando muda o nome da branch(ambiente de trabalho do usuário) atual.
    
```
git branch -m master main
```
    
## Comando para criar uma nova branch
Esse comando cria uma nova branch(ambiente de trabalho do usuário).
```
git branch <nome_da_nova_branch>

# Para criar uma nova branch e ja muda o ambiente de trabalho do usuário para a mesma
git checkout -b <nome_da_nova_branch>

# Para criar a nova branch a partir de uma branch especifica:
git branch -c branchEspecifica MinhaNovaBrach

# Para apagar uma branch
git branch -d <nome_da_branch>
```
    
## Comando para ir para uma outra branch 
Esse comando é usado para mudar de uma branch para outra.
```
git checkout <nome_da_branch>
```
    
## Comando para adiciona o conteúdo do arquivo ao índice
Esse comando adiciona todos os arquivos modificados ao índice do projeto.
```
git add <nome_do_arquivo>
git add .
```
    
## Comando para registrar alterações no repositório (Obs: feito após o git add)
Esse comando registra todas as alterações do código no repositório.
```
git commit -m "mensagem de Commit"
```
    
## Comando para verificar o status do repositório
Esse comando dá todas as informações do repositório, como por exemplo se tem algum arquivo que ainda não foi registrado.
```
git status
```
    
## Comando para criar a origem remota no GitHub
Esse comando adiciona um novo controle remoto.
```
git remote add origin <url>
git remote -v
```
    
## Comando para buscar e interar com  outro repositório ou branch local
Esse comando Incorpora alterações de um repositório remoto na ramificação atual.
```
git pull
```
    
## Comando para adicionar as alterações local para o repositório
Esse comando adiciona as alterações locais para o repositório no GitHub.
```
git push -u add origin <branch_local_atual>
git push -u origin <nome_da_branch>
```
