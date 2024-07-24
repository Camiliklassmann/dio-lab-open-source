
#  Git Shell para Windows

Bem-vindo ao projeto Git Shell para Windows! Este repositório fornece um guia abrangente e recursos para usar o Git Shell em sistemas Windows.

## Índice

1. [Introdução](#introdução)
2. [Instalação](#instalação)
3. [Uso Básico](#uso-básico)
4. [Comandos Comuns](#comandos-comuns)
5. [Navegação no Git Bash](#navegação-no-git-bash)
6. [Recursos Avançados](#recursos-avançados)
7. [Solução de Problemas](#solução-de-problemas)

## Introdução

O Git Shell para Windows é uma interface de linha de comando poderosa que permite aos usuários interagir com repositórios Git. Ele fornece toda a funcionalidade do Git junto com alguns recursos adicionais para melhorar a experiência no Windows.

## Instalação

Para instalar o Git Shell para Windows, siga estas etapas:

1. Baixe o instalador do Git para Windows no [site oficial](https://gitforwindows.org/).
2. Execute o instalador e siga as instruções na tela.
3. Durante a instalação, certifique-se de que a opção "Git Bash Here" esteja selecionada para adicionar o Git Shell ao menu de contexto.
4. Conclua a instalação e reinicie o computador se solicitado.

## Uso Básico

Após a instalação, você pode abrir o Git Shell de várias maneiras:

- Clique com o botão direito em qualquer pasta e selecione `Git Bash Here` no menu de contexto.
- Abra o menu Iniciar, procure por `Git Bash` e execute-o.

### Clonando um Repositório

Para clonar um repositório, use o seguinte comando:

```sh
git clone https://github.com/usuario/repositorio.git
```

### Verificando o Status do Repositório

Para verificar o status do seu repositório, use:

```sh
git status
```

## Comandos Comuns

Aqui estão alguns comandos Git comuns que você usará frequentemente:

- `git init`  Inicializa um novo repositório Git.
- `git add .`  Adiciona todas as mudanças para o próximo commit.
- `git commit -m "mensagem"`  Realiza o commit das mudanças adicionadas com uma mensagem.
- `git pull`  Busca e mescla as mudanças do repositório remoto.
- `git push`  Envia os commits locais para o repositório remoto.
- `git branch`  Lista, cria ou deleta branches.
- `git checkout`  Muda de branch ou restaura arquivos de árvore de trabalho.
- `git merge`  Mescla branches.
- `git log`  Mostra o histórico de commits.
- `git diff`  Mostra as diferenças entre commits, branches, etc.
- `git reset`  Reseta o estado do HEAD para um commit anterior.
- `git rm`  Remove arquivos do índice e do diretório de trabalho.
- `git stash`  Guarda as mudanças temporariamente.
- `git tag`  Marca pontos específicos na história do repositório como versões.
- `git remote`  Gerencia repositórios remotos.
- `git fetch`  Busca mudanças do repositório remoto sem mesclar.

## Navegação no Git Bash

Comandos de navegação são úteis para se mover entre diretórios no Git Bash. Aqui estão alguns dos comandos mais comuns:

- `pwd`  Mostra o diretório atual.
- `ls`  Lista os arquivos e diretórios no diretório atual.
- `cd diretório`  Muda para o diretório especificado.
- `cd ..`  Volta para o diretório pai.
- `cd ~`  Vai para o diretório home do usuário.
- `cd /`  Vai para o diretório raiz.
- `mkdir nome_do_diretório`  Cria um novo diretório.
- `rmdir nome_do_diretório`  Remove um diretório vazio.
- `rm -r nome_do_diretório`  Remove um diretório e seu conteúdo recursivamente.
- `clear`  Limpa a tela do terminal.

## Recursos Avançados

O Git Shell para Windows inclui vários recursos avançados:

- **Gerenciamento de Chaves SSH**: Gerencie facilmente suas chaves SSH para conexões seguras.
- **Prompt Personalizável**: Personalize a aparência do seu prompt Git.
- **Suporte a Aliases**: Crie e use aliases para comandos frequentemente usados.

## Solução de Problemas

### Problemas Comuns

1. **Git Não Reconhecido como Comando Interno ou Externo**:
   - Certifique-se de que o Git está devidamente instalado e adicionado ao PATH do sistema.
   - Reinicie o computador para aplicar as mudanças.

2. **Permissão Negada (Publickey)**:
   - Certifique-se de que suas chaves SSH estão corretamente configuradas e adicionadas ao seu agente SSH.
   - Consulte a [documentação oficial](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh) para instruções detalhadas.
