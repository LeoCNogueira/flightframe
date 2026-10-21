# Site do FlightFrame Studio

Arquivos para o repositório do site (`flightframe`), publicado pelo GitHub Pages em
`https://flightframe.ravendronevideos.com.br`.

## Situação atual

- **E-mail de suporte:** `suporte@internetmidia.com`, nas páginas de privacidade e suporte.
- **Botões de download:** apontam para o beta no TestFlight (`https://testflight.apple.com/join/Wz2NuCgx`)
  até o lançamento.

## No lançamento na App Store

1. Troque nos botões de download o link do TestFlight pelo da App Store:
   `https://apps.apple.com/app/id` + o **Apple ID** do app (App Store Connect ▸ App Information).
   Mantenha o link do TestFlight só no texto "Entre no beta pelo TestFlight" e no rodapé ("Beta").
2. Só então adicione o **selo oficial da Mac App Store** em português, baixado nas App Store Marketing
   Tools, como `assets/mac-app-store-badge.svg`. O selo não deve levar ao TestFlight.
3. Ajuste o texto do criador (`index.html`, procure "Criei o FlightFrame") com as suas palavras.

## Manter atualizado

- **Preços:** a seção `#precos` mostra o preço de lançamento (R$ 99,90, de R$ 149,90). Quando o
  lançamento acabar, troque por R$ 149,90 e tire o valor riscado.
- **"Chegando em breve":** quando a 1.7 (mapa, diário de voo, PDF, SARPAS) for publicada, mova esses
  itens para a lista principal de pilotos e atualize a tabela de comparação.
- **`CNAME`:** é o arquivo que liga o domínio próprio ao GitHub Pages. Nunca apague.

## Publicar pelo GitHub Desktop

1. File ▸ **Clone Repository** ▸ escolha `flightframe` (o repositório **do site**, não o do app).
2. Copie para a pasta clonada **todo o conteúdo desta pasta** (arquivos `.html`, `styles.css`,
   `CNAME` e a pasta `assets`), substituindo os antigos.
3. Commit com o resumo `New landing page` ▸ **Push origin**. Em 1 ou 2 minutos o site novo está no ar.
