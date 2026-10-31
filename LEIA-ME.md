# Site do FlightFrame Studio

Arquivos para o repositório do site (`flightframe`), publicado pelo GitHub Pages em
`https://flightframe.ravendronevideos.com.br`.

## Situação atual (31/10/2026)

- **Na Mac App Store:** FlightFrame Studio **1.8** (com a seleção da cliente), Apple ID `6822035026`.
- **Duas línguas:** `index.html` em português e `en/index.html` em inglês, para o mercado americano
  (preço do Pro em dólar: **$39.99**, links `apps.apple.com/us/...`). As capturas em inglês ficam em
  `assets/en/` (as da loja, 1.8). Privacidade e suporte têm a parte em inglês na mesma página
  (`#english`). Ao mudar um texto, mude nas duas línguas.
  Botões de download: `https://apps.apple.com/app/flightframe-studio/id6822035026`.
- **TestFlight** (`https://testflight.apple.com/join/Wz2NuCgx`) só no convite para o beta: texto do
  criador, suporte e rodapé ("Beta").
- **E-mail de suporte:** `suporte@internetmidia.com`, nas páginas de privacidade e suporte.
- **Selo da Mac App Store:** selo oficial em português (preto) em `assets/mac-app-store-badge.svg`,
  ao lado dos botões do topo da página, com link para a App Store.

## Recursos que ainda vão chegar

Para anunciar um recurso antes de ele estar na loja, use a etiqueta `<span class="next">na 1.8</span>`
ao lado do item (o estilo está em `styles.css`). Quando a versão sair, apague as etiquetas.

## Manter atualizado

- **Preços:** a seção `#precos` mostra o preço de lançamento (R$ 99,90, de R$ 149,90). Confira se é o
  mesmo valor do FlightFrame Pro no App Store Connect. Quando o lançamento acabar, troque por
  R$ 149,90 e tire o valor riscado.
- **Preços em dólar:** o `en/index.html` mostra $39.99 (no topo, nos preços, nas dúvidas e no bloco
  `ld+json`). Se o preço mudar no App Store Connect, mude nos quatro lugares.
- **Selo da Mac App Store em inglês:** `assets/mac-app-store-badge-en.svg`, o oficial preto dos EUA,
  baixado do App Store Marketing Tools (`toolbox.marketingtools.apple.com`).
- **`style.css`** (sem "s") é antigo e nenhuma página usa. Pode ser apagado.
- **`CNAME`:** é o arquivo que liga o domínio próprio ao GitHub Pages. Nunca apague.

## Publicar pelo GitHub Desktop

1. Abra o repositório `flightframe` (o **do site**, não o do app) no GitHub Desktop.
2. Confira as mudanças e faça o commit (ou use o commit já pronto) ▸ **Push origin**.
   Em 1 ou 2 minutos o site novo está no ar.
