# Site do FlightFrame Studio

Arquivos para o repositório do site (`flightframe`), publicado pelo GitHub Pages em
`https://flightframe.ravendronevideos.com.br`.

## Situação atual (4/11/2026)

- **Na Mac App Store:** FlightFrame Studio **2.0** (pré-seleção com IA, prova para a cliente e prazos de entrega), Apple ID `6822035026`.
- **Duas línguas:** `index.html` em português e `en/index.html` em inglês, para o mercado americano
  (preço do Pro em dólar: **$79.99** desde a 2.0, links `apps.apple.com/us/...`). As capturas ficam em `assets/`
  (português) e `assets/en/` (inglês), as mesmas da loja na 2.0 (redimensionadas para 1920 px a partir de `docs/AppStore/2.0/capturas-*` do repositório do app), e cada língua tem a sua imagem de
  prévia de links (`og-image.jpg`). Numa versão nova, troque as capturas e as prévias das duas línguas. Privacidade e suporte têm a parte em inglês na mesma página
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

- **Preços:** a seção `#precos` mostra R$ 149,90 (desde a 2.0; o preço de lançamento de R$ 99,90 acabou),
  também na dúvida "É uma assinatura?". Confira se é o mesmo valor do FlightFrame Pro no App Store Connect.
- **Preços em dólar:** o `en/index.html` mostra $79.99 (no topo, nos preços, nas dúvidas e no bloco
  `ld+json`). Se o preço mudar no App Store Connect, mude nos quatro lugares.
- **Selo da Mac App Store em inglês:** `assets/mac-app-store-badge-en.svg`, o oficial preto dos EUA,
  baixado do App Store Marketing Tools (`toolbox.marketingtools.apple.com`).
- **Tag do Google Ads** (`AW-18549963218`): fica no começo do `<head>` das quatro páginas, para medir as
  conversões dos anúncios. A política de privacidade explica isso em "Este site" / "This website"; se
  trocar ou tirar a tag, atualize o texto. Uma página nova também precisa da tag.
  Logo depois dela vem a conversão "App Store click - FlightFrame" (`AW-18549963218/HikiCJOxvbEdENLzp41F`):
  todo clique num link para `apps.apple.com` conta, sem precisar marcar cada botão.
- **Família de apps** (`#apps`, nas duas línguas, mais uma dúvida no FAQ e "Outros apps" no rodapé):
  Acervo Organizer (`acervoorganizer.ravendronevideos.com.br`, `/en/` na página em inglês) e
  Photo Backup Guardian (`photobackupguardian.app`, site só em inglês). Os ícones estão em
  `assets/app-acervo-organizer.png` e `assets/app-photo-backup-guardian.png` (160 px, tirados dos
  sites dos apps). Quando o Photo Backup Guardian sair do beta, troque "Beta no TestFlight" /
  "Beta on TestFlight" por "Na Mac App Store" / "On the Mac App Store" e aponte o link para a loja, se quiser.
  Se o Guardian ganhar site em português, mude o link e tire o "site em inglês".
- **Cache do CSS:** as páginas carregam `styles.css?v=AAAA-MM-DD`. Ao mudar o `styles.css`, troque a data
  nas quatro páginas, para os visitantes não verem a página nova com o estilo antigo.
- **`style.css`** (sem "s") é antigo e nenhuma página usa. Pode ser apagado.
- **`CNAME`:** é o arquivo que liga o domínio próprio ao GitHub Pages. Nunca apague.

## Publicar pelo GitHub Desktop

1. Abra o repositório `flightframe` (o **do site**, não o do app) no GitHub Desktop.
2. Confira as mudanças e faça o commit (ou use o commit já pronto) ▸ **Push origin**.
   Em 1 ou 2 minutos o site novo está no ar.
