# SyntaxWear — Tênis e Sneakers Online

Projeto estático (HTML/CSS/JS) de uma loja de tênis chamada **SyntaxWear**. Esta repo contém a landing/home estática com componentes CSS modulares, imagens e recursos estáticos prontos para visualização local.

## Descrição

Pequeno projeto front-end que demonstra uma página de e-commerce estática para venda de tênis e sneakers. A página inclui uma área de hero, categorias, grade de produtos e um footer com formulário de newsletter e links sociais.

Meta title extraído: `SyntaxWear - Tênis e Sneakers Online`

Meta description extraído: "Compre os melhores tênis e sneakers online na SyntaxWear. Encontre modelos exclusivos, ofertas imperdíveis e frete grátis para todo o Brasil."

## Estrutura de pastas

Raiz do projeto (resumo):

- `index.html` — página principal
- `css/` — estilos principais
	- `variables.css`, `reset.css`, `base.css`, `layout.css`
	- `components/` — estilos por componente:
		- `header.css`, `hero.css`, `product-category.css`, `product-grid.css`, `product-card.css`, `panel.css`, `newsletter.css`, `footer.css`
- `images/`
	- `banners/` (ex.: `hero.jpg`, `hero-mobile.jpg`)
	- `icons/` (ícones SVG: `hamburguer.svg`, `user.svg`, `help.svg`, `bag.svg`, `instagram.svg`, `whatsapp.svg`, `tiktok.svg`, `facebook.svg`)
	- `logo/` (`logo.svg`)
	- `products/` (imagens de produtos e grids)
- `js/` — scripts (pasta presente para comportamento/integração)
- `docs/`, `fonts/` — recursos adicionais

> Observação: o CSS está organizado em arquivos base + components, facilitando manutenção e reuso.

## Como rodar localmente

Opções rápidas (Windows / PowerShell):

1) Abrir `index.html` diretamente no navegador (duplo clique ou):

```powershell
Start-Process .\index.html
```

2) Servir por um servidor HTTP simples (recomendado para evitar problemas com rotas/paths):

Se tiver Python instalado:

```powershell
# no diretório do projeto
python -m http.server 8000
# depois abra http://localhost:8000
```

Ou, se preferir Node e `http-server` via npx:

```powershell
npx http-server . -p 8000
# depois abra http://localhost:8000
```

3) Usar a extensão Live Server do VS Code — botão "Go Live".

## Como contribuir

- Crie uma issue descrevendo a proposta ou bug.
- Abra um branch com nome significativo (`feature/`, `fix/`), faça commits claros e um PR explicando a mudança.
- Mantenha a consistência do CSS (arquivos em `css/components/`) e otimize imagens ao adicionar novas.

## Notas de desenvolvimento

- Arquitetura CSS: variáveis + reset + base + layout + componentes. Ideal para migrar para um pré-processador (Sass) se o projeto crescer.
- Otimização de imagens: use versões otimizadas para produção e sprites/SVG quando possível.
- A pasta `js/` está pronta para scripts de interação (carrinho, filtros, etc.).

## Licença

Sugestão: `MIT` — atualize conforme necessário. (Se quiser, eu adiciono um arquivo `LICENSE` com o texto MIT.)

## Contato / Autor

Repositório: `ecommerce-syntaxweatr` (owner: Emanuel13pel). Para dúvidas, abra uma issue.

---