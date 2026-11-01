# Amor em Camadas

Site institucional e vitrine da **Amor em Camadas**, loja de bolos de pote, tortas e potes da felicidade, em São Paulo. Os pedidos são combinados diretamente pelo WhatsApp.

## Sobre o projeto

A proprietária precisava de um site para apresentar os produtos e facilitar os pedidos. Como não há pagamento online, o site funciona como uma vitrine, e cada botão leva o cliente para o WhatsApp da loja.

## Tecnologias

- HTML5 semântico
- CSS gerado a partir de SCSS (Sass)
- Fontes do Google Fonts: Fraunces (títulos) e Nunito Sans (texto)
- Extensões do VS Code: Live Server e Live Sass Compiler

## Estrutura de pastas

```
amorEmCamadas/
├── images/
│   ├── icon.png
│   └── logo.png
├── pages/
│   └── index.html
├── styles/
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
└── README.md
```

## Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/GabrielSTNS/amorEmCamadas
   ```
2. Abra a pasta no VS Code.
3. Instale as extensões **Live Server** e **Live Sass Compiler**.
4. Clique em **Watch Sass** na barra de status para compilar o `style.scss` em `style.css`.
5. Clique com o botão direito em `pages/index.html` e escolha **Open with Live Server**.

> O HTML deve apontar para o `style.css`, e não para o `style.scss`.

## Identidade visual

| Cor       | Hex       | Uso                      |
| --------- | --------- | ------------------------ |
| Terracota | `#a94e2c` | Cor principal, fundos    |
| Marrom    | `#7a3a20` | Textos de botões e links |
| Creme     | `#fff8f0` | Fundos claros e botões   |
| Café      | `#3b2217` | Texto sobre fundo claro  |

Fontes: **Fraunces** (peso 800) nos títulos e **Nunito Sans** (pesos 400 e 700) no texto.

## Status

- [x] Cabeçalho com logo e botão do WhatsApp
- [x] Seção hero
- [x] Seção "Mais pedidos"
- [ ] Rodapé (WhatsApp, Instagram, cidade de atendimento e prazo de encomenda)
- [ ] Página de produto
- [ ] Tela "Monte seu pedido"
- [ ] Trocar as imagens de teste pelas fotos oficiais da loja
- [ ] Trocar os `href="#"` pelo link real do WhatsApp (`https://wa.me/55DDDNUMERO?text=...`)
- [ ] Revisar o SEO (title, description e `alt` das imagens em cada página)

## Autor

Desenvolvido por **Gabriel Santana**.
