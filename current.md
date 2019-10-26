---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: novembre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Novembre 2019

> [!IMPORTANT] Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

Nuove funzioni e correzioni in Adobe Experience Cloud.

> [!NOTE] Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 30 ottobre 2019**

* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)

## Interfaccia di Experience Cloud {#ecloud}

Note sulla versione per l’interfaccia di Experience Cloud e per la gestione dei prodotti.

* La pagina Feed è stata rimossa a dicembre 2019. Cercate un avviso di obsolescenza all'interno del prodotto. (MCUI-10039)
* È stato aggiornato il collegamento [Ulteriori](https://www.adobe.com/marketing/campaign.html) informazioni per Adobe Campaign dal selettore delle app. (MCUI-10034)
* Miglioramento della stabilità e della reattività della piattaforma di base per l'interfaccia Experience Cloud. (MCUI-6822)
* Risolte le vulnerabilità di protezione nell’interfaccia utente di Experience Cloud. (MCUI-9942)
* È stato risolto un problema critico in Attributi cliente che bloccava la convalida dello schema per alcuni clienti. (MCUI-10024, MCUI-6479)
* Migliorata la Libreria Pubblico per rimuovere le dimensioni non supportate per la creazione di audience in tempo reale. (MCUI-10046)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html) (Tutti i prodotti Adobe)

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
| Analisi percorso cliente | Il 21 novembre 2019, Adobe renderà disponibile [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) come componente aggiuntivo di Adobe Analytics.<br><br/>Analisi del percorso del cliente consente di portare tutti i dati del cliente da qualsiasi canale — online e offline — in Adobe Experience Platform, quindi analizzi questi dati come faresti con i tuoi dati digitali esistenti utilizzando Analysis Workspace. Analisi del percorso del cliente include la possibilità di controllare come collegare i dati online e offline in Analysis Workspace su qualsiasi ID cliente comune, consentendo infine di eseguire l’attribuzione, la segmentazione, il flusso, l’abbandono ecc. nell’intero set di dati cliente in Adobe Analytics.<br><br/>I clienti Analytics Select, Prime e Ultimate possono acquistare questo prodotto aggiuntivo. Per ulteriori informazioni, contattate il team di account Adobe. |
| API per i Servizi per la privacy: CCPA | Il California Consumer Privacy Act (CCPA) migliora i diritti alla privacy e la protezione dei consumatori per i residenti in California, Stati Uniti. La legge entrerà in vigore il 1° gennaio 2020.<br><br/>Il CCPA conferisce ai residenti della California nuovi diritti sulla privacy dei dati, come il diritto di accesso e cancellazione dei propri dati personali, di sapere se i propri dati personali vengono venduti o divulgati (e a chi), e di rifiutare la vendita degli stessi.<br><br/>In previsione del CCPA, i servizi per la privacy supporteranno le richieste di rinuncia alla vendita di dati personali.<br><br/>I servizi per la privacy erano precedentemente noti come servizi RGPD e manterranno tutte le funzionalità precedenti, in aggiunta al supporto per il CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Panoramica del servizio sulla privacy](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | L’abilitazione di Privacy Reporting per Analytics aggiunge una serie di variabili riservate a una suite di report.  Le variabili sono concepite per facilitare la raccolta di dati sul consenso dei consumatori a livello di hit.<br><br/>Nuove dimensioni:<br/><ul><li>Gestione del consenso Opt-Out</li><li>Gestione del consenso Opt-in</li><li>[Variabili di gestione del consenso](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Analisi audio e video: supporto per la privacy | Sono state aggiunte due nuove variabili all’API di Media Collection:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Si tratta di variabili facoltative che possono essere utilizzate per acquisire lo stato del consenso di un consumatore al momento della hit.<br/><br/>[Documentazione API di Media Collection](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Al modulo Federated Analytics sono state aggiunte le nuove variabili di dati contestuali di per la gestione del consenso di Analytics. Queste variabili sono ora disponibili per l’utilizzo nei casi in cui si contrassegna l’opzione Rifiuta condivisione o Vendi hit per federazione.<br/><br/>[Scarica Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Correzioni

* È stato risolto un problema che causava un errore durante il tentativo di eliminare gli intervalli di date di proprietà di "Utente sconosciuto". (AN-185540)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita di gennaio 2020 per l’opzione **[!UICONTROL Visualizza archivio]** in Gestione dashboard (**[!UICONTROL Componenti &gt; Dashboard]**). |
| Opzione **[!UICONTROL Applica restrizioni]** di accesso IP | 30 ottobre 2019 | Annunciando la data di fine del ciclo di vita di gennaio 2020 per la funzionalità whitelist di accesso IP (**[!UICONTROL Applica limitazioni]** accesso IP) nel menu **[!UICONTROL Admin (Amministratore) &gt; Company Settings (Impostazioni società) &gt; Security (Protezione]** ). |
| Aggiornamento della gestione all'attributo SameSite sui cookie | 15 ottobre 2019 | Nell'agosto 2019, Adobe ha annunciato di aver aggiunto l'impostazione cookie SameSite a tutti i cookie impostati da Analytics. Un aggiornamento nella logica viene applicato dove:<ul><li>Tutti i cookie di terze parti non basati su Webkit hanno l'attributo SameSite impostato su `none`.</li><li>Tutti gli altri cookie non hanno l'attributo SameSite impostato.</li></ul> |
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

Nuove funzioni, miglioramenti e correzioni in Audience Manager.

| Funzione | Descrizione |
|--- |----|
| [Miglioramenti delle regole di unione dei profili](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Abbiamo rilasciato una serie di miglioramenti per le regole di unione dei [!UICONTROL profili]: <ul><li>La valutazione del segmento ora è supportata in batch, fino a 100 dispositivi.</li><li>Abbiamo migliorato la precisione dei rapporti per le caratteristiche e le popolazioni di segmenti.</li><li>Abbiamo migliorato la precisione dei file batch generati utilizzando ID cross-device.</li><li>Abbiamo aggiornato la documentazione con casi di utilizzo più dettagliati per ogni regola. Consulta Casi di utilizzo [generali per le regole](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)di unione dei profili, i casi [di utilizzo di Device Graph](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)esterni e i casi [di utilizzo di](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html)Profile Link Device Graph.</li></ul> |
| [Strumenti di gestione di massa](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | È stata rilasciata una nuova versione del foglio di lavoro Gestione di massa che funziona sui sistemi operativi MacOS e Microsoft Windows e supporta l'accesso a Experience Cloud. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Abbiamo aggiunto il supporto per [!DNL HTTP Strict-Transport-Security], una politica di sicurezza web che protegge contro il dirottamento dei cookie e gli attacchi di downgrade del protocollo. |

**Correzioni e miglioramenti**

* È stato corretto un bug in Audience Marketplace, a causa del quale l'interfaccia utente restituiva l'Errore 409 quando i clienti inviavano l'utilizzo mensile del segmento. (AAM-50825)
* È stato corretto un bug in Segnali derivati, a causa del quale per un breve periodo i clienti non potevano creare nuovi segnali derivati. (AAM-50968)
* È stato corretto un bug in Destinazioni basate sulle persone, a causa del quale i clienti non potevano cambiare il nome di una destinazione. (AAM-51025)
* È stato corretto un bug a causa del quale alcuni utenti disponevano di account duplicati per accedere all’interfaccia utente di Audience Manager. A causa delle autorizzazioni associate agli account duplicati, questi utenti non potevano accedere ad alcune parti dell'interfaccia utente ed eseguire operazioni. (AAM-50818)
* Abbiamo continuato a migliorare l'accessibilità dell'interfaccia utente di Audience Manager. (AAM-48932, AAM-49043, AAM-49054, AAM-49371, AAM-49375)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Rilasci di prodotti

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 è una release che si concentra sulla possibilità per gli utenti del Brand Portal (agenzie/team esterni) di caricare contenuti nel Brand Portal e pubblicarli in Risorse AEM, senza la necessità di accedere all’ambiente di authoring. Questa funzione è denominata [Asset Sourcing in Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)e migliora l’esperienza dei clienti fornendo agli utenti un meccanismo bidirezionale per contribuire e condividere le risorse con altri utenti del Brand Portal distribuiti a livello globale.

   Consulta [Novità di AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms Automated Conversion Service**

   Il servizio di conversione automatizzata dei moduli consente di accelerare la digitalizzazione e la modernizzazione delle esperienze di acquisizione dei dati attraverso la conversione automatizzata dei moduli PDF in moduli adattivi. Il servizio, basato su Adobe Sensei, converte automaticamente i moduli PDF in moduli adattivi semplici da periferica, reattivi e basati su HTML5. Sfruttando gli investimenti esistenti in PDF Forms e XFA, il servizio applica anche convalide, stili e layout appropriati ai campi modulo adattivi durante la conversione.

   Consulta [Adobe Experience Manager Forms Automated Conversion Service](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

   Sono ora disponibili le note sulla versione generali per Cloud Manager 2019.10.0. Nelle note sono inoltre riportati gli aggiornamenti ai passaggi di distribuzione e alla gestione delle versioni dei progetti in modalità "Paradiso".

   Consulta le note [di rilascio di](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)Cloud Manager 2019.10.0.

### Aiuto e documentazione

* **Activity Map**

   A causa di modifiche alla sicurezza nell’API di Adobe Analytics, non è più possibile utilizzare la versione della Activity Map inclusa in AEM. Consultate [Configurazione della connessione ad Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   È ora necessario utilizzare il plug-in [del browser Mappa](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) attività per Chrome, Firefox o Internet Explorer, come fornito da Adobe Analytics.

* **Guida alle best practice per i progetti AEM Screens**

   La nuova Guida alle _best practice per AEM Screens_ offre informazioni approfondite e consigli pratici per immaginare, progettare e introdurre esperienze cliente intenzionali nell'implementazione del digital signage. Inoltre, illustra come creare un impatto positivo sulla tua attività grazie alle best practice, il tutto mentre distribuisci un progetto di digital signage in AEM Screens.

   Consultate Guida alle [best practice per i progetti](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html)AEM Screens.

* **Gestione dell'esperienza headless**

   Sono ora documentate le funzioni di [Remote Content Renderer](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) utilizzate per il rendering lato server delle applicazioni a pagina singola.

* **Rendering lato server e SPA**

   Potete estendere e personalizzare il servizio di rendering dei contenuti remoti utilizzato dalle API AEM per il rendering lato server per soddisfare le vostre esigenze.

   Consultate Rendering [SPA e lato server](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **Archetipo progetto AEM**

   AEM Project Archetype crea un progetto Adobe Experience Manager minimo basato su best practice, come punto di partenza per i progetti AEM. Le proprietà che devono essere fornite quando si utilizza questo archetype consentono di specificare i nomi di tutte le parti del progetto e di controllare alcune funzioni facoltative.

   Consulta [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

* **Aggiornamenti alla documentazione AEM**

   Scopri le modifiche e gli aggiornamenti importanti alla documentazione per Adobe Experience Manager negli ultimi tre mesi.

   Consulta Documentazione di [AEM: Aggiornamenti](https://helpx.adobe.com/experience-manager/documentation-updates.html)recenti della documentazione.

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

### Risorse per la documentazione

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Aggiornato per il rilascio del 12 ottobre 2019

| Visualizzazione | Funzione |
|------|---------|
| Ricerca campagne | Advertising Cloud può ora sincronizzare e fornire il tracciamento a livello di annuncio per gli account su Yahoo! Japan Display Network. Se fornisci i dettagli di accesso per un account, tutte le campagne, i gruppi di annunci e gli annunci esistenti nell’account saranno disponibili in sola lettura nelle viste gestione campagne. Il numero di clic, i costi, le conversioni e altri dati sulle prestazioni sono disponibili nelle viste gestione campagne e nei report di base e avanzati. |
|  | (Per gli inserzionisti che fanno uso di Google Analytics) Advertising Cloud Search può sincronizzare le metriche di conversione per un account Google Analytics specifico, le proprietà e la visualizzazione combinata per l’ottimizzazione e il reporting. Visualizzazioni di pagina, sessioni, frequenza di rimbalzo (calcolata come rimbalzi/sessioni) e durata della sessione sono dati inclusi automaticamente. Puoi includere fino a 16 metriche aggiuntive per ogni origine dati. |
|  | (Account Google Ads esistenti per gli inserzionisti che fanno uso dell’integrazione Advertising Cloud-Adobe Analytics) È disponibile un nuovo formato per il codice di tracciamento s_kwcid, che consente a Advertising Cloud di condividere i dati sull’account con la funzionalità di reporting e analisi di Adobe Analytics. Il formato più recente include i parametri per l’ID della campagna e l’ID del gruppo di annunci, necessari per creare report accurati a livello di campagna e di gruppo di annunci per le campagne Google Drafts ed Experiments in Analytics. Se i tuoi account Google esistenti includono campagne Google Drafts ed Experiments, modifica le impostazioni di tracciamento account per ogni singolo account per migrare al nuovo s_kwcid. Se non disponi di campagne Google Drafts ed Experiments, la migrazione al nuovo formato è facoltativa. Nota: tutti i nuovi account Google utilizzano automaticamente il nuovo formato. |
| Ricerca Advanced Campaign Management (ACM) | (Campagne Google Ads) È ora possibile configurare i suffissi degli URL finali a livello di campagna per i modelli di annunci testuali e di annunci di acquisto di Google. |
|  | (Campagne Google Ads) I campi opzionali “Titolo 3” e “Descrizione 2” sono disponibili per gli annunci testuali espansi Google. |
| Rapporti | Le metriche sulle impression di Bing Ads riportate di seguito, che sono state interrotte con l’API Bing Ads più recente, non verranno più raccolte dopo l’11 ottobre:  Search IS% Lost to Rank, Search IS% Lost to Bid (Bing), Search IS% Lost to Page Relevance (Bing), and Search IS% Lost to Keyword Relevance (Bing). Le metriche raccolte in precedenza sono ancora disponibili per il reporting. |
| Integrazione di Adobe Analytics | (Solo per gli inserzionisti che fanno uso di Adobe Analytics) In Analysis Workspace, la dimensione “Device (AMO ID)”, che non ha mai raccolto dati, non è più disponibile. Per generare rapporti sui dati di Analytics online, usa la dimensione “Tipo di dispositivo mobile”. Per generare report sulle metriche del traffico del motore di ricerca (come clic, costi e impression) per tipo di dispositivo, continua a utilizzare il reporting in Advertising Cloud Search. |
