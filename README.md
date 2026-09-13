# 📊 Dashboard Superstore - Análise de Vendas, Lucro e Devoluções

Este projeto apresenta uma solução completa de Business Intelligence desenvolvida no **Tableau Desktop** sobre a base de dados Superstore. O painel foi construído utilizando um fluxo de navegação estruturado em três níveis de detalhamento (**Roll-Up** e **Drill-Down**).

---

## 📌 1. Visão Geral (Roll-Up)
Visão executiva focada no acompanhamento dos indicadores macro da empresa, como Total de Vendas ($2,3M), Lucro ($292,3K), Margem de Lucro (13%) e Volume de Clientes.

<img width="1544" height="953" alt="Painel 1" src="https://github.com/user-attachments/assets/da738c33-22e7-4fea-8082-b83a4660e8c1" />

**Destaques:**
- Distribuição geográfica de clientes e volume de vendas por país e cidade.
- Análise de receita segmentada (Consumidor representou a maior base com 391 clientes).
- Tendência de crescimento de receita ao longo dos anos (atingindo $745,6K em 2026).

---

## 🔍 2. Visão Aprofundada de Vendas e Lucro (Drill-Down 1)
Nível intermediário focado na identificação de gargalos operacionais e performance por categorias e canais de envio.

<img width="1546" height="954" alt="image" src="https://github.com/user-attachments/assets/b36f5036-e629-4428-919e-818f24b170ce" />

**Destaques:**
- Evolução mensal das vendas revelando sazonalidade de picos ao longo do ano.
- Quebra de receita e volume por **Região** (Região Central liderando com $792,7K / 34,07%).
- Desempenho por **Modo de Envio** (Classe Padrão domina as entregas com $1.378,8K).
- Matriz de vendas relacionando Categoria de Produto (Tecnologia, Móveis, Material de Escritório) com o Segmento do Cliente.

---

## 📦 3. Análise de Clientes e Devoluções (Drill-Down 2)
Análise detalhada voltada para a gestão da qualidade, devoluções de produtos e classificação de clientes.

<img width="1545" height="954" alt="image" src="https://github.com/user-attachments/assets/fd6120ce-b9fe-4f44-a862-31d038703bba" />

**Destaques:**
- Monitoramento do impacto financeiro: 296 itens devolvidos (taxa de 7,86%), gerando $23,2K em lucro perdido.
- Ranking do **Top 10 Clientes Mais Lucrativos** (liderado por Carolina Ferreira com $8.981 em lucro).
- Lista dos **Top 20 Produtos com Mais Devoluções** para ações preventivas de estoque/fornecedor.
- Gráfico de dispersão (*Vendas x Lucro por Cliente*) dividindo a carteira entre Baixo Valor, Valor Moderado, Alto Valor e Clientes Destaque.

---

## 🛠️ Tecnologias Utilizadas
- **Tableau Desktop**: Design de layout, cálculos de indicadores, parâmetros e ações de navegação interativas.
- **Mapbox / OpenStreetMap**: Mapeamento geográfico de vendas.
