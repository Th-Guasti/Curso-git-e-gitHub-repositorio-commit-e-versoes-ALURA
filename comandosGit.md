# Comandos git passados no curso
###
<p>git clone "link do projeto" (para clonar a pasta do github no computador)</p>
<p>cd "nome da pasta" (para entrar na pasta clonada)</p>
<p>ls (para ver os arquivos)</p>
<p>git log (para ver os commits)</p>
<p>git log --oneline (ver os commits de forma menor)</p>
<p>ctrl+l (limpar git bash)</p>
<p>git pull "link do projeto" (atualizar no computador, mudanças feitas no repositório)</p>
<p>git status (ver mudanças)</p>
<p>git push origin main (levar as mudanças do computador para o github)</p>
<p>git commit . -m "mensagem" (commita o projeto todo)</p>
<p>git commit "nome arquivo" -m "mensagem" (commita o arquivo especificado)</p>
<p>git restore --source "codigo do commit" ". ou nome do arquivo específico" (restaura mudanças feitas)</p>

<p>Obs.: se restaurar um código, ele vai restaurar localmente, caso queira mandar para o github, fazer novo commit e push</p>

<p>git log --author="user_name" (pesquisar as informações do autor daquele commit com o comando)</p>
<p>git log --since=1.month.ago --until=1.day.ago (pesquisar informações por data)</p>
<p>git log --pretty="format:%h %s" (formatar a visualização das informações de commit com o comando)</p>

# Arquivo criado -> adicionar a pasta -> commitar -> mandar pro gitHub:
<p>git status -> git add . ou "nome do arquivo" -> git commit -m -> git push</p>