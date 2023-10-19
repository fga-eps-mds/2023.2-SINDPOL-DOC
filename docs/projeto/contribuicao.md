# Plano de Contribuição
<style>body {text-align: justify}</style>

## 1. Introdução

Este Plano de Contribuição determina as regras para submissão de códigos e contribuições nos repositórios do Projeto SINDPOL no semestre 2023-1.

## 2. Issues

Todas as contribuições devem estar vinculadas a uma única _issues_, e todas as _issues_ devem ser criadas e preenchidas de acordo com os templates disponíveis no repositório.

As _issues_ precisaram de responsáveis para desenvolve-las, que seram os _Assignees_ e, além disso cada _issue_ possuirá _labels_ que servirá para indicar o tipo delas. 

## 3. Commits

As menssagens dos _commits_ devem ser escritos na língua inglesa, de maneira\ simples e curta, visando mostrar o trabalho que foi realizado de maneira objetiva.

Se o _commit_ tiver sido realizado por mais de um membro da equipe, será necessário utilizar o _Co-authored-by_.

Como utilizar

Os commits semânticos possuem um esqueleto padrão que consiste em partes opcionais que podem ou não ser acrescentadas.

```
<tipo>: <descrição>

Exemplo:
Fix: Fix user redirection upon sign up
```

A primeira e principal descrição de um commit semântico é o Tipo. Tem como finalidade dizer o que aquele commit está realizando. Os tipos se resumem em feat, fix, refactor, style, chore, doc e test.

```
Feat: É utilizado quando existe uma adição de uma nova funcionalidade ao código.

Fix: Refere-se à resolução de bugs ou problemas identificados no código existente.

Refactor: Indica a reestruturação do código, sem alterar seu comportamento externo, visando melhorar a legibilidade ou o desempenho.
    
Style: Envolve mudanças que não afetam a lógica do código, como alterações de formatação, espaçamento ou convenções de nomenclatura.

Chore: Reflete alterações na infraestrutura do projeto ou tarefas de manutenção, sem modificar o código em si.

Doc: Relaciona-se a modificações ou adições na documentação, incluindo comentários no código, READMEs e documentos do usuário.

Test: Diz respeito a adições ou alterações nos testes existentes ou à inclusão de novos testes para garantir a robustez e a confiabilidade do código.
```

## 4. Pull Requests

Todos os _pull requests_ devem estar obrigatoriamente vinculados a uma _issue_. É necessário também a inclusão de _Reviewers_, que são os responsáveis por averiguar se a _issue_ foi concluida e então fazer a validação do _pull request_. Para que _pull request_ seja mergado na branch principal é necessário a aprovação de pelo menos dois _Reviewers_.

## 5. Branches

Com exceção das _branches_ principais (_main, gh-pages, devel_), cada _branch_ deve estar vinculada a uma única _issue_. Após a conclusão da _issue_ e fechamento do _pull request_ associado, a _branch_ referente não pode ser apagada, porque ela será utilizada para organização de pacotes de entregas para a release.

Para manter o padrão criaremos a branch bem parecido com o commit, sendo adotado os seguintes padrões:

```
<tipo>/<descrição>

Exemplo:
feature/orm-migration
fix/user-redirection
hotfix/password-redirection


feature: Utilizado quando uma nova funcionalidade do sistema é implementada.
fix: Utilizado quando é necessário abrir uma branch de correção de uma funcionalidade já existente no sistema.
refactor: Utilizado quando é necessário abrir uma branch de refatoração de código mas que não altere sua funcionalidade.
documentation: Utilizado quando é necessário abrir uma branch de documentação no projeto.
hotfix: Utilizado quando é necessário abrir uma branch de correção de um bug em produção no projeto.
```

## 6. Referência

<a id="ref1"></a>
[1] O que são Commits Semânticos e como utilizo?. Disponível em: <https://www.letscode.com.br/blog/o-que-sao-commits-semanticos-e-como-utilizo>. Acesso em: outubro, 2023.


<a id="ref2"></a>
[2] Fluxo de trabalho de Gitflow. Disponível em: <https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=O%20que%20%C3%A9%20o%20Gitflow,por%20Vincent%20Driessen%20no%20nvie.>. Acesso em: outubro, 2023.


## 7. Histórico de Revisão

| Data       | Versão | Modificação                     | Autor        |
| :--------- | :----- | :------------------------------ | :----------- |
| 18/10/2023 | 0.1    | Criação do documento.          | Mateus Maia |
