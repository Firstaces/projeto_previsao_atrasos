# projeto_previsao_atrasos

# Projeto: Previsão de Atraso em Entregas de Contratos

Este projeto tem como objetivo aplicar técnicas de Machine Learning para prever se um contrato será entregue com atraso, com base em dados simulados e variáveis de negócio. O modelo foi treinado em Python e os resultados foram analisados e visualizados no Power BI.

## 🔍 Problema

Prever atrasos em entregas de contratos pode ajudar empresas a tomarem decisões mais estratégicas, evitar prejuízos e melhorar a gestão de equipes e prazos.

## 🧠 Etapas do Projeto

1. **Criação de dados fictícios** com lógica de negócio  
2. **Pré-processamento dos dados** com Label Encoding  
3. **Treinamento de modelo de classificação** (Random Forest)  
4. **Avaliação da acurácia e desempenho do modelo**  
5. **Exportação dos dados com previsões**  
6. **Integração com Power BI via script Python**  
7. **Criação de dashboard interativo** comparando previsão x realidade  

## 🧰 Tecnologias Utilizadas

- Python (pandas, numpy, scikit-learn, joblib)  
- Power BI (com script Python)  
- Streamlit (opcional)  
- FPDF (para relatório em PDF)  

## 📊 Resultado

O modelo atingiu **95% de acurácia** e foi avaliado com base na comparação entre os dados reais simulados e as previsões.

### Visual do Dashboard (Power BI):

![Dashboard](./Captura%20de%20tela%202025-08-04%20181037.png)

📄 [Ver versão em PDF do Dashboard](./Dashboard_PowerBI_Previsao_Atrasos.pdf)

## 📁 Arquivos do Repositório

- `criar_dados_ficticios.py` – geração dos dados simulados  
- `treinar_modelo.py` – pré-processamento, treino e exportação  
- `contratos_com_previsoes.csv` – dados prontos para análise  
- `modelo_atraso_contratos.pkl` – modelo treinado salvo  
- `Dashboard_PowerBI_Previsao_Atrasos.pdf` – versão em PDF do dashboard  
- `README.md` – este arquivo  

## 💬 Autoria

Projeto criado por **Andreia Ferreira**, conectando ciência de dados com análise de negócios em Power BI.  
Em aprendizado contínuo com foco em projetos reais e aplicáveis.

---

⭐ Se você gostou deste projeto, não esqueça de deixar uma estrela e compartilhar!
