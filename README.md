# code-editor

Package Code Editor

Repositório: https://github.com/ThinkIac/code-editor.

## Uso no ThinkIac

Este pacote foi extraído de `packages/code-editor`. Preserve a identidade `code-editor` do manifest ao instalá-lo em um workspace Lógos. Views, rotas, ferramentas e hooks são descobertos pelo runtime e dependem dos provedores correspondentes. Esta extração publica o código atual; não converte JavaScript para LógosType nem implementa instalação por perfil.

## Dependências e validação

Consulte `package.json` e os imports para as capacidades exigidas do host.

O pacote não declara scripts npm de build/teste. Os testes existentes acompanham o fonte; a composição completa requer o host ThinkIac.

## Segurança e dados locais

Credenciais devem ser configuradas no ambiente de destino. Não acompanham esta extração bancos, sessões, uploads, perfis pessoais, arquivos `.env`, caches ou backups. As exclusões foram registradas em relatório externo à publicação. Configure segredos pelo host, sem incluí-los em commits.

## Documentação anterior

# thinkiac-code-editor

## Registros encontrados no código

- `hook`: `boot`.
- `router`: `ai/actions`, `ai/assist`, `file/create`, `file/delete`, `file/read`, `file/read-by-path`, `file/rename`, `file/write`, `file/write-by-path`, `files`, `git/diff`, `git/status`, `packages`, `search`.

A lista é um inventário estático e pode incluir registros em testes; não garante disponibilidade sem os provedores do host.

Há imports relativos para diretórios superiores. A instalação isolada e a composição por perfil precisam resolver esses vínculos antes de remover a cópia da base.

