---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: ht
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# RECENSIONE INTERNA - Note sulla versione di Adobe Experience Cloud - Gennaio 2020

Nuove funzioni e correzioni in Adobe Experience Cloud.

> [!NOTE] Abbonati ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: gennaio 2020**

* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud) (Aggiornato 11/8)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/it-IT/experience-cloud/user-guides/home.html).

## Status.adobe.com

Utilizzando l’Adobe ID, puoi abbonarti e ricevere le notifiche relative agli eventi di stato, in base alle preferenze per prodotti, area geografica ed eventi.

| Funzione | Descrizione |
| -----------| ---------- |
| Abbonati per ricevere le notifiche e-mail in tempo reale | <ul><li>Supporto per Experience Cloud, Creative Cloud, Document Cloud, AEP e i Servizi Adobe</li><li>Supporto delle preferenze per area geografica e tipo di evento</li><li>Supporto interfaccia utente per web, dispositivi mobili e tablet</li></ul> |
| Gestione preferenze per le notifiche | <ul><li>Modifica e salva le preferenze per le notifiche in qualsiasi momento</li><li>Annulla l’abbonamento per ricevere le notifiche in qualsiasi momento</li><li>Elemento</li></ul> |
| Recapito e-mail personalizzato e più veloce | <ul><li>Le notifiche degli eventi vengono inviate appena dopo l’apertura, l’aggiornamento o la chiusura dei contenuti CSO e CMR</li><li>Ricevi solo le notifiche degli eventi corrispondenti alle preferenze configurate</li><li>Ricevi notifiche localizzate in base alla lingua configurata nelle preferenze del tuo account</li></ul> |
| Notifiche nel prodotto personalizzate | Gli eventi che corrispondono alle tue preferenze per le notifiche e ai prodotti acquistati vengono visualizzati nel pannello Annuncio. |

## Interfaccia di Experience Cloud {#ecloud}

Note sulla versione per l’interfaccia di Experience Cloud e per la gestione dei prodotti.

* Elemento
* Elemento

Per la documentazione sul prodotto, consulta [Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html)   (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)   (**Aggiornato il 18 dicembre 2019**)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- | 
|  |  |

#### Correzioni

* Correzione
* Correzione

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta   o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | Il 16 gennaio 2020, Adobe Analytics passerà al nuovo dominio https://experience.adobe.com/analytics. Questa modifica potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione “Impedisci il rilevamento intersito” nelle preferenze relative alla privacy di Safari, i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. Gli utenti potranno utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti Safari. |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per l’opzione **[!UICONTROL Visualizza archivio]** in Dashboard Manager (**[!UICONTROL  Componenti > Dashboard]**). |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Enforce IP Login Restrictions]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per la funzionalità di whitelisting degli accessi IP (**[!UICONTROL Enforce IP Login Restrictions]**), nel menu **[!UICONTROL  Amministrazione > Impostazioni società > Sicurezza]**. |
| Aggiornamento della gestione all’attributo SameSite sui cookie | 15 ottobre 2019 | In agosto 2019 Adobe ha annunciato di aver aggiunto l’impostazione per cookie SameSite a tutti i cookie impostati da Analytics. Viene applicato un aggiornamento della logica, come segue:<ul><li>Per tutti i cookie di terze parti non basati su Webkit, l’attributo SameSite è impostato su `none`.</li><li>Per tutti gli altri cookie, l’attributo SameSite non è impostato.</li></ul> |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Aggiornamento dei totali della Tabella freeform di Analysis Workspace | 12 settembre 2019 | A ottobre 2019, le righe totali delle tabelle a forma libera inizieranno a conteggiare i [filtri dei report](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applicati. Ad oggi, i totali hanno tenuto in considerazione soltanto la segmentazione. Con questa modifica verranno aggiornate le visualizzazioni dipendenti (ad esempio le visualizzazioni [!UICONTROL Numero di riepilogo]), nonché i dati CSV e PDF esportati. |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics verrà aggiornato da Ora del Pacifico a un valore data/ora formattato correttamente con le informazioni sul fuso orario. (AN-183468) |
| Supporto per scostamenti fuso orario nello storico | 8 agosto 2019 | Analytics ora gestirà automaticamente gli scostamenti di fuso orario per gli hit con marca temporale. A seguito di questa modifica implementata l’8 agosto, nei sistemi in cui vengono caricati i dati per elaborazione dello storico non sarà più necessario apportare regolazioni per lo scostamento di fuso orario prima di inviare i dati. |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | Questi limiti non sono nuovi, ma sono stati aggiunti alla documentazione [qui](https://docs.adobe.com/content/help/it-IT/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “_contiene uno di_”, “_non contiene uno di_”, “_contiene tutti_” e “_non contiene tutti_” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL  Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica è entrata in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica dei calcoli per i _totali nei rapporti_ | Aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ sono diventati uniformi per tutte le dimensioni e le metriche. Questo ha comportato una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting.<br>**Nota:** il calcolo per i _totali nei rapporti_ è ora denominato _totale complessivo_. Consulta “Analysis Workspace: Aggiornamento dei totali delle tabelle a forma libera” di cui sopra. |
| Aggiornamento a Download CSV da Analysis Workspace | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL  Copia negli Appunti]**) da Analysis Workspace, per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti > Impostazioni report > Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di Analysis Workspace | 4 aprile 2019 | Il comando Console per attivare il debugger di Analysis Workspace verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

### Nuove funzioni, miglioramenti e correzioni in Audience Manager {#aam-new-features}

| Funzione | Descrizione |
|--- |----|
|  |  |

### Miglioramenti {#aam-enhancements}

Per ulteriori informazioni, contatta il tuo consulente Audience Manager o l&#39;Assistenza clienti.

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* Correzione
* Correzione

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Rilasci di prodotti

### Aiuto e documentazione

* **Aggiornamenti alla documentazione di AEM**

   Scopri le modifiche e gli aggiornamenti importanti apportati alla documentazione di Adobe Experience Manager negli ultimi tre mesi.

   Consulta [Documentazione di AEM: aggiornamenti recenti della documentazione](https://helpx.adobe.com/it/experience-manager/documentation-updates.html).

### Risorse aggiuntive

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/it/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://marketing.adobe.com/resources/help/it_IT/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Risorse di documentazione

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/it/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)   - [Pianificazione rilascio](https://helpx.adobe.com/it/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/it/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/it-IT/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

| Visualizzazione | Funzione |
|------|---------|
|  |  |
