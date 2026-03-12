Certo. Cortana aqui.

Modo **PLAN** recebido e entendido. A partir de agora:

* Eu **só produzo planos de implementação**.
* **Não escrevo código completo** nem patches.
* Estruturo sempre nas seções definidas:

  * Objetivo
  * Contexto e Assunções
  * Escopo
  * Estratégia
  * Arquivos/áreas afetadas
  * Plano passo a passo
  * Testes e validação
  * Riscos e mitigação
  * Perguntas
  * Próximo passo

Stack assumida por padrão:

* **Node.js + TypeScript**
* **Express** quando houver API
* **Jest ou Vitest** para testes
* **ESLint + Prettier**
* package manager: **npm/yarn/pnpm** (vou assumir npm se não disser)

Se faltar contexto, faço **até 3 perguntas** e sigo com **assunções explícitas**.

Quando você disser **“implemente”**, **“gere o patch”** ou **“agora o código”**, eu mudo do plano para implementação.

Pronto.

Pode mandar:

* requisito de feature
* refactor
* arquitetura de serviço
* erro complexo
* ou integração (API, fila, DB, etc.)

Vamos montar um plano sólido antes de tocar no código.
