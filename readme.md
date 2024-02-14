Esse projeto serve como treino para comandos de Git.

*** PRINCIPAIS COMANDOS GIT ***

git --version (consultar a versão)
git init (inicializar um repositório git vazio, na branch master)
git add (manda os arquivos para a área de staging. basicamente, prepara os arquivos para serem enviados para a cloud)
git status (verifica o status dos arquivos no repositório)
git commit -m "mensagem" (usado para efetuar a atualização no arquivo LOCALMENTE. A mensagem serve para descrever o que aquela mudança representa)
git branch -M "main" (uma maneira de renomear a branch que eu estou)
git remote add origin "url" (criar a conexão do repositório do github com o repositório local)
git push -u origin "branchname" (enviar as mudanças para o github)

Testando uma nova linha

git reflog (comando que mostra o histórico de versões)
git reset -- hard (id_da_versao) (para voltar à uma versão específica. Deve-se usar o ID da versão)

git branch (listar as branches disponíveis)
git branch "nome_nova_branch" (criar uma nova branch)
A branch atual ficará marcada em verde e com um asterisco
git checkout "nome_branch" (utilizado para trocar de branch)

Para trazer as atualizações de uma dada branch para a branch principal, devemos usar o comando merge.

Primeiro deve-se entrar na branch principal
Depois usar o comando:
git merge "nome_da_outra_branch"

IMPORTANTE: sempre rodar o comando git pull na branch principal antes de se fazer o comando merge com outras branches... Isso garante que a versão dos arquivos na branch principal é a mais atual.



