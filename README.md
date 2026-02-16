# Intent-Analysis-in-Large-Scale-ChatGPT-Conversations


This repo contains a single notebook:

- `Humaid-Ilyas-assignment1.ipynb`

It analyzes the **WildChat** dataset (Parquet shards) and answers two research questions:

- **RQ1:** What latent prompt topics emerge in WildChat, and how does the topic distribution of U.S. users differ from users in the rest of the world?
- **RQ2:** Do GPT-3.5 and GPT-4 differ in language mix, and is Chinese relatively more prevalent in GPT-3.5 conversations?

Dataset reference: WildChat (ICLR 2024). :contentReference[oaicite:0]{index=0}  
Related large-scale chat logs (context): LMSYS-Chat-1M. :contentReference[oaicite:1]{index=1}

---

## 1) Setup

### Environment
Recommended: Python 3.10+

Install dependencies:
```bash
pip install -U pandas pyarrow numpy scikit-learn matplotlib seaborn statsmodels scipy wordcloud
