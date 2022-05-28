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

Ao criar um arquivo chamado ".gitignore", você pode adicionar todos os arquivos que devem ser ignorados no commit e estes ficarão dentro do .gitignore;

Para adicionar um arquivo dentro do .gitignore basta escrever o nome do arquvio dentro do .gitignore EX:

README.md //dentro do aquvio .gitignore

Também é possível definir arquivos que serão ignorados por extensão e até mesmo pastas que podem ser ignoradas. 
Para tal dentro do arquivo .gitignore deve ser escrita qual extensão será ignorada EX:

*.txt //indica que todos os arquivos de texto devem ser ignorados
*.html //indica que todos os arquivos html devem ser ignorados

Para ignorar uma pasta EX:

nome da pasta/* //indica que todos os arquivos daquela pasta serão ignorados.

git revert --no-edit + o código do commit => comando que reverte um commit que foi realizado com erros, revertendo os problemas (sem perder o commit errado, para que possa ser ajustado posteriormente)

git push origin :"nome do branch que deseja remover" => Comando utilizado para remover um branch do remoto (GitHub)

git branch -D "nome do branch que deseja remover" => comando utilizado para remover um branch do sistema local

git pull origin master => comando puxa todas as alterações do repositório remoto para o repositório local
(indicado fazer esse procedimento sempre antes de realizar um push, para a atualização correta dos repositórios)