# PDV LH — Lara Cosméticos

Sistema de ponto de venda (PDV) da Lara Cosméticos. Funciona direto no navegador, sem banco de dados externo:
os dados ficam salvos no próprio navegador (localStorage).

## Estrutura

```
LARA-COSMETICOS-PDV/
├── index.html   Estrutura da página
├── style.css    Todos os estilos
├── script.js    Toda a lógica do sistema
├── assets/
│   ├── images/  (reservada)
│   └── icons/   (reservada)
└── README.md
```

## Como abrir

- No VS Code com Live Server: clique com o botão direito em `index.html` > "Open with Live Server".
  Se o navegador mostrar a lista de pastas, entre em `LARA-COSMETICOS-PDV`.
- Ou dê dois cliques em `index.html`.

## Observações

- Os dados ficam salvos por endereço. Abrir pelo Live Server (127.0.0.1:5500) e abrir o arquivo direto
  (file://) usam espaços de dados diferentes. Escolha um jeito e use sempre o mesmo.
- Limpar os dados do navegador apaga os cadastros e as vendas.
- Em Configurações há o botão "Exportar para o novo PDV", usado para levar os dados para a versão com Supabase no futuro.
