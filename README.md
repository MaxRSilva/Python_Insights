# 📉 Análise de Cancelamento de Clientes (Churn) com Python

Este projeto simula um case real em que uma empresa com mais de 800 mil clientes enfrenta altos índices de cancelamento de seus serviços. A partir de uma amostra representativa (50 mil clientes), foram aplicadas técnicas de análise de dados para identificar padrões de cancelamento e sugerir ações estratégicas para retenção de clientes.

---

## 🧠 Objetivo

- Entender os principais fatores que levam clientes a cancelar seus contratos.
- Gerar insights estratégicos para reduzir o número de cancelamentos.
- Aplicar filtros e políticas baseadas em evidências extraídas dos dados.

---

## 📊 Passo a Passo do Projeto

1. **Importação e visualização dos dados**
   - Fonte: CSV contendo informações demográficas, comportamentais e contratuais dos clientes.

2. **Limpeza e tratamento**
   - Remoção de valores ausentes
   - Eliminação de colunas irrelevantes (como `CustomerID`)

3. **Análise Exploratória**
   - Frequência de cancelamento (absoluta e percentual)
   - Comparações gráficas entre as variáveis e o cancelamento (usando `plotly`)

4. **Geração de Insights**
   - Contratos mensais apresentaram altíssimo índice de churn → sugerido incentivo para planos mais longos.
   - Clientes com mais de 4 ligações ao call center têm maior probabilidade de cancelar → melhoria no atendimento sugerida.
   - Clientes com mais de 20 dias de atraso tendem a cancelar → proposta de política proativa para regularização em até 10 dias.

5. **Filtragem baseada nos insights**
   - Aplicação de filtros nos dados com base em ações corretivas simuladas.
   - Resultado: **queda do churn de 57% para 18%** com simples mudanças estratégicas.

---

## 📁 Estrutura


---

## 📈 Tecnologias Utilizadas

- Python 3.x
- Pandas
- NumPy
- Plotly
- Jupyter Notebook
- OpenPyXL (caso precise ler Excel)
- Google Colab (opcional)

---

## 🧩 Insights Gerados

- **Contrato mensal = risco de cancelamento**  
- **Atendimento ineficiente = cliente perdido**  
- **Atrasos prolongados = insatisfação**  

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/churn-analysis.git
   cd churn-analysis
