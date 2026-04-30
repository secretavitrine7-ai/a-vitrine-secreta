# A Vitrine Secreta

Site estático para uma vitrine de produtos com links de afiliado.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub para este projeto.
2. Envie os arquivos `index.html`, `styles.css` e `README.md`.
3. No GitHub, abra `Settings` > `Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch principal e a pasta `/root`.
6. Salve e aguarde o link público ser gerado.

## Como adicionar produtos

Duplique um bloco `<article class="product-card">` em `index.html` e altere:

- imagem;
- nome;
- links de compra.

Depois duplique também o bloco `<div class="image-modal">` correspondente ao
produto e use um `id` único. O link da imagem do card deve apontar para esse
mesmo `id`, por exemplo:

- card: `href="#nome-do-produto"`;
- modal: `id="nome-do-produto"`.

O site não precisa de WordPress, plugins ou etapa de build.
