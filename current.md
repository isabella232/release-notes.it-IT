---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 77e4ac05707d9aa42ddf2e7fb93027b3226058e9
workflow-type: tm+mt
source-wordcount: '3632'
ht-degree: 99%

---


# Note sulla versione di Adobe Experience Cloud - aprile 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nuove funzioni e correzioni in [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: aprile 2020**

Ultimo aggiornamento: **30 aprile 2020**

Le date di rilascio specifiche potrebbero variare.

* [Stato del sistema di Adobe](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(aggiornato il 29 aprile)**
* [Audience Manager](#aam) **(aggiornato il 30 aprile)**
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (link alla guida di Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (link alla guida di Primetime)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/it-IT/experience-cloud/user-guides/home.html).

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Inoltre, nell’ultima versione, nel processo di autoabbonamento viene ora consigliata una selezione di prodotti e servizi sulla base dei prodotti di cui attualmente disponi. Questo dovrebbe sia semplificare il processo di abbonamento riducendo il numero di decisioni o clic necessari, sia determinare l’invio di notifiche più rilevanti. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Abbonamenti personalizzati in base ai prodotti esistenti | <ul><li>Suggerimenti per abbonamenti preselezionati in base alle attuali adesioni DX dell’utente.</li><li>Gli abbonamenti consigliati sono evidenziati ed elencati per primi, per velocizzarne la visualizzazione.</li><li>Le notifiche e-mail ricevute sono pertinenti in base ai prodotti a cui l’utente ha diritto.</li></ul> |
| Gestione più semplice degli abbonamenti | <ul><li>**[!UICONTROL Gestione abbonamenti]** offre una nuova esperienza utente per gestire gli abbonamenti a prodotti ed eventi.</li><li>Nuova opzione per visualizzare e modificare separatamente gli abbonamenti a prodotti e eventi.</li><li>L’opzione **[!UICONTROL Elimina]** consente di annullare l’abbonamento a un prodotto o un evento.</li><li>L’opzione **[!UICONTROL Annulla tutti gli abbonamenti]** con un solo clic è disponibile per gli abbonamenti dei prodotti.</li><li>Il supporto UX è disponibile per web, mobile e tablet, con localizzazione in 19 lingue.</li></ul> |

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Nuove funzioni e correzioni nell’interfaccia di Experience Cloud:

* La pagina [!UICONTROL Feed] di Experience Cloud è stata dichiarata obsoleta. (EXC-8505)
* La pagina di accesso di Experience Cloud è stata aggiornata con nuovi elementi di branding. (EXC-10747)

Per la documentazione sul prodotto consulta la [guida all’interfaccia di Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

### Dominio di prodotto unificato

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificheranno il tuo attuale flusso di lavoro.

Gli aggiornamenti includono:

* Nuovi URL dell’applicazione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole applicazioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.

## ![Icona](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Note sulla versione [!DNL Experience Platform,] che includono [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offerte], [!UICONTROL Persone], [!UICONTROL Places], [!UICONTROL Mobile Services] e bollettini sulla sicurezza.

### Journey Orchestration {#journey}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

* [Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html)
* [Note sulla versione](http://www.adobe.com/go/platform-release-notes-en)
* [Video sulle procedure](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e Mobile SDK {#mobile}

Android 4.18.2 (3 aprile 2020):

* Messaggi in-app: per motivi di sicurezza, [!UICONTROL WebViews] creato dall’SDK ora imposta la proprietà `setAllowFileAccess` su _false_.

iOS 4.19.2 (24 marzo 2020):

* Generale: sono stati corretti alcuni problemi nel codice di [!DNL Target].

Unity 4.19.0 (10 marzo 2020):

* Il [!UICONTROL plug-in Unity] è stato aggiornato per l’utilizzo delle versioni 4.19.0 di iOS e 4.18.0 di [!DNL Android].
* È stato esposto un nuovo metodo di acquisizione per [!DNL Android] per consentire l’elaborazione di un URL fornito dalle API referente [!DNL Google Play].

### Informazioni aggiuntive sulla versione di Experience Platform

* [Note sulla versione di Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html)
* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html) (Tutti i prodotti Adobe)

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Il rilascio della versione di manutenzione di Adobe Analytics di aprile è stato spostato al 21 maggio 2020. Per informazioni aggiornate sul rilascio di Analytics consulta le [note sulla versione di marzo](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices) (aggiornato il 16 aprile 2020)
* [AppMeasurement](#appm)
* [Nuove esercitazioni per Analytics](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Funzione | Descrizione |
| -----------| ---------- |
| Data Workbench 6.74 (**aggiornato il 29/04/2020**) | Aggiornamento del certificato TLS del servizio di gestione identità (Identity Management Service, IMS) nell’analisi dell’implementazione del server. Questo aggiornamento estende l’analisi dalla corrispondenza di stringhe all’espressione regolare, inclusa la capacità di gestire certificati con nome alternativo del soggetto (SAN). Per maggiori informazioni, consulta le [note sulla versione di Data Workbench](https://docs.adobe.com/content/help/it-IT/data-workbench/using/release-notes/release-notes.html). |
| [!UICONTROL Customer Journey Analytics]: Recupero automatico del set di dati | Questa nuova opzione consente di importare tutti i dati storici per una connessione in [!UICONTROL Customer Journey Analytics]. [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/analytics-platform/using/cja-connections/create-connection.translate.html) |

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
| È stato rimosso il controllo “Segmento applicato in Data Warehouse” | 16 aprile 2020 | A partire dal 16 aprile 2020 non sarà più possibile verificare se un segmento viene applicato in una richiesta di Data Warehouse dall&#39;interno del segment builder. Precedentemente questo controllo cercava segmenti singoli applicati nelle richieste di Data Warehouse (escludeva i segmenti multipli applicati) e restituiva una notifica di avviso se true. Questa modifica non influisce sul controllo della compatibilità del prodotto Data Warehouse per i segmenti. |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Poiché ora in [!UICONTROL Analysis Workspace] è possibile attivare e disattivare i valori _None_, viene applicato il valore _None_ dopo l’entrata o l’uscita, mentre per le eVar veniva già applicato in precedenza. Ad esempio, si supponga che il primo risultato di una visita non presenti alcun valore per le eVar, mentre si verifica il contrario per il secondo. In [!UICONTROL Reports &amp; Analytics] verrà visualizzato come _Non specificato_ per l’entrata, ma in [!UICONTROL Analysis Workspace] verrà visualizzato come valore per il secondo risultato. |
| Impostazione di fine del ciclo vita del **[!UICONTROL Livello di conversione]** | 3 marzo 2020 | L’impostazione non funzionante del [Livello di conversione](https://docs.adobe.com/content/help/it-IT/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Strumenti di amministrazione]** > **[!UICONTROL Suite di rapporti]** > **[!UICONTROL Impostazioni account generali]** sarà rimossa dall’interfaccia utente il 12 marzo 2020. |
| Fine del ciclo vita di **[!UICONTROL Archivio dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL View Archive]** (Visualizza archivio) nella sezione **[!UICONTROL Manage Dashboards]** (Gestione dashboard) in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | A partire dal 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota:** questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione _Impedisci il rilevamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. Potrai utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti [!DNL Safari].</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/it-IT/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html). La versione 2.20.0 è stata rilasciata il 5 marzo 2020.

### Nuove esercitazioni per Analytics {#tutorials-analytics}

| Contenuto | Descrizione |
| -----------| ---------- |
| [Adobe Labs (Anteprime tecnologia) con Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs (Anteprime tecnologiche) consente di interagire con le tecnologie emergenti, scoprire informazioni importanti e influenzare le priorità e lo sviluppo delle future funzioni di [!DNL Analytics]. |
| [Miglioramento nella pubblicazione dei tipi di pubblico in Experience Cloud](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Sono stati apportati miglioramenti alla [!UICONTROL pubblicazione dei tipi di pubblico in Experience Cloud]. Ora puoi pubblicare i tipi di pubblico (segmenti) e renderli disponibili fino a sei volte più rapidamente. Questo riduce il tempo di latenza da 48 ore a circa 8 ore, e possibilmente ancora meno, a seconda del traffico e della dimensione del segmento. |
| [Più suite di rapporti in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | È possibile analizzare più suite di rapporti in un unico progetto [!UICONTROL Workspace] selezionandole a livello di pannello. Questo consente di eseguire analisi in pannelli affiancati tra diversi set di dati. |

Per la documentazione del prodotto, consulta la [pagina Home dell’Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html).

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni e correzioni in Adobe Audience Manager:

**(aggiornato il 30 aprile)**

| Funzione | Descrizione |
| -----------| ---------- |  
| [Predictive Audiences](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) | [!UICONTROL Predictive Audiences] (tipi di pubblico predittivi) aiuta a classificare in tempo reale un tipo di pubblico sconosciuto in persone distinte utilizzando tecniche avanzate di scienza dei dati. <br><br> In un contesto marketing una persona è un segmento di pubblico definito da visitatori, utenti o potenziali acquirenti che condividono una specifica serie di caratteristiche quali demografia, abitudini di navigazione, cronologia acquisti, ecc.I modelli <br><br>[!UICONTROL Predictive Audiences] sviluppano ulteriormente questo concetto, consentendo di utilizzare le capacità di machine learning di Audience Manager per classificare tipi di pubblico sconosciuti in persone distinte. <br><br>Audience Manager consente di ottenere questo risultato calcolando la propensione del pubblico di prima parte sconosciuto per un set di tipi di pubblico di prima parte conosciuti. |
| Ulteriori miglioramenti delle [!UICONTROL Regole di unione dei profili] | Le [!UICONTROL Regole di unione dei profili] consentono ai clienti di Audience Manager di definire, gestire e attivare i segmenti di pubblico in base all’identità anziché ai dispositivi. <br><br> A partire dal 29 aprile i clienti di Audience Manager potranno comprendere meglio il raggruppamento della popolazione degli ID dispositivo e multidispositivo per caratteristiche e segmenti sia all’interno della segmentazione individuale che nella generazione di rapporti in blocco nell’interfaccia utente di Audience Manager. <br><br> In questo modo sarà possibile conoscere meglio le identità all’interno di Audience Manager fornendo ai clienti una visione olistica della popolazione totale dei segmenti in base al dispositivo, alla persona e alla famiglia. Anche le esportazioni di caratteristiche in blocco degli ID dispositivo e multidispositivo verranno aggiornate per riflettere questi miglioramenti.<br><br> Aggiornamenti specifici includono la possibilità di: <ul><li>segnalare gli [ID multidispositivo](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reference/ids-in-aam.html) nei rapporti [generali](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reporting/general-reports.html) e [delle tendenze](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reporting/trend-reports.html);</li><li>migliorare il [!UICONTROL Selettore delle caratteristiche] nel [Generatore di segmenti](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/features/segments/segment-builder.html) per includere le popolazioni con caratteristiche date dagli [ID gestione delle relazioni con i clienti](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reference/ids-in-aam.html);</li><li>creare esportazioni precise di caratteristiche date dagli [ID multidispositivo](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reference/ids-in-aam.html);</li><li>creare esportazioni precise di caratteristiche date dagli [ID dispositivo](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reference/ids-in-aam.html) (escludendo i tratti autenticati);</li><li>restituire i conteggi corretti per le caratteristiche associate agli [ID gestione delle relazioni con i clienti](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/reference/ids-in-aam.html) quando richiesto utilizzando lo strumento [BAAAM](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html).</li></ul> |
| [Principali problemi dall’assistenza clienti](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Abbiamo aggiunto una nuova sezione al portale della documentazione con le risposte alle domande più frequenti ricevute dal team di assistenza clienti. |

* È stato risolto un problema che causava la generazione di rapporti non accurati di [Tipi di pubblico indirizzabili](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/features/addressable-audiences.html) per i segmenti contenenti ID per dispositivo mobile. In seguito a questo aggiornamento, potrebbe verificarsi un aumento dei [Tipi di pubblico indirizzabili](https://docs.adobe.com/content/help/it-IT/audience-manager/user-guide/features/addressable-audiences.html).
* È stato risolto un problema che impediva il funzionamento dei pulsanti [!UICONTROL Duplica test] e [!UICONTROL Duplica modello di allocazione] in [!UICONTROL Audience Lab]. (AAM-53388)
* È stato risolto un problema a causa del quale il [!UICONTROL Tasso di corrispondenza] e i [!UICONTROL Tipi di pubblico indirizzabili per segmento] venivano visualizzati come 0 quando una destinazione era configurata per l’esportazione di UUID. Ora [!UICONTROL Tasso di corrispondenza] e [!UICONTROL Tipi di pubblico indirizzabili per segmento] vengono visualizzati al 100%. (AAM-51615)
* È stato risolto un problema a causa del quale i nomi delle caratteristiche contenenti caratteri speciali venivano codificati in HTML due volte. (AAM-54001)
* È stato risolto un problema che impediva ad alcuni utenti di passare ad altre applicazioni di Adobe Experience Cloud dall’interfaccia utente di [!DNL Audience Manager]. (AAM-52917)
* È stato risolto un problema che impediva ad alcuni utenti di creare un’origine dati SHA256 per le destinazioni basate su persone. (AAM-53525)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aiuto e documentazione

* **Newsletter di AEM**

   Consulta l’ultima [newsletter di Adobe Experience Manager](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM as a Cloud Service - Configurazione di Dynamic Media Cloud Service**

   È disponibile una nuova opzione per la configurazione di Dynamic Media Cloud Service:

   **Pubblicazione selettiva**: quando selezioni questa opzione, le risorse vengono pubblicate automaticamente solo per la visualizzazione in anteprima protetta e possono essere pubblicate in modo esplicito in AEM senza la pubblicazione su DMS7 per la distribuzione nel dominio pubblico.

   Consulta [Configurazione di Dynamic Media Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media - Smart imaging**

   L’intero argomento dell’Aiuto dedicato allo Smart imaging è stato aggiornato con nuove informazioni, inclusi esempi di risorse di immagini che illustrano la nuova ottimizzazione Smart imaging.

   Consulta [Smart imaging](https://docs.adobe.com/content/help/it-IT/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configurazione di Dynamic Media - Modalità Scene7**

   La pagina Configurazione di Dynamic Media, disponibile da **[!UICONTROL Strumenti > Servizi cloud]**, contiene la nuova opzione Sincronizza tutti i contenuti.

   Consulta [Creazione di una configurazione di Dynamic Media](https://docs.adobe.com/content/help/it-IT/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets Brand Portal supporta AEM Assets as a Cloud Service**

   Ora puoi pubblicare le risorse da AEM Assets as a Cloud Service ad AEM Assets Brand Portal.

   Consulta [Configurare AEM Assets con Brand Portal](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) e [Pubblicare risorse su Brand Portal](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Rilascio di Adobe Asset Link 2.0**

   Adobe Asset Link 2.0 supporta l’utilizzo con più ambienti AEM nonché AEM as a Cloud Service. AEM supporta le esigenze degli esperti di marketing di configurare l’esecuzione automatica del flusso di lavoro per l’elaborazione delle risorse quando queste vengono caricate in una cartella tramite Adobe Asset Link.

   Consulta [Adobe Asset Link](https://helpx.adobe.com/it/enterprise/using/adobe-asset-link.html).

### Nuove esercitazioni per Experience Manager

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Impostare strumenti Dispatcher locali](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Scopri come semplificare la configurazione, la convalida e la simulazione locale di [!UICONTROL Dispatcher]. |
| [Impostare strumenti di sviluppo per progetti AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Lo sviluppo per Adobe Experience Manager (AEM) richiede l’installazione e la configurazione di un set minimo di strumenti di sviluppo nel computer dello sviluppatore. Questi strumenti supportano lo sviluppo e la creazione di progetti AEM. |
| [Configurare AEM Runtime locale](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) può essere eseguito localmente utilizzando [!UICONTROL QuickStart Jar] dell’SDK di AEM as a Cloud Service. Questo consente agli sviluppatori di implementare e testare il codice personalizzato, la configurazione e i contenuti prima di passare al controllo del codice sorgente e di distribuirli in un ambiente AEM as a Cloud Service. |
| [Navigazione](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Scopri le nozioni di base per la navigazione in AEM Assets. |
| [Versioni](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Scopri in che modo AEM crea e gestisce le versioni delle risorse. |
| [AEM - [!DNL Magento] Integrazione con [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Questo video illustra la configurazione dell’integrazione tra AEM e [!DNL Magento]. |
| [Introduzione allo stack dell’architettura di AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | L’archetipo del progetto CIF crea un progetto CIF minimo di Adobe Experience Manager (AEM) da usare come punto di partenza per i progetti dei clienti con componenti CIF di base. |
| [Introduzione a OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Introduzione a OSGi, architettura modulare dinamica per le applicazioni Java alla base di Adobe Experience Manager. |
| [Introduzione a Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Introduzione a Java Content Repository (JCR) utilizzato da Adobe Experience Manager. |
| [Introduzione a Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Introduzione a [!DNL Sling], framework web RESTful open-source che fa parte dello stack di tecnologia sottostante di Adobe Experience Manager. |
| [Introduzione ai livelli Author e Publish](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Introduzione ai livelli [!UICONTROL Author] e [!UICONTROL Publish], parte dell’architettura di Adobe Experience Manager. |
| [Introduzione a Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Introduzione alle funzionalità di Dispatcher, parte dell’architettura di AEM. |
| [Introduzione allo sviluppo dei componenti](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Panoramica sullo sviluppo di componenti con Adobe Experience Manager Sites. Include un’introduzione a [!UICONTROL Finestre di dialogo], [!UICONTROL Modelli Sling], [!UICONTROL Script HTL ]e [!UICONTROL Librerie lato client]. |
| [Archetipo del progetto AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | Il progetto AEM contiene tutto il codice e le configurazioni necessari per un’implementazione. L’[!UICONTROL Archetipo del progetto] AEM crea un progetto Adobe Experience Manager minimo basato su best practice, da usare come punto di partenza per i progetti AEM. |
| [Informazioni sui componenti core](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | I [!UICONTROL componenti core] di AEM sono set di componenti standard da utilizzare con Adobe Experience Manager. |
| [Utilizzo di AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Scopri come installare ed eseguire un’istanza locale di Adobe Experience Manager in pochi minuti con [!UICONTROL AEM Quickstart Jar]. |

### Risorse aggiuntive

* [AEM come Cloud Service](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/landing/home.html)
* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://docs.adobe.com/content/help/it-IT/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

## ![Icona](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html)

### Nuove esercitazioni per Campaign Standard {#tutorials-acs}

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Sostituzione profilo - Verifica dei messaggi e-mail tramite profili di destinazione](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Verifica i messaggi e-mail utilizzando la funzione Sostituzione profilo. |

### Risorse aggiuntive per Campaign

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

[!DNL Marketo Engage] è un’applicazione completa per lead management e marketer B2B che intendono trasformare le esperienze dei clienti impegnandosi in ogni fase dei percorsi d’acquisto complessi.

### Aggiornamenti principali di Marketo Engage

Per ulteriori informazioni, consulta le [Note sulla versione](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) di [!DNL Marketo].

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
