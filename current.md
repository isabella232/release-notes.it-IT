---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 41c551a6c2e3e8b621abacb5afe2240c30b851da

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Aprile 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nuove funzioni e correzioni in [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

>[!NOTE]
>
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: aprile 2020**

(date di rilascio specifiche della soluzione potrebbero variare.)

* [Stato del sistema di Adobe](#status)
* [Interfaccia e servizi principali di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (Modifica della data di **rilascio - vedere aggiornamento il 15 aprile**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (collegamenti alla pagina della guida della soluzione)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (collegamenti alla pagina della guida della soluzione)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/it-IT/experience-cloud/user-guides/home.html).

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Inoltre, nell&#39;ultima versione, il processo di autoiscrizione ora consiglia una selezione di prodotti e servizi basati sulle adesioni dei prodotti. Questo dovrebbe semplificare il processo di iscrizione riducendo il numero di decisioni o clic necessari per creare le iscrizioni e, cosa più importante, inviare notifiche più rilevanti nella inbox. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Iscrizioni personalizzate basate su adesioni | <ul><li>Raccomandazioni di iscrizione pre-selezionate in base alle adesioni DX dell&#39;utente.</li><li>Le iscrizioni consigliate sono evidenziate nella parte superiore dell&#39;elenco dei prodotti per una visualizzazione rapida.</li><li>Le notifiche e-mail ricevute sono pertinenti alle adesioni dei prodotti dell&#39;utente.</li></ul> |
| Gestione più semplice delle iscrizioni | <ul><li>**[!UICONTROL Gestione iscrizioni]** dispone di una nuova esperienza utente per gestire le iscrizioni a prodotti ed eventi.</li><li>Nuova opzione per visualizzare e modificare separatamente le iscrizioni a prodotti e eventi.</li><li>L’opzione **[!UICONTROL Elimina]** consente di annullare l’iscrizione a un prodotto o a un’iscrizione a un evento.</li><li>L’opzione **[!UICONTROL Annulla sottoscrizione tutto]** è disponibile con un solo clic per le iscrizioni al prodotto.</li><li>Il supporto UX è disponibile per le superfici Web/Mobile/Tablet e per la localizzazione in 19 lingue.</li></ul> |

## ![Icona](/assets/ec_appicon_24.png) Interfaccia e servizi principali di Experience Cloud {#ecloud}

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, tra cui gestione e servizi principali (attributi del cliente, pubblico, trigger, cookie e così via):

* La pagina [!UICONTROL Feed] di Experience Cloud era obsoleta. (EXC-8505)
* La pagina di accesso di Experience Cloud è stata aggiornata per riflettere i nuovi elementi di branding. (EXC-10747)

Per la documentazione sul prodotto, consulta la guida di [Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

### Dominio di prodotto unificato

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificheranno il tuo attuale flusso di lavoro.

Gli aggiornamenti includono:

* Nuovi URL della soluzione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole soluzioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.

## ![Icona](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Note sulla versione di [!UICONTROL Experience Platform], [!UICONTROL Experience Platform Launch], [!UICONTROL Identity Service], Journey Orchestration, Mobile Services e bollettini sulla sicurezza.

### Journey Orchestration {#journey}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

* [Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html)
* [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html)
* [Video sulle procedure](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e Mobile SDK {#mobile}

Android 4.18.2 (3 aprile 2020):

* Messaggi in-app: Per motivi di sicurezza, [!UICONTROL WebViews] creato dall’SDK ora imposta la proprietà `setAllowFileAccess` su _false_.

iOS 4.19.2 (24 marzo 2020):

* Generale: Sono stati corretti alcuni problemi di [!DNL Target] codice.

Unità 4.19.0 (10 marzo 2020):

* È stato aggiornato [!UICONTROL Unity Plugin] per utilizzare le versioni 4.19.0 di iOS e 4.18.0 o [!DNL Android].
* Nuovo metodo di acquisizione esposto per [!DNL Android] consentire l’elaborazione di un URL fornito dalle API [!DNL Google Play] Referente.

### Informazioni aggiuntive sulla versione della piattaforma Experience

* [Note](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html)sulla versione di Experience Platform Launch.
* [Note sulla versione della piattaforma Experience](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html) (Tutti i prodotti Adobe)

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>La maggior parte della versione di manutenzione di Adobe Analytics è stata spostata al 21 maggio 2020. Per informazioni aggiornate sulla versione di Analytics, consultate le note sulla versione di [marzo](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices) (aggiornato il 7 aprile 2020)
* [AppMeasurement](#appm)
* [Nuove esercitazioni di Analytics](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Analisi]percorso cliente: Backfill automatizzato del set di dati | Questa nuova opzione consente di importare tutti i dati storici per una connessione in [!UICONTROL Customer Journey Analytics]. [Ulteriori informazioni](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Change to how [!UICONTROL Entries/Exits] are calculated in [!UICONTROL Workspace] | 7 aprile 2020 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. Ad esempio, si supponga che il primo hit di una visita non contenga alcun valore per le eVar, ma anche per il secondo. In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| Impostazione di fine del ciclo vita del **[!UICONTROL Livello di conversione]** | 3 marzo 2020 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/it-IT/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| Fine del ciclo vita dell’**[!UICONTROL Archivio del dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL View Archive]** (Visualizza archivio) nella sezione **[!UICONTROL Manage Dashboards]** (Gestione dashboard) in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | A partire dal 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota:** questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione _Impedisci il rilevamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. Potrai utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti [!DNL Safari].</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/it-IT/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html). La versione 2.20.0 è stata rilasciata il 5 marzo 2020.

### Nuove esercitazioni di Analytics {#tutorials-analytics}

| Contenuto | Descrizione |
| -----------| ---------- |
| [Adobe Labs (Anteprime tecnologia) con Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs (Anteprime tecnologiche) consente di interagire con le tecnologie emergenti, scoprire informazioni importanti e influenzare lo sviluppo e le priorità future [!DNL Analytics] delle funzioni. |
| [Miglioramento della pubblicazione Experience Cloud Audience](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Sono stati apportati miglioramenti a [!UICONTROL Experience Cloud Audience Publishing]. Ora puoi pubblicare i tipi di pubblico (segmenti) e renderli disponibili sei volte più rapidamente. Questo riduce il tempo di latenza corrente da 48 ore a circa 8 ore, e possibilmente più veloce, a seconda del traffico e della dimensione del segmento. |
| [Suite di rapporti multiple in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | È possibile analizzare più suite di rapporti in un unico progetto [!UICONTROL Workspace] selezionando le suite di rapporti a livello di pannello. Questo consente di eseguire analisi affiancate dei pannelli tra diversi set di dati. |

Per la documentazione del prodotto, consultate Home [dell&#39;Aiuto di](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html) Adobe Analytics.

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni e correzioni in Adobe Audience Manager:

| Funzione | Descrizione |
| -----------| ---------- |  
| [Principali problemi di assistenza clienti](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Abbiamo aggiunto una nuova sezione al nostro portale della documentazione, che include le risposte alle domande più frequenti ricevute dal nostro team di assistenza clienti. |

* È stato risolto un problema che causava la generazione di rapporti non accurati dei tipi di pubblico di [riferimento](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) per i segmenti contenenti ID dispositivo mobile. In seguito a questo aggiornamento, potrebbe verificarsi un aumento del pubblico [indirizzabile](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* È stato risolto un problema che impediva il funzionamento dei pulsanti [!UICONTROL Duplica test] e [!UICONTROL Duplica modello] di allocazione in [!UICONTROL Audience Lab] . (AAM-53388)
* È stato risolto un problema che causava la visualizzazione di [!UICONTROL Tasso] di corrispondenza e Pubblico [!UICONTROL indirizzabile al] segmento come 0 quando una destinazione è configurata per l’esportazione di UUID. Il [!UICONTROL valore Frequenza] di corrispondenza e Pubblico [!UICONTROL indirizzabile ai] segmenti ora viene visualizzato al 100%. (AAM-51615)
* È stato risolto un problema che causava la doppia codifica HTML dei nomi delle caratteristiche contenenti caratteri speciali. (AAM-54001)
* È stato risolto un problema che impediva ad alcuni utenti di passare dall&#39;interfaccia [!DNL Audience Manager] utente ad altre soluzioni Adobe Experience Cloud. (AAM-52917)
* È stato risolto un problema che impediva ad alcuni utenti di creare un&#39;origine dati SHA256 per le destinazioni basate su Persone. (AAM-53525)
* Miglioramenti a livello di accessibilità nell&#39;interfaccia. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aiuto e documentazione

* **Newsletter AEM**

   Consulta la newsletter [più recente di](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)Adobe Experience Manager.

* **AEM come servizio cloud - Configurazione del servizio Dynamic Media Cloud**

   Quando configuri il servizio Dynamic Media Cloud, è disponibile una nuova opzione:

   **Pubblicazione** selettiva: quando selezionate questa opzione, le risorse vengono pubblicate automaticamente solo per la visualizzazione in anteprima protetta e possono essere pubblicate in modo esplicito in AEM senza pubblicare contenuti DMS7 per la distribuzione nel dominio pubblico.

   Consultate [Configurazione del servizio](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)Dynamic Media Cloud.

* **Contenuti multimediali dinamici - Immagini intelligenti**

   L&#39;intero argomento della Guida di Smart Imaging è stato aggiornato con nuove informazioni, inclusi gli esempi di risorse di immagini che rappresentano l&#39;ottimizzazione di Smart Imaging aggiunta.

   Consultate [Smart Imaging](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configurazione di contenuti multimediali dinamici - Modalità Scene7**

   Una nuova opzione Sincronizza tutto il contenuto è ora disponibile nella pagina Configurazione elementi multimediali dinamici disponibile in **[!UICONTROL Strumenti > Servizi]** cloud.

   Consultate [Creazione di una configurazione](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)per contenuti multimediali dinamici.

* **AEM Assets Brand Portal supporta Risorse AEM come servizio cloud**

   Ora puoi pubblicare le risorse da Risorse AEM come servizio Cloud nel portale dei marchi di AEM Assets.

   Consultate [Configurare AEM Assets con Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) e [Pubblicare risorse su Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Rilascio di Adobe Asset Link 2.0**

   Adobe Asset Link 2.0 supporta l’utilizzo con più ambienti AEM e supporta AEM come servizio cloud. AEM supporta la necessità per gli esperti di marketing di configurare l’esecuzione automatica del flusso di lavoro di elaborazione delle risorse quando le risorse vengono caricate in una cartella tramite Adobe Asset Link.

   See [Adobe Asset Link](https://helpx.adobe.com/it/enterprise/using/adobe-asset-link.html).

### Nuove esercitazioni Experience Manager

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Imposta strumenti di dispatcher locali](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Scopri come semplificare la configurazione, la convalida e la simulazione locale del [!UICONTROL dispatcher] . |
| [Impostazione di strumenti di sviluppo per progetti AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Lo sviluppo di Adobe Experience Manager (AEM) richiede l&#39;installazione e la configurazione di un set minimo di strumenti di sviluppo nel computer dello sviluppatore. Questi strumenti supportano lo sviluppo e la creazione di progetti AEM. |
| [Configurare AEM Runtime locale](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) può essere eseguito localmente utilizzando AEM come [!UICONTROL QuickStart Jar]dell’SDK di Cloud Service. Questo consente agli sviluppatori di implementare e testare codice, configurazione e contenuto personalizzati prima di impegnarli nel controllo del codice sorgente e di distribuirli in un ambiente AEM come servizio cloud. |
| [Navigazione](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Esplora le nozioni di base per la navigazione in Risorse AEM. |
| [Versioni](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Scopri in che modo AEM crea e gestisce le versioni delle risorse. |
| [Integrazione di AEM - [!DNL Magento] tramite [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Questo video illustra la configurazione dell’integrazione tra AEM e [!DNL Magento]. |
| [Introduzione allo stack AEM Architecture](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | L’archetipo CIF del progetto crea un minimo progetto Adobe Experience Manager (AEM) CIF come punto di partenza per i progetti dei clienti che utilizzano CIF Core Components (Componenti di base CIF). |
| [Introduzione a OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Introduzione a OSGi, un&#39;architettura modulare dinamica per le applicazioni Java alla base di Adobe Experience Manager. |
| [Introduzione a Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Introduzione a [JCR (Java Content Repository)) utilizzato da Adobe Experience Manager. |
| [Introduzione alla Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Un&#39;introduzione a [!DNL Sling]un framework Web RESTful open-source che fa parte dello stack di tecnologia sottostante di Adobe Experience Manager. |
| [Introduzione a Author and Publish Tier](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Un&#39;introduzione ai livelli [!UICONTROL Author] e [!UICONTROL Publish] come parte dell&#39;architettura in Adobe Experience Manager. |
| [Introduzione al dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Un&#39;introduzione alle funzionalità e alle funzionalità del dispatcher come parte dell&#39;architettura AEM. |
| [Introduzione allo sviluppo dei componenti](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Panoramica sullo sviluppo di componenti con Adobe Experience Manager Sites. Include un&#39;introduzione a [!UICONTROL Dialogs], [!UICONTROL Sling Models], [!UICONTROL HTL Scripts]e [!UICONTROL Client-Side Libraries]. |
| [Archetipo di progetto AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | Il progetto AEM contiene tutto il codice e le configurazioni per un’implementazione. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Informazioni sui componenti core](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | I componenti  core di AEM sono componenti set standard da utilizzare con Adobe Experience Manager. |
| [Utilizzo di AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Scopri come installare ed eseguire un’istanza locale di Adobe Experience Manager in pochi minuti con il Jar [!UICONTROL AEM Quickstart]. |

### Risorse di aiuto aggiuntive

* [AEM come Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/landing/home.html)
* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/it/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

## ![Icona](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html)

### Esercitazioni su New Campaign Standard {#tutorials-acs}

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Sostituzione profilo - Verifica dei messaggi e-mail tramite profili di destinazione](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Verificate i messaggi e-mail utilizzando la funzione Sostituzione profilo. |

### Risorse aggiuntive della guida Campaign

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/it/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Pianificazione rilascio](https://helpx.adobe.com/it/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/it/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/it-IT/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] è una soluzione completa per i responsabili della gestione dei lead e per gli esperti di marketing B2B che desiderano trasformare l’esperienza dei clienti seguendo tutte le fasi dei processi di acquisto più complessi.

### Aggiornamenti principali di Marketo Engagement

Per ulteriori informazioni, consulta [!DNL Marketo] Note [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) sulla versione.

### Funzionalità in arrivo

Nel corso del trimestre verranno presentate le seguenti funzionalità:

| Funzione | Descrizione |
|------|---------|
| [!DNL Bizible] | <ul><li>Nuova segmentazione basata sugli account</li><li>Possibilità di salvare filtri specifici per dashboard</li><li>Esportazione dashboard Bizible in formato PDF</li></ul> |
| Sales Connect | Aggiornamenti/miglioramenti relativi a finestre di composizione e centri di comando |

### Annunci

**Success Center di Marketo Engage:** lancio a febbraio 2020. Success Center è un centro di assistenza interno al prodotto che consente di effettuare ricerche nei documenti sui prodotti e nella community, avviare guide informative, accedere ai contenuti di adozione e altro ancora. Nota: questa funzionalità verrà lanciata come versione beta in Australia e Nuova Zelanda e verrà implementata nel Nord America in un secondo momento nel corso del trimestre.

### Funzionalità deprecate

* **Parametro &quot;_method&quot; dell&#39;API risorsa:** Dopo settembre 2020, gli endpoint API risorsa non accetteranno più `_method` di trasmettere i parametri di query in un corpo POST per bypassare i limiti di lunghezza URI.
* **Supporto in Internet Explorer:** a partire dalla versione di luglio del 31 luglio 2020, Internet Explorer non supporterà più l’interfaccia utente di Marketo Engage.

Per leggere le note precedenti e complessive, consulta le [note sulla versione Marketo](https://docs.marketo.com/x/CgA6Ag).
