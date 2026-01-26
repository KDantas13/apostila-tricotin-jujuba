# Apostila de Tricotin - Jujuba I-Cords

Este repositório contém o código-fonte da página de vendas da **Apostila de Tricotin** da Jujuba I-Cords.

## 🚀 Sobre o Projeto

A página foi desenvolvida para vender o acesso a 150 moldes/padrões de tricotin por R$ 35,00. Ela possui um design moderno, responsivo e focado em conversão.

### Funcionalidades:
- **Design Responsivo:** Otimizado para dispositivos móveis e desktop.
- **Integração com Kiwify:** Botões de compra direcionando para o checkout.
- **Integração com Instagram:** Links diretos para o perfil da Jujuba I-Cords.
- **Google Analytics:** Rastreamento de conversões configurado (ID: AW-16459616921).
- **Galeria de Imagens:** Exibição de exemplos reais dos moldes.

## 🛠️ Como Editar

Se você precisar fazer alterações básicas no futuro, aqui estão os pontos principais no arquivo `index.html`:

### Alterar o Preço
Procure por `R$ 35,00` no código e substitua pelo novo valor.

### Alterar o Link de Compra
Procure pela função `buyNow()` no final do arquivo e altere a URL:
```javascript
function buyNow() {
    window.open('https://pay.kiwify.com.br/IQ3gS8v', '_blank');
}
```

### Alterar o Link do Instagram
Procure pela função `openInstagram()` no final do arquivo:
```javascript
function openInstagram() {
    window.open('https://www.instagram.com/jujuba_icords...', '_blank');
}
```

## 📦 Arquivos
- `index.html`: Arquivo principal da página.
- `IMG_*.jpeg`: Imagens dos produtos exibidas na galeria.

---
Desenvolvido com ❤️ para Jujuba I-Cords.
