# Portfólio de Inteligência Artificial 🇧🇷

> **Autor(a):** _Seu Nome_  
> **Última atualização:** Julho 2025  
> **Objetivo:** Demonstrar competências práticas em IA (modelos preditivos e agentes), MLOps e engenharia de dados.

---

## 🗂️ Estrutura

```
portfolio-ia/
├── predictive-systems/      # Projetos de modelos preditivos (tabulares, séries temporais)
├── agents/                  # Projetos de agentes/LLMs (LangChain, CrewAI, etc.)
├── notebooks/               # Estudos exploratórios, provas de conceito, rascunhos de mestrado
└── README.md                # Você está aqui 🙂
```

- **`predictive-systems/`**  
  - `churn-prediction/` – Modelo de churn com XGBoost + explicabilidade SHAP  
  - `energy-forecast/` – Previsão de consumo energético com LSTM

- **`agents/`**  
  - `data-quality-validator/` – Agente LangChain que valida _data lakes_ migrados para nuvem  
  - `autonomous-ingestion/` – Agente CrewAI que automatiza ingestão e catalogação de tabelas

- **`notebooks/`**  
  Notebooks Jupyter usados para EDA, experimentos rápidos e artigos do mestrado.

---

## ⚙️ Ambiente

```bash
# Crie e ative o ambiente
conda create -n ia-portfolio python=3.11
conda activate ia-portfolio

# Instale dependências comuns
pip install -r requirements.txt
# ou se preferir pip-tools
pip-sync requirements.txt
```

Depêndencias principais:
- `scikit-learn` ≥ 1.5  
- `xgboost`  
- `tensorflow` / `torch`  
- `langchain`, `crewai`, `openai`  
- `mlflow`, `fastapi`, `docker`

---

## 🚀 Como executar um projeto

```bash
# Exemplo: churn-prediction
cd predictive-systems/churn-prediction
python src/train.py --config configs/train.yaml
mlflow ui  # visualizar métricas
```

Para os agentes:

```bash
cd agents/data-quality-validator
python app.py --config configs/agent.yaml
```

---

## 🛣️ Roadmap (2025 → 2026)

- [x] Estrutura inicial do repositório
- [x] Modelo de churn com pipeline de MLflow
- [ ] Fine‑tuning de BERT para classificação de tickets (Ago 2025)
- [ ] Agente de validação de dados usando LangGraph (Set 2025)
- [ ] Deploy CI/CD no GitHub Actions (Out 2025)
- [ ] Certificação **Google Cloud Generative AI** (Dez 2025)
- [ ] Certificação **AWS ML Specialty** (Jun 2026)

---

## 🎓 Certificações & Estudos

| Programa | Status | Data |
|----------|--------|------|
| Hugging Face LLM Course | Em andamento | Jul–Set 2025 |
| Google Cloud Gen AI Leader | 👀 agendado | Dez 2025 |
| TensorFlow Developer Certificate | Planejado | Jan 2026 |
| AWS ML Specialty | Planejado | Jun 2026 |

---

## 🤝 Contribuindo

Pull requests são bem‑vindos! Para mudanças maiores, abra uma _issue_ primeiro descrevendo o que pretende alterar.

1. Fork o repositório  
2. Crie uma branch (`git checkout -b feature/NovaFeature`)  
3. Commit suas mudanças (`git commit -m 'feat: Minha nova feature'`)  
4. _Push_ para a branch (`git push origin feature/NovaFeature`)  
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está licenciado sob os termos da licença **MIT** – consulte o arquivo `LICENSE` para detalhes.

---

## 📫 Contato

- LinkedIn: [seu‑linkedin](https://linkedin.com/in/seu-linkedin)
- Medium: [seu‑medium](https://medium.com/@seu-medium)
- E‑mail: `seu.email@dominio.com`
