# DarkTech - Landing Page Dark Theme

Uma landing page moderna e elegante com tema escuro, desenvolvida com HTML5 e CSS3 puro, utilizando CSS Variables para fácil manutenção e customização.

## 🎨 Design

O projeto apresenta um design moderno focado em UI/UX com tema dark, proporcionando uma experiência visual sofisticada e profissional.

### Características Visuais

* **Tema Dark Completo**: Paleta de cores escuras com acentos em roxo/azul
* **Gradientes Modernos**: Efeitos visuais sutis e elegantes
* **Tipografia Hierárquica**: Sistema de fontes bem estruturado
* **Micro-interações**: Animações suaves e efeitos hover
* **Design Responsivo**: Adaptável a diferentes tamanhos de tela

## 🚀 Tecnologias Utilizadas

* **HTML5**: Estrutura semântica e acessível
* **CSS3**: Estilização avançada com recursos modernos
* **JavaScript (Vanilla)**: Interatividade e animações
* **CSS Variables**: Sistema de design escalável
* **CSS Grid & Flexbox**: Layout responsivo

## 📁 Estrutura do Projeto

```
darktech-landing/
├── index.html          # Arquivo principal
├── README.md           # Documentação do projeto
└── assets/             # (se necessário)
    └── images/         # Imagens do projeto
```

## ⚙️ Funcionalidades

### 🎯 Seções Principais

* **Header Fixo**: Navegação com efeito blur e transparência
* **Hero Section**: Apresentação impactante com call-to-actions
* **Features Grid**: Showcase de recursos em cards interativos
* **Footer Estruturado**: Links organizados e informações da empresa

### 🎪 Interatividade

* **Smooth Scrolling**: Navegação suave entre seções
* **Intersection Observer**: Animações de entrada para cards
* **Hover Effects**: Micro-interações em botões e cards
* **Responsive Design**: Adaptação automática para mobile

## 🎨 Sistema de Design

### CSS Variables Organizadas

```css
:root {
  /* Cores principais */
  --bg-primary: #0a0a0a;
  --bg-secondary: #1a1a1a;
  --text-primary: #ffffff;
  --accent-primary: #6366f1;
  
  /* Tipografia */
  --font-size-xl: 1.25rem;
  --font-size-3xl: 1.875rem;
  
  /* Espaçamento */
  --spacing-lg: 1.5rem;
  --spacing-xl: 2rem;
  
  /* Transições */
  --transition-normal: 0.3s ease;
}
```

## 🚀 Como Executar

1. **Clone ou baixe o projeto**
2. **Abra o arquivo `index.html`** em qualquer navegador moderno
3. **Pronto!** A landing page estará funcionando

```bash
# Se usar um servidor local (opcional)
python -m http.server 8000
# ou
npx serve .
```

## 📱 Responsividade

O projeto é totalmente responsivo e foi testado em:

* **Desktop**: 1200px+
* **Tablet**: 768px - 1199px
* **Mobile**: até 767px

### Breakpoints Principais

* `@media (max-width: 768px)`: Ajustes para mobile
* Layout em grid adaptável com `auto-fit`
* Navegação colapsada em telas pequenas

## 🎨 Customização

### Alterando Cores

Modifique as CSS Variables no `:root`:

```css
:root {
  --accent-primary: #your-color;
  --bg-primary: #your-bg-color;
}
```

### Adicionando Novos Cards

```html
<div class="feature-card">
  <div class="feature-icon">🎯</div>
  <h3>Seu Título</h3>
  <p>Sua descrição aqui...</p>
</div>
```

## 🌟 Destaques Técnicos

* **CSS Variables**: Sistema de design escalável
* **Semantic HTML**: Estrutura acessível e SEO-friendly
* **Modern CSS**: Grid, Flexbox, backdrop-filter
* **Vanilla JavaScript**: Performance otimizada
* **Cross-browser**: Compatível com navegadores modernos

## 📄 Licença

Este projeto é de uso educacional e pode ser utilizado livremente para fins de aprendizado.

## 👥 Desenvolvimento

**Desenvolvido em sala com Luan Oliveira** - Projeto educacional focado em práticas modernas de desenvolvimento web e design de interfaces com tema dark.

***

*Projeto criado para demonstrar técnicas avançadas de CSS, uso de variáveis CSS, design responsivo e implementação de UI/UX modernas com tema escuro.*
