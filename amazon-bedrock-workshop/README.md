# Amazon Bedrock Workshop

> Fork do repositório oficial [aws-samples/amazon-bedrock-workshop](https://github.com/aws-samples/amazon-bedrock-workshop) — estudo e aplicação prática dos recursos do Amazon Bedrock

🔗 [Repositório original (aws-samples)](https://github.com/aws-samples/amazon-bedrock-workshop)  
🔗 [Workshop Guide (AWS Catalog)](https://catalog.workshops.aws/amazon-bedrock)

---

## Sobre o workshop

Workshop hands-on desenvolvido pela AWS para desenvolvedores e solution builders que querem aprender a usar os **foundation models (FMs)** do Amazon Bedrock. Os labs cobrem os principais padrões de uso de GenAI na AWS, desde inferência direta até RAG, agentes e modelos open-weight.

---

## Módulos do workshop

| Módulo | Tópico |
|--------|--------|
| `01_Inference_APIs` | Inferência direta com foundation models via Bedrock APIs |
| `02_Knowledge_Bases_and_RAG` | Knowledge Bases e Retrieval-Augmented Generation (RAG) |
| `03_Agents` | Bedrock Agents — orquestração e automação de workflows |
| `04_Open_Source_models` | Modelos open-weight via Bedrock |

> Os módulos seguem a numeração do repositório original. Consulte o [workshop guide](https://catalog.workshops.aws/amazon-bedrock) para instruções detalhadas de cada lab.

---

## Pré-requisitos técnicos

- Conta AWS com acesso ao **Amazon Bedrock** habilitado (incluindo permissão para subscrever modelos no AWS Marketplace)
- Python 3.11+
- AWS CLI configurado (`aws configure`)
- [`uv`](https://docs.astral.sh/uv/) — recomendado para gerenciar versões Python e virtualenvs
- Extensões de Jupyter e Python (se usar VS Code ou Kiro)

### Permissões AWS necessárias

- `Amazon Bedrock` — todos os labs
- `Amazon OpenSearch Serverless` + `Amazon S3` — labs de Knowledge Base / RAG
- `Amazon Bedrock AgentCore`, `AWS CloudFormation`, `Amazon DynamoDB`, `AWS IAM` — labs de agentes

---

## Setup do ambiente

```bash
# Com uv (recomendado)
uv venv .venv
source .venv/bin/activate
uv sync --all-extras --all-groups

# Com pip
pip install .[all]

# Instalação parcial (só os labs desejados, ex: lab2 e lab4)
pip install .[lab2,lab4]
```

---

## Executando os notebooks

Os exercícios usam arquivos `.ipynb`. Para rodar:

1. Abra o notebook no VS Code / Kiro
2. Selecione o kernel: **Python Environments > .venv**
3. Execute as células com `Shift+Enter` ou o botão ▶️

Comece pelo primeiro notebook:

```
01_Inference_APIs/01_Inference_APIs.ipynb
```

---

## Progresso

- [ ] Lab 01 — Inference APIs
- [ ] Lab 02 — Knowledge Bases & RAG
- [ ] Lab 03 — Agents
- [ ] Lab 04 — Open Source Models

---

## Notas e aprendizados

> Registre aqui insights, dificuldades e descobertas durante os labs.

---

## ⚠️ Aviso de custos

Executar os exemplos na sua conta AWS gera custos. Lembre-se de rodar os **cleanup steps** ao finalizar cada lab para evitar cobranças desnecessárias.

---

## Referências

- [Amazon Bedrock — Documentação oficial](https://docs.aws.amazon.com/bedrock/latest/userguide/)
- [aws-samples/amazon-bedrock-samples](https://github.com/aws-samples/amazon-bedrock-samples) — exemplos adicionais
- [AWS Solutions Library — AI](https://aws.amazon.com/solutions/ai/)
