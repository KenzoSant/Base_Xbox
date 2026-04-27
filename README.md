# Projeto Xbox Game Pass - Análise de Vendas e Assinaturas

<img width="1480" height="738" alt="Captura de tela 2026-04-27 202146" src="https://github.com/user-attachments/assets/d7868a0d-b099-4c40-bf62-d6c1b1e13595" />

## Visão Geral

Este projeto tem como objetivo analisar os dados de assinantes do **Xbox Game Pass**, incluindo informações sobre planos, tipos de assinatura, renovação automática, adesão a add-ons (EA Play e Minecraft Season Pass), uso de cupons e receita gerada. Os dados estão organizados em uma planilha Excel com múltiplas abas, contendo desde a base bruta de assinantes até cálculos agregados e um dashboard visual.

## Estrutura do Arquivo Excel

O arquivo `Base_Xbox.xlsx` contém as seguintes abas:

### 1. Bases
- **Descrição**: Dados brutos de cada assinante.
- **Colunas principais**:
  - `Subscriber ID`: Identificador único do assinante.
  - `Name`, `Plan`, `Start Date`, `Auto Renewal`, `Subscription Price`, `Subscription Type`.
  - `EA Play Season Pass`, `EA Play Season Pass Price`.
  - `Minecraft Season Pass`, `Minecraft Season Pass Price`.
  - `Coupon Value`, `Total Value`.

### 2. Calculos
- **Descrição**: Tabelas consolidadas com métricas e indicadores.
  - **Plano x Tipo de Assinatura**: Soma do valor total por plano (Core, Standard, Ultimate).
  - **Plano x Tipo de Renovação**: Contagem de assinantes por plano e período (Annual, Monthly, Quarterly).
  - **Assinantes EA**: Número de assinantes do EA Play e receita gerada.
  - **Assinantes Minecraft**: Número de assinantes do Minecraft Season Pass e receita gerada.
  - **Plano x Cupom**: Assinantes e valor total de cupons por plano.
  - **Renda Anual (Meses)**: Distribuição mensal da soma do `Total Value`.

### 3. Dashboard
- **Descrição**: Painel resumido com título e possíveis visualizações (dados não totalmente preenchidos no exemplo).

## Principais Métricas Calculadas

- **Total de assinantes**: 295
- **Receita total**: 7.633
- **Distribuição por plano**:
  - Core: 444
  - Standard: 1.801
  - Ultimate: 5.388
- **Add-ons mais contratados**:
  - Minecraft Season Pass: 194 assinantes (receita 3.880)
  - EA Play Season Pass: 98 assinantes (receita 2.940)
- **Uso de cupons**: 2.122 no total, com destaque para o plano Standard (1.079)
