# Contribuindo para o projeto

Este documento define as regras para desenvolvimento e colaboração no projeto.

## 1. Fluxo de desenvolvimento

A branch `main` representa a versão estável do projeto.

Não devem ser realizadas alterações diretamente na `main`.

Cada tarefa deve ser desenvolvida em uma branch própria e, após sua conclusão, enviada para revisão por meio de um Pull Request.

Fluxo básico:

```text
main
  ↓
criação da branch
  ↓
desenvolvimento
  ↓
commit
  ↓
Pull Request
  ↓
revisão
  ↓
merge na main
```

## 2. Branches

As branches devem seguir uma nomenclatura clara.

### Novas funcionalidades

```text
feature/nome-da-funcionalidade
```

Exemplo:

```text
feature/sistema-de-pontuacao
```

### Correções

```text
fix/nome-da-correcao
```

Exemplo:

```text
fix/calculo-pontuacao
```

### Documentação

```text
docs/nome-da-documentacao
```

Exemplo:

```text
docs/regras-do-jogo
```

### Refatorações

```text
refactor/nome-da-refatoracao
```

Exemplo:

```text
refactor/estrutura-do-jogo
```

Os nomes das branches devem ser curtos, descritivos e escritos em minúsculas, utilizando hífens para separar palavras.

## 3. Commits

As mensagens de commit devem ser objetivas e explicar a alteração realizada.

Utilizamos os seguintes prefixos:

* `feat:` — nova funcionalidade
* `fix:` — correção de problema
* `docs:` — alteração de documentação
* `refactor:` — refatoração sem mudança de comportamento
* `style:` — alterações de formatação ou estilo
* `test:` — criação ou alteração de testes
* `chore:` — tarefas de manutenção

Exemplos:

```text
feat: adiciona sistema de pontuação
fix: corrige validação da resposta
docs: atualiza instruções do projeto
refactor: reorganiza componentes do jogo
```

O commit deve representar uma alteração coerente. Evite reunir alterações independentes em um único commit.

## 4. Pull Requests

Toda alteração destinada à `main` deve passar por um Pull Request.

O Pull Request deve informar:

* o que foi alterado;
* qual problema ou tarefa foi resolvido;
* possíveis impactos da alteração;
* informações necessárias para testar a mudança.

O título do Pull Request deve ser objetivo e descrever a alteração principal.

Antes de solicitar revisão, o responsável deve verificar se o projeto continua funcionando conforme esperado.

## 5. Revisão de código

Pull Requests devem ser revisados por outro integrante da equipe antes do merge, sempre que possível.

A revisão deve verificar principalmente:

* funcionamento da alteração;
* organização do código;
* compatibilidade com o restante do projeto;
* ausência de alterações desnecessárias;
* cumprimento das regras deste documento.

Comentários de revisão devem ser objetivos e relacionados ao projeto.

## 6. Alterações fora do escopo

Uma tarefa deve permanecer dentro do escopo definido.

Não devem ser incluídas alterações não relacionadas apenas porque surgiram durante o desenvolvimento.

Caso seja identificada outra necessidade, ela deve ser registrada como uma tarefa separada.

## 7. Código e organização

O código deve priorizar:

* clareza;
* simplicidade;
* organização;
* manutenção;
* consistência com o restante do projeto.

Não devem ser adicionadas dependências, bibliotecas ou tecnologias sem necessidade.

Alterações estruturais relevantes devem ser discutidas antes da implementação.

## 8. Uso de ferramentas de IA

Ferramentas de inteligência artificial podem ser utilizadas como apoio ao desenvolvimento.

Entretanto, qualquer código produzido com auxílio de IA deve ser compreendido, revisado e validado pelo integrante responsável pela alteração.

O uso de IA não substitui a responsabilidade do desenvolvedor sobre o código enviado ao projeto.

## 9. Responsabilidade sobre as alterações

Cada integrante é responsável pelas alterações realizadas em sua branch e pelo conteúdo enviado em seus Pull Requests.

Antes de solicitar o merge, o responsável deve garantir que:

* a alteração corresponde à tarefa;
* não existem alterações acidentais;
* arquivos desnecessários não foram adicionados;
* o código foi testado;
* a documentação foi atualizada quando necessário.

## 10. Regra principal

A estabilidade da `main` deve ser preservada.

Em caso de dúvida sobre uma alteração que possa afetar outras partes do projeto, a equipe deve discutir a mudança antes de realizar o merge.
