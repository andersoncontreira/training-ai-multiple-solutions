# Amazon Bedrock AgentCore: Build AI Agents on AWS [HANDS-ON]

> Curso Udemy — prática e exploração dos recursos do Amazon Bedrock AgentCore

🔗 [Acessar curso na Udemy](https://www.udemy.com/course/amazon-bedrock-agentcore-build-ai-agents-on-aws-hands-on/)

---

## Sobre o curso

Curso hands-on focado em desenvolvimento e deploy de AI Agents serverless na AWS usando o **Amazon Bedrock AgentCore**. Cobre desde a construção de agentes com frameworks open-source (CrewAI) até observabilidade, memória e identidade em produção.

**Nível:** Avançado  
**Pré-requisitos recomendados:** familiaridade com Amazon Bedrock e Agentic AI

---

## Estrutura do curso

| Seção | Tópico | Pasta |
|-------|--------|-------|
| 1 | Course Overview | — |
| 2 | AgentCore Building Blocks & Primitives | `section-02-building-blocks/` |
| 3 | Build Agentic AI App from Scratch — Personal Vacation Planner (CrewAI) | `section-03-vacation-planner/` |
| 4 | AgentCore Runtime — Lambda + API Gateway | `section-04-runtime/` |
| 5 | Observability — OpenTelemetry & CloudWatch | `section-05-observability/` |
| 6 | Identity & Gateway — AgentCore Gateway + Agent Tools | `section-06-identity-gateway/` |
| 7 | Memory — Context e Session Memory | `section-07-memory/` |
| 8 | Refresher: Agentic AI, CrewAI e MCP | `section-08-refresher/` |

---

## Pré-requisitos técnicos

- Conta AWS com acesso ao **Amazon Bedrock** habilitado
- Python 3.11+
- AWS CLI configurado (`aws configure`)
- [`uv`](https://docs.astral.sh/uv/) (recomendado para gerenciar ambientes Python)

### Setup do ambiente

```bash
uv venv .venv
source .venv/bin/activate
uv sync
```

Ou com pip:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

---

## Permissões AWS necessárias

- `Amazon Bedrock` — todas as seções
- `Amazon Bedrock AgentCore` — seções 3 a 7
- `AWS Lambda` + `API Gateway` — seção 4
- `Amazon CloudWatch` — seção 5
- `AWS IAM` — seções 6 e 7

---

## Progresso

- [ ] Seção 2 — Building Blocks
- [ ] Seção 3 — Vacation Planner (CrewAI)
- [ ] Seção 4 — AgentCore Runtime
- [ ] Seção 5 — Observability
- [ ] Seção 6 — Identity & Gateway
- [ ] Seção 7 — Memory
- [ ] Seção 8 — Refresher

---

## Notas e aprendizados

> Registre aqui insights, dificuldades e descobertas durante o curso.

---

## Referências

- [Amazon Bedrock AgentCore — Documentação oficial](https://docs.aws.amazon.com/bedrock/latest/userguide/agentcore.html)
- [CrewAI](https://docs.crewai.com/)
- [OpenTelemetry](https://opentelemetry.io/)
