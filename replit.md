# ML × MP — Conciliação 360°

Ferramenta de conciliação financeira para sellers do Mercado Livre e Mercado Pago.

## O que faz

- Carrega relatórios CSV/XLSX do Mercado Pago (Dinheiro em conta, Vendas extraídas, Faturamento MP) e do Mercado Livre (Faturamento ML, Vendas, Full)
- Cruza as bases usando `EXTERNAL_REFERENCE = N.º de venda`
- Gera KPIs consolidados: bruto, líquido, comissões, frete, rebates e delta
- Lista filtrada/ordenável de pedidos com status de conciliação
- Modal por pedido com razão completo, cascata financeira e dados de NF-e
- Exportação para CSV

## Como rodar

```
node server.js
```

Serve o arquivo `index.html` na porta 5000.

## User preferences

- Linguagem: Português (pt-BR)
- Interface dark com design JetBrains Mono + DM Sans
