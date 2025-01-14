---
type: "news"
date: "2021-02-17"
title: "SPID e CIE, disponibili nuove risorse open source"
subtitle: "Creates a link between a parent and child node. This is used when you transform content from a node creating a new child node. You need to add this new child node to the children array of the parent but since you don’t have direct access to the immutable parent node, use this action instead."

tags:
- Spid
- Migrazione
---

Entro il 28 febbraio 2021 tutte le amministrazioni locali e centrali dovranno integrare
[questo è un link](https://docs.italia.it/italia/manuale-di-abilitazione-al-cloud/manuale-di-abilitazione-al-cloud-docs/it/bozza/pianificare-la-migrazione/le-strategie-di-migrazione.html){class="text-decoration-none font-weight-semibold", rel='noreferrer', target='_blank', aria-label='questo è un link (link esterno)'}
(Sistema Pubblico di Identità Digitale) e come sistemi di autenticazione, uniformando di fatto l’accesso ai servizi pubblici digitali in tutto il Paese.
Una scadenza importante, quella prevista dal Decreto Legge “semplificazione e innovazione digitale”, che ha portato in questi mesi il team e la community di Developers Italia a impegnarsi su più fronti per supportare gli enti, effettuando numerosi rilasci di librerie e software applicativo.

Un esempio significativo è rappresentato dal che permette una facile integrazione di SPID e CIE all’interno di architetture web basate sullo stack tecnologico **Express**.

Un'altra risorsa pubblicata è un proxy di autenticazione compatibile con il Sistema Pubblico di Identità Digitale italiano. Nella fattispecie questa soluzione consente di abbattere i tempi di accreditamento per tutte le organizzazioni che già sfruttano **SAML2** come protocollo di autenticazione. Satosa-Saml2SPID è un esempio di un software open source sviluppato originariamente all'interno della pubblica amministrazione italiana, l’[Università della Calabria](https://developers.italia.it/it/pa/unical), con una potenziale ricaduta positiva per molti altri enti che stanno effettuando il percorso di trasformazione digitale.

![Una spiaggia con gli ombrelloni](images/spiaggia.jpg)

Per gli enti che utilizzano il **CMS Entando** è disponibile.
Di fatto questo si basa su *keycloak* come piattaforma di gestione delle identità e il modulo pubblicato permette di configurarla facilmente per agevolare l’integrazione. Come per *Satosa-Saml2SPID*, anche questa componente può essere usata in modalità standalone.

Altri progetti degni di nota sviluppati da membri della community di Developers Italia e recentemente pubblicati **AspNetCore MVC**. In questo caso un ringraziamento speciale del team è rivolto a Daniele Giallonardo per il suo contributo.

Tutte le soluzioni citate sono accomunate dalla loro natura open source che garantisce la possibilità di consultare il codice sorgente e testare in modo indipendente le possibili integrazione per adattarle alle proprie esigenze.

### Questo è un titolo
{class="h4 font-weight-semibold mb-4"}

Hai già sviluppato un integrazione con SPID o CIE oppure ci stai lavorando? Parliamone insieme nei canali di community.

Il Team Developers Italia