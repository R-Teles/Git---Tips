# Comandos do Git :smirk_cat:

## Para configurar nova instalação - usuário:

> > git config --global user.name "(colocar usuário)"
> >
> > git config --global user.email "(colocar email)"

## Para criar um novo projeto de Git.

> > git init      #Cria um novo repositório em branco. 
> >
> > git init <nome do repositório> # se quiser dar nome específico

## Para criar diretório, navegar...

> > mkdir (nome rep)
> >
> > dir      #listar diretórios
> >
> > cd (nome di)      #navegar para
> >
> > cd ..       #retomar diretório anterior
> >
> > pwd    #visualizar o caminho de diretório completo
> >
> > mv (nome) ./ (nome repositório)   #mover de para outro repositório

## Para criar uma cópia exata de um repositório já existente.

> > git clone

## Para adicionar arquivos especificados de código ao seu repositório. Na fila. Novos ou antigos.

> > git add*
> >
> > git add (_arquivo) # adiciona um arquivo específico ao repositório

## Para remover arquivos da pasta.

> > git rm (nome)

## Para executar o commit dos arquivos que foram add e cria uma revisão com um log.

> > git commit
> >
> > git commit -m "com comentário"

 ## Para criar, renomear, excluir ou alternar uma ramificação.

> > git branch --list    #lista todas as ramificações no seu repositório
> >
> > git branch (nome)    #cria nova ramificação
> >
> > git branch -d (nome)    #exclui a ramificação de forma segura.
> >
> > git branch -D (nome)    #esclui a ramificação mesmo que haja mudanças não mescladas.
> >
> > git branch -m (nome)      #renomeia a ramificação atual para
> >
> > git checkout (nome)      #trocar de uma ramificação para outro.

## Para uma conexão entre o repositório local e um remoto

> > git remote add (nome) (url)
> >
> > git remote -v   #lista repositórios remotos cadastrados

## Para upar modificações para um repositório remoto já conecado com o remote

> > git push -u (nome) (nome do branch)

## Para baixar as mudanças criadas por outros usuários do projeto.

> > git fetch # recebe informações de commits .

## Para baixar o conteúdo do que foi alterado no repositório remoo para repositório local e atualiza seu conteúdo para a última versão.

> > git pull (url)

## Para armazenar temporariamente seus arquivos modificados em um esconderijo.

> > git stash
> >
> > git stash list      #listas os esconderijos
> >
> > git stash apply    #quando for aplicar o coneúdo a um branch

## Para integrar - mesclar as mudanças de dois branches diferentes em um único. Precisa ser iniciado a partir de um branch já selecionado.

> > git merge (nome do branch)

## Para determinar qual usuário realizou qual mudança em um determinado arquivo.

> > git blame (nome arquivo)

## Para combinar múltiplos arquivos em um.

> >  git archive -format zip HEAD > archive-HEAD.zip

## Para ajuda

> > git --help
> >
> > git help (nome comando)   #ajuda específica

