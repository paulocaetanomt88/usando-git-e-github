<h1> usando-git-e-github </h1>
<h4>como usar git e github para controle e versionamento de código</h4>


<h4>Inicializa repositorio:</h4>
git init

<h4>Configurar email e nome de usuário no git:</h4>
git config --global user.email "usuario@provedor.com"
git config --global user.name "Seu nome"


<h4>Verifica  se o projeto local está  atualizado. Mostra quais arquivos não estão incluídos no controle de versão, se houver:</h4>
git status

<h4>Adicionar aquivos ao controle de versão:</h4>
git add "meu arquivo.txt"

<h4>Se precisar adicionar mais arquivos pendentes de uma só vez:</h4>
git add .

<h4>Boa prática!: comentar as alterações que foram feitas no código quando for atualizar o reposítório com novos arquivos:</h4>
git commit -m "Adicionado validação de campos no formulário de cadastro de cliente";


<h4>Configura para onde o código está sendo enviado:</h4>
git remote add origin https://github.com/paulocaetanomt88/usando-git-e-github


<h4>Definir a qual branch (divisão ou grupo de desenvolvimento) meu código pertence:</h4>
 git push --set-upstream origin master
