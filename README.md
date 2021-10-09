>> Aula 04 (07/10/2021) - Práticas GIT

# git init 
inicializa o git

# git config --global user.email "you@example.com"
# git config --global user.name "Your Name"
inicializa o usuário que irá realizar as alterações

# git clone /path/to/local/repository
comando para alterar o diretório 

# git add nome_do_arquivo.extensao>
add um ponto na história 

# git commit -m "primeira submissão da página"
leva a alteração ao repositório / cria o ponto (de fato) na história

# git log 
comando para verificar os pontos da história

# git status
verifica o status do arquivo (se foi alterado e ainda não foi adicionado no diretório)

>> para atualizar os arquivos alterados, é necessário o realizado os comandos /add/ e o /commit/

# git show <numero_do_commit> 
verifica o histórico de alterações

# git branch <nome/da/branch>
criar uma nova ramificação no repositório

# git checkout <nome/da/branch>
altera para a o repositório em outra branch

# git brench
mostra todas as ramificações 

>> criar novo arquivo HTML (o que seria uma nova página) para a nova ramificação
>> adicionar o novo arquivo na branch nova e realizar o commit

# git log --oneline
verifica a linha do tempo do commit

# git merge <nome/da/branch>
traz as atualizações da ramificação para a master (em produção)

# git breanch -D <nome/da/branch>
deleta a branch criada

>> criar repositório no GitHub para enviar o projeto a um repositório remoto

# git remote add origin <link_do_repositorio_remoto>
adicionar o repositório remoto no git

# git remote -v
verificar o repositório remoto

# git push -u origin main
envia o projeto para o servidor remoto e cria a linha do tempo 
(na primeira execução pede o login no GitHub)

# git push
envia o projeto para o servidor remoto (github)

# git add .
adiciona todos os arquivos na história (necessário realizar commit)

