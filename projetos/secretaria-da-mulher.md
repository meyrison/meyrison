# Sistema da Secretaria da Mulher

**Gestão de atendimentos · Triagens · Encaminhamentos · Relatórios**

[Voltar ao portfólio](../README.md)

## O projeto

Sistema voltado à organização de fluxos de atendimento da Secretaria da Mulher. O backend possui operações para triagens, encaminhamentos e acompanhamento, com consultas e relatórios.

## Escopo funcional

- Registro e consulta de triagens.
- Encaminhamentos e atualização de suas informações.
- Organização do fluxo de acompanhamento.
- Gestão de usuários e acesso aos módulos.
- Importação de cadastros e relatórios por período e módulo.

```mermaid
flowchart LR
    T["Triagem"] --> E["Encaminhamento"]
    E --> A["Acompanhamento"]
    A --> R["Consultas e relatórios"]
```

## Tecnologias

**Python, FastAPI, Pydantic, PostgreSQL, JWT, ReportLab e bibliotecas para documentos.**

## Aspectos técnicos

- Tradução de fluxos de atendimento em modelos e operações de API.
- Validação de dados e organização do acesso por usuário.
- Integração entre consultas, atualização de status e relatórios.

## Privacidade e escopo

Esta ficha apresenta somente funcionalidades e tecnologias. Não inclui cadastros, relatórios reais, dados de atendimento ou informações pessoais. O código-fonte e os dados operacionais permanecem privados.

O escopo foi identificado no backend; esta revisão não executou o sistema com dados reais.

---

**English:** Management backend for intake, referrals, follow-up workflows and reporting in Women's Affairs.
