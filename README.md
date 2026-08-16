<p align="center">
  <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?q=80&w=1200&auto=format&fit=crop" alt="La Bella Cantina Banner" width="100%" style="border-radius: 12px; margin-bottom: 20px;">
</p>

# 🍕 La Bella Cantina — Cardápio Digital Interativo (Centro de São Paulo)

<p align="center">
  <strong>Aplicação Web Single Page (SPA) de alto impacto visual, ultra-veloz e 100% responsiva para foodtechs e pizzarias artesanais.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge" alt="Status">
</p>

---

## 📸 Conceito & Estética (Paulistana Vibe)

O **La Bella Cantina** traz o conceito marcante das tradicionais pizzarias do Centro de São Paulo (*vibe Bixiga, Consolação, República*): rústica, acolhedora, com receitas centenárias assadas em forno a lenha, aliada à mais moderna experiência de atendimento digital (Self-ordering SPA).

* 🎨 **Paleta de Cores**: Vermelho Terracota Rústico (`#9B2226` / `#AE2012`), Amarelo Ouro (`#EE9B00` / `#E9D8A6`) e Fundo Dark Carvão/Madeira (`#0D0D0D` / `#1A1A1A`).
* ✍️ **Tipografia Elegante**: Titulares em **Playfair Display** (estilo cantina italiana) e corpo em **Plus Jakarta Sans** (leitura cristalina de preços e ingredientes).
* ✨ **Efeitos Visuais**: Efeitos *Glassmorphism*, badges chamativas (*"🔥 Paulistana Raíz"*, *"⭐ Mais Pedida"*, *"🌱 Clássico Italiano"*), animações fluidas de modal e drawer off-canvas.

---

## 🔥 Funcionalidades Principais

### 1. 🍕 Personalizador Dinâmico de Pizzas (Modal)
* **Tamanhos**: Escolha entre **Grande (8 Pedaços)** e **Brotinho (4 Pedaços)**.
* **Modo Meio a Meio (2 Sabores)**: Selecione um 2º sabor para pizzas grandes, calculando automaticamente o valor com base na pizza de maior preço.
* **Bordas Recheadas**: Sem Borda (Grátis), Catupiry Original (+R$ 12), Cheddar (+R$ 12), Nutella (+R$ 15) e Doce de Leite (+R$ 14).
* **Observações Personalizadas**: Peça sem cebola, massa bem assada, etc.

### 2. 🔍 Busca em Tempo Real & Navegação Sticky
* Filtro por categorias em cápsulas deslizantes: `Pizzas Salgadas`, `Pizzas Doces`, `Brotinhos`, `Bebidas` e `Combos do Centro`.
* Barra de pesquisa instantânea por nome ou ingrediente (ex: *Catupiry, Guaraná, Tubaína*).

### 3. 🛒 Carrinho Lateral Off-Canvas com LocalStorage
* Detalhamento completo de cada produto, sabores selecionados, bordas e observações.
* **Persistência contínua**: O pedido não é perdido se a página for recarregada.
* **Sistema de Cupons de Desconto**:
  * `CENTRO10` (10% OFF)
  * `BIXIGA` (15% OFF)

### 4. 💳 Checkout Integrado & Envio Duplo
* Seleção entre **Delivery** (com cálculo automático de taxa e bairros do Centro de SP) ou **Retirada no Balcão**.
* Opções de pagamento: **PIX** (com chave Copia-e-Cola), **Cartão na Entrega** ou **Dinheiro** (com campo de troco).
* **Integração WhatsApp**: Botão *"Enviar Pedido via WhatsApp"* que formata automaticamente todo o carrinho com emojis e abre a conversa no WhatsApp.
* **Confirmação no Site**: Botão *"Concluir no Site"* com modal animado de status do pedido, cronômetro de entrega e chuva de confetes (`canvas-confetti`).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**: Estrutura acessível e otimizada para SEO.
* **Tailwind CSS (v3 CDN)**: Estilização utilitária com sistema de design customizado.
* **JavaScript ES6+ (Vanilla)**: Manipulação reativa de estado sem frameworks ou bibliotecas pesadas.
* **Lucide Icons**: Conjunto de ícones vetoriais modernos e leves.
* **Canvas Confetti**: Animação festiva no encerramento do pedido.
* **Google Fonts**: Fontes web `Playfair Display` e `Plus Jakarta Sans`.

---

## 🚀 Como Executar o Projeto

Como o projeto é construído em arquitetura autônoma (Single File SPA), não é necessária a instalação de dependências ou gerenciadores de pacotes (`npm`/`yarn`).

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/maluizaaf/cardapio-pizzaria.git
   ```
2. **Navegue até a pasta do projeto:**
   ```bash
   cd cardapio-pizzaria
   ```
3. **Abra o arquivo `index.html`:**
   Abra diretamente em qualquer navegador web (Google Chrome, Edge, Firefox, Safari) ou direto pelo celular.

---

## 📱 Responsividade (Mobile First)

A interface foi projetada com foco total na experiência mobile, garantindo:
* Botões e alvos de toque com dimensões confortáveis (mínimo 44px).
* Navegação deslizante rápida no polegar.
* Adaptabilidade perfeita para telas pequenas (smartphones) até monitores ultrawide (4K).


---

<p align="center">
  Desenvolvido com 🍕 e ☕ para enriquecimento de portfólio Front-End.
</p>
