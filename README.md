# 📊 Dashboard Xbox - Análise de Assinaturas

Este projeto tem como objetivo analisar os dados de assinaturas de serviços relacionados ao Xbox, estruturando informações em um dashboard interativo no Excel, com base em perguntas de negócio.

---

## 📁 Estrutura da Planilha

A planilha é composta por três áreas principais:

### 1. `Base_Assinantes`
Tabela com todos os dados brutos:
- ID do Assinante
- Nome
- Tipo de Plano: `Core`, `Standard`, `Ultimate`
- Data de Início
- Valor da Assinatura
- Cupons Aplicados
- EA Play / Minecraft Season Pass
- Status de Renovação Automática

### 2. `Resumo_Dinamico`
Contém as Tabelas Dinâmicas que respondem às perguntas de negócio com os dados tratados.

### 3. `Dashboard`
Interface visual com gráficos, filtros suspensos e resumos automáticos para facilitar a análise.

---

## ❓ Perguntas de Negócio

### 🧩 Pergunta 1
**Qual o faturamento total de vendas de planos anuais?**
- **Dado gerado:** R$ 3.571,00
- **Gráfico:** Colunas verticais agrupadas

---

### 🧩 Pergunta 2
**Qual o faturamento dos planos anuais por status de renovação automática?**
- **Dado gerado:**  
  - `Yes`: R$ 747,00  
  - `No`: R$ 2.824,00
- **Gráfico:** Gráfico de colunas lado a lado

---

### 🧩 Pergunta 3
**Total de vendas de assinaturas EA Play**
- **Dado gerado:** R$ 1.350,00
- **Gráfico:** Coluna por tipo de plano (só *Ultimate* possui)

---

### 🧩 Pergunta 4
**Total de vendas de Minecraft Season Pass**
- **Dado gerado:** R$ 1.800,00
- **Gráfico:** Coluna comparando *Standard* e *Ultimate*

---

### 🧩 Pergunta 5
**Distribuição de assinantes por tipo de plano e status de renovação**
- **Dado gerado:** Tabela cruzada
- **Gráfico:** Barras empilhadas

---

### 🧩 Pergunta 6
**Valor total em cupons aplicados por plano**
- **Dado gerado:** Soma por tipo de assinatura
- **Gráfico:** Colunas agrupadas

---

### 🧩 Pergunta 7
**Ticket médio por tipo de assinatura**
- **Dado gerado:**  
  Exemplo:  
  - `Ultimate`: R$ X  
  - `Standard`: R$ Y  
- **Gráfico:** Colunas

---

### 🧩 Pergunta 8
**Quantas pessoas têm cada tipo de plano?**
- **Dado analisado:** Contagem de `Subscriber ID` por `Subscription Type`
---

## 🎨 Recursos Visuais

O dashboard foi estilizado com cores temáticas:
- Verde Xbox: `#9BC848`
- Aqua: `#2AE6B1`
- Neutro: `#E8E6E9`

Foi utilizado segmentação de dados para filtragem dinâmica e tabelas com fórmulas automatizadas (SOMASES, CONT.SES, MÊS, entre outras).

---

## 🚀 Como usar

1. Baixe a planilha `.xlsx` do repositório
2. Abra no Excel (preferencialmente 2019 ou superior)
3. Navegue até a aba `Dashboard` para interagir com os filtros e gráficos


