# Awesome APIs Brasil

> API pubbliche brasiliane: CEP, CNPJ, Banca Centrale, IBGE, Legislativo, Giudiziario, festività e dati aperti.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-abbonarsi-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/apibr-cartas) [![Sostieni](https://img.shields.io/badge/Sostieni-un%20caff%C3%A8-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/apibr-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/apibr-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/apibr-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/it.xml) ![30 voci](https://img.shields.io/badge/voci-30-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it-on.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

Per chi ha bisogno di un dato brasiliano dentro un sistema e non vuole fare scraping dei siti. Si parte dagli aggregatori, che raccolgono molte cose in un'unica API, e poi per tema fino ai portali ufficiali. Ogni indirizzo è stato aperto prima di essere inserito; quando la versione gratuita ha dei limiti, la descrizione lo dice.

## Contenuti

- [Aggregatori](#aggregatori)
- [CEP e indirizzo](#cep-e-indirizzo)
- [Aziende e CNPJ](#aziende-e-cnpj)
- [Economia e cambi](#economia-e-cambi)
- [Governo e Legislativo](#governo-e-legislativo)
- [Portali di dati aperti](#portali-di-dati-aperti)
- [Festività e date](#festività-e-date)
- [Altre liste](#altre-liste)
- [Etichette](#etichette)
- [Come contribuire](#come-contribuire)
- [Altre liste](#altre-liste)
- [Realizzato da Ciro Cesar Maciel](#realizzato-da-ciro-cesar-maciel)
- [Licenza](#licenza)

## Aggregatori

Un'unica API per vari dati brasiliani.

- [BrasilAPI](https://go.mymarketing.click/apibr-brasilapi) - CEP, CNPJ, banche, festività, DDD, NCM, tassi e altro in un'API aperta e comunitaria. `gratis` `API` `open source`
- [Invertexto API](https://go.mymarketing.click/apibr-invertexto-api) - Festività, CEP, CNPJ, validazione di documenti e altre utilità, con token gratuito. `gratis` `API`
- [CNPJ e CEP para agentes](https://go.mymarketing.click/apibr-cnpj-e-cep-para-agentes) - Server MCP remoto con azienda tramite CNPJ, CEP, festività, DDD, banche, NCM, Selic, CDI e IPCA. `gratis` `dell'autore`

## CEP e indirizzo

In ordine alfabetico.

- [ApiCEP](https://go.mymarketing.click/apibr-apicep) - Consultazione di CEP con piano gratuito. `gratis` `API`
- [OpenCEP](https://go.mymarketing.click/apibr-opencep) - API di CEP gratuita e aperta. `gratis` `API`
- [ViaCEP](https://go.mymarketing.click/apibr-viacep) - Consultazione di CEP gratuita in JSON e XML, senza registrazione. `gratis` `API`

## Aziende e CNPJ

In ordine alfabetico.

- [CNPJ.ws](https://go.mymarketing.click/apibr-cnpj-ws) - API di CNPJ con versione pubblica gratuita e piani a pagamento. `gratis` `a pagamento` `API`
- [CNPJá](https://go.mymarketing.click/apibr-cnpja) - API di CNPJ con consultazione pubblica gratuita e piani a pagamento. `gratis` `a pagamento` `API`
- [ReceitaWS](https://go.mymarketing.click/apibr-receitaws) - Consultazione di CNPJ con piano gratuito limitato al minuto. `gratis` `a pagamento` `API`

## Economia e cambi

In ordine alfabetico.

- [AwesomeAPI de cotações](https://go.mymarketing.click/apibr-awesomeapi-de-cotacoes) - Quotazioni di valute in tempo reale, gratis. `gratis` `API`
- [Dados abertos do Banco Central](https://go.mymarketing.click/apibr-dados-abertos-do-banco-central) - Il portale dati della BCB, con serie su tassi, cambi, credito e Pix. `ufficiale` `gratis` `API`
- [PTAX no Olinda](https://go.mymarketing.click/apibr-ptax-no-olinda) - La quotazione ufficiale del dollaro e di altre valute, in OData. `ufficiale` `gratis` `API`
- [SGS do Banco Central](https://go.mymarketing.click/apibr-sgs-do-banco-central) - Il Sistema Gestore di Serie Temporali: Selic, IPCA, cambio e migliaia di serie. `ufficiale` `gratis` `API`
- [Tabela FIPE](https://go.mymarketing.click/apibr-tabela-fipe) - API per consultare la tabella FIPE dei veicoli. `gratis` `API` `open source`

## Governo e Legislativo

In ordine alfabetico.

- [API do Portal da Transparência](https://go.mymarketing.click/apibr-api-do-portal-da-transparencia) - Spese, contratti, dipendenti pubblici e benefici del governo federale, con token gratuito. `ufficiale` `gratis` `API`
- [API Pública do DataJud](https://go.mymarketing.click/apibr-api-publica-do-datajud) - Metadati dei processi giudiziari di tutti i tribunali, dal CNJ. `ufficiale` `gratis` `API`
- [Catálogo de APIs do gov.br](https://go.mymarketing.click/apibr-catalogo-de-apis-do-gov-br) - Il catalogo delle API del governo federale su Conecta gov.br. `ufficiale` `API`
- [Dados Abertos da Câmara](https://go.mymarketing.click/apibr-dados-abertos-da-camara) - Deputati, proposte, votazioni e spese. `ufficiale` `gratis` `API`
- [Dados Abertos do Senado](https://go.mymarketing.click/apibr-dados-abertos-do-senado) - Senatori, materie, votazioni e commissioni. `ufficiale` `gratis` `API`
- [Dados abertos do TSE](https://go.mymarketing.click/apibr-dados-abertos-do-tse) - Candidati, elettorato e risultati elettorali. `ufficiale` `gratis`
- [IBGE: API de serviços de dados](https://go.mymarketing.click/apibr-ibge-api-de-servicos-de-dados) - Località, nomi, aggregati, reti territoriali e notizie dell'IBGE. `ufficiale` `gratis` `API`

## Portali di dati aperti

Basi complete da scaricare o consultare.

- [Base dos Dados](https://go.mymarketing.click/apibr-base-dos-dados) - Basi pubbliche brasiliane elaborate e pronte su BigQuery, con SDK in Python e R. `gratis` `open source`
- [Brasil.IO](https://go.mymarketing.click/apibr-brasil-io) - Dati pubblici brasiliani in formato accessibile, open source. `gratis` `open source`
- [Dados abertos da Anvisa](https://go.mymarketing.click/apibr-dados-abertos-da-anvisa) - Registri di farmaci, alimenti e altri prodotti regolamentati. `ufficiale` `gratis`
- [dados.gov.br](https://go.mymarketing.click/apibr-dados-gov-br) - Il Portale Brasiliano dei Dati Aperti. `ufficiale` `gratis`

## Festività e date

In ordine alfabetico.

- [Nager.Date](https://go.mymarketing.click/apibr-nager-date) - Festività nazionali di oltre 100 paesi, incluso il Brasile, in un'API aperta. `gratis` `API` `open source`

## Altre liste

In ordine alfabetico.

- [public-apis](https://go.mymarketing.click/apibr-public-apis) - La lista collettiva delle API pubbliche di tutto il mondo. `gratis`
- [Awesome MCP Brasil](https://go.mymarketing.click/apibr-awesome-mcp-brasil) - Server MCP per servizi brasiliani, per far usare queste API all'agente IA. `gratis`
- [Awesome Pix](https://go.mymarketing.click/apibr-awesome-pix) - Standard, API e SDK di Pix. `gratis`
- [Awesome NF-e](https://go.mymarketing.click/apibr-awesome-nf-e) - Portali, librerie e API per la fattura elettronica. `gratis`

## Etichette

Ogni voce spiega di cosa si tratta. Le etichette a fianco aiutano a scegliere: ufficiale quando arriva da chi definisce lo standard, open source quando il codice è pubblicato, gratis o a pagamento in base al modello d'uso, API e SDK in base al modo di integrare. Le voci con l'etichetta "dell'autore" sono realizzate da Ciro Cesar Maciel e seguono le stesse regole di tutte le altre.

## Come contribuire

Hai trovato qualcosa che manca, è cambiato o non funziona più? Apri una issue con il modulo di nuova inclusione oppure invia una pull request modificando data/list.json. Il README di ogni lingua viene generato a partire da questo file.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Altre liste

Liste curate nello stesso formato, in portoghese e in altre 14 lingue.

- [Awesome IA no trabalho](https://go.mymarketing.click/apibr-lista-ia-no-trabalho) - IA sul lavoro, per professione: assistenti, privacy, norme e fonti ufficiali per verificare ciò che ha scritto l'IA.
- [Awesome IA na advocacia](https://go.mymarketing.click/apibr-lista-ia-advocacia) - IA per avvocati: assistenti, privacy, norme sull'IA nell'avvocatura e nel Giudiziario, e le fonti ufficiali per verificare.
- [Awesome IA na contabilidade](https://go.mymarketing.click/apibr-lista-ia-contabilidade) - IA per commercialisti: assistenti, privacy, norme del CFC e le fonti di Receita, eSocial e Simples per verificare.
- [Awesome IA na sala de aula](https://go.mymarketing.click/apibr-lista-ia-sala-de-aula) - IA per insegnanti: assistenti, età minima e privacy di ciascuno, e le norme sull'istruzione per verificare.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/apibr-lista-ia-atendimento-e-vendas) - IA per chi assiste e vende: assistenti, privacy, diritti dei consumatori e le regole di lavoro per chi sta al banco, alla cassa e al telefono.
- [Awesome IA no escritório](https://go.mymarketing.click/apibr-lista-ia-escritorio) - IA per segretarie, assistenti e addetti amministrativi: assistenti, privacy, redazione ufficiale e truffe che arrivano via e-mail.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/apibr-lista-ia-pequeno-negocio) - IA per il MEI e il piccolo imprenditore: assistenti, privacy, le regole del MEI e del Simples, del consumatore e della LGPD per chi è piccolo.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/apibr-lista-ia-primeiro-trabalho) - IA per chi inizia a lavorare: assistenti, privacy, dove cercare lavoro, i diritti del primo impiego e le truffe dell'offerta di lavoro falsa.
- [Awesome Pix](https://go.mymarketing.click/apibr-awesome-pix) - Pix per chi integra: norme, API, SDK, fornitori e strumenti, verificati uno per uno.
- [Awesome MCP Brasil](https://go.mymarketing.click/apibr-awesome-mcp-brasil) - Server MCP per servizi brasiliani: dati pubblici, CNPJ, fiscale, giuridico, mercato finanziario, commercio e pagamenti.
- [Awesome livros de IA](https://go.mymarketing.click/apibr-lista-livros-ia) - Libri sull'intelligenza artificiale in portoghese: dal primo uso alla professione, da chi costruisce al dibattito.
- [Awesome ferramentas online](https://go.mymarketing.click/apibr-lista-ferramentas-online) - Strumenti gratuiti che si aprono nel browser, senza installare: immagini, PDF, testo, codice, siti, e-mail, video e vendite.
- [Awesome NF-e](https://go.mymarketing.click/apibr-awesome-nf-e) - Fattura elettronica per chi integra: portali ufficiali, librerie per linguaggio, API di emissione e server MCP.
- [Awesome Claude Code BR](https://go.mymarketing.click/apibr-lista-claude-code-br) - Claude Code in portoghese: documentazione, corsi, skill, regole, plugin e server MCP realizzati in Brasile.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/apibr-lista-pagamentos-brasil) - Pagamenti in Brasile per chi integra: norme, gateway, acquirer, boleto, abbonamenti, split e antifrode.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/apibr-lista-open-finance-brasil) - Open Finance e Open Insurance in Brasile: norme, specifiche, dati aperti, aggregatori e open source.
- [Awesome WhatsApp API](https://go.mymarketing.click/apibr-lista-whatsapp-api) - WhatsApp per chi integra: l'API ufficiale di Meta, i fornitori, le librerie non ufficiali e il rischio di ogni strada.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/apibr-lista-empresa-de-uma-pessoa) - Ciò che serve per gestire un'intera attività con agenti IA: mettere online, incassare, misurare, promuovere ed essere trovata.

## Realizzato da Ciro Cesar Maciel

Usare quello che faccio è un modo per sostenere queste liste.

Se una lista ti ha fatto risparmiare tempo, un caffè aiuta a mantenerle tutte. Chi dona sceglie l'importo, tramite Pix o carta. [![Sostieni](https://img.shields.io/badge/Sostieni-un%20caff%C3%A8-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/apibr-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/apibr-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/apibr-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/apibr-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/apibr-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/apibr-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/apibr-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/apibr-por-agents)

## Licenza

Questa lista è sotto CC0 1.0: copia, adatta e ridistribuisci come vuoi, senza chiedere il permesso. Il codice del generatore si trova in awesome-kit, sotto licenza MIT.

<sub>Aggiornata il 2026-11-10.</sub>
