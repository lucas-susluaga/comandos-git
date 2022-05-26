Primeiro repositório e commits realizados pelo Git Bash, abaixo comandos relevantes para a utilização destes recursos:

git init => comando que inicializa um repositório local em uma determinada pasta

git status => comando que mostra o arquivo que teve alterações 

git add -A => comando que prepara os arquivos alterados para receberem o commit

git commit => comando que registra as alterações realizadas e as salva localmente

git log => comando que mostra o registro de commits já realizados com um código de verificação

git reset --soft => comando que espera receber o código hash do registro de log para voltar um commit, porém deixa a alteração preparada para receber o commit

git reset --hard => comando que espera receber o código hash do registro de log para voltar até o commit do código apagando todas e qualquer alteração realizada

dir => comando que exibe todos os arquivos dentro daquela pasta específica

git diff => comando que apresenta todas as alterações feitas naquele arquivo

git diff --name-only => comando que mostra apenas o nome dos arquivos que foram alterados

ssh-keygen -t rsa -b 4096 -C "meu e-mail do git" = > comando que cria uma chave SSH pública e privada para fazer commits do repositório local para o remoto (necessário Git Bash)

git remote add origin "url do repositório" => comando que adiciona ao repositório local o repositório remoto

git push -u origin master => comando que envia os dados salvos no git localmente para o git remoto (github nesse caso)