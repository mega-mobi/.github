# `.github` — perfil público da Mega Mobi

Repositório especial da organização [mega-mobi](https://github.com/mega-mobi). O GitHub usa este repo de duas formas:

1. **`profile/README.md`** — aparece na aba Overview **pública** de [github.com/mega-mobi](https://github.com/mega-mobi).
2. **Arquivos de saúde da comunidade** (templates de issue/PR, `CONTRIBUTING.md`, `SECURITY.md`, `CODEOWNERS`, etc.) — viram o padrão de todos os repositórios da org que não tiverem o próprio.

Este repositório **precisa ser público**. Se ficar privado, o README de perfil não aparece para quem não é membro.

O README visível **só para membros** mora em [`.github-private`](https://github.com/mega-mobi/.github-private) (`profile/README.md`). Membros autenticados podem alternar entre as visões *Member* e *Public* no Overview da org.

## Estrutura

```
.
├── README.md              # este arquivo (página do repositório)
└── profile/
    └── README.md          # Overview pública da org
```

## Como editar o perfil público

1. Altere `profile/README.md`.
2. Faça commit em `main`.
3. Confira em https://github.com/mega-mobi com a visão **Public**.

Não coloque aqui secrets, IDs de conta AWS, URLs internas nem links que só resolvem para membros — este repo é público.

Documentação oficial: [Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).
