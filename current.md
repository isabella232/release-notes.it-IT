---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: c62d85f09ce596482a019aa5d0f1d517bf2df9fe

---


# Note sulla versione di Adobe Experience Cloud - Febbraio 2020

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!NOTE]
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 20 febbraio 2020**

(date di rilascio specifiche del prodotto possono variare)

Ultimo aggiornamento: 10 febbraio 2020

* [Stato del sistema di Adobe](#status)
* [Interfaccia e servizi principali di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services e Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il vostro Adobe ID, potete iscrivervi alle notifiche evento in base alle preferenze di prodotto, regione, evento e lingua. Gli utenti che configurano le proprie preferenze di iscrizione ricevono una notifica degli eventi rilevanti relativi a incidenti e manutenzione del prodotto non appena vengono aperti, aggiornati o chiusi. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Maggiore consapevolezza degli eventi di prodotto | <ul><li>30 giorni di anticipo sulla manutenzione del servizio. Questa funzione fornisce un periodo di tempo maggiore per valutare l&#39;impatto potenziale sulle operazioni aziendali, consentendo di implementare un piano di mitigazione, se necessario.</li><li>Le notifiche avanzate sono disponibili su superfici Web/mobili/tablet e tramite notifiche e-mail.</li></ul> |
| Personalizza la tua esperienza in base alla lingua preferita | <ul><li>Scegliete una lingua preferita per le notifiche e-mail. La funzione di autoiscrizione è ora disponibile in diciannove lingue.</li></ul> |
| Esperienza utente di iscrizione e notifica migliorata | <ul><li>Specificate le preferenze di regione e evento con un solo clic per tutti i prodotti ai quali desiderate iscrivervi.</li><li>Ricevi notifiche quando _potenziali_ problemi vengono promossi a _minori_ o _maggiori_ .</li><li>La pagina del browser si aggiorna automaticamente quando lo stato di un prodotto o evento viene aggiornato.</li></ul> |

## Interfaccia e servizi principali di Experience Cloud {#ecloud}

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, tra cui gestione e servizi principali (attributi del cliente, pubblico, trigger, cookie e così via).

**Correzioni**

* **** Attributi cliente: L&#39;interfaccia utente Attributi del cliente ora mostra stati aggiuntivi di profili sincronizzati in Target. (MCUI-10231)
* **** Triggers Core Service: Per mancanza di utilizzo, il punteggio di propensione &quot;Probabilità di ritorno in 30 giorni&quot; durante la creazione di un attivatore di tipo Abbandono è stato rimosso. (MCUI-10056)

### Dominio di prodotto unificato

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificheranno il tuo attuale flusso di lavoro.

Gli aggiornamenti includono:

* Nuovi URL della soluzione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole soluzioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.
* Notifiche migliorate: Il menu a discesa [!UICONTROL Notifiche] ora include due schede, una per le notifiche sui prodotti e una per gli annunci globali dei prodotti.

**Nota:** La pagina [!UICONTROL Feed] verrà rimossa a gennaio 2020. Nel prodotto verrà visualizzato un avviso di funzione rimossa.

Per la documentazione sul prodotto, consulta [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html)  (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services e Mobile SDK {#mobile}

**4 febbraio 2020: versione 4.19.0**

In questa versione è stato effettuato il seguente aggiornamento:

**** Ciclo di vita: È stata aggiunta una nuova API `pauseCollectingLifecycleData`per attenuare i dati anormali relativi alla lunghezza di sessione segnalati da alcuni vecchi dispositivi iOS.

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)  (aggiornato il 21 gennaio 2020)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **Nuovo modello** Workspace per le organizzazioni che utilizzano l’analisi tra dispositivi:Questo modello mostra l’efficacia di CDA nel raggruppare le visite e nel fornire informazioni sulle dimensioni e metriche esclusive di CDA. È necessaria una suite di rapporti che utilizza CDA. Per ulteriori informazioni, consulta [Configurazione di analisi](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) cross-device.
* **** La latenza di cucitura CDA per le organizzazioni che utilizzano Private Graph è ridotta a un giorno: La funzionalità Private Graph è stata migliorata per ridurre la latenza di generazione del grafico da un processo batch settimanale a un grafico aggiornato ogni giorno, consentendo ai clienti CDA di accedere a grafici e collegamenti con identità più aggiornati.
* **** Labs (anteprime tecnologia): Questa nuova funzione di Analytics consente di testare i nuovi prototipi di funzionalità in produzione e di fornire un feedback prezioso ad Adobe. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **Nuovi tasti di scelta rapida in Workspace:**<ul><li>Comprimi/Espandi tutti i pannelli: `alt + m`</li><li>Comprimi/Espandi pannello attivo: `alt + ctrl + m`</li><li>Cerca nella barra a sinistra: `ctrl + /`</li><li>Passa al pannello successivo: `alt + Right Key`</li><li>Passa al pannello precedente: `alt + Left Key`</li></ul>[Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **Altri miglioramenti all’area di lavoro:**<ul><li>Quando un pannello o una visualizzazione viene rilasciato in [!UICONTROL Workspace], la barra a sinistra passa automaticamente ai componenti per un flusso di lavoro più semplice.</li><li>I componenti modello ora possono essere attivati (ad esempio con tag, contrassegnati come preferiti, approvati).</li><li>Gli elenchi di metriche filtrate e segmenti offrono al `+` pulsante l’opportunità di aggiungere un nuovo componente in caso contrario.</li></ul>
* Il debugger di **Workspace** è stato aggiunto al menu Aiuto, per consentirvi di eseguire il debug delle richieste di Workspace in modo più semplice. [Ulteriori informazioni...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** Browser Microsoft Edge basato su cromo: Questa versione include modifiche per riconoscere il browser Microsoft Edge basato su Chromio (versione 79 e successive) a scopo di reporting.

#### Correzioni

* È stato risolto un problema relativo all&#39;interfaccia utente Segmento che causava la compatibilità delle dimensioni del canale  Marketing con [!UICONTROL Data Warehouse], quando in realtà non lo sono. In futuro, il Generatore [!UICONTROL di] segmenti non mostrerà più queste dimensioni come compatibili con [!UICONTROL Data Warehouse] . (AN-202297)
* È stato risolto un problema con il nome di un segmento pubblicato aggiornato in Analytics che non veniva aggiornato in Audience Manager entro 24 ore. (AN-199974)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | `https://experience.adobe.com/analytics.`<br>** Il 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi in un nuovo dominio - **Nota: Questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Potrai utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti Safari.</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per l’opzione **[!UICONTROL Visualizza archivio]** in Dashboard Manager (**[!UICONTROL Componenti > Dashboard]**). |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Enforce IP Login Restrictions]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per la funzionalità di whitelisting degli accessi IP (**[!UICONTROL Enforce IP Login Restrictions]**), nel menu **[!UICONTROL Amministrazione > Impostazioni società > Sicurezza]**. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics è stato aggiornato da Ora del Pacifico a un valore di data e ora formattato correttamente con le informazioni sul fuso orario.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versione 2.18.0 è stata rilasciata il 13 febbraio 2020.

## Audience Manager {#aam}

Correzioni e funzioni aggiunte ad Audience Manager.

### Nuove funzioni, miglioramenti e correzioni in Audience Manager {#aam-features}

| Funzione | Descrizione |
|----|----|
| [Report sull&#39;utilizzo dell&#39;attività](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | Il rapporto [!UICONTROL sull&#39;uso dell&#39;] attività consente di visualizzare e monitorare l&#39;utilizzo dell&#39;attività dell&#39;istanza Audience Manager, fornendo un&#39;idea chiara di come l&#39;utilizzo dell&#39;attività è paragonabile all&#39;impegno contrattuale. |

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* È stato corretto un bug a causa del quale il flusso di creazione della destinazione interrompe l&#39;interfaccia utente per la selezione di Account integrati (AAM-52414).
* È stato corretto un bug a causa del quale l&#39;interfaccia utente si interrompe durante la navigazione attraverso il flusso di creazione dei modelli algoritmici (AAM-37942).
* È stato corretto un bug a causa del quale la selezione dell&#39;esportazione dei dati non veniva salvata quando si salvavano i controlli di esportazione dei dati per destinazioni nuove o esistenti, per clienti che utilizzavano l&#39;integrazione con Adobe Experience Platform (AAM-52814).
* È stato corretto un bug a causa del quale le raccomandazioni sulle caratteristiche di terze parti non funzionavano correttamente per le caratteristiche che contengono caratteri di pipe (`|`) nel nome (AAM-51635).
* Numerosi miglioramenti a livello di accessibilità nell’interfaccia utente.

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Rilasci di prodotti

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0 semplifica la gestione self-service delle sandbox per Adobe Experience Manager come servizio Cloud.

   Consulta le [note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Aiuto e documentazione

* **Esercitazioni per AEM come servizio cloud**

   Inizia rapidamente con le [esercitazioni per AEM come servizio](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)cloud.

* **API batch di comunicazione interattiva AEM Forms**

   L&#39;API batch della comunicazione interattiva AEM Forms consente ai clienti di produrre più comunicazioni interattive, automaticamente o su richiesta. I clienti possono generare simultaneamente output di stampa e Web.
Consultate [Generare più comunicazioni interattive utilizzando l&#39;API](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)Batch.

* **Piattaforme supportate per AEM Forms su JEE**

   È stato aggiunto il supporto per Oracle 19c per i clienti AEM Forms su JEE.
Consultate Piattaforme [supportate per AEM Forms su JEE](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

### Risorse aggiuntive

* [AEM come Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### Campaign Classic 19.2.3

Fai riferimento alle [note sulla versione Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) per correzioni e miglioramenti.

### Campaign Standard 20.1

Fai riferimento alle [note sulla versione Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) per correzioni e miglioramenti.

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aggiornato il 10 febbraio 2020 per la versione dell’8 febbraio

| Visualizzazione | Funzione |
|------|---------|
| Portfolio | Ora puoi aggiungere campagne Yahoo Japan Display Network (YDN) ai portfolio per ottimizzare il budget delle campagne e le offerte dei gruppi di annunci. La stessa offerta viene applicata a tutti gli annunci di un gruppo di annunci. I dati per le campagne YDN sono inclusi nelle simulazioni per il portfolio. |
| Ricerca > Bulksheet | Ora puoi creare, modificare ed eliminare gli annunci adattabili alla rete di ricerca di Google (RSA, Responsive Search Ads) utilizzando i bulksheet. Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| Ricerca > Campagne, Report | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

Per le note sulla versione di Magento, vedi:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
