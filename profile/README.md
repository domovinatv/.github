# DOMOVINA

Otvoreni kod ekosustava DOMOVINA. Glavni proizvod je **[DOMOVINA.ai](https://domovina.ai)**:
aplikacija za hrvatske podcaste koje je obradio AI (članak, sažetak, poglavlja,
govornici, titlovi, teološka provjera). Oko nje su otvoreni katalozi hrvatskih
javnih podataka, alati za plaćanja i infrastruktura koju svi dijele.

Video podcast: [DOMOVINA.tv](https://domovina.tv)

## Podcast platforma

| Repo | Što radi | Uživo |
|---|---|---|
| [domovina.ai](https://github.com/domovinatv/domovina.ai) | Flutter aplikacija: web, iOS, Android, Android TV | [domovina.ai](https://domovina.ai) |
| [fetch.domovina.tv](https://github.com/domovinatv/fetch.domovina.tv) | pipeline: preuzimanje, transkripcija, AI obrada, upload na CDN | |
| [domovina-rag](https://github.com/domovinatv/domovina-rag) | semantička pretraga korpusa i MCP server | |
| [pipeline.domovina.ai](https://github.com/domovinatv/pipeline.domovina.ai) | red za ad-hoc obradu pojedinačnih videa | |
| [domovina-cutter](https://github.com/domovinatv/domovina-cutter) | rezanje poglavlja u MP4 za dijeljenje | |
| [podcast.domovina.ai](https://github.com/domovinatv/podcast.domovina.ai) | katalog hrvatskih podcasta po kategorijama | [podcast.domovina.ai](https://podcast.domovina.ai) |
| [domovina-stats](https://github.com/domovinatv/domovina-stats) | statistika korpusa | [stats.domovina.ai](https://stats.domovina.ai) |
| [dataset.domovina.tv](https://github.com/domovinatv/dataset.domovina.tv) | javni dataset transkripata (SRT, diarizacija) | |
| [producer.domovina.tv](https://github.com/domovinatv/producer.domovina.tv) | macOS alat za sinkronizaciju snimki | |

## Otvoreni katalozi hrvatskih podataka

Svaki katalog je reproducibilan iz javnih izvora, bez API ključeva. Karta ih
sve prikazuje na [gis.domovina.ai](https://gis.domovina.ai).

| Repo | Sadržaj |
|---|---|
| [karta-hrvatske](https://github.com/domovinatv/karta-hrvatske) | interaktivna karta (gis.domovina.ai) |
| [crkve.domovina.ai](https://github.com/domovinatv/crkve.domovina.ai) | crkve i sakralni objekti, župe, biskupije |
| [udruge.domovina.ai](https://github.com/domovinatv/udruge.domovina.ai) | katoličke udruge |
| [oou.domovina.ai](https://github.com/domovinatv/oou.domovina.ai) | vrtići, škole i ostale odgojno-obrazovne ustanove |
| [klubovi.domovina.ai](https://github.com/domovinatv/klubovi.domovina.ai) | nogometni klubovi, HNL do 3. ŽNL |
| [stranke.domovina.ai](https://github.com/domovinatv/stranke.domovina.ai) | političke stranke |
| [zakoni.domovina.ai](https://github.com/domovinatv/zakoni.domovina.ai) | akti iz Narodnih novina |
| [izbori.domovina.ai](https://github.com/domovinatv/izbori.domovina.ai) | arhiva izbornih rezultata |
| [company-details-api](https://github.com/domovinatv/company-details-api) | veličina poduzetnika i udruga iz javnih registara |

## Plaćanja, računi i potpis

| Repo | Što radi |
|---|---|
| [domovina-fiskal](https://github.com/domovinatv/domovina-fiskal) | izdavanje fiskaliziranih računa (fiskalizacija 1.0 + eRačun) |
| [domovina-fiskal-app](https://github.com/domovinatv/domovina-fiskal-app) | korisnička nadzorna ploča za fiskal.domovina.ai |
| [domovina-ulaznice](https://github.com/domovinatv/domovina-ulaznice) | prodaja ulaznica bez provizije |
| [pay.domovina.ai](https://github.com/domovinatv/pay.domovina.ai) | generator SEPA EPC QR, HUB3 i EIP-681 kodova |
| [pkk.domovina.ai](https://github.com/domovinatv/pkk.domovina.ai) | izračun plaćenih javnih davanja iz ePorezne |
| [certilia-esign](https://github.com/domovinatv/certilia-esign) | kvalificirani elektronički potpis PDF-a (Certilia) |
| [mpt-landing](https://github.com/domovinatv/mpt-landing) | landing za Mint Pay Transfer (mpt.hr) |
| [donate.domovina.ai](https://github.com/domovinatv/donate.domovina.ai) | stranica za donacije |
| [domovina-gnosis-node](https://github.com/domovinatv/domovina-gnosis-node) | Gnosis Chain čvor i validator |
| [domovina-blockchain](https://github.com/domovinatv/domovina-blockchain) | arhitektonska vizija EVM lanca s EUR stablecoinom |
| [wallet-wasp](https://github.com/domovinatv/wallet-wasp) | eksperiment: passkey Safe novčanik |

## Zajednička infrastruktura

| Repo | Što radi |
|---|---|
| [domovina-api](https://github.com/domovinatv/domovina-api) | Supabase (shema, RLS, edge funkcije), jedna prijava za cijeli ekosustav |
| [cal.domovina.ai](https://github.com/domovinatv/cal.domovina.ai) | self-hosted Cal.com |
| [sms.domovina.ai](https://github.com/domovinatv/sms.domovina.ai) | SMS gateway |
| [app.domovina.link](https://github.com/domovinatv/app.domovina.link) | Cloudflare Worker koji brandira Coolify dashboard |

## Ostalo

[provjera.domovina.ai](https://github.com/domovinatv/provjera.domovina.ai) (samoprocjena
ADHD-a, offline PWA), [research.domovina.tv](https://github.com/domovinatv/research.domovina.tv),
[mediakit.domovina.tv](https://github.com/domovinatv/mediakit.domovina.tv),
[domovinatv.github.io](https://github.com/domovinatv/domovinatv.github.io).
Napušteno: [domovina-wsrv](https://github.com/domovinatv/domovina-wsrv).

## Kako se repoi zovu

| Uzorak | Kada |
|---|---|
| `<poddomena>.domovina.ai` | proizvod koji živi na svojoj adresi (`zakoni.domovina.ai`) |
| `domovina.ai` | glavna aplikacija, na korijenskoj domeni |
| `domovina-<ime>` | backend, servis ili infrastruktura bez vlastite adrese (`domovina-api`) |
| `<ime>.domovina.tv` | starija generacija, vezana uz DOMOVINA.tv; nova imena ne idu na `.tv` |
| sufiks `-private` | privatni repo koji nikad ne smije postati javan |

Novi repo dobiva ime po ovoj tablici, opis od jedne rečenice i, ako je uživo,
adresu u polju *Website*. Postojeći repoi se ne preimenuju samo radi tablice.
Iznimka je `domovina.ai`, koji se do 6.10.2026. zvao `ai.domovina.tv`. GitHub
staru adresu preusmjerava, pa se ime `ai.domovina.tv` ne smije ponovno
iskoristiti.
