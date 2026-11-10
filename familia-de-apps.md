# Família de apps: o que os três sites dizem uns dos outros

Fonte única dos textos da seção "família de apps" nos sites do **FlightFrame Studio**, do **Acervo Organizer** e do
**Photo Backup Guardian**. Antes de mudar essa seção em qualquer site, mude aqui primeiro e depois nos três.

- **Última mudança:** 10/11/2026, Acervo Organizer 2.11 publicado, com a sincronização de pastas (Espelho e Adicionar e atualizar, na compra separada "Sincronização e Backup"). A seção não muda: o papel do Acervo na família continua "arrumar o que você já tem", e vigiar os backups segue com o Guardian. A sincronização aparece só na página do Acervo (recursos, preço e FAQ). Antes: 8/11/2026, FlightFrame 2.1 aprovado: a resposta da dúvida do FAQ diz que o FlightFrame também faz a terceira cópia e reconfere as cópias que ele mesmo fez, e que o Guardian cobre o que nunca passou pelo FlightFrame e as cópias só online. Antes: 5/11/2026, primeira versão. Seção no ar no FlightFrame e no Acervo. O Photo Backup Guardian
  entra depois da aprovação da Apple: o site dele não muda durante a revisão.

## Onde fica cada site

| App | Código do site | Publicação | Endereço |
|---|---|---|---|
| FlightFrame Studio | `~/Developer/GitHub/flightframe` | GitHub Pages | `https://flightframe.ravendronevideos.com.br` (`/en/`) |
| Acervo Organizer | `~/Developer/acervoorganizer-site` (repositório `acervoorganizer`) | GitHub Pages | `https://acervoorganizer.ravendronevideos.com.br` (`/en/`) |
| Photo Backup Guardian | `~/Developer/PhotoBackupGuardian/site/` (copiado para o repositório `photobackupguardiansite`) | Cloudflare | `https://photobackupguardian.app` (português ou inglês pelo navegador, numa página só) |

## Situação de cada app

| App | Situação | Link da loja |
|---|---|---|
| FlightFrame Studio | Mac App Store | `https://apps.apple.com/app/flightframe-studio/id6822035026` |
| Acervo Organizer | Mac App Store | `https://apps.apple.com/app/id6821982992?mt=12` |
| Photo Backup Guardian | Beta no TestFlight, em revisão na Apple | ainda não tem |

Quando a situação mudar (saiu do beta, preço, recurso novo que muda o papel do app), atualize esta tabela e os três sites.

## A seção

Os três apps aparecem pelo **momento do trabalho**, sempre nesta ordem: Antes · Hoje · Sempre. Cada site marca o próprio
cartão com "Você está aqui" / "You are here" e mostra, nos outros dois, a situação e o link para o site do app.
Visual: o de cada site (cores, fontes, modo escuro); o conteúdo e a estrutura são os mesmos.

### Título e frase

- pt: **Uma família de apps para quem não pode perder um arquivo**
- en: **A family of apps for people who can't lose a file**
- Frase, que muda conforme o site (o app da página primeiro):
  - FlightFrame: "O FlightFrame Studio cuida de cada cartão novo. Do mesmo criador, mais dois apps cuidam do que veio antes e de todos os backups." / "FlightFrame Studio takes care of every new card. From the same maker, two more apps take care of what came before and of all your backups."
  - Acervo: "O Acervo Organizer arruma o que você já tem. Do mesmo criador, mais dois apps cuidam de cada cartão novo e de todos os backups." / "Acervo Organizer tidies up what you already have. From the same maker, two more apps take care of every new card and of all your backups."
  - Guardian: "O Photo Backup Guardian vigia todos os seus backups. Do mesmo criador, mais dois apps cuidam do que veio antes e de cada cartão novo." / "Photo Backup Guardian watches over all your backups. From the same maker, two more apps take care of what came before and of every new card."

### Os três cartões

**Antes · o acervo antigo / Before · your old archive: Acervo Organizer**
- pt: Organiza anos de fotos e vídeos espalhados por HDs e NAS, sem arriscar nenhum arquivo.
  - Mostra o resultado antes de mover qualquer coisa
  - Encontra duplicatas pelo conteúdo, não pelo nome
  - Desfaz qualquer organização com um clique
- en: Organizes years of photos and videos scattered across hard drives and NAS, without risking a single file.
  - Shows the result before anything moves
  - Finds duplicates by content, not by name
  - Undoes any organization in one click

**Hoje · cada cartão novo / Today · every new card: FlightFrame Studio**
- pt: Leva o cartão até o projeto organizado e o Lightroom, com cada arquivo conferido.
  - Cópia e backup verificados pelo SHA-256
  - Voos, sets e pré-seleção com IA no Mac
  - Diz se o cartão já pode ser formatado
- en: Takes the card all the way to an organized project and Lightroom, with every file verified.
  - Copies and backups verified by SHA-256
  - Flights, sets and on-device AI culling
  - Tells you when the card is safe to format

**Sempre · a biblioteca inteira / Always · your whole library: Photo Backup Guardian**
- pt: Confere se cada foto e cada vídeo da sua biblioteca tem as cópias da regra 3-2-1, mesmo o que nunca passou pelo FlightFrame.
  - Discos externos, NAS e pastas na nuvem
  - Cópias “só online” no Google Drive e no OneDrive
  - “Posso apagar este disco?” antes de reaproveitar um HD
- en: Checks that every photo and video in your library has its 3-2-1 backup copies, even files that never went through FlightFrame.
  - External drives, NAS and cloud folders
  - “Online only” copies in Google Drive and OneDrive
  - “Can I erase this disk?” before you reuse a drive

Situação no cartão: "Na Mac App Store" / "On the Mac App Store"; "Beta no TestFlight" / "Beta on TestFlight".
Link: "Conhecer o <app>" / "Meet <app>".

### Regras em comum (frase depois dos cartões)

- pt: "Os três seguem as mesmas regras: nada é sobrescrito, nada é apagado, cada cópia é conferida pelo conteúdo e suas fotos não saem do seu Mac. O FlightFrame Studio e o Photo Backup Guardian usam ainda o mesmo padrão de pastas, cópias e relatórios."
- en: "All three follow the same rules: nothing is overwritten, nothing is deleted, every copy is verified by its content, and your photos never leave your Mac. FlightFrame Studio and Photo Backup Guardian also share the same standard for folders, copies and reports."
- Cuidado: o Acervo **move** arquivos (é a função dele), então não escreva que "os originais nunca são alterados" para os três.
  O padrão comum de pastas vale só para o FlightFrame e o Guardian (`flightframe-app/docs/padroes-compartilhados.md`).

### Dúvida no FAQ (o app da página primeiro na resposta)

- pt: "Qual a diferença entre o FlightFrame Studio, o Acervo Organizer e o Photo Backup Guardian?"
- en: "What's the difference between FlightFrame Studio, Acervo Organizer and Photo Backup Guardian?"
- Resposta: cada um entra num momento do trabalho (o que cada um faz, em uma frase) e "Você pode usar só um ou os três juntos." / "Use one, or all three together."
- Desde a 2.1, o FlightFrame também confere backups. Para não confundir:
  - FlightFrame: "…faz o backup e a terceira cópia, diz se o cartão já pode ser formatado e reconfere as cópias que ele mesmo fez." / "…makes the backup and the third copy, tells you when the card is safe to format and checks again the copies it made."
  - Guardian: "…vigia a biblioteca inteira, inclusive o que nunca passou pelo FlightFrame, em todos os discos e pastas na nuvem, com as cópias só online do Google Drive e do OneDrive, e avisa quando falta uma cópia da regra 3-2-1." / "…watches your whole library, including what never went through FlightFrame, across every drive and cloud folder, with the online-only copies in Google Drive and OneDrive, and warns you when a 3-2-1 copy is missing."

### Rodapé

"Outros apps:" / "Other apps:" com os links dos outros dois.

### Ícones

160 px, tirados dos sites de cada app:
- FlightFrame: `flightframe/assets/icon.png`
- Acervo: `acervoorganizer-site/assets/icone-256.png`
- Guardian: `PhotoBackupGuardian/site/icon.png`

Cada site guarda cópias dos outros dois em `assets/` (`app-<nome>.png`).
