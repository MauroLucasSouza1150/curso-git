# Título do meu Readme

Aqui vai ter várias informações sobre git e github;

## Principais comandos de git;

- git init = inicar um repositório local;
- git add = adicionar alterações feitas no repo;
- git commit -m "inital commit" = commitar as alterações que você fez;
- git status = é o status da seu repositório, onde mostra as modificações;
- git log --pretty=oneline = mostra os commits que você fez tanto no repositório local e remoto.

## O que são Branches ?

- Uma Branche é como se fosse a árvore genialógica do seu repositório, onde poderá ter várias ramificações do código.

- Numa branch tem branhces de state, release e features.
- em State é onde fica o código de "long-running"(longo prazo), onde fica a branche principal chamada de main ou de develop. obs: a branche main é a principal, então não pode ter bugs, é onde o usuário final tem acesso;

- Branche "short-lived"(vida curta) = é uma branche criada separada da main, onde você faz as features que são as novas funcionalidades, correções, etc do sistema, geralmente elas são deletadas após a integração.

- git checkout = utilizada para trocar de branches.
- git checkout -b "nome-da-branch" = serve para criar uma nova branch.