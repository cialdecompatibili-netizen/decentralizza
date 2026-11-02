---
layout: single
title: "Moneta privata: la tecnologia spiegata"
permalink: /progetti/moneta-privata/
ref: moneta-privata
author_profile: true
seo_description: "Come funziona una moneta digitale privata: firme ad anello, indirizzi stealth, importi nascosti, rete e rischi. Guida per investitori e appassionati."
---

**Stato: idea in fase di studio.** Nessuna rete attiva, nessun token in vendita, nessun rendimento promesso. Questa pagina spiega le tecnologie e le logiche su cui ragioniamo, per chi vuole capire e magari partecipare.

## Il problema che si vuole risolvere
Sulla maggior parte delle blockchain pubbliche, come Bitcoin, ogni transazione è visibile a tutti: chi paga, chi riceve, quanto. Chi conosce un indirizzo può seguire i movimenti. Una moneta privata nasce per fare il contrario: la privacy è la regola, non un'opzione.

## Le tre idee tecniche di base
**1. Firme ad anello: nascondere chi paga.** Quando spendi, la tua firma digitale viene mescolata a quelle di altri utenti ("decoy", esche) presi dalla blockchain. Dall'esterno si vede che uno dei membri dell'anello ha firmato, ma non quale.

**2. Indirizzi stealth: nascondere chi riceve.** Il destinatario ha un indirizzo pubblico, ma per ogni pagamento il mittente genera un indirizzo monouso. Sulla blockchain compaiono solo indirizzi usa e getta, non collegabili tra loro da un osservatore.

**3. Importi riservati (RingCT): nascondere quanto.** Gli importi sono cifrati con impegni crittografici. La rete può verificare che la transazione sia valida, cioè che non si crei denaro dal nulla, senza vedere la cifra. Delle prove di intervallo, dette *range proof*, mostrano che gli importi sono positivi.

## Cosa resta verificabile
Una moneta privata non è una moneta senza regole. I nodi controllano ancora tutto ciò che serve: firme valide, nessuna doppia spesa e quantità di moneta coerente. La privacy riguarda ciò che un osservatore esterno può dedurre, non il rispetto delle regole.

## Rete e mining
- **Nodi**: chiunque può far girare un nodo e verificare la catena.
- **Mining**: è l'attività che aggiunge i blocchi. Esistono algoritmi pensati per essere minabili con un normale processore, così da non favorire solo hardware specializzato.
- **Emissione**: una moneta deve avere una regola chiara di creazione. Una piccola emissione continua può pagare chi tiene in piedi la rete anche dopo il periodo iniziale.
- **Rete peer-to-peer**: esistono tecniche per rendere più difficile collegare una transazione all'indirizzo IP di chi la invia.

## Limiti da dire chiaramente
- **Non è anonimato assoluto.** Errori d'uso, metadati di rete e analisi statistiche possono ridurre la privacy.
- **Piattaforme di scambio.** Alcuni exchange hanno tolto o limitato le monete orientate alla privacy.
- **Regole.** In Europa le norme sulle cripto-attività e sull'antiriciclaggio cambiano e vanno verificate prima di qualsiasi attività commerciale o raccolta di fondi.
- **Rischio tecnico.** Modificare codice crittografico senza un audit indipendente è pericoloso.
- **Rischio di mercato.** Una nuova moneta può non trovare utenti, liquidità o scambi.

## Per investitori
Non offriamo rendimenti né quote. In questa fase cerchiamo persone che aiutino a valutare l'idea. Prima di qualsiasi raccolta di capitale servono verifica legale e regole chiare, come per ogni progetto del nostro hub di startup.

## Per appassionati e sviluppatori
Servono crittografi, sviluppatori di sistemi distribuiti, esperti di sicurezza, chi sa scrivere documentazione e chi vuole testare. Per un approfondimento sulla tecnologia di riferimento leggi: [Monero (XMR): cos'è e come funziona](https://cialdecompatibili-netizen.github.io/cryptomagazine/blog/enciclopedia/monero-xmr-cose-e-come-funziona/).

[Voglio partecipare]({{ '/contatti/' | relative_url }}){: .btn .btn--primary}

*Questa pagina ha scopo informativo: non è un'offerta di investimento né una consulenza finanziaria o legale.*
