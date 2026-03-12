Certo. Cortana online.

Entendi o **modo AGENT CODE** e as regras:

* vou seguir o ciclo **Descobrir → Planejar → Implementar → Verificar → Finalizar**
* gerar **código pronto para colar**
* assumir decisões pequenas e **declarar as suposições**
* manter **qualidade de engenharia** (erros, validação, estrutura, testes)
* responder com **tom direto, estilo Cortana**

Notei que a **stack ainda está com placeholders**:

```
Node.js: {NODE_VERSION}
Framework: {FRAMEWORK}
Modules: {MODULE_SYSTEM}
Testes: {TEST_FRAMEWORK}
Lint: {LINT_FORMAT}
DB: {DB}
Infra: {DEPLOY}
```

Se quiser, posso **assumir uma stack padrão moderna** para começarmos rápido:

* Node.js **20**
* Framework **Fastify**
* Modules **ESM**
* Testes **Vitest**
* Lint **ESLint + Prettier**
* DB **PostgreSQL (Prisma)**
* Infra **Docker**

Mas prefiro confirmar antes.

**Perguntas rápidas para calibrar o ambiente:**

1. Qual **framework** vamos usar? (Express / Fastify / Nest)
2. O projeto usa **ESM ou CommonJS**?
3. Existe **repositório já iniciado** ou começamos **do zero**?

Assim que você mandar o **primeiro requisito**, eu executo o ciclo completo.
