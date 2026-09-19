# Meu Harness de Engenharia de Software com IA

Repositório pessoal que replica meu "modo de pensar" em qualquer projeto ou exercício feito com apoio de IA. Baseado nos 4 pilares da engenharia de software moderna com IA:

1. **Specification-first** (`/specs`) — nada de código antes de escrever o que deve ser feito.
2. **Agente com ferramentas** (`/agents`) — como a IA deve operar: o que pode executar, ler, testar.
3. **Contexto persistente** (`/context`) — memória viva do projeto: decisões, padrões, stack.
4. **Revisão humana no loop** (`/reviews`) — checklist para eu validar antes de aceitar qualquer output.

## Como usar em um novo projeto
1. Copie este repositório (ou use como template no GitHub: *Use this template*).
2. Preencha `/context/architecture.md` e `/context/stack.md` primeiro.
3. Escreva a spec do que vai construir em `/specs/` antes de pedir código para a IA.
4. Cole `/agents/agent-instructions.md` no início de qualquer sessão com Claude/Cursor/Copilot.
5. Ao final, passe pelo checklist em `/reviews/review-checklist.md`.

## Estrutura
```
ai-swe-harness/
├── specs/
│   └── spec-template.md
├── agents/
│   └── agent-instructions.md
├── context/
│   ├── architecture.md
│   ├── stack.md
│   └── decisions-log.md
├── reviews/
│   └── review-checklist.md
└── .github/
    └── pull_request_template.md
```
