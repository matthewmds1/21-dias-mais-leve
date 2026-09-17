# Projeto 21 Dias Mais Leve — página de vendas

Página de vendas e carrinho do produto digital **Projeto 21 Dias Mais Leve**.

## Estrutura

```
docs/
  index.html      página de vendas
  carrinho.html   carrinho com o adicional opcional
  style.css       estilos das duas páginas
  meal.jpg        foto do topo
  mockup.jpg      imagem dos materiais
  .nojekyll       impede o GitHub de processar os arquivos como Jekyll
```

O site é publicado pelo GitHub Pages a partir da pasta `docs/` no branch `main`.

## Antes de publicar

Substitua no código:

| Onde | O quê |
|---|---|
| `docs/carrinho.html` | os dois links de checkout, na constante `CHECKOUT` no fim do arquivo |
| `docs/index.html` | `[CANAL DE SUPORTE]`, `[RAZÃO SOCIAL]`, `[CNPJ]`, `[E-MAIL]` |
| `docs/index.html` | `[TERMOS DE USO — LINK]` e `[POLÍTICA DE PRIVACIDADE — LINK]` |

## O que NÃO entra neste repositório

Os PDFs do produto (`kit-v2/`) e os pacotes de entrega (`*.zip`) estão no `.gitignore`.
**Este repositório é público.** Qualquer arquivo commitado aqui fica acessível a qualquer pessoa,
e permanece no histórico do Git mesmo depois de removido.
