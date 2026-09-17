# 📊 Dinâmica do Mercado de Ações — Painel de Análise em Excel

Projeto de análise de dados em Excel que simula a operação de uma corretora: uma base de
**2.000 transações** (compra e venda de ações) de aproximadamente 90 clientes ao longo de 2023,
transformada em estatísticas, tendências e uma página de gráficos consolidada.

## 🎯 Objetivo

Demonstrar domínio de Excel para análise de dados: desde a base bruta de transações até
indicadores, tabelas dinâmicas e visualizações gráficas — sem depender de nenhuma ferramenta
externa, tudo dentro da própria planilha.

## 🗂️ Estrutura da planilha

| Aba | Conteúdo |
|---|---|
| `mercado_acoes` | Base bruta com as 2.000 transações (cliente, ação, operação, preço, data) |
| `cliente` | Consulta de um cliente específico por código (nome, e-mail, perfil, resultados) |
| `estatística` | Medidas estatísticas dos preços negociados (média, mediana, moda, desvio padrão etc.) |
| `tendencia_temporal` | Quantidade de operações por mês, ao longo do ano |
| `compra_venda` | Tabela dinâmica: totais gerais por tipo de operação |
| `cliente_compra_venda` | Tabela dinâmica: totais por cliente |
| `cliente_lucro_prejuizo` | Tabela dinâmica: lucro/prejuízo por ação, para o cliente selecionado |
| **`gráficos`** | Página consolidada com 6 gráficos, um para cada aba de análise |

## 🛠️ Técnicas utilizadas

- Fórmulas de agregação condicional (`SOMASE`, `SOMASES`, `CONT.SES`, `MÉDIASE`)
- `PROCX` (XLOOKUP) para consulta dinâmica de cliente por código
- Tabelas dinâmicas (Pivot Tables) para totais por operação e por cliente
- Estatística descritiva (média, mediana, moda, variância, desvio padrão)
- 6 tipos de gráficos nativos do Excel: barras, linha, pizza, rosca, dispersão e área
- Formatação condicional e organização visual da página de resultados

## ⚠️ Nota sobre os dados

Todos os nomes, e-mails e códigos de clientes são fictícios, gerados apenas para fins de
demonstração. Nenhum dado real foi utilizado.
