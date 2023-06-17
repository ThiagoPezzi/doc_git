Documentação do git: comandos Inicia o arquivo ".git/" para controlar a pasta. ´´git init:´´

### Ele é responsavel por validar os arquivos modificados dentro do projeto. Em vermelho, mostra os arquivos modificados. Em verde, mostra os arquivos que foram adicionados pelo "git add"
````
git status:
````
### Ele é responsável por colocar o arquivo modificado em uma área segura.
````
git add
````
### Ele é responsavel por criar uma nova versão do projeto.
````
git commit -m "<texto-da-modificação>"
````

### Validar os meus comentários e modificações;
````
git log
````

### Cria uma nova branch ou ramo.
````
git checkout -b <Nome_da_branch>
````

### Muda de brangh ou ramo.
````
git checkout <Nome_da_branch> 
````

### Ele adiciona o branch atual o conteúdo de outra branch.
````
git merge <nome_da_branch>
````

### Baixa o projeto do repositório.
````
git clonhe <url>
````

### Ele envia as alterações para o repositório.
````
git push
````

### Ele puxa as alterações do repositório.
````
git pull
````



### Possiveis Erros:
403: Apagando as credenciais, gerenciamento de credenciais



### Cofigurações de usuário do git:
````
git config --global user.email "you@example.com"
````
````
git config --global user.name "Your Name"
````
