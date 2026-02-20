# Documentação Arquitetural: Modos de Operação do Assistente (Professor Xavier)

![DIO Bootcamp](https://img.shields.io/badge/DIO-Bootcamp-blue)
![AI Assistant](https://img.shields.io/badge/AI-Data_Science_Mentor-darkgreen)
![Prompt Engineering](https://img.shields.io/badge/Prompt-Engineering-gray)

O presente repositório documenta os modos de operação do assistente técnico estruturado para a resolução de problemas complexos em Ciência de Dados, Engenharia Geoespacial e Inteligência de Mercado. A arquitetura modular do copiloto permite transitar entre o diagnóstico passivo, a estruturação metodológica e a implementação autônoma de pipelines de dados, garantindo rigor estatístico e otimização computacional (Python/Google Earth Engine). Selecione o modo de operação adequado à etapa do seu ciclo analítico.

---

## Modo ASK (Consultoria e Diagnóstico)
O modo **Ask** é projetado para análise diagnóstica e elucidação teórica, operando estritamente em **somente leitura**. O assistente atua como um consultor técnico sênior.

Utilização recomendada para:
* Diagnóstico de anomalias estatísticas e vazamento de dados (Data Leakage).
* Análise de stack traces complexos (ex: falhas de alocação de memória no Pandas ou desalinhamento de tensores).
* Compreensão de lógicas de negócio e arquiteturas de dados existentes.
* **Restrição:** Este modo não gera alterações no repositório; seu foco é fornecer a fundamentação para a tomada de decisão técnica.

📄 **Prompt:** [prompts/prompt-ask.md](prompts/prompt-ask.md)

---

## Modo EDIT (Refatoração e Otimização)
O modo **Edit** é focado na intervenção direta em blocos de código pré-existentes, visando a excelência em engenharia de software e eficiência de processamento.

Aplicações de engenharia exigidas:
* Adequação estrita à PEP 8, inserção de Type Hinting e Docstrings detalhadas.
* Refatoração de rotinas iterativas (loops) para operações vetorizadas via NumPy ou Pandas.
* Otimização de consultas SQL complexas (Window Functions) e processamento espacial (PostGIS).
* Aprimoramento de complexidade algorítmica e tratamento de exceções.

📄 **Prompt:** [prompts/prompt-edit.md](prompts/prompt-edit.md)

---

## Modo PLAN (Planejamento Metodológico)
O modo **Plan** antecede a fase de codificação. O assistente estrutura metodologias robustas para mitigar riscos computacionais e garantir o alinhamento com os KPIs de negócios.

Entregáveis desta fase:
* Escopo analítico e premissas estatísticas.
* Arquitetura do pipeline de dados (ETL/ELT) e integração de ecossistemas (ex: processamento local vs. nuvem).
* Definição de métricas de validação de modelos de Machine Learning (RMSE, AUC-ROC).
* Mapeamento de potenciais falhas de arquitetura antes da alocação de recursos computacionais.

📄 **Prompt:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

---

## Modo AGENT (Implementação de Engenharia)
O modo **Agent** opera com autonomia supervisionada para a construção de soluções ponta a ponta. O assistente transforma os requisitos de inteligência de mercado em código implementável.

Capacidades operacionais:
* Construção e modularização de scripts Python para ingestão e tratamento de Big Data.
* Treinamento, validação e otimização de modelos preditivos (Scikit-learn, XGBoost).
* Automação de geoprocessamento integrando bases governamentais e processamento em nuvem.
* Foco na tradução de resultados quantitativos em Business Insights estratégicos.

📄 **Prompt:** [prompts/prompt-agent.md](prompts/prompt-agent.md)

---

## Modo STUDY (Mentoria Acadêmica)
O modo **Study** é dedicado ao aprofundamento rigoroso nas bases matemáticas e estatísticas que sustentam a Ciência de Dados.

Metodologia de ensino aplicada:
* Progressão estruturada: da nomenclatura técnica à intuição matemática (Cálculo e Álgebra Linear).
* Demonstração prática via blocos de código vetoriais e comentados.
* Identificação de trade-offs computacionais e armadilhas estatísticas frequentes.
* Checkpoints cognitivos para atestar a compreensão antes de avançar na complexidade arquitetural.

📄 **Prompt:** [prompts/prompt-study.md](prompts/prompt-study.md)

---

## Resumo Executivo das Operações
* **Ask:** Diagnóstico de anomalias e fundamentação teórica estrita.
* **Edit:** Otimização de complexidade algorítmica e refatoração de código legado.
* **Plan:** Arquitetura metodológica preditiva e mapeamento de riscos.
* **Agent:** Desenvolvimento automatizado de pipelines analíticos ponta a ponta.
* **Study:** Aprofundamento acadêmico e consolidação de modelos matemáticos.
