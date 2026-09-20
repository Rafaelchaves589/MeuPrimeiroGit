# MeuPrimeiroGit

Projeto de um sistema WEB para uma pequena lanchonete.

## Desenvolvimento

Até o momento, foram realizadas as seguintes etapas:

- Criação da estrutura inicial do projeto.
- Criação da documentação dos produtos.
- Criação da página de produtos.
- Adição da estilização inicial com CSS.
- Criação da página de pedidos.
- Criação da documentação dos pedidos.

## Estrutura

O projeto possui arquivos de documentação na pasta `docs` e páginas WEB e arquivos CSS na pasta `src`.

## Questionário

### 1. Qual é a diferença entre Working Directory, Staging Area e Repository?

O Working Directory é onde ficam os arquivos do projeto que estamos editando.

A Staging Area é a área onde colocamos as alterações que queremos incluir no próximo commit usando o comando `git add`.

O Repository é onde ficam armazenados os commits e o histórico das alterações do projeto.

### 2. Qual é a diferença entre git commit e git push?

O `git commit` salva as alterações no repositório local, criando um ponto no histórico do projeto.

O `git push` envia os commits que estão no repositório local para o repositório remoto, como o GitHub.

### 3. É possível realizar vários commits antes de executar um git push? Explique.

Sim. É possível realizar vários commits localmente antes de executar o `git push`.

Cada commit fica armazenado no repositório local. Quando o `git push` é executado, os commits que ainda não foram enviados são enviados para o repositório remoto.

### 4. Por que é interessante realizar commits pequenos e descritivos?

Porque commits pequenos facilitam a organização e o acompanhamento do histórico do projeto.

Mensagens descritivas também ajudam a identificar rapidamente o que foi alterado em cada versão.

### 5. O que acontece com os commits locais quando ainda não executamos o git push?

Os commits continuam armazenados no repositório local.

Eles ainda não aparecem no histórico do repositório remoto do GitHub até que seja executado o `git push`.

### 6. Como verificar, pelo GitHub, se os commits foram enviados corretamente?

É possível acessar o repositório no GitHub e abrir o histórico de commits, normalmente através da opção de histórico do repositório.

Também é possível verificar no terminal usando `git log --oneline` e comparar com o histórico mostrado no GitHub.