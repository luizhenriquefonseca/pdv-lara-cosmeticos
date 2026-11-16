# 🛍️ PDV LH — Sistema de Ponto de Venda (Lara Cosméticos)

Sistema web de Ponto de Venda (PDV) e controle comercial desenvolvido sob medida para a **Lara Cosméticos**. A aplicação resolve a necessidade de registrar vendas, gerenciar produtos e acompanhar movimentações de forma rápida e intuitiva diretamente pelo navegador, sem depender de servidores complexos ou conexão constante para operar.

---

## ✨ Funcionalidades

- **Frente de Caixa (PDV):** Registro ágil de vendas com cálculo automático de totais.
- **Gestão de Dados Local:** Persistência completa via `localStorage`, garantindo resposta instantânea e funcionamento offline.
- **Portabilidade e Backup:** Funcionalidade de exportação de dados integrada na aba de Configurações, preparada para migração futura para banco de dados em nuvem (Supabase).
- **Interface Responsiva:** Layout limpo e focado na produtividade do operador de caixa.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica das telas e modais.
- **CSS3:** Estilização customizada, layout responsivo e identidade visual[cite: 1].
- **JavaScript (Vanilla):** Lógica de negócios, manipulação dinâmica do DOM, cálculos de venda e gerenciamento de estado no `localStorage`[cite: 1].

---

## 📂 Estrutura do Projeto

```text
pdv-lara-cosmeticos/
├── index.html          # Estrutura principal da aplicação[cite: 1]
├── style.css           # Folha de estilos e layout[cite: 1]
├── script.js           # Regras de negócio, eventos e persistência[cite: 1]
├── assets/             # Recursos visuais e ícones[cite: 1]
│   ├── images/
│   └── icons/
└── README.md           # Documentação do projeto[cite: 1]
