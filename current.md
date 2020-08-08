---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di Adobe Experience Cloud
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dab2c3fb8b9920f079195693a584f7c48b813e23
workflow-type: tm+mt
source-wordcount: '6207'
ht-degree: 43%

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Agosto 2020

![Banner](/assets/experience-cloud-banner-3.png)

Questa pagina descrive nuove funzioni, correzioni e avvisi importanti in [!DNL Adobe Experience Cloud]. Inoltre mette in evidenza documentazione, corsi di formazione ed esercitazioni video farti per ottenere il massimo da Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima del rilascio ufficiale.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni.

**Data di rilascio: 13 agosto 2020**

Le date di rilascio del prodotto possono variare. Controlla spesso la disponibilità di aggiornamenti.

Ultimo aggiornamento: **7 agosto 2020**

* [Stato del sistema di Adobe](#status)
* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/it-IT/primetime/release-notes/home.translate.html)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/#home) per trovare documentazione tecnica e dei prodotti, corsi curati da Adobe, esercitazioni video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Per informazioni aggiornate sulla versione, consultate [il 21 maggio 2020](c-legacy-releases/2020/05212020.md#status) .

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Per informazioni aggiornate sull&#39;interfaccia aggiornata e sul dominio unificato del prodotto, consulta le note [di luglio](c-legacy-releases/2020/07162020.md#ecloud) precedenti sulla versione.

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Note sulla versione per [!DNL Experience Platform] e per i servizi dell’applicazione, tra cui [!DNL Experience Platform Launch,] [!UICONTROL Offerte], [!UICONTROL Persone], [!UICONTROL Places], [!UICONTROL Mobile Services] e bollettini di sicurezza.

Latest release date: **July 15, 2020**

Per informazioni aggiornate su Experience Platform, consulta le [Note sulla versione di Experience Platform](https://docs.adobe.com/content/help/it-IT/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

### Nuovi corsi e tutorial su Campaign

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Descrizione |
| ----------- | ---------- | ---------- |  
| 10 luglio 2020 | [Generazione di rapporti sugli eventi delle fasi del viaggio in Adobe Experience Platform](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | Scopri cosa sono gli eventi dei passaggi di viaggio e quali passaggi di dati vengono creati automaticamente  Experience Platform e come esplorarli. |

### Risorse aggiuntive per Journey Orchestration

[Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/it-IT/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni in Customer Journey Analytics](#cust-journey)
* [Nuove funzioni di Media Analytics](#media-aa)
* [Problemi risolti in Adobe Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-------|
| Miglioramenti alla raccolta dati in Cina | 13 agosto 2020 | I miglioramenti includono: Supporto per  servizio ID Experience Cloud; supporto per SSL di prime parti; e supporto per l&#39;inoltro lato server. Per la documentazione, contattate il rappresentante commerciale  Adobe. |
| [!UICONTROL Analisi]multi-dispositivo: Disponibilità in EMEA e APAC | 31 agosto 2020 | [Analisi](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) cross-device e grafico privato saranno disponibili per i clienti nell&#39;area EMEA e in APAC. |
| Miglioramento dell&#39;unione basata sul campo in Analytics  multi-dispositivo (disponibile in America ed EMEA) | 17 agosto 2020 | Questa implementazione semplificata per i nuovi clienti di Analytics  multi-dispositivo consente di eseguire l&#39;unione in base a un ID utente memorizzato in un campo Analytics (prop o  eVar) invece di utilizzare il grafico del dispositivo (co-op o privato). Questo miglioramento elimina il requisito di implementare ECID e rimuove il requisito di implementare la sincronizzazione ID ai fini di CDA. (per alcune altre funzioni è ancora necessaria la sincronizzazione di ECID e ID.) |

### Nuove funzioni in Customer Journey Analytics {#cust-journey}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-----|
| [!UICONTROL Opzione di Identity Map per l’ID persona] | 26 giugno 2020 | [!UICONTROL Mappa] identità è una struttura dati mappa che consente di caricare coppie chiave-valore come parte della creazione di una connessione nel [!UICONTROL Customer Journey Analytics]. Le chiavi sono spazi dei nomi dell’identità e il valore è una struttura che contiene il valore dell’identità. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### Nuove funzioni di [!UICONTROL Media Analytics] {#media-aa}

Data di rilascio: **16 luglio 2020**

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- | ---------- |
| [Piattaforme e dispositivi supportati](https://docs.adobe.com/content/help/it-IT/media-analytics/using/supported-devices.html) | 18 giugno 2020 | The [!UICONTROL Media Launch Extension] with AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Piattaforme e dispositivi supportati](https://docs.adobe.com/content/help/it-IT/media-analytics/using/supported-devices.html) | 18 giugno 2020 | L’estensione Media Launch con SDK di AEP ora supporta i seguenti dispositivi OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Tracciamento dello stato del lettore](https://docs.adobe.com/content/help/it-IT/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 maggio 2020 | I clienti [!UICONTROL Media Analytics] possono visualizzare le interazioni dei visualizzatori durante la riproduzione facendo uso di un set standard di variabili della soluzione per visualizzazione a schermo intero, sottotitoli, modalità muto, immagine nell’immagine e messa a fuoco. È inoltre possibile creare degli stati del lettore personalizzati. Le variabili di tracciamento dello stato del lettore sono ora disponibili per il reporting in [!UICONTROL Analysis Workspace]. Questa funzione richiede uno dei seguenti elementi: <ul><li>SDK di [!DNL JavaScript] Media 3.0 o versione successiva</li><li>Per l’utilizzo con l’SDK di [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Estensione Media Analytics] (per il web): [!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 o versione successiva</li><li>[!UICONTROL Estensione Media Analytics] (per dispositivi mobile): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 o versione successiva</li><li>[!UICONTROL Media Collection]</li></ul> |

### Problemi risolti in Adobe Analytics {#aa-fixes}

* È stato risolto un problema che impediva all&#39;API di reporting di restituire valori di metriche aggiornati. (AN-225617)
* È stato risolto un problema che impediva alle regole [!UICONTROL di] classificazione di classificare i dati per i dettagli [!UICONTROL canale]marketing. (AN-224832)
* È stato risolto un problema che causava un errore di componenti __ mancanti durante la creazione di nuovi progetti in una suite [!UICONTROL di rapporti]virtuale.(AN-226808)
* È stato risolto un problema che causava un errore di componenti __ mancanti durante la cura di una suite di rapporti virtuale. (AN-228257)
* È stato risolto un problema che impediva la creazione di nuovi target e eventi di calendario per [!UICONTROL Reporting e analisi] . (AN-224872, AN-224890, AN-224914, AN-226661)
* È stato risolto un problema che causava attività mancanti nel pannello A4T in [!UICONTROL Workspace]. (AN-224606)
* È stato risolto un problema relativo agli hit duplicati nei feed dati. (AN-226308)
* È stato risolto un problema per il quale le metriche calcolate con attribuzione di partecipazione non restituivano valori corretti. (AN-224642, AN-225190)
* È stato risolto un problema con i dati del segmento condivisi che [!DNL Analytics] richiedeva più di tre [!DNL Audience Manager] giorni per essere visualizzati in [!DNL Audience Manager].(AN-226649)
* È stato risolto un problema che impediva l&#39;utilizzo del collegamento [!UICONTROL Analizza ulteriormente] nelle e-mail di avvisi  intelligenti. (AN-226823)
* È stato risolto un problema che impediva la creazione di segmenti in una suite [!UICONTROL di rapporti]virtuale. (AN-227039)
* È stato risolto un problema che impediva la modifica degli avvisi intelligenti. (AN-227162)

#### Ulteriori correzioni di Adobe Analytics

AN-219351; AN-220960; AN-223788; AN-224630; AN-224948; AN-225618; AN-226261; AN-226828; AN-226845; AN-226937; AN-226961; AN-227070; AN-227079; AN-227521; AN-227610; AN-228203; AN-228451; AN-228466; AN-228538

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Fine del ciclo di vita dei connettori dati di Adobe | 13 luglio 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. Per continuare a offrire e supportare le integrazioni, si consiglia di adottare il nuovo programma standard [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). La data ufficiale di fine del ciclo di vita è ancora da definire, ma è prevista nei prossimi 12-18 mesi, nella seconda metà del 2021. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mappatura delle suite di rapporti per organizzazioni IMS | Luglio 2020 | Lo strumento di mappatura delle suite di rapporti verrà terminato a novembre 2020. Questa funzione consente integrazioni quali la pubblicazione di segmenti Advertising Analytics e Experience Cloud in Adobe Analytics. Una suite di rapporti deve essere mappata su un’organizzazione IMS per abilitare questi e altri servizi. Le nuove suite di rapporti vengono mappate automaticamente al momento della creazione. Tuttavia, le suite di rapporti meno recenti devono essere mappate manualmente su un’organizzazione IMS. See [Map report suites to an organization](https://docs.adobe.com/content/help/it-IT/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| Migrazione a un dominio di prodotto unificato | Data di validità: 28 maggio 2020 | La migrazione a un dominio di prodotto unificato per Adobe Analytics, iniziata a gennaio 2020, è stata completata il 28 maggio 2020. Adobe Analytics si impegna a rimuovere dalla propria architettura tutti i riferimenti al dominio `omniture.com`, ma è importante inserire `omniture.com` nell’elenco Consentiti in quanto cookie di terze parti. A breve, quando verrà portata a termine la migrazione dell’architettura, riceverai una notifica tramite le note sulla versione e non sarà più necessario compiere questo passaggio. [Qui](https://helpx.adobe.com/it/analytics/kb/adobe-ip-addresses.html) puoi trovare un elenco completo degli indirizzi IP consigliati e dei domini che dovresti inserire nell’elenco dei consentiti.<br>Se l’organizzazione blocca i cookie di terze parti, contatta l’assistenza clienti per recuperare l’accesso ad Adobe Analytics. |
| Nuova pagina di destinazione predefinita di Adobe Analytics | Data di validità: 18 giugno 2020 | Il 18 giugno 2020 la pagina di destinazione predefinita per Adobe Analytics passerà da [!UICONTROL Reports] a [!UICONTROL Workspace]. Questa modifica verrà applicata agli utenti che non hanno precedentemente impostato una pagina di destinazione personalizzata. |
| Elenco delle tecnologie di terze parti consentite | 12 marzo 2020 (data effettiva) | Adobe Analytics ha iniziato a sfruttare tecnologie di terze parti per la gestione del rollout delle funzioni e per il supporto integrato nel prodotto. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti per assicurare l’accesso a tutte le funzioni:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Miglioramento della ridondanza per la disponibilità di [!UICONTROL Analysis Workspace] | 21 maggio 2020 | Per assicurare la disponibilità di [!UICONTROL Analysis Workspace], verrà aggiunta una rete per la distribuzione di contenuti (CDN) secondaria per migliorare la ridondanza. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Poiché ora in [!UICONTROL Analysis Workspace] è possibile attivare e disattivare i valori _None_, viene applicato il valore _None_ dopo l’entrata o l’uscita, mentre per le eVar veniva applicato prima dell’entrata o dell’uscita. Ad esempio, si supponga che il primo risultato di una visita non presenti alcun valore per le eVar, ma il secondo sì. In [!UICONTROL Reports &amp; Analytics] il primo risultato verrà visualizzato come _non specificato_ per l’Entrata, ma in [!UICONTROL Analysis Workspace] verrà visualizzato come valore per il secondo risultato. |
| Fine del ciclo vita di **[!UICONTROL Archivio dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL Visualizza archivio]** nella sezione **[!UICONTROL Gestione dashboard]** in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| Fine del ciclo di vita delle API legacy di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Per gli ultimi aggiornamenti sulle versioni di AppMeasurement, fare riferimento alle [note sulla versione di AppMeasurement per JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html).

#### Nuovi corsi ed esercitazioni di Analytics {#tutorials-analytics}

Nuovi corsi, esercitazioni video e articoli in Analytics e Customer Journey Analytics.

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| ----------- | ----------- | ---------- | ---------- |  
| 30 luglio 2020 | [Limita accesso alle suite di rapporti nel Admin Console](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | Esercitazione | Scopri come utilizzare il [!UICONTROL Admin Console] per garantire che gli utenti possano accedere solo alle suite di rapporti necessarie per il loro ruolo. |
| 24 luglio 2020 | [Aggiunta di un amministratore a  Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | Esercitazione | Scoprite come aggiungere un utente come amministratore nel Adobe  [!UICONTROL Admin Console]. |
| 17 luglio 2020 | [Pannello Quick Insights in  Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | Esercitazione | Quick Insights fornisce indicazioni ai non analisti e ai nuovi utenti di Analysis Workspace per scoprire come rispondere alle domande aziendali in modo rapido e semplice. |
| 17 luglio 2020 | [Pannello Analytics for Target (A4T) in  Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | Esercitazione | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 6 luglio 2020 | [Creare  dashboard Advertising Cloud con  Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | Esercitazione | Tecniche per creare un dashboard Advertising Cloud  per il monitoraggio delle campagne live. |
| 6 luglio 2020 | [Creare metriche personalizzate di Analytics con  dati Advertising Cloud](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | Esercitazione | Metriche personalizzate utili da creare quando si utilizzano  dati Advertising Cloud all&#39;interno  Adobe Analytics. |
| 6 luglio 2020 | [Creare profili percorso sito di Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | Esercitazione | Come utilizzare  Adobe Analytics per creare solidi pool di retargeting dei siti per  remarketing Advertising Cloud. |
| 6 luglio 2020 | [Creazione di segmenti di Analytics per attivazione e reporting](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | Esercitazione | Utilizzo  dimensioni Advertising Cloud per creare segmenti per reporting e analisi più nitidi. |
| 6 luglio 2020 | [Creazione di un&#39;analisi di campagna preliminare con  Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | Esercitazione | Come utilizzare  Adobe Analytics per impostare le basi per l&#39;avvio di una  campagna media a pagamento Advertising Cloud. |
| 6 luglio 2020 | [Condivisione di progetti in  Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | Esercitazione | La condivisione dei progetti è uno dei modi per democratizzare i dati e le informazioni da  Analysis Workspace agli utenti dell&#39;organizzazione. I destinatari possono essere inseriti in uno dei tre ruoli di progetto, a seconda dell&#39;esperienza di progetto che desiderano che abbiano: Modifica, Duplica e Visualizza. |
| 26 giugno 2020 | [Finestre di look-back personalizzate nelle Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | Esercitazione | Le finestre di look-back personalizzate consentono di espandere la finestra di attribuzione oltre l&#39;intervallo di reporting (fino a un massimo di 90 giorni) e si applica a ogni conversione nell&#39;intervallo di reporting. |
| 26 giugno 2020 | [Visualizzare progetti di sola lettura in  Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | Esercitazione | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 26 giugno 2020 | [Modello algoritmico nelle Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | Esercitazione | Il modello [!UICONTROL attribuzione algoritmica] di Analysis Workspace utilizza tecniche statistiche per determinare in modo dinamico l’allocazione ottimale del credito per la metrica selezionata. |

#### Risorse dell’Aiuto di Analytics

* [Esercitazioni di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentazione dei prodotti Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html)

## ![Icona](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuove funzioni, correzioni, documentazione ed esercitazioni in Audience Manager.

Data di rilascio: **13 agosto 2020**

### Nuove funzioni e correzioni in Adobe Audience Manager

* [Le audience](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) predittive ora supportano la selezione di una regola [!UICONTROL di unione] profilo per modello, durante la creazione del modello. (AAM-55178)
* Le date di inizio e di fine della mappatura della destinazione sono ora visibili nella pagina di ciascun segmento. (AAM-40056)
* È stato risolto un problema per il quale il tipo [!UICONTROL di] dispositivo di una caratteristica veniva automaticamente impostato su [!UICONTROL cross-Device] durante la creazione di una nuova caratteristica. (AAM-55368)
* È stato risolto un problema che impediva il caricamento dell&#39;Audience Marketplace  . (AAM-55549)
* Ora puoi rimuovere la mappatura dei segmenti dalle [!DNL Google] destinazioni quando il [!DNL Google UserList] parametro non è recuperabile. (AAM-42655)
* È stato corretto un problema a causa del quale l&#39;aggiunta di più segmenti a una destinazione non sempre funzionava correttamente. (AAM-55651)
* È stato corretto un problema a causa del quale gli utenti con [!DNL Profile Merge Rules] limite aumentato non visualizzavano il pulsante [!UICONTROL Aggiungi nuova regola] . (AAM-55700)
* È stato risolto un problema a causa del quale il titolo Utenti [!UICONTROL univoci con sovrapposizione di] 30 giorni risultava mancante nelle metriche [!UICONTROL del rapporto Feed]dati. (AAM-55801)
* Le metriche del ciclo di vita ora sono escluse dalla visualizzazione [!UICONTROL Destinazione] quando la destinazione è configurata per l&#39;esportazione [!DNL UUID]s. (AAM-54196)
* È stato risolto un problema che impediva agli utenti di visualizzare [!DNL Tableau] i rapporti. (AAM-55868)
* È stato risolto un problema a causa del quale gli utenti ricevevano un errore durante la creazione di un nuovo modello [!UICONTROL Predictive Audiences] . (AAM-55921)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-49062, AAM-49063, AAM-49365).

### Nuove esercitazioni di Audience Manager {#tutorials-aam}

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| ----------- | ----------- | ---------- | ---------- |
| 7 agosto 2020 | [Risparmia denaro e ottimizza l&#39;esperienza dei clienti eliminando gli annunci ai convertitori](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | Esercitazione | In questo corso, scopri tutti i concetti da seguire dall&#39;inizio alla fine con il caso d&#39;uso di risparmiare denaro e ottimizzare l&#39;esperienza del cliente rimuovendo i clienti esistenti dalle campagne di portata. Ciò include la creazione di caratteristiche e segmenti, l&#39;aggiunta delle regole di unione dei profili corrette, l&#39;aggiunta di segmenti alle destinazioni e persino il calcolo del ROI durante l&#39;utilizzo di questo caso. |
| 7 agosto 2020 | [Scelta della regola di unione profilo corretta](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | Esercitazione | In questo video, scopri tre dei casi d’uso più comuni per le regole [!UICONTROL di unione dei]profili e come possono essere utili per le tue attività di marketing. |
| 5 agosto 2020 | [Creazione di una tassonomia segmento](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | Esercitazione | Quando create un segmento in  Audience Manager, lo archiviate in una struttura basata su cartelle o in una _tassonomia_. Scopri alcuni suggerimenti per creare e gestire la tassonomia dei segmenti. |
| 4 agosto 2020 | [Recuperare le credenziali API in  I/O Adobe](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | Esercitazione | Invece di contattare  Consulente di Adobe o l&#39;Assistenza clienti per ottenere le credenziali per l&#39;utilizzo dell&#39;API REST, potete semplicemente andare `Adobe.io` in un browser e recuperare o registrare le vostre credenziali. |
| 31 luglio 2020 | [Utilizzo della frequenza e della frequenza nei segmenti](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | Esercitazione | Utilizzate [!UICONTROL Recency] e [!UICONTROL Frequenza] per fornire i parametri del segmento del numero di volte che un visitatore deve qualificarsi per una caratteristica entro un determinato periodo di tempo. Ideale per l’affinità dei contenuti e per i casi di utilizzo dei limiti di frequenza, così come per altri. |
| 22 luglio 2020 | [Nozioni di base sulla creazione di segmenti](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | Esercitazione | Scorri i campi nell’interfaccia utente per creare un segmento in  Audience Manager. |
| 22 luglio 2020 | [Definizione e creazione di segmenti pratici](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | Esercitazione | Questo video illustra un processo di definizione dei segmenti e quindi suddividerli in base alle caratteristiche e ai segnali necessari per crearli. |
| 17 luglio 2020 | [Sopprimi annunci a convertitori](https://video.tv.adobe.com/v/36658?captions=ita) | Esercitazione | Risparmiate denaro e ottimizzate l&#39;esperienza dei clienti eliminando gli annunci ai convertitori. |
| 15 luglio 2020 | [Misurazione del ROI in un caso di utilizzo di soppressione del cliente](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | Esercitazione | Scopri come utilizzare un paio di formule per determinare il risparmio sui costi della campagna eliminando gli annunci ai clienti esistenti. |
| 10 luglio 2020 | [Creazione di un segmento per sopprimere gli annunci ai clienti](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | Esercitazione | Questo video illustra le opzioni per la creazione di segmenti, al fine di escludere coloro che hanno già convertito lo stato del cliente. |

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### **Rilasci di prodotti**

* **AEM as a Cloud Service**

   Cosa c&#39;è di nuovo in AEM come Cloud Service? Le evidenziazioni disponibili includono:

   * AEM Commerce è ora disponibile sul Cloud Service. Consulta [Guida introduttiva AEM Commerce come Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * I connettori per  miglioramenti di Adobe Target e Adobe Analytics  includono miglioramenti dell&#39;interfaccia utente, sostituzione dell&#39;interfaccia utente classica e integrazione  lancio Adobe. Consultate [Integrazione  Adobe Analytics](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) e [Integrazione  Adobe Target.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * Asset Compute Service è un servizio scalabile ed estensibile per l’elaborazione delle risorse. Gli amministratori possono configurare  Experience Manager per richiamare il lavoratore personalizzato creato utilizzando il servizio Asset Compute Service. Gli sviluppatori possono utilizzare il servizio per creare lavoratori personalizzati specializzati in casi di utilizzo complessi. Questo servizio Web può generare miniature per diversi tipi di file, rendering di immagini di alta qualità da  formati di file di Adobe, codificare video (in futuro), estrarre metadati, estrarre testo completo come precursore per l’indicizzazione ed eseguire una risorsa tramite tutti i servizi Sensei disponibili. Consultate [Utilizzare i microservizi delle risorse e i profili di elaborazione.](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * Numerosi miglioramenti per i modelli di flussi di lavoro e per gli elementi multimediali dinamici in AEM come Cloud Service.
   * Release 2.11.0 of the [AEM Core Components](https://docs.adobe.com/content/help/it-IT/experience-manager-core-components/using/introduction.html) is now available as part of AEM Sites including the following:
      * Introduzione di un nuovo componente visualizzatore [PDF.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * Supporto delle pagine mobili accelerate (AMP) per i componenti core. Consente di creare esperienze cliente più veloci effettuando la transizione di pagina istantaneamente quando si accede al sito da un risultato di ricerca Google Mobile, migliorando il coinvolgimento degli utenti e il SEO. Consultate Supporto [AMP per i componenti core.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)
      * Compatibilità con la versione 1.0.2 del [Livello](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)dati client del Adobe.
   * Miglioramenti a più interfacce in Cloud Manager.
   * Le pipeline di Cloud Manager ora supportano variabili e segreti impostati dal cliente. Consultate Variabili [della tubazione.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [I registri possono essere inoltrati agli account](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs)Splunk, consentendo alle organizzazioni di sfruttare i propri [!DNL Splunk] investimenti.
   * Potete assegnare [un indirizzo](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) IP di uscita statico e dedicato al traffico in uscita programmato nel codice Java, utile per alcune integrazioni.
   * Cloud Readiness Analyzer v1.0.2 è stato rilasciato. Vedere [Installazione di CRA su AEM 6.1.](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html#installing-on-aem61)
   * Vedi le note [complete sulla versione AEM come Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### Aiuto e documentazione

* **AEM Forms**

   *  componente aggiuntivo AEM Forms sui pacchetti ora è disponibile su [AEM distribuzione](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Acontent%2Fmetadata%2Fdc%3Asolution&amp;2_group.property.operation=equals&amp;2_group.property.0_values=target-solution%3Aem%2Fforms&amp;orderby=%40jcr%3Acontent%2Fjcr%3AlastModified&amp;orderby.sort=desc list&amp;p.offset=0&amp;p.limit=24)software. Potete trovare collegamenti diretti per i pacchetti di ciascuna release supportata nell&#39;articolo delle [versioni](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html) di AEM Forms.
   * Utilizzate il sito [di](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) riferimento per apprendere il flusso di lavoro end-to-end del servizio di conversione Forms automatizzata.
   * Sono disponibili Javadocs per le release AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) e AEM [6.4.8.1](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) .
   * [Importa certificati](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) attendibili in JVM durante l&#39;indurimento di un AEM Forms  in ambiente JEE.
   * Miglioramento della documentazione di configurazione di [PDF Generator.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **Componenti core**

   La release 2.11.0 dei componenti core supporta AMP ed è ora disponibile insieme alla documentazione [sull&#39;](https://docs.adobe.com/content/help/it-IT/experience-manager-core-components/using/introduction.html) authoring e ai dettagli per [gli sviluppatori e al download dei progetti disponibili su GitHub.](https://github.com/adobe/aem-core-wcm-components)

### **Community**

* **Ultimi contenuti AEM su Experience League**

   Questa è la fonte ufficiale di contenuti tecnici Digital Experience prodotti da  Adobe. Vedi l&#39;elenco completo [qui.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Nuovi corsi ed esercitazioni di Experience Manager

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 7 agosto 2020 | [Guida introduttiva alla gestione multisito per utenti aziendali](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | Corso | Scoprite come creare solide basi per l&#39;implementazione  di AEM Assets configurando i problemi principali, dalla configurazione di un&#39;architettura di contenuto e di una tassonomia di base alla personalizzazione dei metadati e dell&#39;elaborazione delle risorse. |
| 7 agosto 2020 | [Configurazione  AEM Assets per gli amministratori](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | Esercitazione | Descrizione |
| 19 luglio 2020 | [Utilizzo dello strumento di trasferimento dei contenuti](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | Esercitazione | Lo strumento [!UICONTROL Content Transfer] Tool è il metodo consigliato per migrare il contenuto da una versione in hosting locale o AMS di  Experience Manager a un [!UICONTROL AEM come ambiente Cloud Service] . |
| 21 luglio 2020 | [Creare una Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | Esercitazione | Come creare una [!UICONTROL Live Copy] per il sito da una [!UICONTROL Blueprint] utilizzando la procedura guidata [!UICONTROL Crea Live Copy] . |
| 21 luglio 2020 | [Console Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | Esercitazione | Scoprite come visualizzare o gestire l&#39;ereditarietà in un sito o eseguire operazioni di rollout tramite la console Panoramica di Live Copy. |
| 21 luglio 2020 | [Progetti di traduzione](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Esercitazione | Scopri come creare, modificare e gestire un progetto di traduzione per la copia [!UICONTROL della]lingua. |
| 21 luglio 2020 | [Processi di traduzione](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Esercitazione | Scoprite come aggiungere un processo di traduzione a un progetto di traduzione esistente. |
| 21 luglio 2020 | [Aggiornamento della copia della lingua con avvii](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | Esercitazione | Scopri come aggiornare, rivedere e approvare le modifiche in una [!UICONTROL copia] della lingua con l’aiuto dei lanci. |
| 21 luglio 2020 | [Panoramica della gestione multisito](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | Esercitazione | Ottenete una panoramica su come creare un sito multilingue utilizzando [!UICONTROL Language Copy] in [!UICONTROL AEM Sites]. |
| 21 luglio 2020 | [Live Copy e Blueprint](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | Esercitazione | Comprendere la relazione tra una [!UICONTROL Live Copy] e la relativa [!UICONTROL Blueprint] in [!UICONTROL AEM Sites]. |
| 21 luglio 2020 | [Gestire l&#39;ereditarietà Live Copy su una pagina](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | Esercitazione | Scoprite come gestire l&#39;ereditarietà tra una [!UICONTROL Live Copy] e la relativa [!UICONTROL Blueprint] a livello di pagina. |
| 21 luglio 2020 | [Gestire l’ereditarietà Live Copy su un componente](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Esercitazione | Come gestire l&#39;ereditarietà tra una [!UICONTROL Live Copy] e la relativa [!UICONTROL Blueprint] a livello di componente. |
| 21 luglio 2020 | [Creare una copia della lingua](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Esercitazione | Descrizione. |
| 21 luglio 2020 | [Creare una copia della lingua](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | Esercitazione | Scoprite come creare una copia [!UICONTROL della] lingua per il sito AEM utilizzando la procedura guidata Crea copia lingua. |
| 21 luglio 2020 | [Creare un progetto di traduzione multilingue](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | Esercitazione | Scopri come creare, modificare e gestire un progetto di traduzione in più lingue per la copia [!UICONTROL della] lingua dalla console AEM progetto. |
| 21 luglio 2020 | [Creare un sito paese](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | Esercitazione | Scoprite come creare un sito per paese da Copie [!UICONTROL di] lingua esistenti utilizzando la procedura guidata [!UICONTROL Crea sito] . |
| 21 luglio 2020 | [Creare una pagina Copia lingua](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | Esercitazione | Scoprite come creare una pagina in una copia [!UICONTROL della]lingua esistente, quindi tradurre il contenuto in un’altra copia [!UICONTROL della]lingua. |
| 21 luglio 2020 | [Stato processo di traduzione](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | Esercitazione | Comprendere i diversi stati associati a un processo di traduzione o a un elemento del processo. |
| 21 luglio 2020 | [Introduzione alla gestione multisito](https://video.tv.adobe.com/v/36686?captions=ita) | Esercitazione | Introduzione al corso Guida introduttiva alla gestione multisito per gli utenti aziendali. |
| 21 luglio 2020 | [Creazione di frammenti di modulo adattivi](https://video.tv.adobe.com/v/37325?captions=ita) | Esercitazione | I moduli adattivi consentono di creare segmenti di modulo come un pannello o un gruppo di campi una sola volta e di riutilizzarli nei moduli adattivi. Questi segmenti riutilizzabili e standalone sono denominati frammenti di modulo adattivi. |
| 21 luglio 2020 | [Casella AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | Esercitazione | [!UICONTROL AEM Posta in arrivo] consolida le notifiche e le attività da vari componenti AEM, inclusi i flussi di lavoro Forms. |
| 21 luglio 2020 | [Eseguire il debug dell’avvio rapido locale dell’SDK di AEM tramite i registri](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Esercitazione | I registri fungono da front-line per il debug AEM applicazioni, ma dipendono dall’accesso adeguato nell’applicazione AEM distribuita. |
| 21 luglio 2020 | [Introduzione all&#39;editor SPA](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=ita) | Esercitazione | Introduzione al corso Guida introduttiva AEM SPA Editor per gli sviluppatori. |
| 2020 | [Autorizzazioni di base](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | Esercitazione | Gestire l’accesso degli utenti nelle cartelle delle risorse della baseline è un aspetto fondamentale della governance e garantisce che i processi possano essere supportati correttamente. |
| 21 luglio 2020 | [Avvio automatico dei flussi di lavoro](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | Esercitazione | I flussi di lavoro con avvio automatico estendono l&#39;elaborazione delle risorse in AEM come Cloud Service richiamando automaticamente il flusso di lavoro personalizzato al momento del caricamento o della rielaborazione. |
| 21 luglio 2020 | [Eseguire il debug dell’avvio rapido locale dell’SDK di AEM tramite i registri](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Esercitazione | I registri fungono da front-line per il debug AEM applicazioni, ma dipendono dall’accesso adeguato nell’applicazione AEM distribuita. |
| 21 luglio 2020 | [Creare un modello di modulo adattivo](https://video.tv.adobe.com/v/37324?captions=ita) | Esercitazione | Quando gli autori utilizzano il modello per creare un modulo adattivo, il nuovo modulo eredita la struttura e i componenti specificati nel modello. |
| 21 luglio 2020 | [Crea origine dati pool di connessioni Apache Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | Esercitazione | Il primo passaggio nella creazione del modello dati del modulo basato su RDBMS consiste nella configurazione di Apache Sling Connection Pooled DataSource. |
| 21 luglio 2020 | [Pre-compilazione di moduli adattivi tramite il modello dati del modulo](https://video.tv.adobe.com/v/36387?captions=ita) | Esercitazione | Introduzione alla precompilazione dei moduli tramite il modello dati del modulo. |
| 21 luglio 2020 | [Creazione del primo modulo adattivo](https://video.tv.adobe.com/v/37701?captions=ita) | Esercitazione | Questo video illustra come creare il primo modulo adattivo. |

### Informazioni sulla versione di Experience Manager

Nelle pagine seguenti trovi tutte le note sulla versione di Experience Manager:

* [Informazioni sulla versione di AEM as a Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/release-notes/home.html)
* [Note sulla versione di AEM Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://docs.adobe.com/content/help/it-IT/aem-forms-automated-conversion-service/using/release-notes.html)
* [Note sulla versione di AEM 6.5 Service Pack](https://docs.adobe.com/content/help/it-IT/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Note sulla versione di AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/it-IT/experience-manager-64/release-notes/cfp-release-notes.html)
* [Note sulla versione di AEM Assets Dynamic Media](https://docs.adobe.com/content/help/it-IT/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Note sulla versione di AEM Brand Portal](https://docs.adobe.com/content/help/it-IT/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Note sulla versione dell’app desktop AEM](https://docs.adobe.com/content/help/it-IT/experience-manager-desktop-app/using/release-notes.html)
* [Note sulla versione di AEM Dispatcher](https://docs.adobe.com/content/help/it-IT/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Note sulla versione di Adobe Primetime](https://docs.adobe.com/content/help/it-IT/primetime/release-notes/home.translate.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

### Risorse aggiuntive per AEM

* [Guide utente di AEM as a Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/landing/home.html)
* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Nuove versioni del prodotto

Informazioni sulla versione per Campaign Classic, Campaign Standard e Pannello di controllo.

#### Campaign Classic

* Release 20.2.1 - [Leggi tutto](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Nuovi corsi e tutorial su Campaign

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| ----------- | ----------- | ---------- | ---------- |  
| 10 luglio 2020 | [Pannello di controllo Campaign - Gestione chiavi GPG - Decrittografare i dati](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | Scopri come creare una chiave pubblica da importare e installare in un’istanza Campaign per la decrittografia dei dati in entrata. |
| 10 luglio 2020 | [Pannello di controllo Campaign - Gestione chiavi GPG - Utilizzo di una chiave GPG per cifrare i dati](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | Scopri come esportare i dati utilizzando una chiave GPG installata sul Pannello di controllo Campaign. |
| 10 luglio 2020 | [Pannello di controllo Campaign - Generazione e installazione di chiavi GPG per la crittografia dei dati](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | Scoprite come generare una coppia di chiavi GPG pubblica/privata e installare la chiave pubblica nel Pannello di controllo Campaign per essere in grado di crittografare i dati prima di inviarli dall&#39;istanza. |
| 21 luglio 2020 | [Gestione di campagne di marketing](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | Scopri i concetti chiave di  Adobe Campaign che aiutano a pianificare, eseguire e misurare efficacemente le campagne di marketing su più canali. |
| 22 luglio 2020 | [Creazione di un piano di marketing, programmi e campagne](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | Scopri come creare un piano di marketing, un programma e una campagna, impostare le proprietà per una campagna e capire come utilizzare la pianificazione. Il video vi guida attraverso un esercizio che potete seguire. |
| 23 luglio 2020 | [Creazione e gestione di profili](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | Comprendere il concetto di profili in Adobe Campaign Classic. Scopri come accedere ai dati del profilo, ordinare e filtrare i profili e come creare e gestire manualmente i profili. |
| 28 luglio 2020 | [Personalizzazione di e-mail mediante contenuto condizionale](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | Scoprite come aggiungere contenuti condizionali a una distribuzione, ad esempio una newsletter multilingue. |
| 28 luglio 2020 | [Personalizzazione di e-mail tramite campi di personalizzazione](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | Scoprite come aggiungere un campo di personalizzazione alla riga dell&#39;oggetto e al contenuto di una distribuzione tramite e-mail. |
| 28 luglio 2020 | [Targeting dei profili in un flusso di lavoro](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | Comprendi l’utilizzo dei flussi di lavoro delle campagne e come creare un flusso di lavoro e profili di destinazione in un flusso di lavoro utilizzando le condizioni di filtro. |
| 31 luglio 2020 | [Generazione di un rapporto di analisi descrittivo](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | Scopri come generare un rapporto di analisi descrittivo. |
| 9 luglio 2020 | [Pannello di controllo Campaign - Gestione chiavi GPG - Utilizzo di una chiave GPG per cifrare i dati](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | Scopri come esportare i dati utilizzando una chiave GPG installata sul Pannello di controllo Campaign. |
| 9 luglio 2020 | [Pannello di controllo Campaign - Gestione chiavi GPG - Decrittografare i dati](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | Scopri come creare una chiave pubblica da importare e installare in un’istanza Campaign per la decrittografia dei dati in entrata. |
| 9 luglio 2020 | [Pannello di controllo Campaign - Gestione chiavi GPG - Generazione e installazione di chiavi GPG per la crittografia dei dati](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | Scopri come generare e installare una coppia di chiavi pubblica/privata in una specifica istanza di Campaign per la crittografia dei dati in uscita. |

### Risorse di supporto

* Adobe Campaign Standard: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/campaign-standard-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/overview.html) - [Piano delle versioni future](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-planning.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/campaign-classic-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-classic-learn/tutorials/overview.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/documentation-updates.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html) - Video introduttivi per [Campaign Standard](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/it-IT/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Note sulla versione di Adobe Advertising Cloud.

### Nuove funzioni di [!UICONTROL Advertising Cloud Search] {#adcloud-search}

**Release 8** agosto

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Portfolio] | I limiti di posizione a livello di Portfolio non sono più disponibili nelle impostazioni del portfolio. Eventuali limiti di posizione creati in precedenza venivano rimossi. |
| [!UICONTROL Vincoli] | I vincoli e le condizioni di vincolo basate sulla posizione non sono più supportati:<br/><ul><li>I vincoli Pos minimi e Pos massimi non sono più disponibili e sono stati rimossi da tutti i vincoli Bid &amp; Position creati in precedenza e dai vincoli di Condivisione impression.</li><li>I vincoli Offerta e Posizione esistenti che includevano vincoli di posizione ma non vincoli di offerta sono stati messi in pausa. Sono ancora disponibili nell’interfaccia utente e nei rapporti.</li><li>I vincoli Offerta e Posizione sono stati rinominati Limiti Offerta.</li><li>Sono state rimosse tutte le condizioni basate sulla posizione (utilizzando le metriche Posizione media, Posizione media ponderata o Ultimi punti noti) in qualsiasi tipo di vincolo.</li></ul><br/>**Nota:**I dati di posizione continueranno a essere compilati purché siano disponibili dai motori di ricerca. Microsoft Ads andrà in pensione a settembre 2020. |  |
| [!UICONTROL Campagne] | (Campagne Google Ads) Advertising Cloud Search ora supporta i clienti di annunci pubblicitari in RSA (responsive Search ads). Precedentemente, erano supportati in tutti i tipi di annunci eccetto RSA. |

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per lead management e marketer B2B che intendono trasformare le esperienze dei clienti impegnandosi in ogni fase dei percorsi d’acquisto complessi.

### Aggiornamenti principali di Marketo Engage

Consulta le [note sulla versione](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720) di [!DNL Marketo] per informazioni aggiornate.

### Funzionalità in arrivo

Nel corso del trimestre verranno presentate le seguenti funzionalità:

| Funzione | Descrizione |
|------|---------|
| [!DNL Bizible] | <ul><li>Nuova segmentazione basata sugli account</li><li>Possibilità di salvare filtri specifici per dashboard</li><li>Esportazione dashboard Bizible in formato PDF</li></ul> |
| Sales Connect | Aggiornamenti/miglioramenti relativi a finestre di composizione e centri di comando |

### Annunci

**Success Center di Marketo Engage:** lancio a febbraio 2020. Success Center è un centro di assistenza interno al prodotto che consente di effettuare ricerche nei documenti sui prodotti e nella community, avviare guide informative, accedere ai contenuti di adozione e altro ancora. Nota: questa funzionalità verrà lanciata come versione beta in Australia e Nuova Zelanda e verrà implementata nel Nord America in un secondo momento nel corso del trimestre.

### Funzionalità deprecate

* **Parametro “_method” di Asset API:** dopo settembre 2020, gli endpoint di Asset API non accetteranno più `_method` per trasmettere i parametri di query nel corpo di un POST per aggirare le limitazioni relative alla lunghezza degli URI.
* **Supporto in Internet Explorer:** a partire dalla versione di luglio del 31 luglio 2020, Internet Explorer non supporterà più l’interfaccia utente di Marketo Engage.

Per leggere le note precedenti e complessive, consulta le [note sulla versione Marketo](https://docs.marketo.com/x/CgA6Ag).
