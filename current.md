---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: November 2019
author: mfrei
translation-type: tm+mt
source-git-commit: c8dca487e2a2f4992b7850632a8219ccca269713

---


# Note sulla versione di Adobe Experience Cloud - novembre 2019

Nuove funzioni e correzioni in Adobe Experience Cloud.

> [!NOTE] Abbonati ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 31 ottobre 2019**

* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud) (Aggiornato 11/8)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).
<!-- ## Status.adobe.com

Using your Adobe ID, you can subscribe to status event notifcations, based on your produts, region, and event preferences.

| Feature    | Description  |
| -----------| ---------- |
|Self-subscription to pro-active notifications | <ul><li>Select products from Experience Cloud, Creative Cloud, Document Cloud</li><li>Item</li><li>Item</li></ul> |
|Notifications preferences management | <ul><li>item</li><li>Item</li><li>Item</li></ul> |
|Personalized and faster email delivery | <ul><li>item</li><li>Item</li><li>Item</li></ul> |
|Personalized in-product notifications | <ul><li>item</li><li>Item</li><li>Item</li></ul> |
 -->

## Interfaccia di Experience Cloud {#ecloud}

Note sulla versione per l’interfaccia di Experience Cloud e per la gestione dei prodotti.

* La pagina Feed verrà rimossa a dicembre 2019. Nel prodotto verrà visualizzato un avviso di funzione rimossa. (MCUI-10039)
* È stato aggiornato il collegamento [Ulteriori informazioni](https://www.adobe.com/marketing/campaign.html) per Adobe Campaign dal selettore delle app. (MCUI-10034)
* Sono stati introdotti miglioramenti di stabilità e reattività della piattaforma core per l’interfaccia Experience Cloud. (MCUI-6822)
* Sono state risolte alcune vulnerabilità di sicurezza nell’interfaccia utente di Experience Cloud. (MCUI-9942)
* È stato risolto un problema critico in Attributi cliente che impediva ad alcuni clienti di eseguire la convalida dello schema. (MCUI-10024, MCUI-6479)
* È stata migliorata la libreria dei tipi di pubblico, con la rimozione di dimensioni non supportate per la creazione di un pubblico in tempo reale. (MCUI-10046)

Per la documentazione sul prodotto, consulta [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Note sulla versione della piattaforma Experience](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html)   (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- | 
| Customer Journey Analytics | Il 21 novembre 2019 [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) sarà disponibile come componente aggiuntivo di Adobe Analytics.<br><br/>Customer Journey Analytics consente di raccogliere in Adobe Experience Platform i dati del cliente da un qualsiasi canale scelto, online e offline, e quindi di analizzarli in modo analogo all'attuale analisi dei dati digitali esistenti tramite Analysis Workspace. Customer Journey Analytics include la possibilità di controllare come collegare i dati online e offline in Analysis Workspace su qualsiasi ID cliente comune, per poter poi eseguire attività di attribuzione, segmentazione, flusso, abbandono ecc. sull’intero set di dati cliente in Adobe Analytics.<br><br/>I clienti di Analytics Select, Prime e Ultimate possono acquistare questo prodotto aggiuntivo. Per ulteriori informazioni, contatta il team del tuo account Adobe. |
| API per i Servizi per la privacy: CCPA | Il California Consumer Privacy Act (CCPA) migliora i diritti alla privacy e la protezione dei consumatori per i residenti in California, Stati Uniti. La legge entrerà in vigore il 1° gennaio 2020.<br><br/>Il CCPA conferisce ai residenti della California nuovi diritti sulla privacy dei dati, come il diritto di accesso e cancellazione dei propri dati personali, di sapere se i propri dati personali vengono venduti o divulgati (e a chi), e di rifiutare la vendita degli stessi.<br><br/>In previsione del CCPA, i servizi per la privacy supporteranno le richieste di rinuncia alla vendita di dati personali.<br><br/>I servizi per la privacy erano precedentemente noti come servizi RGPD e manterranno tutte le funzionalità precedenti, in aggiunta al supporto per il CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Panoramica del servizio sulla privacy](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | L’abilitazione di Privacy Reporting per Analytics aggiunge una serie di variabili riservate a una suite di report.  Le variabili sono concepite per facilitare la raccolta di dati sul consenso dei consumatori a livello di hit.<br><br/>Nuove dimensioni:<br/><ul><li>Gestione del consenso Opt-Out</li><li>Gestione del consenso Opt-in</li><li>[Variabili di gestione del consenso](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Analisi audio e video: supporto per la privacy | Sono state aggiunte due nuove variabili all’API di Media Collection:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Si tratta di variabili facoltative che possono essere utilizzate per acquisire lo stato del consenso di un consumatore al momento della hit.<br/><br/>[Documentazione API di Media Collection](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Al modulo Federated Analytics sono state aggiunte le nuove variabili di dati contestuali di per la gestione del consenso di Analytics. Queste variabili sono ora disponibili per l’utilizzo nei casi in cui si contrassegna l’opzione Rifiuta condivisione o Vendi hit per federazione.<br/><br/>[Scarica Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Correzioni

* È stato risolto un problema che causava un errore durante il tentativo di eliminare gli intervalli di date con proprietario “Utente sconosciuto”. (AN-185540)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta   o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, in gennaio 2020, per l’opzione **[!UICONTROL Visualizza archivio]** in Dashboard Manager (**[!UICONTROL Componenti &gt; Dashboard]**). |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Enforce IP Login Restrictions]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, in gennaio 2020, per la funzionalità di whitelisting degli accessi IP (**[!UICONTROL Enforce IP Login Restrictions]**), nel menu **[!UICONTROL Amministrazione &gt; Impostazioni società &gt; Sicurezza]**. |
| Aggiornamento della gestione all’attributo SameSite sui cookie | 15 ottobre 2019 | In agosto 2019 Adobe ha annunciato di aver aggiunto l’impostazione per cookie SameSite a tutti i cookie impostati da Analytics. Viene applicato un aggiornamento della logica, come segue:<ul><li>Per tutti i cookie di terze parti non basati su Webkit, l’attributo SameSite è impostato su `none`.</li><li>Per tutti gli altri cookie, l’attributo SameSite non è impostato.</li></ul> |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Aggiornamento dei totali della Tabella freeform di Analysis Workspace | 12 settembre 2019 | A ottobre 2019, le righe totali delle tabelle a forma libera inizieranno a conteggiare i [filtri dei report](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applicati. Ad oggi, i totali hanno tenuto in considerazione soltanto la segmentazione. Con questa modifica verranno aggiornate le visualizzazioni dipendenti (ad esempio le visualizzazioni [!UICONTROL Numero di riepilogo]), nonché i dati CSV e PDF esportati. |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics verrà aggiornato da Ora del Pacifico a un valore data/ora formattato correttamente con le informazioni sul fuso orario. (AN-183468) |
| Supporto per scostamenti fuso orario nello storico | 8 agosto 2019 | Analytics ora gestirà automaticamente gli scostamenti di fuso orario per gli hit con marca temporale. A seguito di questa modifica implementata l’8 agosto, nei sistemi in cui vengono caricati i dati per elaborazione dello storico non sarà più necessario apportare regolazioni per lo scostamento di fuso orario prima di inviare i dati. |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | Questi limiti non sono nuovi, ma sono stati aggiunti alla documentazione [qui](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “_contiene uno di_”, “_non contiene uno di_”, “_contiene tutti_” e “_non contiene tutti_” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica è entrata in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica dei calcoli per i _totali nei rapporti_ | Aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ sono diventati uniformi per tutte le dimensioni e le metriche. Questo ha comportato una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da Analysis Workspace | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL Copia negli Appunti]**) da Analysis Workspace, per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di Analysis Workspace | 4 aprile 2019 | Il comando Console per attivare il debugger di Analysis Workspace verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

### Nuove funzioni, miglioramenti e correzioni in Audience Manager {#aam-new-features}

| Funzione | Descrizione |
|--- |----|
| [Miglioramenti per le regole di unione dei profili](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Abbiamo rilasciato una serie di miglioramenti per le [!UICONTROL regole di unione dei profili]: <ul><li>La valutazione dei segmenti è ora supportata in batch, fino a 100 dispositivi.</li><li>Abbiamo migliorato la precisione di reporting per le caratteristiche e le popolazioni dei segmenti.</li><li>Abbiamo migliorato la precisione dei file di batch generati utilizzando ID validi per più dispositivi.</li><li>Abbiamo aggiornato la documentazione con casi di utilizzo più dettagliati per ogni regola. Consulta [Casi d’uso generali per le regole di unione dei profili](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html), [Casi d’uso sui grafici dei dispositivi esterni](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html) e [Casi d’uso sui grafici dei dispositivi collegati a profili](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html).</li></ul> |
| [Consigli intelligenti per i dati di Audience Marketplace, con tecnologia Adobe Sensei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | Con i consigli sulle caratteristiche, quando si crea o modifica un segmento in [Segment Builder](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html), è ora possibile ricevere consigli sulle caratteristiche aggiuntive da includere dai feed di dati di [!UICONTROL Audience Marketplace] ai quali non si è iscritti. Aggiungi le caratteristiche consigliate al segmento per aumentare il pubblico di destinazione. <br> Inoltre, abbiamo riprogettato la pagina [!UICONTROL Marketplace] per semplificare la ricerca di caratteristiche simili e filtrare i feed di dati. |
| [Strumenti per la gestione di massa](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | È stata rilasciata una nuova versione del foglio di lavoro Bulk Management che funziona sui sistemi operativi macOS e Microsoft Windows e supporta l’accesso a Experience Cloud. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Abbiamo aggiunto il supporto per [!DNL HTTP Strict-Transport-Security], un criterio di sicurezza web per la protezione contro attacchi di tipo cookie hijacking e protocol downgrade. |

### Miglioramenti {#aam-enhancements}

A partire da novembre 2019, Audience Manager supporta anche l'invio di ID Roku, ID Amazon Fire TV e ID Xbox/Microsoft a Google Ad Manager e DV360, oltre ai cookie supportati in precedenza, gli ID dispositivo IDFA (Identifier for Advertisers) e GAID (Google Advertising). Non è necessario apportare modifiche alle integrazioni Google esistenti.

In Audience Manager gli ID Roku, gli ID Amazon Fire TV e gli ID Xbox/Microsoft prendono il nome di ID dispositivo globale. Per ulteriori informazioni su questi ID e sulle fonti di dati a cui sono associati nella documentazione di Audience Manager, consulta le pagine:

* [ID dispositivo globale](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html#global-device-ids)
* [Fonti di dati globali](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)

L'inserimento dei dati per le fonti di dati Roku, Amazon Fire TV e Xbox/Microsoft funziona esattamente come per gli ID IDFA e GAID: viene generato automaticamente un ID Audience Manager, che viene collegato agli ID Device Advertising (DAID) al momento dell'acquisizione dei dati inseriti. I nuovi ID vengono inviati automaticamente alle destinazioni Google, nuove e preesistenti, che sono configurate nel tuo account.

Per ulteriori informazioni, contatta il tuo consulente Audience Manager o l'Assistenza clienti.

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* È stato corretto un bug in Audience Marketplace, a causa del quale l’interfaccia utente restituiva l’errore 409 in seguito all’invio dell’utilizzo di segmenti mensile. (AAM-50825)
* È stato corretto un bug nella funzione per segnali derivati, a causa del quale per un breve periodo i clienti non potevano creare nuovi segnali derivati. (AAM-50968)
* È stato corretto un bug nelle destinazioni people-based, a causa del quale i clienti non potevano cambiare il nome di una destinazione. (AAM-51025)
* È stato corretto un bug a causa del quale alcuni utenti avevano account duplicati per accedere all’interfaccia utente di Audience Manager. Per via delle autorizzazioni associate agli account duplicati, non era possibile accedere ad alcune parti dell’interfaccia utente ed eseguire operazioni. (AAM-50818)
* Abbiamo continuato a migliorare l’accessibilità dell’interfaccia utente di Audience Manager. (AAM-48932, AAM-48997, AAM-49043, AAM-49054, AAM-49371, AAM-49375, AAM-51313)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Rilasci di prodotti

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 è una versione con nuove funzioni che fornisce agli utenti di Brand Portal (agenzie/team esterni) di caricare contenuti in Brand Portal e pubblicarli in AEM Assets, senza dover accedere all’ambiente di creazione. Questa funzione si chiama [Origine risorse in Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html) e migliora l’esperienza dei clienti grazie a un meccanismo bidirezionale che consente agli utenti di contribuire e condividere risorse con altri utenti di Brand Portal distribuiti a livello globale.

   Consulta [Novità di AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   Consulta le [note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **Servizio Automated Forms Conversion di AEM**

   Il servizio Automated Forms Conversion consente di accelerare la digitalizzazione e la modernizzazione delle esperienze di acquisizione dati grazie alla conversione automatizzata di moduli PDF in moduli adattivi. Il servizio, con tecnologia Adobe Sensei, converte automaticamente i moduli PDF in moduli adattivi basati su HTML5, reattivi e facili da utilizzare sui dispositivi mobili. Questo servizio sfrutta le attuali soluzioni PDF Forms e XFA e, durante la conversione, ai campi modulo adattivi vengono anche applicate convalide, stili, layout appropriati.

   Consulta [Adobe Experience Manager Forms Automated Conversion Service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

   Sono ora disponibili le note sulla versione generali per Cloud Manager 2019.10.0. Nelle note sono inoltre riportati gli aggiornamenti ai passaggi di implementazione e alla gestione delle versioni dei progetti Maven.

   Consulta le [note sulla versione di Cloud Manager 2019.10.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Aiuto e documentazione

* **Activity Map**

   A causa di modifiche di sicurezza nell’API di Adobe Analytics, non è più possibile utilizzare la versione di Activity Map inclusa in AEM. Consulta [Configurazione della connessione ad Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   Ora è necessario utilizzare il [plug-in browser Activity Map](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) per Chrome, Firefox o Internet Explorer, fornito da Adobe Analytics.

* **Guida alle best practice per i progetti AEM Screens**

   La nuova _Guida alle best practice per AEM Screens_ offre informazioni complete e consigli pratici per ideare, progettare e introdurre esperienze cliente intenzionali nell’implementazione per insegne digitali. Inoltre, illustra come applicare le best practice per ottenere un impatto positivo sul business, mentre si implementa un progetto di insegne digitali in AEM Screens.

   Consulta la [Guida alle best practice per i progetti AEM Screens](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html).

* **Gestione delle esperienze headless**

   Sono ora documentate le funzioni di [Remote Content Renderer](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) utilizzate per il rendering lato server delle applicazioni a pagina singola.

* **Rendering lato server e applicazioni a pagina singola**

   Puoi estendere e personalizzare per le tue esigenze il servizio di rendering remoto dei contenuti, utilizzato dalle applicazioni a pagina singola basate su AEM per il rendering lato server.

   Consulta [Rendering lato server e applicazioni a pagina singola](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **Archetipo di progetto AEM**

   L’archetipo di progetto AEM crea un progetto Adobe Experience Manager minimo basato su best practice, da usare come punto di partenza per i progetti AEM. Quando si utilizza questo archetipo, si forniscono delle proprietà che consentono di specificare i nomi di tutte le parti del progetto e di controllare alcune funzioni facoltative.

   Consulta [Archetipo di progetto AEM](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

* **Aggiornamenti alla documentazione di AEM**

   Scopri le modifiche e gli aggiornamenti importanti apportati alla documentazione di Adobe Experience Manager negli ultimi tre mesi.

   Consulta [Documentazione di AEM: aggiornamenti recenti della documentazione](https://helpx.adobe.com/experience-manager/documentation-updates.html).

### Risorse aggiuntive

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Risorse di documentazione

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Aggiornato nella versione dell’8 novembre 2019

| Visualizzazione | Funzione |
|------|---------|
| Monitoraggio delle conversioni | Il tag di mappatura della conversione basato su JavaScript per Advertising Cloud ora supporta il monitoraggio di click-through da Mozilla Firefox versione 69 e successive, che blocca i cookie di terze parti per impostazione predefinita. Lo stesso tag include già il supporto per Apple Safari.<br><br/>Nel caso in cui si utilizzi il monitoraggio delle conversioni di Advertising Cloud e il tag di mappatura della conversione di Advertising Cloud non sia stato ancora implementato, è necessario applicare il seguente codice su tutte le pagine di destinazione:<br></br>`<script src="//www.everestjs.net/static/amo-conversion-mapper.js"></script>`<br></br>Nota: Questo tag supporta i tag di monitoraggio delle conversioni v2 e v3 di JavaScript per Advertising Cloud, ma non il tag di monitoraggio delle immagini. |
| Portfolio | Quando è attivata l’opzione di portfolio “Abilita % massima dell’obiettivo di spesa di campagna”, l’obiettivo di spesa massima non viene mai superato. In precedenza, Advertising Cloud superava l’obiettivo di spesa massima nel caso in cui lo ritenesse ideale. |
| Cerca tipi di pubblico | La libreria dei tipi di pubblico in Cerca &gt; Pubblico &gt; Libreria ora include automaticamente una colonna “Dimensione pubblico”, popolata ogni giorno da Bing Ads e Google Ads. Facoltativamente è possibile utilizzare la colonna come filtro dati. |
| Integrazione con Adobe Analytics | Analytics ora include la dimensione “Landing Type (AMO ID)” per le campagne Advertising Cloud DSP.  Utilizza questa dimensione per segmentare le metriche di Analytics in base al modo in cui i visitatori sono arrivati sul sito. I valori includono “Click Through” e “View Through”.<br><br/>**Nota:** I dati per le visite precedenti al 31 ottobre 2019 vengono mostrati come dati per le operazioni di click-through. Pertanto, non consigliamo di utilizzare questa dimensione con dati precedenti a metà novembre 2019. |
