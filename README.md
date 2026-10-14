# Mamão — loja demonstrativa Angular

Este pacote corrige a ausência da pasta `src` no ZIP fornecido, criando uma loja de demonstração funcional com catálogo, busca, filtros por categoria e carrinho interativo. Os produtos e preços são fictícios. O código original das páginas **não estava presente** no ZIP e não pôde ser recuperado.

## Como executar no Windows

1. Extraia este arquivo ZIP.
2. No VS Code, abra a pasta `mamao` (a que contém `package.json`).
3. Abra o terminal nessa pasta e execute:

```powershell
npm install
npx ng serve --open
```

4. Se não abrir automaticamente, acesse http://localhost:4200/.

> O projeto foi ajustado para execução no navegador, sem SSR, porque os arquivos necessários ao servidor não estavam presentes. A loja é apenas demonstrativa; checkout e pagamento real não estão configurados.

## Onde personalizar

- `src/app/app.component.ts` — produtos, preços, categorias e interações.
- `src/app/app.component.html` — conteúdo das telas.
- `src/app/app.component.css` — visual do site.
- `src/styles.css` — estilos globais.

## Fotos e easter egg

Os cartões de produto, a faixa principal e a seção Sobre usam fotografias reais de Unsplash/Pexels exibidas por URLs HTTPS. **É necessário ter conexão com a internet para carregar essas imagens.** Créditos e fontes: Unsplash (fotos de mamão e suco), Pexels (cesta de frutas 12597141, mel 7939743, vitamina 4051764, castanhas 5472169 e frutas 8426698). As fotos são ilustrativas, não representam um estoque real.

Clique no logotipo `mamão.` **no rodapé** para revelar o easter egg. Feche pelo X, clicando fora da caixa ou no botão de fechar.
