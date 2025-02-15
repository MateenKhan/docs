---
title: Níveis de permissão em quadros de projeto pertencentes a usuários
intro: 'A project board owned by a personal account has two permission levels: the project board owner and collaborators.'
redirect_from:
  - /articles/permission-levels-for-user-owned-project-boards
  - /github/setting-up-and-managing-your-github-user-account/permission-levels-for-user-owned-project-boards
  - /github/setting-up-and-managing-your-github-user-account/managing-user-account-settings/permission-levels-for-user-owned-project-boards
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
shortTitle: Permissão de seções de projetos do usuário
---

## Visão geral das permissões

There is only one owner of a user-owned project board; this permission cannot be shared with another personal account. Além do proprietário, outras pessoas podem colaborar em quadros de projeto.

Existem três níveis de permissões para colaboradores de quadro de projeto:

{% data reusables.project-management.project-board-permissions %}

## Permissões de proprietário e administrador em um quadro de projeto pertencente a um usuário

O proprietário do quadro de projeto e colaboradores com acesso de administrador têm controle total do quadro de projeto. Além de todas as permissões de colaboradores de quadro de projeto, um proprietário de quadro de projeto e um colaborador com acesso de administrador podem:

- [Gerenciar, visualizar e adicionar colaboradores](/articles/managing-access-to-your-user-account-s-project-boards)
- [Configurar um quadro de projeto como {% ifversion ghae %}interno{% else %}público{% endif %} ou privado](/articles/changing-project-board-visibility)
- [Excluir um quadro de projeto](/articles/deleting-a-project-board/)
- [Fechar um quadro de projeto](/articles/closing-a-project-board/)
- [Reabrir um quadro de projeto fechado](/articles/reopening-a-closed-project-board)

## Permissões de leitura e gravação em um quadro de projeto pertencente a um usuário

Colaboradores com acesso de leitura em um quadro de projeto pertencente a um usuário podem:

- Visualizar um quadro de projeto
- Copiar um quadro de projeto
- Filtrar cartões em um quadro de projeto

Colaboradores com acesso de gravação em um quadro de projeto pertencente a um usuário podem:

- Visualizar um quadro de projeto
- Copiar um quadro de projeto
- Filtrar cartões em um quadro de projeto
- Editar um quadro de projeto
- Vincular um repositório a um quadro de projeto
- Configurar automação para quadros de projeto
- Copiar um quadro de projeto
- Adicionar problemas e pull requests a um quadro de projeto
- Adicionar observações a um quadro de projeto
- Acompanhar o andamento do quadro de projeto
- Arquivar cartões em um quadro de projeto

## Visibilidade do quadro de projeto

Você pode alterar a visibilidade do painel do projeto de privado para {% ifversion ghae %}interno{% else %}público{% endif %} e de volta. Por padrão, os quadros de projeto pertencentes a um usuário são privados. Para obter mais informações, consulte "[Alterar a visibilidade do quadro de projeto](/articles/changing-project-board-visibility)".

## Leia mais

  - "[Managing access to your personal account's project boards](/articles/managing-access-to-your-user-account-s-project-boards)"
