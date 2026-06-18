# Dashboard de Vendas - Restaurante

Dashboard web de faturamento de um restaurante (com múltiplas lojas), desenvolvido com **Dash** e **Plotly**. Lê os dados de uma planilha Excel e exibe gráficos interativos com filtro por loja.

## 🧰 Tecnologias
- Python 3
- Dash • Plotly • Pandas • openpyxl

## 📂 Estrutura
| Arquivo | Descrição |
|---------|-----------|
| `projeto/restauranteLTDA.py` | Aplicação Dash |
| `projeto/Vendas.xlsx` | Base de dados de vendas |

## 📊 Recursos
- Aba "Visão Geral": quantidade de produtos por loja (com dropdown de filtro)
- Aba "Análise de Faturamento": percentual de vendas por loja (gráfico de pizza)

## ▶️ Como executar
```bash
pip install dash plotly pandas openpyxl
cd projeto
python restauranteLTDA.py
```
O dashboard ficará disponível em `http://localhost:8050`.
