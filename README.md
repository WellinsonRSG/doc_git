
# :hammer: COMANDOS DO GIT
<h1 align="center"> Documentação do git para ajudar nos comandos </h1>

* CRIAÇÃO:  
git init: Ele inicia o arquivo ".git/" para controlar a pasta.
git clone: cria um novo repositório local.
git commit -m "<texto_da_modificação>": Responsável por criar uma nova versão do projeto com as referências do criador.

* MUDANÇAS LOCAIS:  
git status: Identifica qual o status do arquivo, responsável por validar os arquivos modificados dentro do projeto.
git diff: mostra mudanças em arquivos rastreados.
git add: Inseri a pasta, ele é responsável por colocar o arquivo em uma área segura.
git add. -p <file>: adiciona algumas mudanças em <file> para o próximo commit.
git commit -a: confirma todas as alterações locais em arquivos rastreados.
git commit: confirma alterações previamente preparados.
git commit --amend: muda o último commit.

* HISTÓRICO:  
git log: Valida os meus comentários e modificações, mostra todos os commit, começando pelo mais novo.
git log -p <file>: mostra mudanças ao longo do tempo para um arquivo específico.
git blame <file>: mostra quem alterou, o quê e quando em <file>.

* BRANCHES:  
git branch -av: lista todos os ramos existentes.
git checkout <nome_da_branch>: muda de branch ou ramo.
git checkout <new-branch>: cria uma nova filial com base.
git checkout-track <remote/branch>: cria uma nova filial com base.
git checkout -b <nome_da_branch>: cria uma nova branch ou ramo.
git branch -d <brach>: deleta uma filial local.
git tag <tag-name>: marca um commit atual com uma nova tag.

* ATUALIZAR E PUBLICAR:  
git remote -v: lista todos os controles remotos configurados atualmente.
git remove show <remove>: mostra informações sobre um controle remoto.
git remote add <shortname> <url>:adiciona un novo repositório remoto, denominado <remote>.
git fetch <remote>: baixa todas as alterações de <remote>, mas não integra no HEAD.
git pull: <remote> <branch>: baixa as alterações e marca/integra diretamente no HEAD.

* FUNDIR E REBASE:  
git merge <nome_da_branch>: Ele adiciona a branch atual o conteúdo da outra branch.
git rebase <branch>: rebase seu HEAD  atual em <branch>.
git rebase --abort: aborta um rebase.
git base --continue: continua um rebase após resolver os conflitos.
git mergetool: usa a ferramenta de fusão configurada do tour para resolver conflitos:
git add <resolved-file>: usa o editor de tour para resolver conflitos manualmente e (após resolver) marcar o arquivo como resolvido.
git rm <resolved-file>: usa o editor de tour para resolver conflitos manualmente e (após resolver) marcar o arquivo como resolvido.

* DESFAZER:  
git reset-hard HEAD: descarta todas as mudanças locais em seu diretório de trabalho.
git checkout HEAD <file>: descarta as alterações locais em um arquivo específico.
git revert <commit>: reverte um commit (produzindo um novo commit com mudanças contrárias).
git reset-hard <commit>: redefine o ponteiro HEAD para um commit anterior, e descarta todas as alterações até então.
git reset <commit>: redefine o ponteiro HEAD para um commit anterior, e preserva todas as mudanças como mudanças não planejadas.
git reset-keep <commit>: redefine o ponteiro HEAD para um commit anterior, e preserva as mudanças locais não comprometidas.

* ADICIONAIS:  
ATALHOS: CTRL + L: avança linhas das informações já inseridas, deixando a tela limpa para inserir novas informações.
ERROS DE CONFIGURAÇÃO DO USUÁRIO DO GIT:  
git config --global user.name "<seu_nome>  
git config --global user.email "<seu_email>.  
ERRO 403: exclua as credencias do antigo usuário em "Gerenciador de Credenciais".
