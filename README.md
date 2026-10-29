# Estudos de Ciência de Dados

Repositório de referência histórica, consolidando pequenos estudos e cases de ciência de dados produzidos entre 2019 e 2023. Cada subpasta corresponde a um repositório original, mantido com seu conteúdo integral (exceto arquivos removidos por motivo de privacidade/segurança — ver notas abaixo); o histórico de commits original permanece preservado nos repositórios arquivados individuais.

## Conteúdo

- [`azul/`](./azul) — Case de negócio sobre NPS da Azul.
- [`consulting/`](./consulting) — Notas de estudo.
- [`credit-risk-model/`](./credit-risk-model) — Projeto end-to-end de modelo de risco de crédito (Kaggle "Give Me Some Credit"), com infra de CI/CD e AWS.
- [`studies/`](./studies) — Coletânea de estudos diversos: interpretabilidade de modelos (SHAP), redução de dimensionalidade (PCA), modelos de classificação, engenharia de features, geodata, web scraping com Selenium, entre outros.
- [`uci_default_credit_card/`](./uci_default_credit_card) — Modelo de ML sobre o dataset público UCI "Default of Credit Card Clients".

## Notas de privacidade/segurança

- `credit-risk-model/task_definition.json` foi removido por conter um AWS Account ID e ARNs reais.
- `studies/selenium/temp/*.tmp` (PDFs públicos da CVM baixados durante um teste de scraping) foram removidos por serem apenas artefatos de execução, sem valor de conteúdo.

> Este repositório existe para preservar e organizar material de aprendizado. Para projetos atuais, veja o perfil principal: https://github.com/rknagao
