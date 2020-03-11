---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 6fa8ddb48734849f15490dce814b1fd8763051d3

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Marzo 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nuove funzioni e correzioni in [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

>[!NOTE]
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: marzo 2020**

Ultimo aggiornamento: 11 marzo 2020

* [Stato del sistema di Adobe](#status)
* [Interfaccia e servizi principali di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [Nuova documentazione ed esercitazioni](#selfhelp)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

(date di rilascio specifiche del prodotto possono variare.)

## ![Icona](/assets/adobe.png) Stato del sistema Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il vostro Adobe ID, potete iscrivervi alle notifiche dell&#39;evento con maggiore granularità, fino all&#39;offerta di prodotti e al livello del componente aggiuntivo. Cerca questa nuova funzionalità nei prodotti Experience Cloud, dove il processo di autoiscrizione presenta le offerte secondarie per i prodotti e i servizi ai quali vuoi iscriverti. Questo miglioramento dovrebbe ridurre in modo significativo il volume di notifiche ricevute e rendere le notifiche più pertinenti per i prodotti e le funzionalità utilizzati.  Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Iscrizione personalizzata per sottoofferte di prodotti | <ul><li>Iscrizione automatica per offerta di prodotti o componenti aggiuntivi per prodotti Experience Cloud.</li><li>Le notifiche di evento ricevute sono pertinenti alle preferenze offerte da prodotti e prodotti.</li></ul> |
| Esperienza personalizzata in base alle preferenze utente | <ul><li>Nelle notifiche e-mail viene utilizzata la preferenza relativa al fuso orario in base alle impostazioni del browser.</li><li>Conferma e-mail inviata al momento della sottoscrizione/annullamento della sottoscrizione con tutte le preferenze selezionate.</li></ul> |
| Migliore distribuzione dei messaggi evento | <ul><li>Cronologia eventi ordinata in base agli aggiornamenti cronologici degli eventi.</li><li>Timestamp della risoluzione dell&#39;evento aggiunto ai problemi principali/secondari chiusi.</li></ul> |

## ![Icona](/assets/experience-cloud.png) dell&#39;interfaccia Experience Cloud e dei servizi di base {#ecloud}

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, tra cui gestione e servizi principali (attributi del cliente, pubblico, trigger, cookie e così via).

| Funzione | Data di rilascio | Descrizione |
| ----|----|---- |
| Admin Tool - visualizza dettagli utente | 26 febbraio 2020 | Gli amministratori possono visualizzare un elenco ordinabile e filtrabile di tutti gli utenti Experience Cloud e dei relativi dettagli nel nuovo Admin Tool. I dettagli utente includono l’accesso ai prodotti, i ruoli e le informazioni sull’ultimo accesso. Consulta la guida [Admin Tool di Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) per ulteriori dettagli. |

### Dominio di prodotto unificato

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificheranno il tuo attuale flusso di lavoro.

Gli aggiornamenti includono:

* Nuovi URL della soluzione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole soluzioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.
* Notifiche migliorate: Il menu a discesa [!UICONTROL Notifiche] ora include due schede, una per le notifiche sui prodotti e una per gli annunci globali dei prodotti.

**Nota:** La pagina [!UICONTROL Feed] è stata rimossa a gennaio 2020. Nel prodotto verrà visualizzato un avviso di funzione rimossa.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## ![Icon](/assets/platform.png) Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Orchestrazione viaggio](#journey)
* [Mobile Services e Mobile SDK](#mobile)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html)   (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

### Orchestrazione viaggio {#journey}

Utilizzando Adobe Experience Platform, potete coordinare i percorsi dei singoli clienti su larga scala tra i canali di esperienze anticipando in modo intelligente le esigenze di ogni individuo in tempo reale, ovunque il percorso lo conduca.

La versione Q1 è stata pubblicata. [Leggi tutto](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

**Risorse aggiuntive**

[Documentazione](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Note](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) sulla versione - Video [introduttivi](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e Mobile SDK {#mobile}

**iOS v4.19.1**

* Generale - È stato risolto un potenziale arresto anomalo quando gli enum [!UICONTROL Swift] venivano inclusi nei dati contestuali per le chiamate di tracciamento.
* [!DNL Target] - L&#39;ID [!DNL Target] sessione verrà ora aggiunto come parametro dei dati contestuali `a.target.sessionId` nell&#39;hit interno [!UICONTROL Analytics-for-Target] inviato ad Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] - L&#39;ID [!DNL Target] sessione verrà ora aggiunto come parametro di dati contestuali &quot;a.target.sessionId&quot; nell&#39;hit [!UICONTROL Analytics-for-Target] interno inviato ad Adobe Analytics.

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

Data di rilascio: **12 marzo 2020**

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

* **Più suite di rapporti in[!UICONTROL Analysis Workspace ]**: Ora puoi inserire dati da più suite di rapporti in un unico progetto[!UICONTROL Analysis Workspace]per visualizzarli in pannelli affiancati.[Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: Questa funzione consente di pubblicare i segmenti in Experience Cloud entro 8 ore (anziché entro 48 ore). [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - Modello** Esercitazione formazione: Questo nuovo modello standard illustra la terminologia e i passaggi comuni per la creazione della prima analisi in Workspace. È disponibile come modello standard nel modale [!UICONTROL Nuovo progetto] e sostituisce il progetto di esempio esistente oggi per i nuovi utenti che non hanno altri progetti nel loro elenco.

#### Correzioni

* È stato risolto un problema in [!UICONTROL Reporting e analisi] che impediva il download `.xls` dei report. Questo problema ha interessato i clienti che utilizzano valute diverse da dollaro statunitense ed euro. (AN-206541, AN-204008)
* L&#39;implementazione di una nuova shell ha risolto diversi problemi dei clienti relativi al passaggio a un&#39;organizzazione Experience Cloud.(AN-200844, AN-186920)
* È stato risolto un problema che causava la mancata inclusione di un&#39;analisi approfondita sull&#39;elemento di riga _Non specificato_ (o su altri elementi della riga di reporting) nei filtri di ricerca _Non specificato (Nessuno)_ , senza risultati nella suddivisione.
* È stato risolto un problema che si verificava quando si utilizzava una dimensione classificata, i totali delle metriche di entrata o uscita non corrispondevano al totale degli elementi di riga in una suddivisione.
* È stato corretto un problema a causa del quale i primi e gli ultimi modelli di tocco in Attribution IQ non calcolavano correttamente il credito per alcuni elementi di riga in alcune dimensioni predefinite.
* È stato risolto un problema che causava la restituzione di risultati errati durante la suddivisione di una dimensione data per un&#39;altra dimensione data.
* È stato risolto un problema a causa del quale talvolta le metriche di entrata o uscita venivano conteggiate in modo non corretto se applicate a &quot;Non specificato&quot; in un report di dimensioni classificate.

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta   o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Impostazione EOL del livello **[!UICONTROL di]** conversione | 3 marzo 2020 | L’impostazione del livello [di](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversione non funzionante in Strumenti **[!UICONTROL di]amministrazione > Suite[!UICONTROL di]rapporti > Impostazioni[!UICONTROL account]** generali verrà rimossa dall’interfaccia utente il 12 marzo 2020. |
| EOL di archivio **[!UICONTROL dashboard]** | 3 marzo 2020 | L&#39;impostazione **[!UICONTROL Visualizza archivio]** in **[!UICONTROL Gestione dashboard]** in [!UICONTROL Reporting e analisi] non sarà più disponibile dal 12 marzo 2020. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | A partire dal 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota:** questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione _Impedisci il rilevamento intersito_ nelle preferenze relative alla privacy di , i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. [!DNL Safari] You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versione 2.20.0 è stata rilasciata il 5 marzo 2020.

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni e aggiornamenti di Audience Manager:

### Fixes and improvements {#aam-fixes-and-improvements}

* È stato corretto un bug a causa del quale i clienti non potevano aggiornare il nome del segmento a causa di un’autorizzazione RBAC [!UICONTROL VIEW_ALL_DESTINATIONS]mancante. L’autorizzazione [!UICONTROL VIEW_ALL_DESTINATIONS] non deve essere necessaria per aggiornare un segmento. Per ulteriori informazioni sulle autorizzazioni RBAC, consultate [Amministrazione (controlli RBAC)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* È stato corretto un bug in [Esplora](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) dati a causa del quale alcuni clienti non potevano visualizzare il contenuto nella sezione delle informazioni di base e gli operatori nel generatore di espressioni durante la creazione di caratteristiche basate su segnali di [!UICONTROL Esplora] dati. (AAM-53130)
* È stato corretto un bug a causa del quale alcuni clienti non potevano caricare l’interfaccia [!UICONTROL Audience Marketplace] . (AAM-52070)
* È stato corretto un bug nell’API  Segments a causa del quale, a causa di alcuni segmenti senza descrizione, l’interfaccia si bloccava quando gli utenti tentavano di accedere a tali segmenti e gli utenti dovevano allontanarsi da quella pagina. (AAM-53071)
* Numerosi miglioramenti a livello di accessibilità nell&#39;interfaccia. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058,AAM-493 (92)

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (6.5.4.0 rilasciato il 5 marzo 2020) è un aggiornamento importante che include nuove funzioni, miglioramenti fondamentali per i clienti, prestazioni migliorate, stabilità e sicurezza, rilasciato a partire dalla disponibilità generale di AEM 6.5, aprile 2019.
   * [Novità in Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versioni finali di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (6.4.8.0 rilasciato il 5 marzo 2020) è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.4, aprile 2018.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 rilasciato il 5 marzo 2019) è un aggiornamento importante che include correzioni di problemi fondamentali per il cliente, introdotte successivamente alla data di disponibilità generale di AEM 6.3, aprile 2017.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 rilasciato il 5 marzo 2020) modifica il modo in cui Risorse AEM è configurato con [!UICONTROL Brand Portal.] Inoltre, la release include altri miglioramenti e correzioni di bug.
   * [Note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Aiuto e documentazione

* **AEM come servizio cloud - Autorizzazioni basate su ruoli**

   Cloud Manager dispone di ruoli preconfigurati con le autorizzazioni appropriate. A ciascun ruolo sono associate autorizzazioni specifiche, attività preconfigurate o autorizzazioni specifiche. L&#39;argomento della guida Autorizzazioni [basate sul](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) ruolo identifica le funzioni disponibili e i ruoli che possono eseguirle.

* **AEM come servizio cloud - Dispatcher**

   Le sezioni di annullamento della validità della cache del [dispatcher e CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) e del dispatcher [esplicito](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) sono state aggiornate per chiarire le opzioni disponibili e come funzionano.

* **Configurare AEM Assets con Brand Portal**

   AEM Assets è ora configurato con [!UICONTROL Brand Portal] tramite Adobe I/O, che fornisce un token IMS per l&#39;autorizzazione del tenant del Brand Portal. In precedenza, era stato configurato nell&#39;interfaccia classica tramite il gateway OAuth [!UICONTROL legacy.]
Consultate [Configurare AEM Assets con il Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM come servizio cloud - Smart Crop in Dynamic Media**

   Una nuova opzione è disponibile in AEM come servizio Cloud quando si utilizza SmartCrop nel componente per file multimediali dinamici:

   **Abilita corrispondenza** proporzioni: selezionate questa opzione per consentire a Contenuti multimediali dinamici di scegliere una rappresentazione di ritaglio intelligente che corrisponda al meglio alle proporzioni dell&#39;immagine originale.
Consultate [Utilizzo di Smart Crop](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Community

* **Webinar di AEM Skill Builder**

   * AEM Sites - A partire dal 17 marzo 2020, vengono illustrati gli elementi di base per l’authoring dei contenuti e i concetti e le operazioni fondamentali di AEM Sites. [Registrati ora](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * Risorse AEM - A partire dal 19 marzo 2020, affina le tue competenze di gestione delle risorse digitali, oltre a conoscere le basi del portale del marchio, dei supporti [!UICONTROL dinamici,] del collegamento delle [!UICONTROL risorse e altro ancora] . [Registrati ora](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

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

## ![Icona](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Campaign Classic

* [Aggiornamento Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)      - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Aggiornato il 10 febbraio 2020 per la versione dell’8 febbraio:

| Visualizzazione | Funzione |
|------|---------|
| [!UICONTROL Portfolio] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. La stessa offerta viene applicata a tutti gli annunci di un gruppo di annunci. I dati per le campagne Japan Display Network sono inclusi nelle simulazioni per il portfolio. |
| [!UICONTROL Cerca] > [!UICONTROL Bulksheet] | Ora puoi creare, modificare ed eliminare gli annunci adattabili alla rete di ricerca di Google (RSA, Responsive Search Ads) utilizzando i bulksheet. In precedenza, il supporto era disponibile solo tramite l’interfaccia standard di gestione campagne in **[!UICONTROL Ricerca]** > **[!UICONTROL Campagne]** |
| [!UICONTROL Cerca] > [!UICONTROL Campagne, Rapporti] | Le metriche di prominenza di Google Ads `Impr. (Abs. Top) %` e `Impr. (Top) %` sono ora disponibili in tutti i report semplici e in tutte le visualizzazioni di gestione campagne a livello di entità, eccetto per le campagne Shopping con i gruppi di prodotti, nei report [!UICONTROL Campaign Daily Impression Share (Quota impressioni campagna giornaliera)] e [!UICONTROL Keyword Daily Impression Share (Quota impressioni parola chiave giornaliera)], nelle visualizzazioni delle etichette e dei vincoli. |

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] è una soluzione completa per i responsabili della gestione dei lead e per gli esperti di marketing B2B che desiderano trasformare l’esperienza dei clienti seguendo tutte le fasi dei processi di acquisto più complessi.

### Aggiornamenti principali di Marketo Engagement

Data di rilascio: 21 febbraio 2020

* **Azione di flusso _Change Owner in Microsoft_ di Microsoft Dynamics**: cambia il proprietario di lead o contatti direttamente da Marketo Engage.
* **Miglioramenti alle chiamate API:**
   * API per gestione utenti
   * API per schemi di oggetti personalizzati
   * API per le regole di reindirizzamento delle pagine di destinazione
* **Memorizzazione in cache di descrittori moduli:** miglioramenti alle pagine di destinazione e ai moduli.

Consulta le note sulla versione [!DNL Marketo] di [febbraio 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) per ulteriori informazioni.

### Funzionalità in arrivo

Nel corso del trimestre verranno presentate le seguenti funzionalità:

| Funzione | Descrizione |
|------|---------|
| [!DNL Bizible] | <ul><li>Nuova segmentazione basata sugli account</li><li>Possibilità di salvare filtri specifici per dashboard</li><li>Esportazione dashboard Bizible in formato PDF</li></ul> |
| Sales Connect | Aggiornamenti/miglioramenti relativi a finestre di composizione e centri di comando |

### Annunci

**Success Center di Marketo Engage:** lancio a febbraio 2020. Success Center è un centro di assistenza interno al prodotto che consente di effettuare ricerche nei documenti sui prodotti e nella community, avviare guide informative, accedere ai contenuti di adozione e altro ancora. Nota: questa funzionalità verrà lanciata come versione beta in Australia e Nuova Zelanda e verrà implementata nel Nord America in un secondo momento nel corso del trimestre.

### Funzionalità deprecate

* **Parametro “_method” della risorsa API:** dopo settembre 2020, Asset API Endpoints non accetterà più “_method” per passare i parametri di query nel corpo di un POST per disabilitare le limitazioni relative alla lunghezza degli URI.
* **Supporto in Internet Explorer:** a partire dalla versione di luglio del 31 luglio 2020, Internet Explorer non supporterà più l’interfaccia utente di Marketo Engage.

Per leggere le note precedenti e complessive, consulta le [note sulla versione Marketo](https://docs.marketo.com/x/CgA6Ag).

## ![Icona](/assets/experience-cloud.png) Nuova documentazione ed esercitazioni {#selfhelp}

Articoli e video nuovi e recenti di supporto autonomo. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Soluzione | Contenuto | Descrizione |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Video - [Creazione di più categorie e pagine di prodotti](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Scopri come creare un progetto CIF (Adobe Experience Manager) minimo come punto di partenza per i progetti dei clienti che utilizzano i componenti CIF di base. Applica ai componenti il tema e lo stile CSS ed esamina un nuovo progetto AEM CIF, generato dall’archetipo. Inoltre, scoprite come sono organizzati CSS e JavaScript utilizzati dai componenti CIF di base. |
| [!UICONTROL Moduli di AEM] | Articolo - [Autenticazione in AEM Author tramite OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Scoprite come configurare l&#39;app sul portale OKTA e le impostazioni normalmente utilizzate per la registrazione di una nuova applicazione. |
| [!UICONTROL AEM Commerce] | Esercitazione - [Personalizza componenti CIF di base](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Rivedete diversi punti di estensione forniti da CIF Core Components e AEM in generale. CIF Core Components fornisce un set standard di componenti Commerce che possono essere utilizzati per accelerare un progetto che integra soluzioni Adobe Experience Manager (AEM) e Magento. |
| [!DNL Adobe Campaign] - Destinazioni di pubblico | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Crea un pubblico in Campaign Standard utilizzando Adobe [!UICONTROL Experience Platform Segment Builder]. Puoi accedere a questa funzione direttamente in Adobe Campaign Standard tramite i moduli [!UICONTROL Audiences] . |
| [!DNL Adobe Campaign] - Destinazioni di pubblico | Video - [Attivazione del pubblico della piattaforma Adobe Experience in un flusso di lavoro di marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Scopri come attivare [!UICONTROL Data Services Query Audience] all&#39;interno di un flusso di lavoro utilizzando l&#39;attività [!UICONTROL Leggi pubblico] . |
| [!DNL Adobe Campaign] | Esercitazione - Notifica [push con Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Inviare notifiche push personalizzate e segmentate ai dispositivi mobili iOS e Android. Questa esercitazione illustra i passaggi necessari per inviare notifiche push da Adobe Campaign e ricevere queste notifiche nell&#39;app Android. |
| [!DNL Adobe Campaign] | Video - [Creare una notifica push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Crea una notifica push in Adobe Campaign Standard. Puoi inviare notifiche push personalizzate e segmentate ai dispositivi mobili iOS e Android. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - [Controllare lo stato di un processo di inserimento dei dati](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Scopri come verificare lo stato di un processo di assimilazione dei dati e se i dati sono stati trasferiti da Adobe Campaign Standard ad Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - [Modificare la mappatura dei dati](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Scopri come controllare lo stato e modificare la mappatura dei dati. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - Eventi esperienza [Mappa](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Scopri come mappare gli eventi esperienza in Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - [Mappare risorse personalizzate](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Scopri come mappare diversi tipi di dati tra Adobe Campaign Standard e Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - [Informazioni sul connettore dati della piattaforma Adobe Experience](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Scopri come rendere i tuoi dati disponibili su Adobe Experience Platform mappando i dati XTK (i dati acquisiti in Campaign) su Experience Data Model (XDM) su Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video - [Mappa dei dati della tabella dei valori iniziali](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Scopri come mappare i dati e i profili di test con Adobe Experience Platform. |
| [!DNL Adobe Campaign]- Destinazioni di pubblico | Video - [Modificare la dimensione di targeting di una distribuzione per un pubblico piattaforma](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Scopri come modificare la dimensione di targeting di una distribuzione per un pubblico piattaforma al di fuori della tabella del profilo principale in Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Video - [Gestione dei grandi dati su Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Utilizza il connettore Snowflake in Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Destinazioni di pubblico | Articolo - Destinazioni [pubblico (BETA) - Panoramica](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Scopri come sfruttare dati di profilo centralizzati e consolidati da Adobe Experience Platform per campagne di marketing in Adobe Campaign Standard. |
| [!DNL Adobe Target] - SDK di Mobile | Esercitazione - [Personalizzare le esperienze app con Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implementa Adobe Target nella tua app Android. Convalida la configurazione dell&#39;SDK Mobile Services e implementa [!DNL Target] richieste come preacquisizione di contenuto, richieste di blocco e altro ancora. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Al Summit 2019 potrete vedere i video della &quot;super session&quot; high tech. |
| Adobe Analytics | Video - [Introduzione alle metriche calcolate nell&#39;analisi del percorso del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Approfondisci le nozioni di base sulla creazione di metriche [!UICONTROL calcolate] in [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Guarda le clip curate dalla sessione di viaggio e ospitalità al Summit 2019. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Guarda i video della sessione retail al Summit 2019. |
| Adobe Analytics | Video - Caso di utilizzo [cliente: Accent Group investe nell&#39;esperienza cliente per stimolare le vendite](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Scopri in che modo Accent Group utilizza Adobe Experience Cloud per creare esperienze digitali senza soluzione di continuità. |
| Adobe Analytics | Video - Caso di utilizzo [cliente: ServiceNow ottiene le informazioni giuste per connettersi con i potenziali clienti](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Scopri come [!DNL ServiceNow] ottenere dati fruibili dai suoi canali di marketing e incrementare il ROI sulla ricerca a pagamento pubblicitaria con Adobe Advertising Cloud e Adobe Analytics. |
| Adobe Analytics | Video - [Adobe Analytics - È più di dati è informazione dei clienti](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Scopri ulteriori informazioni sul marketing basato sui dati e su come sfruttare la maturità dell&#39;analisi dai dati alle informazioni fino alle azioni. |
| Adobe Analytics | Video - [Adobe Sensei e Adobe Analytics - Versione estesa](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Visualizza le funzioni chiave di Adobe Analytics [!DNL Sensei,] tra cui Rilevamento [!UICONTROL anomalie,] Analisi [!UICONTROL contributi,] Avvisi [!UICONTROL intelligenti,] [!UICONTROL Clustering,] IQ  [!UICONTROL segmento, Modellazione delle tendenze e delle tendenze.] |
| Adobe Analytics | Video - [Come Adobe Analysis Workspace Può Cambiare La Tua Azienda](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Scopri come eseguire analisi ad hoc, analisi flessibile, analisi per coorte e analisi di abbandono utilizzando [!UICONTROL Analysis Workspace]. È inoltre possibile condividere l&#39;ambiente di lavoro di analisi con tutti gli utenti dell&#39;azienda, e la sua funzione di trascinamento consente a tutti di analizzare i dati in modo semplice e ottenere informazioni rapidamente. |
| Adobe Analytics | Video - Caso di utilizzo [cliente: Home Depot Innovazione con la gestione dell&#39;esperienza dei clienti](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Scopri come [!DNL Home Depot] utilizzano le soluzioni Adobe per creare fidelizzazione e soddisfazione dei clienti con un&#39;esperienza di acquisto personalizzata e personalizzata. |
| Adobe Analytics | Presentazione - [Informazioni sull&#39;analisi del percorso del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Scopri in che modo Adobe [!UICONTROL Customer Journey Analytics], un servizio di applicazione basato su [!DNL Adobe Experience Platform], trasferisce [!UICONTROL Analysis Workspace] nella piattaforma Experience. Questa funzione consente l&#39;analisi multicanale su qualsiasi set di [!DNL Adobe Experience Platform] dati. |
| Adobe Analytics | Video - Attribuzione [tra canali in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Scopri come utilizzare le visualizzazioni per mostrare l&#39;attribuzione (con un accredito) tra i canali in [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Articolo - Suggerimenti [del cliente per continuare il percorso di apprendimento di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Scopri tre clienti Adobe che hanno suggerimenti e consigli su come ottenere il massimo valore da Adobe Analytics. |
| Adobe Analytics | Video - [Creare visualizzazioni tra canali in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Scopri come [!UICONTROL Customer Journey Analytics] consente di creare visualizzazioni che includono dati da più set di dati su più canali, inclusa l&#39;unione dei dati per visitatore. |
| Adobe Analytics | Video - [Sposta le metriche calcolate da Adobe Analytics all&#39;analisi del percorso del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Trova suggerimenti per ricreare le metriche [!UICONTROLCcalcolate] di Analytics in [!UICONTROL Customer Journey Analytics]. |
