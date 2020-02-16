# Git Alias
Alias de algumas funções `GIT` feitas em português para facilitar o uso.

### Como usar
Execute o comando abaixo para abrir o arquivo de configurações e insira os `[alias]` no final do arquivo, caso o mesmo não exista.

```bash
git config --global --edit
```

### Comandos
`git projeto [nome]`
Vincula o projeto remoto a sua pasta com o nome <u>origin</u>
<small style="color:darkgray">_Exemplo: `git projeto https://github.com/dyogophoenix/git-alias.git`_</small>

`git criar [branch]`
Cria uma nova branch e te move para dentro dela.
<small style="color:darkgray">_Exemplo: `git criar nova-branch`_</small>

`git deletar [branch]`
Deleta uma branch.
<small style="color:darkgray">_Exemplo: `git deletar nova-branch`_</small>

`git adicionar [file]`
Adiciona um arquivo para o próximo commit, mesmo que `git add`.
<small style="color:darkgray">_Exemplo: `git add README.md`_</small>

`git remover [file]`
Remove um arquivo vinculado ao próximo commit.
<small style="color:darkgray">_Exemplo: `git desfazer README.md`_</small>

`git comitar [msg]`
Adiciona todos os arquivos e realiza o commit.
<small style="color:darkgray">_Exemplo: `git registrar "Atualizado projeto"`_</small>

`git recomitar [msg]`
Altera o nome do último commit.
<small style="color:darkgray">_Exemplo: `git corrigir "Atualizando projeto"`_</small>

`git descomitar`
Desfaz o último commit.

`git atualizar [branch]`
Atualiza sua pasta com os arquivos remotos.
<small style="color:darkgray">_Exemplo: `git atualizar master`_</small>

`git subir [branch]`
Sobe os arquivos para o projeto remoto.
<small style="color:darkgray">_Exemplo: `git subir master`_</small>

`git registros`
Exibe os últimos 05 logs realizados.

`git mover [branch]`
Te move para o lugar desejado, seja para uma branch, uma hash ou qualquer outra possibilidade do `checkout`.
<small style="color:darkgray">_Exemplo: `git mover branch2`_</small>

`git raiz`
Te move de volta para a raiz do projeto (master).

`git checar`
Exibe o `git status` de uma forma simplificada.

`git verificar [hash]`
Exibe um git log da hash exibindo o nome dos arquivos que foram modificados naquele commit.
<small style="color:darkgray">_Exemplo: `git verificar f70ca6d`_</small>

`git mesclar [branch]`
Te retorna a raiz e executa o merge da branch indicada com `master`.
<small style="color:darkgray">_Exemplo: `git mesclar branch2`_</small>

`git remoto`
Exibe se existe commits no projeto remoto que não se encontram na sua pasta.

`git pendentes`
Exibe se existe commits na sua pasta que não se encontram no projeto remoto.

`git desfazer [file]`
Desfaz as modificações de um arquivo para o estado do último commit.
<small style="color:darkgray">_Exemplo: `git desfazer README.md`_</small>