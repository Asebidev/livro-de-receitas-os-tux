# Guia de Contribuição – Os Tux

Este documento apresenta as regras e orientações para contribuir com o Livro de Receitas Colaborativo da equipe Os Tux.

Nosso objetivo é manter o projeto organizado, facilitar o trabalho em equipe e garantir que todas as alterações sejam revisadas antes de serem integradas à branch principal.

## 1. Organização das contribuições

Cada integrante poderá contribuir adicionando receitas, corrigindo informações ou melhorando a documentação do projeto.

Toda contribuição deverá seguir o fluxo de trabalho definido neste documento.

## 2. Criação de Issues

Antes de começar uma nova receita, o integrante deverá abrir uma Issue no GitHub informando:

- Nome da receita.
- Categoria correspondente.
- Descrição breve da contribuição.
- Responsável pela tarefa.

Exemplo de título:

`[Receita] Bolo de Cenoura - Sobremesas`

## 3. Padrão de nomenclatura das branches

Cada contribuição deverá ser realizada em uma branch própria, criada a partir da branch `main` atualizada.

Utilize o seguinte padrão:

`feature/<categoria>-<nome-da-receita>`

Exemplo:

`feature/sobremesas-bolo-de-cenoura`

Não realize alterações diretamente na branch `main`.

## 4. Padrão de commits

Os commits deverão utilizar o padrão Conventional Commits, com mensagens claras e objetivas.

Prefixos utilizados:

- `feat:` para adicionar novas funcionalidades ou receitas.
- `docs:` para alterações na documentação.
- `fix:` para correções de erros.
- `refactor:` para reorganização sem alteração de conteúdo funcional.

Exemplos:

```bash
git commit -m "feat: adicionar receita de bolo de cenoura"
git commit -m "docs: atualizar menu com link para bolo de cenoura"
```

## 5. Organização dos arquivos

Cada receita deverá ser criada em um arquivo Markdown próprio, dentro da pasta da categoria correspondente.

Exemplo:

`/sobremesas/bolo-de-cenoura.md`

Toda receita deverá conter:

- Título da receita.
- Lista de ingredientes.
- Modo de preparo.
- Link para voltar à categoria.
- Link para voltar ao menu principal.

Ao adicionar uma receita, o integrante também deverá atualizar o arquivo `menu.md`, incluindo o link correspondente.

## 6. Pull Requests

Após concluir as alterações, o integrante deverá enviar sua branch ao GitHub e abrir um Pull Request direcionado à branch `main`.

O Pull Request deverá conter:

- Descrição clara das alterações realizadas.
- Identificação da receita adicionada ou modificada.
- Referência à Issue relacionada, utilizando uma palavra-chave de fechamento automático, como `Closes #5`.
- Solicitação de revisão aos colegas da equipe.

## 7. Revisão de código (Code Review)

Todo Pull Request deverá passar por revisão antes de ser integrado à branch principal.

Os revisores deverão verificar:

- Organização e qualidade do conteúdo.
- Formatação dos arquivos Markdown.
- Funcionamento dos links.
- Atualização correta do menu.
- Atendimento aos padrões estabelecidos neste documento.

**Regra obrigatória: Todo PR deve ter no mínimo 3 aprovações antes do merge na main.**

As aprovações deverão ser realizadas por três integrantes diferentes da equipe.

## 8. Merge e integração

O Pull Request somente poderá ser integrado à branch `main` após receber as três aprovações obrigatórias.

A integração deverá ser realizada pelo responsável autorizado pelo repositório.

Após o merge, a branch utilizada poderá ser excluída.

## 9. Boas práticas

- Utilize nomes claros para arquivos, branches e commits.
- Não altere diretamente a branch `main`.
- Mantenha os links do menu atualizados.
- Evite modificar arquivos que não fazem parte da sua contribuição.
- Revise suas alterações antes de abrir um Pull Request.
- Respeite as contribuições dos demais integrantes.

[Voltar ao README](README.md)