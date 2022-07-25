# usando-git-e-github
como usar git e github para controle e versionamento de código


#Inicializa repositorio:
git init

#Configurar email e nome de usuário no git:
git config --global user.email "usuario@provedor.com"
git config --global user.name "Seu nome"


#Verifica  se o projeto local está  atualizado. Mostra quais arquivos não estão incluídos no controle de versão, se houver:
git status

#Adicionar aquivos ao controle de versão:
git add "meu arquivo.txt"

#Se precisar adicionar mais arquivos pendentes de uma só vez:
git add .

#Boa prática!: comentar as alterações que foram feitas no código quando for atualizar o reposítório com novos arquivos
git commit -m "Adicionado validação de campos no formulário de cadastro de cliente";


#Configura para onde o código está sendo enviado:
git remote add origin https://github.com/paulocaetanomt88/usando-git-e-github


#Definir a qual branch (divisão ou grupo de desenvolvimento) meu código pertence:
 git push --set-upstream origin master
