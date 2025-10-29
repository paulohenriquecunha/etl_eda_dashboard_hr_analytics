# HR Analytics — Employee Attrition

Este projeto analisa a **rotatividade de funcionários** com base em um dataset de RH (simulado, Kaggle/IBM HR Attrition).  
O objetivo é entender **quem sai, por quê e qual o impacto financeiro**, utilizando **Python** (ETL + EDA + estatística) e **Power BI** (visualizações executivas e interativas).

---

## 🚀 Estrutura do Projeto
```
hr-analytics-portfolio/
│-- data/
│   ├─ WA_Fn-UseC_-HR-Employee-Attrition.csv
│   └─ WA_Fn-UseC_-HR-Employee-Attrition_clean.csv
│-- notebooks/
│   └─ 01_etl_eda_employee_attrition.ipynb
│-- dashboard/
│   ├─ dashboard_hr_employee_attrition.pbix
│   └─ dashboard_hr_employee_attrition.pdf
│-- docs/
│   ├─ documentation_en.txt
│   ├─ documentation_pt.txt
│   ├─ professional_report_en.pdf
│   └─ relatorio_profissional_pt.pdf
│-- README.md
```

---

## 📊 Perguntas de Negócio Respondidas
- Qual é a taxa de rotatividade da empresa?  
- Quais departamentos concentram mais saídas?  
- Qual perfil de colaborador tem maior risco de desligamento?  
- Existe relação entre tempo de casa, salário e saída?  
- Salário e satisfação influenciam a decisão de sair?  
- Qual o custo estimado da rotatividade e o potencial de economia?

---

## 🔎 Principais Resultados
- **Taxa geral de rotatividade**: 16,1% (237/1470).  
- **Departamentos críticos**: Vendas (20,6%) e RH (19%).  
- **Perfis de risco**: jovens até 25 anos, funcionários com até 1 ano de empresa, baixa renda e alta carga de horas extras.  
- **Impacto financeiro**: U$ 6,8 milhões.  
- **Economia potencial**: U$ 1,02 milhão (redução de 15% com programas de retenção, segundo benchmarks SHRM, Gallup, Deloitte).  

---

## 🛠️ Ferramentas Utilizadas
- **Python**: Pandas, Matplotlib, Seaborn.  
- **Power BI**: dashboards interativos, DAX.  
- **Relatórios**: documentação técnica e executiva (PDF).

---

## 📑 Relatório Profissional
O relatório completo está disponível em [`docs/Relatorio_Profissional.pdf`](./docs/Relatorio_Profissional.pdf).  
Ele inclui: Resumo Executivo, Objetivo, Dados, Metodologia, Resultados, Insights, Recomendações, Limitações e Apêndices.
