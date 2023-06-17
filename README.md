Documentação do git: comandos Inicia o arquivo ".git/" para controlar a pasta. ´´git init:´´

### Ele é responsavel por validar os arquivos modificados dentro do projeto. Em vermelho, mostra os arquivos modificados. Em verde, mostra os arquivos que foram adicionados pelo "git add"
````
git status:
````
<img width="454" alt="gitstatus" src="https://github.com/ThiagoPezzi/doc_git/assets/112133027/3652e4d2-cb3c-4352-8654-a60e2437ea5a">

###  Ele inicia o arquivo "/.git" para controlar a pasta.
````
git init
````
<img width="454" alt="gitinit" src="https://github.com/ThiagoPezzi/doc_git/assets/112133027/0dab33dd-0f90-41ac-8f65-f7720ab3f5ac">

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
<img width="455" alt="gitclone" src="https://github.com/ThiagoPezzi/doc_git/assets/112133027/6ce2559f-414e-4d54-be1c-6946ad7acf05">

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
