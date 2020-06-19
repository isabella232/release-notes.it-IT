---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di Adobe Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: a9dfcbc1fdd459212ffb898e2a1c508d9aaf84f7
workflow-type: tm+mt
source-wordcount: '6687'
ht-degree: 35%

---


# Note sulla versione di Adobe Experience Cloud - Giugno 2020

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Vengono inoltre evidenziate nuove documentazione, corsi di formazione ed esercitazioni video per consentirvi di sfruttare al meglio  Experience Cloud.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni.

**Data di rilascio: 18 giugno 2020**

Le date di rilascio del prodotto possono variare. Controllate spesso la disponibilità di aggiornamenti.

Ultimo aggiornamento: **18 giugno 2020**

* [Stato del sistema di Adobe](#status)
* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) (e [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (link alla guida di Primetime)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/#home) per trovare documentazione tecnica e sui prodotti, corsi specifici per Adobe, esercitazioni video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Rilasciato: **21 maggio 2020**

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Per velocizzare l’iscrizione, il processo di autoabbonamento ora consiglia una selezione di prodotti e offerte in base alle adesioni dei prodotti. Questo dovrebbe ridurre il numero di e-mail che ricevi e far sì che le notifiche nell’inbox siano più pertinenti. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Miglioramento dell’esperienza utente di abbonamento e notifica | <ul><li>Le posizioni regionali di [!DNL Marketo Engage] ora vengono filtrate in base all’elenco delle offerte di prodotti selezionate.</li><li>Le notifiche e-mail di [!DNL Marketo Engage] sono pertinenti all’area geografica, alla posizione e alle preferenze di ambiente dell’utente.</li></ul> |
| Conferma dell’abbonamento agli eventi | <ul><li>Ora puoi ricevere una conferma e-mail quando effettui un abbonamento agli aggiornamenti per un singolo evento in corso.</li></ul> |
| Miglioramenti dell’usabilità della navigazione globale | <ul><li>Esperienza utente coerente con `Adobe.com` nel menu di navigazione di livello principale.</li></ul> |

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Aggiornamenti generali &#39;interfaccia Experience Cloud.

**Dominio di prodotto unificato**

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificano il flusso di lavoro attuale.

Gli aggiornamenti includono:

* Nuovi URL dell’applicazione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** Sebbene &#39;interfaccia Experience Cloud supporti questi browser, le singole applicazioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.

Le app seguenti utilizzano il nuovo dominio experience.adobe.com:

| App o servizio | Dominio |
| -----------| ---------- |
| Homepage di Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Journey Management | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Pannello di controllo di Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribuzione software | `experience.adobe.com/downloads` |
| Strumento admin (versione beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board &amp; Collections]** (Bacheca e Raccolte), un filtro legacy nel selettore [!UICONTROL Experience Cloud Assets], è in fase di rimozione.

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Data di rilascio: **10 giugno 2020**

[!DNL Adobe Experience Platform] include le seguenti nuove funzionalità:

* **Area di lavoro Data Science:** Ora [!DNL JupyterLab Launcher] è incluso un [!DNL Python] blocco appunti per l&#39;apprendimento automatico in tempo reale (Alpha).
* **Segmentazione:** È stato aggiunto un campo data anniversario per le funzioni data, che consente agli utenti di valutare le date senza l&#39;anno.
* **Origini:** Nuovi connettori sorgente per [!DNL Apache HDFS] e [!DNL Couchbase].

Per ulteriori informazioni su queste funzioni, consultate [note](https://docs.adobe.com/content/help/it-IT/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)sulla versione di Experience Platform.

### Informazioni aggiuntive sulla versione di Experience Platform

* [Note sulla versione di Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html) (Tutti i prodotti Adobe)

### Nuovi corsi  Experience Platform ed esercitazioni {#tutorials-plat}

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |
| [Introduzione al Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Corso | Scopri come  Adobe Experience Platform ti aiuta a fornire l&#39;esperienza giusta trasformando i tuoi dati in solidi profili cliente in tempo reale e informazioni basate sull&#39;intelligenza artificiale che puoi attivare in ogni canale. Questo corso introduttivo offre una panoramica  funzionalità di Experience Platform, casi di utilizzo, relazione con Adobe Experience Cloud, architettura di base, interfaccia e ruoli di progetto. |
| [Introduzione a Web SDK e Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Esercitazione video | Panoramica di  Adobe Experience Platform SDK e Edge Network.  Experience Platform Web SDK è una libreria JavaScript lato client che consente ai clienti di utilizzare una libreria JavaScript, un tipo di beacon, un flusso di dati, una e una destinazione lato server per inviare dati a tutte le applicazioni Adobe e a destinazioni terze parti. |
| [Demo di Web SDK e Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Esercitazione video | Guarda l’SDK Web  Adobe Experience Platform e Edge Network in azione, con una singola chiamata ad Adobe che invia dati a  Experience Platform,  Analytics,  Audience Manager e Target. |
| [Demo di Platform sui dati dei clienti in tempo reale](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Esercitazione video | Scopri come la tecnologia CDP in tempo reale viene utilizzata per raccogliere dati da più origini. Puoi unire tali dati in un unico profilo cliente in tempo reale e attivarli per creare esperienze cliente personalizzate. |

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

### Ultima versione

Per gli ultimi aggiornamenti sulla versione, consulta Note sulla versione di [Journey Orchestration](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html)

### Nuovi corsi ed esercitazioni Journey Orchestration {#jo-tutorials}

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |
| [Guida introduttiva ad Journey Orchestration per gli amministratori](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Corso | Scoprite come configurare e utilizzare Journey Orchestration. Questo corso descrive i concetti chiave e le fasi di configurazione necessarie per consentire l&#39;orchestrazione di un percorso. Scopri come creare, pubblicare e come segnalare e analizzare i viaggi orchestrati. |
| [Guida introduttiva ad Journey Orchestration per gli utenti aziendali](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Corso | Scoprite come configurare e utilizzare Journey Orchestration. Questo corso descrive i concetti chiave. Scoprirai come creare, pubblicare, generare rapporti e analizzare i tuoi viaggi organizzati. |

### Risorse aggiuntive per Journey Orchestration

[Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni in Customer Journey Analytics](#cust-journey)
* [Nuove funzioni di Media Analytics](#media-aa)
* [Problemi risolti in Adobe  Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [Nuovi corsi ed esercitazioni su Adobe  Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-------|
| IQ attribuzione: Attribuzione algoritmica | 18 giugno 2020 | Il modello [!UICONTROL Attribuzione] algoritmica in  Analysis Workspace utilizza tecniche statistiche per determinare in modo dinamico l’allocazione ottimale del credito per la metrica selezionata. Disponibile per i clienti Adobe  Analytics Ultimate. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| IQ attribuzione: Finestre di lookback personalizzate | 18 giugno 2020 | Ora puoi configurare qualsiasi modello di attribuzione in [!UICONTROL Attribution IQ] per includere punti di contatto fino a 90 giorni prima del periodo di tempo di reporting. In genere, ciò aumenta la precisione di attribuzione per gli eventi che si verificano all&#39;inizio del periodo di reporting, tenendo conto delle interazioni che si sono verificate nei mesi precedenti. Disponibile per i clienti Adobe  Analytics Foundation, Select, Prime, Premium, Premium Attribution, Premium Complete e Ultimate. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Ruoli del progetto per progetti Workspace condivisi | 18 giugno 2020 | Quando condividi un progetto Workspace, ora puoi posizionare i destinatari in uno dei tre ruoli di progetto, a seconda dell’esperienza di progetto che desideri abbiano: Modifica, Duplica e Visualizza. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Visualizza progetti Workspace | 18 giugno 2020 | I progetti Workspace possono essere condivisi con gli utenti solo come &quot;Può visualizzare&quot;. Quando un destinatario di visualizzazione apre il progetto condiviso, riceve un&#39;esperienza di progetto più restrittiva, senza barra a sinistra e interazioni limitate. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Possibilità di co-modificare i progetti Workspace | 18 giugno 2020 | I destinatari aggiunti al ruolo &quot;Can edit&quot; possono salvare su un progetto condiviso con loro. Questo vale sia per gli amministratori che per gli utenti non amministratori. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Pannello vuoto aggiornato in Workspace | 18 giugno 2020 | Il pannello vuoto in Workspace ora include pannelli e visualizzazioni, per consentirvi di scegliere in modo più semplice il flusso di lavoro di analisi più adatto alle vostre esigenze. |
| Domini di prime parti disponibili in Cina RDC | 18 giugno 2020 | Consente ai clienti con un `.cn` dominio di richiedere un dominio di prime parti da utilizzare all&#39;interno della Cina continentale. (Documentazione disponibile con l&#39;acquisto di SKU &quot;China Performance Optimization&quot;.) |
| Pannello Quick Insights (Approfondimenti rapidi) in Workspace (Area di lavoro) | 25 giugno 2020 | Quick Insights fornisce indicazioni ai non analisti e ai nuovi utenti di Analysis Workspace per scoprire come rispondere alle domande aziendali in modo rapido e semplice. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Pannello Analytics for Target in Workspace (Area di lavoro) | 25 giugno 2020 | Il pannello  Analytics per Target (A4T) consente di analizzare le attività e le esperienze di  Adobe Target, con estrema sicurezza, in  Analysis Workspace. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL La pagina Workspace] | Giugno 18,2020 | La pagina [!UICONTROL Informazioni su Workspace] contiene informazioni sull’ambiente  Analysis Workspace, sugli amministratori di Adobe  Analytics (se necessario) e su come fornire feedback all’interno del prodotto. È disponibile in **[!UICONTROL Workspace]** > **[!UICONTROL Aiuto]** > **[!UICONTROL Informazioni su Workspace]**. |

### Nuove funzioni in Customer Journey Analytics {#cust-journey}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-----|
| Supporto per gli array di oggetti | 18 giugno 2020 | I clienti CJA possono ora creare rapporti sulle dimensioni e le metriche visualizzate negli array di oggetti all&#39;interno dei loro schemi di set di dati  Adobe Experience Platform. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| IQ attribuzione: [!UICONTROL Attribuzione algoritmica] | 18 giugno 2020 | Il modello [!UICONTROL Attribuzione] algoritmica in [!UICONTROL Analysis Workspace] utilizza tecniche statistiche per determinare in modo dinamico l’allocazione ottimale del credito per la metrica selezionata. Disponibile per i clienti Adobe  Analytics Ultimate. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| IQ attribuzione: Finestre di lookback personalizzate | 18 giugno 2020 | Ora puoi configurare qualsiasi modello di attribuzione in [!UICONTROL Attribution IQ] per includere punti di contatto con un massimo di 90 giorni prima del periodo di tempo di reporting. In genere, ciò aumenta la precisione di attribuzione per gli eventi che si verificano all&#39;inizio del periodo di reporting, tenendo conto delle interazioni che si sono verificate nei mesi precedenti. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html) |
| Supporto per il rilevamento delle [!UICONTROL anomalie] | 18 giugno 2020 | [!UICONTROL Il rilevamento] delle anomalie fornisce un metodo statistico per determinare in che modo una determinata metrica è cambiata rispetto ai dati precedenti. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Ruoli di progetto per progetti condivisi [!UICONTROL Workspace] | 18 giugno 2020 | Quando condividi un progetto [!UICONTROL Workspace] , ora puoi posizionare i destinatari in uno dei tre ruoli di progetto, a seconda dell’esperienza di progetto che desideri abbiano: Modifica, Duplica e Visualizza. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Visualizza progetti [!UICONTROL Workspace] | 18 giugno 2020 | [!UICONTROL I progetti Workspace] possono essere condivisi con gli utenti come _[!UICONTROL Solo visualizzabili]_. Quando un destinatario di visualizzazione apre il progetto condiviso, riceve un&#39;esperienza di progetto più restrittiva senza barra a sinistra e interazioni limitate.[Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| Possibilità di co-modificare i progetti [!UICONTROL Workspace] | 18 giugno 2020 | I destinatari aggiunti al ruolo _[!UICONTROL Can Edit]_(Può modificare) possono salvare in un progetto condiviso con loro.[Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Pannello Quick Insights (Approfondimenti rapidi) in [!UICONTROL Workspace] (Area di lavoro) | 25 giugno 2020 | Quick Insights fornisce indicazioni ai non analisti e ai nuovi utenti di [!UICONTROL Analysis Workspace] per scoprire come rispondere alle domande aziendali in modo rapido e semplice. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL La pagina Workspace] | Giugno 18,2020 | La pagina [!UICONTROL Informazioni su Workspace] contiene informazioni sull’ambiente  Analysis Workspace, sugli amministratori di Adobe  Analytics (se necessario) e su come fornire feedback all’interno del prodotto. È disponibile in **[!UICONTROL Workspace]** > **[!UICONTROL Aiuto]** > **[!UICONTROL Informazioni su Workspace]**. |

### Nuove funzioni di [!UICONTROL Media Analytics] {#media-aa}

Data di aggiornamento: **18 giugno 2020**

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- | ---------- |
| [Dispositivi e piattaforme supportati](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 giugno 2020 | L’estensione Media Launch con AEP SDK ora supporta i seguenti dispositivi OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Dispositivi e piattaforme supportati](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 giugno 2020 | L’estensione Media Launch con AEP SDK ora supporta i seguenti dispositivi OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Tracciamento dello stato del lettore](https://docs.adobe.com/content/help/it-IT/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 maggio 2020 | [!UICONTROL I clienti di Analytics]  Media possono acquisire l&#39;interazione del visualizzatore durante la riproduzione utilizzando un set standard di variabili di soluzioni per la visualizzazione a schermo intero, sottotitoli codificati, disattivazione dell&#39;audio, picture-in-picture e messa a fuoco. È inoltre possibile creare degli stati del lettore personalizzati. Le variabili di tracciamento dello stato del lettore sono ora disponibili per il reporting in [!UICONTROL Analysis Workspace]. Questa funzione richiede uno dei seguenti elementi: <ul><li>SDK di [!DNL JavaScript] Media 3.0 o versione successiva</li><li>Per l’utilizzo con l’SDK di [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Estensione Media Analytics] (per il web): [!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 o versione successiva</li><li>[!UICONTROL Estensione Media Analytics] (per dispositivi mobile): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 o versione successiva</li><li>[!UICONTROL Media Collection]</li></ul> |

### Problemi risolti in Adobe  Analytics {#aa-fixes}

* È stato risolto un problema che causava la mancata corrispondenza tra segmenti con ricerche multibyte per determinate suite di rapporti. Ora verranno confrontati con le stringhe corrette. (AN-220043)
* È stato risolto un problema con il Filtro  elemento in [!UICONTROL Reporting e  Analytics] che non funzionava. (AN-206132)
* È stato corretto un tempo di risposta lento nell&#39;interfaccia Progetti  pianificati. (AN-214837)
* È stato risolto un problema che causava un errore  Analytics Reporting API 2.0 con un intervallo di date. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Ciò si verifica quando un hit senza valore per la dimensione (ad es. Nome programma) viene seguito nello stesso secondo. (AN-211074)
* È stato corretto un problema a causa del quale gli utenti non potevano accedere ai progetti [!UICONTROL Workspace] condivisi con loro. (AN-217561)
* È stato corretto un problema a causa del quale le chiavi non venivano classificate da Generatore [!UICONTROL regole di]classificazione. (AN-221538)
* È stato risolto un problema con l&#39;utilizzo [!UICONTROL delle chiamate] server che non segnalava i dati di utilizzo. (AN-210452)
* Sono stati risolti dei problemi relativi ai segmenti Adobe  Analytics pubblicati per i quali i dati mancanti  Audience Manager erano mancanti. (AN-220208, AN-220659)
* È stato risolto un problema che causava la visualizzazione di dati nei rapporti ma i registri Feed  dati dicevano &quot;Nessun dato Data warehouse&quot;. (AN-220784, AN-220858)
* Sono stati risolti dei problemi che impedivano il lancio di [!UICONTROL Ad hoc analysis] dal `experiencecloud.com` dominio. (AN-219680, AN-221629)
* Sono stati risolti i problemi relativi all&#39;utilizzo del tasto di scelta rapida &quot;Ctrl (o Comando) + C&quot;. (AN-221101, AN-221537)
* È stato risolto un problema con la pagina di abilitazione dei Activity Map  . (AN-222029, AN-221242)
* È stato risolto un problema che impediva di aggiungere un punto di contatto nel mezzo di una visualizzazione [!UICONTROL Abbandono] . (AN-221648)

#### Ulteriori correzioni di Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Migrazione a un dominio di prodotto unificato | Data di validità: 28 maggio 2020 | La migrazione a un dominio di prodotto unificato per Adobe Analytics, iniziata a gennaio 2020, è stata completata il 28 maggio 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Al termine della migrazione dell&#39;architettura completa (presto), riceverai una notifica tramite le note sulla versione e questo passaggio di elenco consentito non sarà più necessario. [Di seguito](https://helpx.adobe.com/it/analytics/kb/adobe-ip-addresses.html) è riportato un elenco completo degli indirizzi IP e dei domini consigliati da includere nell&#39;elenco.<br>Se l’organizzazione blocca i cookie di terze parti, contatta l’assistenza clienti per recuperare l’accesso ad Adobe Analytics. |
| Nuova pagina di destinazione predefinita di Adobe Analytics | Data di validità: 18 giugno 2020 | Il 18 giugno 2020 la pagina di destinazione predefinita per Adobe Analytics passerà da [!UICONTROL Reports] a [!UICONTROL Workspace] (Area di lavoro). Questa modifica verrà applicata agli utenti che non hanno precedentemente impostato una pagina di destinazione personalizzata. |
| Elenco delle tecnologie di terze parti consentite | 12 marzo 2020 (data effettiva) | Adobe Analytics ha iniziato a sfruttare tecnologie di terze parti per la gestione del rollout delle funzioni e per il supporto integrato nel prodotto. I seguenti URL devono essere aggiunti a qualsiasi firewall di rete necessario per consentire agli elenchi di garantire l&#39;accesso completo alle funzioni:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 maggio 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. È necessario aggiungere i seguenti URL a eventuali mailing list del firewall di rete:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] (Area di lavoro) | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Poiché ora in [!UICONTROL Analysis Workspace] è possibile attivare e disattivare i valori _None_, viene applicato il valore _None_ dopo l’entrata o l’uscita, mentre per le eVar veniva applicato prima dell’entrata o dell’uscita. Ad esempio, si supponga che il primo risultato di una visita non presenti alcun valore per le eVar, ma il secondo sì. In [!UICONTROL Reports &amp; Analytics] il primo risultato verrà visualizzato come _non specificato_ per l’Entrata, ma in [!UICONTROL Analysis Workspace] verrà visualizzato come valore per il secondo risultato. |
| Fine del ciclo vita di **[!UICONTROL Archivio dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL Visualizza archivio]** nella sezione **[!UICONTROL Gestione dashboard]** in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Nuovi corsi  Analytics ed esercitazioni {#tutorials-analytics}

Nuovi corsi, video di esercitazione e articoli in  Analytics e Customer Journey Analytics.

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |
| [Guida introduttiva ad Customer Journey Analytics per gli utenti](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Corso | In questo corso verrà illustrato come utilizzare Customer Journey Analytics (CJA) per analizzare i dati provenienti da diverse origini dati. Verranno illustrate le differenze tra Adobe  Analytics e Customer Journey Analytics e la modalità di gestione dei dati in CJA. Dopo aver seguito questo corso, devi essere in grado di creare e personalizzare visualizzazioni tra canali per migliorare la comprensione dei clienti. |
| [Guida introduttiva ad Customer Journey Analytics per gli amministratori](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Corso | Scoprite come configurare e utilizzare [!UICONTROL Journey Orchestration]. Questo corso illustra i concetti chiave e i passaggi di configurazione necessari per consentire l&#39;orchestrazione di un viaggio. Scoprirai come creare, pubblicare e come segnalare e analizzare i tuoi viaggi organizzati. |
| [Guida introduttiva ad Customer Journey Analytics per i tecnici dei dati](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Corso | In questo corso imparerai come i dati vengono inviati ad Customer Journey Analytics e come influenzano i rapporti per l&#39;analista. Questo corso si basa sulla conoscenza generale del Adobe Experience Platform . |
| [Guida introduttiva ad Customer Journey Analytics per gli amministratori](https://video.tv.adobe.com/v/34349?captions=ita) | Esercitazione video | Video introduttivo per Customer Journey Analytics per gli amministratori. |
| [Implementazione guidata  Analytics](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Corso | In questo corso imparerai come iniziare ad implementare Adobe  Analytics, capire  concetti di Analytics, creare un piano e implementare Adobe  Analytics utilizzando l&#39;Experience Platform Launch. |
| [Nozioni di base di Adobe  Analytics per i leader](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Corso | In questo corso, scopri le  basi di Analytics e come  Analysis Workspace può cambiare la tua attività. Scopri come scoprire informazioni approfondite con Adobe Sensei, ascoltare le testimonianze dei clienti e vedere le testimonianze degli esperti del settore al Summit 2019. |
| [Guida introduttiva  Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Corso | Scoprite come utilizzare  Analysis Workspace. Crea il primo progetto, scopri come definire intervalli di date, applicare segmenti, condividere e collaborare ai progetti. |
| [Adobe  Analytics dashboards Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Esercitazione video | In questo video, scopri come creare e condividere [!UICONTROL scorecard] in [!UICONTROL Analysis Workspace] da visualizzare sulle dashboard Adobe  Analytics (app mobile). |
| [Adobe  Analytics Dashboard per l&#39;esperienza in-app](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Esercitazione video | In questo video, scopri come utilizzare le dashboard Adobe  Analytics (app mobile) per accedere e visualizzare le [!UICONTROL scorecard] create da o condivise con te. |

#### Risorse dell’Aiuto di Analytics

* [Esercitazioni di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentazione dei prodotti Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html)

## ![Icona](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuove funzioni, correzioni, documentazione e tutorial in Audience Manager.

Updated **June 10, 2020**

### Aggiornamenti dell’interfaccia utente

Audience Manager sta aggiornando il dominio e la barra di intestazione per migliorare la tua esperienza e unificarla a quella offerta da altre applicazioni Experience Cloud.

* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* È stata migliorata la Guida utente, inclusi gli articoli contenuti e i video pertinenti al contesto nel menu Guida.
* Possibilità di fornire feedback su  Experience Platform e sui biglietti di supporto per i file.
* Un nuovo pattern URL più semplice. Aggiorna i segnalibri nel nuovo URL: `experience.adobe.com/audience-manager`.

Questi aggiornamenti sono disponibili solo per gli utenti che accedono utilizzando l’Adobe ID. Per passare a un accesso Adobe ID, consulta [Gestione di utenti e prodotti Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nuove funzioni e correzioni in Adobe Audience Manager

| Funzione | Descrizione |
| -----------| ---------- |  
| [Plug-in Audience Manager per IAB TCF v2.0 ](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | Continuando a prestare attenzione alla privacy by Design da parte di Adobe, il plug-in  Audience Manager per IAB TCF verrà aggiornato alla versione 2.0 di IAB Transparency &amp; Consent Framework (TCF), a partire dal 10 giugno 2020. I clienti che hanno implementato il plug-in Audience Manager  per IAB TCF devono effettuare l&#39;aggiornamento alla versione 2.0 entro il 15 agosto 2020, per poter continuare a utilizzare la funzione. Dopo il 15 agosto 2020, la versione 1.1 diventerà obsoleta e non più supportata. |

**Correzioni**

* Aggiornati i Termini e le Condizioni [!UICONTROL di Audience Marketplace] per riflettere i requisiti legali in aree geografiche specifiche. (AAM-54518)
* È stato risolto un problema che causava un errore 404 durante l&#39;accesso alla pagina [!UICONTROL Caratteristiche] dai segnalibri. (AAM-54768)
* È stato risolto un problema che causava il timeout dell&#39;API di aggiornamento di destinazione durante il recupero dei modelli algoritmici. (AAM-54342)
* Gli utenti ora possono vedere un indicatore di precisione della classificazione del modello per [!UICONTROL Smart Personas]. (AAM-54847)
* È stato risolto un problema che causava la rimozione dell&#39;espressione anziché salvarla se si premeva Invio dopo l&#39;aggiunta di un&#39;espressione caratteristica. (AAM-54210)
* È stato risolto un problema che causava il fallimento delle chiamate al metodo GET dell&#39;API [!UICONTROL Traits] per gli utenti che non disponevano dell&#39;autorizzazione VIEW_MODELS. (AAM-53104)
* È stato risolto un problema a causa del quale gli utenti non potevano eliminare i modelli [!UICONTROL algoritmici] contenenti caratteristiche delle [!UICONTROL cartelle]. (AAM-50192)
* Le espressioni con tratto lungo ora si estendono su più righe. (AAM-54972)
* È stato risolto un problema per il quale gli utenti con autorizzazioni di sola lettura potevano vedere il pulsante [!UICONTROL Crea nuovo] nelle pagine dei modelli algoritmici. (AAM-54889)
* È stato risolto un problema che causava il caricamento dell’indicatore di caricamento dei report [!UICONTROL Generale] e [!UICONTROL Tendenza] dopo il completamento del download CSV. (AAM-54571)
* È stato risolto un problema che impediva agli utenti di aggiungere caratteristiche in blocco ai segmenti nel Generatore segmenti. (AAM-55033)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Nuovi corsi  Audience Manager ed esercitazioni {#tutorials-aam}

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |  
| [Introduzione a  Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Corso | Questo corso illustra le nozioni di base di  Audience Manager e i problemi che è possibile risolvere. Informazioni sui casi d’uso comuni e sui principali  termini e concetti di Audience Manager. |
| [Introduzione all&#39;identità in  Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Esercitazione video | Scopri come  Adobe Audience Manager gestisce l&#39;identità, inclusi profili interni e unione di profili, nonché la sincronizzazione degli ID con i partner. |
| [Informazioni e configurazione della destinazione basata su LinkedIn](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Corso | Questo video illustra i concetti e i passaggi necessari per creare una destinazione basata sulle persone su LinkedIn. Si basa sui video aggiuntivi e la documentazione relativa alle destinazioni basate sulle persone. |
| [Creazione di caratteristiche basate su regole](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Esercitazione video | Scopri come utilizzare [!UICONTROL Trait Builder] nell&#39;interfaccia Audience Manager  per creare una caratteristica basata su regole, consentendo di acquisire l&#39;attività in tempo reale  profili Audience Manager. |
| [Abilitazione del plug-in  Audience Manager per IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Esercitazione video | Scoprite come abilitare il plug-in Audience Manager  per IAB TCF. Abilitare questo plug-in è semplice se si utilizza  lancio Adobe Experience Platform. |
| [Demo del plug-in Audience Manager  per IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Esercitazione video | In questo video, scopri in che modo i cookie e i beacon di  Experience Cloud ID Service e delle soluzioni sono influenzati dalle selezioni di scelta dell’utente IAB. |

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0 rilasciato il 04 giugno 2020) è un aggiornamento importante che include nuove funzioni, miglioramenti fondamentali richiesti dai clienti e prestazioni, stabilità e miglioramenti in termini di sicurezza, rilasciati a partire dalla disponibilità generale di AEM 6.5 nell’aprile 2019.

   * [Note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Rilascio delle versioni finali di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 rilasciato il 4 giugno 2020) è un aggiornamento importante che include diverse correzioni interne e per i clienti a partire dalla data di disponibilità generale di AEM 6.4, Service Pack 8 (6.4.8.0) nel marzo 2020.

   * [Note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Rilascio delle versioni finali di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

### Aiuto e documentazione

* **AEM as a Cloud Service**

   Novità su AEM come Cloud Service

   Le evidenziazioni includono:

   * AEM Sites Commerce Integration Framework.
   * Tag avanzati avanzati e nuove funzionalità nell’esperienza di formazione guidata dell’interfaccia utente.
   * Supporto di Adobe Asset Link per Adobe Xd.
   * Supporto AEM Assets Dynamic Media 3D.
   * I nuovi miglioramenti Self Service riducono le dipendenze da Adobe per le operazioni sandbox.
      * Il supporto sandbox self-service migliorato in Cloud Manager consente agli utenti autorizzati di eliminare tutti gli ambienti all&#39;interno di una sandbox e ricevere crediti.
      * Gli ambienti sandbox con sospensione automatica &quot;ibernano&quot; automaticamente le sandbox dopo un periodo di inattività. I clienti possono attivare attivamente la disattivazione.
   * Strumenti di transizione per supportare l&#39;accelerazione cloud
   Con l&#39;obiettivo di ridurre il tempo e i costi per la transizione dalla sede ad Cloud Service, questo mese sono stati lanciati due strumenti di transizione. Questi strumenti sono progettati per automatizzare alcune delle attività chiave durante il processo di transizione e quindi, riducendo lo sforzo complessivo. .

   1. [Utilizzando Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) (disponibile su SD) è possibile semplificare l&#39;attività di trasferimento dei contenuti e renderla scalabile. Grazie a un’interfaccia utente semplice, lo strumento è self-service per clienti e partner esistenti (on-prem/AMS) che passano ad AEM come Cloud Service.
   1. [Strumento AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source) per automatizzare la conversione delle configurazioni AMS Dispatcher in configurazioni Cloud Service Dispatcher.
   [Note sulla versione di AEM come Cloud Service 2020.6.0](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Strumenti di transizione:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Componenti di base**

   Core Components 2.9.0 introduce l&#39;integrazione con [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) e un nuovo componente Progress Bar ed è ora disponibile insieme alla documentazione [di](https://docs.adobe.com/content/help/it-IT/experience-manager-core-components/using/introduction.html) authoring e ai dettagli per [gli sviluppatori e al download del progetto disponibile su GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Passaggio ad AEM as a Cloud Service**

   [Il passaggio ad AEM come Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/moving/home.html) descrive il percorso di transizione consigliato per un cliente AEM già esistente che si sposta su Cloud Service. L&#39;obiettivo di questa documentazione è quello di fornire ai clienti informazioni, indicazioni e best practice per aiutarli a prepararsi a questa transizione e rendere il percorso strutturato e prevedibile.

   Uno degli strumenti di transizione cloud - Strumento di trasferimento dei contenuti è stato rilasciato. [Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) è sviluppato da Adobe e può essere utilizzato per spostare il contenuto esistente da un’istanza AEM di origine (locale o AMS) all’istanza Cloud Service AEM di destinazione.

   È stato rilasciato uno degli strumenti di refactoring del codice - AEM Dispatcher Converter. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) è uno strumento per convertire le configurazioni AEM Dispatcher esistenti in AEM come configurazioni Cloud Service Dispatcher ed è disponibile.

* **Accessibilità e linee guida WCAG 2.1**

   Aggiornamenti relativi alle linee guida WCAG 2.1:

   * [Adobe Experience Manager as a Cloud Service e le linee guida per l’accessibilità dei contenuti web](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Guida rapida alle linee guida WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Creazione di contenuto accessibile (conformità WCAG 2.1)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **Newsletter di AEM**

   La newsletter di AEM di Experience League è stata progettata per aiutarti a imparare a usare AEM in modo da poter iniziare a realizzare valore fin da subito. Ecco la newsletter più recente:

   * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager è disponibile come servizio cloud.
   * [Iscriviti](https://adobeeventsonline.com/AEM/2017/NL/Optin/) alla newsletter Experience Insider.
   * Accedi agli archivi delle newsletter nella sezione [Risorse AEM](https://helpx.adobe.com/it/support/experience-manager/6-5.html) della pagina Informazioni e supporto di Adobe Experience Manager 6.5.

### **Community**

* **Discussione sulla community AEM**

   Ora puoi consultare tutti gli annunci relativi ad AEM e gli interessanti riferimenti ai blogger interni ed esterni in un&#39;unica posizione. Consulta la sezione [Discussione della community AEM.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Nuovi corsi  Experience Manager ed esercitazioni

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |
| [Guida introduttiva ad Adobe Asset Link per gli utenti aziendali](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Corso | In questo corso, scopri come utilizzare le funzioni e le funzionalità di Adobe Asset Link per arricchire il design creativo con il contenuto memorizzato in  risorse di Adobe Experience Manager. Il corso illustra tutte le procedure, dal lancio del collegamento delle risorse Adobe, alle operazioni di base sulle risorse, alle opzioni di ricerca e navigazione e alla collaborazione efficace con altri utenti. |
| [Guida introduttiva ai AEM Assets per gli utenti aziendali](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Corso | Scoprite come iniziare a utilizzare i AEM Assets per gli utenti aziendali. Scoprite le nozioni di base di AEM Assets, funzioni di collaborazione, ricerca, organizzazione e download delle risorse e delle relative rappresentazioni. |
| [Guida introduttiva ai AEM Sites per gli utenti aziendali](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Corso | Scoprite come utilizzare le funzioni e le funzionalità di base di AEM Sites per gestire le pagine Web dell&#39;organizzazione. Il corso tratta tutto, dall’introduzione agli AEM Sites, i concetti di base dell’authoring, le funzioni di authoring avanzate e le funzionalità di gestione delle pagine. |
| [Struttura dei progetti AEM](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Articolo | Descrive le modifiche necessarie per  progetti Adobe Experience Manager Maven in modo che siano compatibili con AEM Cloud Service. |
| [Modelli Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Esercitazione video | Scopri come eseguire il debug di AEM come avvio rapido locale di Cloud Service SDK tramite la console Web Sling Models. |
| [Componenti della console Web AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Esercitazione video | Scopri come eseguire il debug di AEM come avvio rapido locale dell’SDK Cloud Service tramite la console Web Components. |
| [Debug dell’avvio rapido locale dell’SDK AEM tramite i registri](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Esercitazione video | Scopri come eseguire il debug di AEM come avvio rapido locale dell’SDK Cloud Service tramite la console Web Bundles. |
| [Debug remoto di AEM come avvio rapido locale di Cloud Service SDK](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Esercitazione video | Scopri il debugging Java remoto dall’IDE, per consentirti di analizzare a fondo l’esecuzione del codice in tempo reale in AEM per comprendere esattamente il flusso di esecuzione. |
| [Impostazione smart tag](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Esercitazione video | Istruzioni passo passo per integrare  Adobe Experience Manager (AEM) con Smart Content Service tramite Adobe I/O. |
| [Generazione batch di documenti](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Articolo | Scopri come utilizzare l&#39;API Batch per produrre più comunicazioni interattive da un modello. |
| [Creazione di un documento canale di stampa in AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Articolo | Scopri i passaggi necessari per creare una comunicazione interattiva per il canale di stampa. |
| [Accesso ad Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Esercitazione video | Scopri come accedere al contenuto memorizzato in  risorse di Adobe Experience Manager (AEM Assets), senza uscire dalle app desktop Creative Cloud che hai più familiarità con. |
| [Panoramica del pannello Collegamento risorse](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Esercitazione video | Adobe Asset Link consente agli utenti creativi di sfogliare, cercare, estrarre e archiviare le risorse memorizzate in AEM Assets mediante il pannello in-app in InDesign, Photoshop e Illustrator. Scopri l’interfaccia utente e le funzionalità del pannello Collegamento risorse di Adobe. |
| [Ricerca risorse](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Esercitazione video | Gli utenti Creative possono cercare risorse memorizzate in AEM Assets utilizzando le parole chiave oppure eseguire una ricerca in una posizione specifica. |
| [Versioni e commenti del file](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Esercitazione video | Con il pannello Collegamento risorse di Adobe potete accedere ai dettagli dei file per le risorse in AEM Assets, come miniature, metadati di base e versioni direttamente dal pannello. |
| [Check-In Check-Out](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Esercitazione video | Adobe Asset consente di estrarre i AEM Assets direttamente dall’app creativa su cui state lavorando e di iniziare subito a apportare modifiche. |
| [Per rappresentazione solo posizionamento per AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Esercitazione video | Scopri come creare e utilizzare una rappresentazione Solo posizionamento (FPO) per le risorse AEM. |
| [Inserisci copia](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Esercitazione video | Scoprite come utilizzare le risorse dai AEM Assets mediante l’operazione Inserisci copia. |
| [Download e caricamento](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Esercitazione video | Scoprite come scaricare e caricare i file di risorse da e verso AEM Assets mediante il pannello Collegamento risorse. |
| [File e raccolte](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Esercitazione video | Scoprite come accedere in modo rapido e semplice ai file AEM Assets e alle raccolte dal pannello Collegamento risorse. |
| [Scarica](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Esercitazione video | Scoprite come scaricare le risorse e le relative rappresentazioni nel computer locale per utilizzarle e condividerle. |

### Risorse aggiuntive

* [AEM come Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/landing/home.html)
* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Nuovi rilasci di prodotti

[rilascio](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) Classic 20.2 include:

* _Supporto di Emoticon_ - _Azure Synapse FDA Connector_ - _Nuove norme sulla privacy_
* Pannello di controllo campagna: [Monitoraggio del profilo attivo](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### Nuovi corsi ed esercitazioni per le campagne

| Contenuto | Tipo di contenuto | Descrizione |
| -----------| ---------- | ---------- |  
| [Guida introduttiva  Adobe Campaign Standard per gli utenti aziendali](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Corso | Scopri come navigare nell&#39;interfaccia, lavorare con le consegne e creare e gestire i dati dei destinatari. |
| [Installazione e configurazione del client di Adobe Campaign](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Video | Scoprite come scaricare e installare la console client  Adobe Campaign, creare e gestire le connessioni a più ambienti e verificare l&#39;accesso alla console client  Adobe Campaign |

### Risorse di aiuto

* Adobe Campaign Standard: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/campaign-standard-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/overview.html) - [Piano delle versioni future](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-planning.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/campaign-classic-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/documentation-updates.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html) - Video per [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Nuove funzioni in Advertising Cloud DSP](#adcloud-dsp)
* [Nuove funzioni in Advertising Cloud Search](#adcloud-search)

### Nuove funzioni in Advertising Cloud DSP {#adcloud-dsp}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Campaign] Home | (rilascio del 3 giugno) Sono disponibili nuove metriche di valutazione a livello di campagna basate sul budget della campagna fornito e sul tempo trascorso. |
| Previsione posizionamento | (rilascio del 3 giugno) Per i posizionamenti CTV e video con ottimizzazione a livello di posizionamento, le impostazioni di posizionamento ora includono previsioni per lunghezze di annunci multipli (15 sec e 30 sec). Includono anche previsioni per l&#39;inventario VAST e VPAID. |
| Ottimizzazione CPA/ROAS | (rilascio del 20 maggio) I manager delle campagne non devono più limitare i nuovi posizionamenti all&#39;interno dei pacchetti per evitare la sovraallocazione del budget. I posizionamenti ricevono ora una allocazione di budget dinamica in base alle prestazioni CPM o CPA/ROAS. |

### Nuove funzioni in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Campagne] | Microsoft Advertising (ex Bing Ads) sta eliminando le metriche di posizione media dopo il 30 settembre 2020. In preparazione, a partire dall&#39;11 luglio, i vincoli basati sulla posizione verranno ignorati e anche le condizioni basate sulla posizione in qualsiasi tipo di vincolo verranno ignorate. |
| [!UICONTROL Approfondimenti sulla pubblicità] | (rilascio del 13 giugno) Sono state rimosse le seguenti informazioni:<br/><br/><ul><li>Audience Target Performance (la versione più recente)</li><li>Prestazioni storiche (la versione più recente)</li><li>Tipo corrispondenza (versione più recente)</li><li>Controllo impostazioni (versione più recente)</li><li>Pre-Post portfolio (legacy)</li></ul><br/>Le informazioni rimanenti sono versioni precedenti e l&#39;etichetta _Legacy_ è stata rimossa dai nomi. Inoltre, sono state rimosse le modalità Live/Edit. |

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per lead management e marketer B2B che intendono trasformare le esperienze dei clienti impegnandosi in ogni fase dei percorsi d’acquisto complessi.

### Aggiornamenti principali di Marketo Engage

Consulta le [note sulla versione](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) di [!DNL Marketo] per informazioni aggiornate.

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
