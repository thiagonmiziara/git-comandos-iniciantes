# **Comandos Git Iniciantes** 
![alt text](https://www.hostinger.com.br/tutoriais/wp-content/uploads/sites/12/2017/04/comandos-basicos-git-1280x720.png)
---------------------------------
______________________________
###### comando de ajuda
```git help```
   
   Você pode usar os comandos especificos exemplo:

   ```js
   git help add
   git help commit
   git help <qualquer_comando_git>
   ```

###### comando de configuração

* configurando usuário

```git config --global user.name "Thiago Miziara"```

* configurando email

`git config --global user.email thiagonmiziara@gmail.com`

###### comando para adicionar arquivo/diretório

* adicionar um arquivo especifico

`git add nome_do_arquivo.txt`

* adicionar todos os diretótios

`git add .`

###### comando para verificar diretórios

`git status`

###### comando para comitar arquivos

`git commit -m "mensagem do diretório"`

###### comando para remover o arquivo e diretório

```
git rm nome_do_arquivo.txt
git rm -r diretorio
```

###### comando para visualizar histórico

`git log`


###### Exibir histórico modificação de um arquivo

`	git log --diff-filter=M -- <caminho_do_arquivo>`


###### Exibir histório de um determinado autor

`git log --author`

###### Enviar arquivos/diretórios para o repositório remoto

O primeiro **push** de um repositório deve conter o nome do repositório remoto e o branch.

`git push -u origin master`

Os demais **push** não precisam dessa informação

`git push`


###### Atualizar repositório local de acordo com o repositório remoto

`git pull`

### Tags

###### Criando uma tag leve

`git tag vs-1.1`

###### Criando uma tag anotada

`git tag -a vs-1.1 -m "Minha versão 1.1"`

###### Criar um novo branch

`git checkout -b nova1`

###### Voltar para o branch principal (master)

`git checkout master`

###### Apagando um branch

`git branch -d nova1`

# Contribuições

Sinta-se a vontade para adicionar mais informações ou realizar correções.

[**Contato**](https://www.linkedin.com/in/thiago-miziara-92a85b6a/)
