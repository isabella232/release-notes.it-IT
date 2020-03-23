---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: ht
source-git-commit: e73b72e29cc5b953fe908623d54a9daf486a7ffc

---


# Note sulla versione di Adobe Experience Cloud - marzo 2020

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
* [!DNL Analytics](#analytics) - Data di rilascio: **12 marzo 2020**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [Nuovi documentazione e tutorial](#selfhelp)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/it-IT/experience-cloud/user-guides/home.html).

(Le date di rilascio del prodotto potrebbero variare).

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Cerca questa nuova funzionalità nei prodotti Experience Cloud, dove il processo di abbonamento automatico presenta le offerte secondarie per i prodotti e i servizi ai quali vuoi abbonarti. Questo miglioramento dovrebbe ridurre in modo significativo il volume di notifiche che ricevi e renderle più pertinenti ai prodotti e alle funzionalità che utilizzi. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Abbonamento automatico personalizzato per offerte secondarie di prodotti | <ul><li>Abbonamento automatico per offerta di prodotti o componenti aggiuntivi per prodotti Experience Cloud.</li><li>Le notifiche degli eventi ricevute sono pertinenti ai tuoi prodotti e alle tue preferenze relative a offerte di prodotti.</li></ul> |
| Esperienza personalizzata in base alle preferenze dell’utente | <ul><li>Nelle notifiche via e-mail viene utilizzata la preferenza relativa al fuso orario in base alle impostazioni del browser.</li><li>Una conferma via e-mail con tutte le preferenze selezionate viene inviata quando si attiva/annulla l’abbonamento.</li></ul> |
| Migliore distribuzione dei messaggi evento | <ul><li>La cronologia degli eventi viene ordinata in base agli aggiornamenti cronologici degli eventi.</li><li>La data e l’ora della risoluzione dell’evento sono state aggiunte ai problemi principali/secondari chiusi.</li></ul> |

## ![Icona](/assets/experience-cloud.png) Interfaccia e servizi principali di Experience Cloud {#ecloud}

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, tra cui gestione e servizi principali (attributi del cliente, pubblico, trigger, cookie e così via).

| Funzione | Data di rilascio | Descrizione |
| ----|----|---- |
| Admin Tool - visualizza dettagli utente | 26 febbraio 2020 | Gli amministratori possono visualizzare un elenco ordinabile e filtrabile di tutti gli utenti Experience Cloud e dei relativi dettagli nel nuovo Admin Tool. I dettagli utente includono l’accesso ai prodotti, i ruoli e le informazioni sull’ultimo accesso. Consulta la guida [Admin Tool di Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) per ulteriori dettagli. |

### Dominio di prodotto unificato

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificheranno il tuo attuale flusso di lavoro.

Gli aggiornamenti includono:

* Nuovi URL della soluzione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole soluzioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.
* Notifiche migliorate: Il menu a discesa [!UICONTROL Notifiche] ora include due schede, una per le notifiche sui prodotti e una per gli annunci globali dei prodotti.

**Nota:** La pagina [!UICONTROL Feed] è stata rimossa a gennaio 2020. Nel prodotto verrà visualizzato un avviso di funzione rimossa.

Per la documentazione sul prodotto, consulta la guida di [Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

## ![Icona](/assets/platform.png) Experience Platform {#platform}

Note sulla versione di [!UICONTROL Experience Platform], [!UICONTROL Experience Platform Launch], [!UICONTROL Identity Service], Journey Orchestration, Mobile Services e bollettini sulla sicurezza.

* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Journey Orchestration](#journey)
* [Mobile Services e Mobile SDK](#mobile)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html)  (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html).

### Journey Orchestration {#journey}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

È stata pubblicata la versione Q1. [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Risorse aggiuntive per Journey Orchestration

[Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services e Mobile SDK {#mobile}

**iOS v4.19.1**

* Generale – Risolto un potenziale arresto anomalo quando gli enum di [!UICONTROL Swift] vengono inclusi nei dati contestuali per le chiamate di tracciamento.
* [!DNL Target] – L’ID della [!DNL Target] sessione verrà ora aggiunto come parametro dei dati contestuali `a.target.sessionId` nel risultato interno di [!UICONTROL Analytics-for-Target] inviato ad Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] – L’ID della [!DNL Target] sessione verrà ora aggiunto come parametro dei dati contestuali “a.target.sessionId” nel risultato interno di [!UICONTROL Analytics-for-Target] inviato ad Adobe Analytics.

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

Data di rilascio: **12 marzo 2020**

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

* **Più suite di rapporti in [!UICONTROL Analysis Workspace ]**: ora puoi inserire dati provenienti da più suite di rapporti in un unico progetto [!UICONTROL Analysis Workspace] per visualizzarli in pannelli vicini. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: questa funzione consente di pubblicare segmenti in Experience Cloud entro 8 ore (anziché 48 ore come in precedenza). [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - Modello di tutorial di formazione**: questo nuovo modello standard illustra la terminologia e i passaggi comuni per la creazione della tua prima analisi in Workspace. È disponibile come modello standard nel modale [!UICONTROL Nuovo progetto] e sostituisce il progetto di esempio attuale per i nuovi utenti che non hanno altri progetti nel loro elenco.

#### Correzioni

* Corretto un problema in [!UICONTROL Reports &amp; Analytics] che impediva il download `.xls` dei report. Questo problema ha interessato i clienti che utilizzano valute diverse da dollaro statunitense ed euro. (AN-206541, AN-204008)
* L’implementazione di una nuova shell ha risolto diversi problemi dei clienti relativi al passaggio tra organizzazioni di Experience Cloud. (AN-200844, AN-186920)
* Corretto un problema a causa del quale l’esecuzione di un raggruppamento sulla riga _Non specificato_ (o su altre righe di reporting) senza includere _Non specificato (Nessuno)_ nei filtri di ricerca non restituiva alcun risultato nel raggruppamento.
* Corretto un problema che si verificava quando si utilizzava una dimensione classificata e a causa del quale i totali delle metriche di entrata o uscita non corrispondevano al totale della riga in un raggruppamento.
* Corretto un problema a causa del quale i modelli di primo e ultimo punto di contatto in Attribution IQ non calcolavano correttamente il credito per alcune righe in alcune dimensioni predefinite.
* Corretto un problema a causa del quale la suddivisione di una dimensione di data in un’altra restituiva risultati errati.
* Corretto un problema a causa del quale talvolta le metriche di entrata o uscita venivano conteggiate in modo errato se applicate a “Non specificato” in un report di dimensioni classificate.

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Impostazione di fine del ciclo vita del **[!UICONTROL Livello di conversione]** | 3 marzo 2020 | L’impostazione non funzionante del [Livello di conversione](https://docs.adobe.com/content/help/it-IT/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Admin Tools (Strumenti di amministrazione)] > [!UICONTROL Report Suite (Suite di rapporti)] > [!UICONTROL General Account Settings (Impostazioni generali dell’account)]** sarà rimossa dall’interfaccia utente il 12 marzo 2020. |
| Fine del ciclo vita dell’**[!UICONTROL Archivio del dashboard]** | 3 marzo 2020 | L’impostazione **[!UICONTROL View Archive (Visualizza archivio)]** alla voce **[!UICONTROL Manage Dashboards (Gestione dashboard)]** in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile dal 12 marzo 2020. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | A partire dal 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota:** questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione _Impedisci il rilevamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. Potrai utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti [!DNL Safari].</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/it-IT/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html). La versione 2.20.0 è stata rilasciata il 5 marzo 2020.

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni e aggiornamenti di Audience Manager:

| Funzione | Descrizione |
| -----------| ---------- |
| [Foglio di lavoro Strumenti per la gestione di massa](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | È disponibile una nuova versione del foglio di lavoro che risolve un problema che alcuni clienti riscontravano durante la creazione di modelli algoritmici con il sistema operativo Windows a 64 bit. Scarica la versione più recente [qui](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm). |

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* Corretto un bug per cui i clienti non potevano aggiornare il nome del segmento a causa di un’autorizzazione RBAC [!UICONTROL VIEW_ALL_DESTINATIONS] mancante. L’autorizzazione [!UICONTROL VIEW_ALL_DESTINATIONS] non dovrebbe essere necessaria per aggiornare un segmento. Per ulteriori informazioni sulle autorizzazioni RBAC, consulta [Amministrazione (controlli RBAC)](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Corretto un bug in [Data Explorer](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) che impediva ad alcuni clienti di visualizzare il contenuto della sezione informazioni di base e gli operatori nel generatore di espressioni durante la creazione di caratteristiche basate su segnali di [!UICONTROL Data Explorer]. (AAM-53130)
* Corretto un bug che impediva ad alcuni clienti di caricare l’interfaccia di [!UICONTROL Audience Marketplace]. (AAM-52070)
* Corretto un bug nell’[!UICONTROL API dei segmenti] per cui, a causa di alcuni segmenti senza descrizione, l’interfaccia si bloccava quando gli utenti tentavano di accedere a tali segmenti ed essi erano costretti a chiudere la pagina. (AAM-53071)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-49392)

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **AEM 6.5.4.0**
AEM 6.5, Service Pack 4.0 (6.5.4.0, rilasciato 5 marzo 2020), è un aggiornamento importante che include nuove funzionalità, miglioramenti fondamentali per i clienti, prestazioni, stabilità e sicurezza migliorate introdotti successivamente alla data di disponibilità generale di AEM 6.5 di aprile 2019.
   * [Novità in Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/it-IT/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Note sulla versione](https://helpx.adobe.com/it/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Rilascio delle versioni finali di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4 Service Pack 8.0 (6.4.8.0, rilasciato 5 marzo 2020), è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.4 di aprile 2018.
   * [Note sulla versione](https://helpx.adobe.com/it/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3 Service Pack 3–Cumulative Fix Pack 8 (6.3.3.8 rilasciato il 5 marzo 2019), è un aggiornamento importante che include correzioni fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.3, aprile 2017.
   * [Note sulla versione](https://helpx.adobe.com/it/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   Brand Portal di AEM Assets 6.4 Service Pack 6 (6.4.6 rilasciato il 5 marzo 2020) modifica il modo in cui AEM Assets viene configurato con [!UICONTROL Brand Portal.] Inoltre, la release include altri miglioramenti e correzioni di bug.
   * [Note sulla versione](https://docs.adobe.com/content/help/it-IT/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Aiuto e documentazione

* **AEM come Cloud Service: autorizzazioni basate su ruoli**

   Cloud Manager dispone di ruoli preconfigurati con le autorizzazioni appropriate. A ciascun ruolo sono associate autorizzazioni specifiche e attività o autorizzazioni preconfigurate. La guida [Role Based Permissions (Autorizzazioni basate sul ruolo)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) identifica le funzioni disponibili e i ruoli che possono eseguirle.

* **AEM come Cloud Service – Dispatcher**

   Le sezioni [Dispatcher e CDN](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) e [Annullamento della validità della cache del dispatcher esplicito](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) sono state aggiornate per chiarire quali siano le opzioni disponibili e come funzionino.

* **Configurare AEM Assets con Brand Portal**

   AEM Assets è ora configurato con [!UICONTROL Brand Portal] tramite Adobe I/O, che fornisce un token IMS per l’autorizzazione del tenant del Brand Portal. In precedenza, era configurato nell’interfaccia Classica tramite la [!UICONTROL versione precedente del gateway OAuth.]
Consulta [Configure AEM Assets with Brand Portal (Configurare AEM Assets con Brand Portal)](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM come Cloud Service: ritaglio intelligente in elementi multimediali dinamici**

   Una nuova opzione è disponibile in AEM come Cloud Service quando utilizzi il ritaglio intelligente nel componente elementi multimediali dinamici:

   **Abilita corrispondenza proporzioni**: seleziona questa opzione per consentire agli elementi multimediali dinamici di scegliere un rendering di ritaglio intelligente che corrisponda al meglio alle proporzioni dell’immagine originale.
Consulta [When working with Smart Crop (Utilizzo di Smart Crop)](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Community

* **Webinar di AEM Skill Builder**

   * AEM Sites: a partire dal 17 marzo 2020, apprendi gli elementi di base dell’authoring di contenuti e i concetti e le operazioni fondamentali di AEM Sites. [Registrati ora](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets: a partire dal 19 marzo 2020, affina le tue competenze di gestione delle risorse digitali, in più, apprendi le basi di Brand Portal, degli [!UICONTROL Dynamic Mediaa], di [!UICONTROL Asset Link] e altro ancora. [Registrati ora](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Risorse aggiuntive

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

### Campaign Classic

* [Aggiornamento 19.1.4 di Campaign Classic](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/it/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  - [Pianificazione rilascio](https://helpx.adobe.com/it/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/it/support/campaign/classic.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.translate.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Aggiornato il 10 febbraio 2020 per la versione dell’8 febbraio:

| Visualizzazione | Funzione |
|------|---------|
| [!UICONTROL Portfolio] | Ora puoi aggiungere campagne [!DNL Yahoo!] Yahoo Japan Display Network (YDN) ai portfolio per ottimizzare il budget delle campagne e le offerte dei gruppi di annunci. La stessa offerta viene applicata a tutti gli annunci di un gruppo di annunci. I dati per le campagne Yahoo Japan Display Network sono inclusi nelle simulazioni per il portfolio. |
| [!UICONTROL Ricerca] > [!UICONTROL Bulksheet] | Ora puoi creare, modificare ed eliminare gli annunci adattabili alla rete di ricerca di Google (RSA, Responsive Search Ads) utilizzando i bulksheet. In precedenza, il supporto era disponibile solo tramite l’interfaccia standard di gestione campagne in **[!UICONTROL Ricerca]** > **[!UICONTROL Campagne]** |
| [!UICONTROL Ricerca] > [!UICONTROL Campagne, Report] | Le metriche di prominenza di Google Ads `Impr. (Abs. Top) %` e `Impr. (Top) %` sono ora disponibili in tutti i report semplici e in tutte le visualizzazioni di gestione campagne a livello di entità, eccetto per le campagne Shopping con i gruppi di prodotti, nei report [!UICONTROL Campaign Daily Impression Share (Quota impressioni campagna giornaliera)] e [!UICONTROL Keyword Daily Impression Share (Quota impressioni parola chiave giornaliera)], nelle visualizzazioni delle etichette e dei vincoli. |

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

## ![Icona](/assets/experience-cloud.png) Nuovi documentazione e tutorial {#selfhelp}

Articoli e video di auto-aiuto nuovi e recenti. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Soluzione | Contenuto | Descrizione |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Video: [creare più categorie e pagine di prodotti](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Scopri come creare un semplice progetto CIF di Adobe Experience Manager (AEM) come punto di partenza per i progetti dei clienti che utilizzano i componenti CIF di base. Applica ai componenti il tema e lo stile CSS ed esamina un nuovo progetto AEM CIF generato dall’archetipo. Inoltre, scopri come sono organizzati CSS e JavaScript utilizzati dai componenti CIF di base. |
| [!UICONTROL AEM Forms] | Articolo: [effettuare l’autenticazione in AEM Author tramite OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Scopri come configurare l’app sul portale OKTA e le impostazioni normalmente utilizzate nella registrazione di una nuova applicazione. |
| [!UICONTROL AEM Commerce] | Tutorial: [personalizza componenti CIF di base](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Esamina diversi punti di estensione forniti dai componenti CIF di base e da AEM in generale. I componenti CIF di base forniscono un set standard di componenti Commerce che possono essere utilizzati per accelerare un progetto che integra soluzioni Adobe Experience Manager (AEM) e Magento. |
| [!DNL Adobe Campaign] - Audience Destinations | Video: [crea un pubblico...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Crea un pubblico in Campaign Standard utilizzando Adobe [!UICONTROL Experience Platform Segment Builder (Generatore di segmenti)]. Puoi accedere a questa funzione direttamente in Adobe Campaign Standard tramite i moduli [!UICONTROL Audiences]. |
| [!DNL Adobe Campaign] - Audience Destinations | Video: [attivare audience di Adobe Experience Platform in un flusso di lavoro di marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Scopri come attivare la [!UICONTROL Data services query audience (audience di query dei servizi di dati)] all’interno di un flusso di lavoro utilizzando l’attività [!UICONTROL Read audience (Analizza pubblico)]. |
| [!DNL Adobe Campaign] | Tutorial: [notifica push con Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Invia notifiche push personalizzate e segmentate ai dispositivi mobili iOS e Android. Questa esercitazione ti illustrerà i passaggi necessari per inviare notifiche push da Adobe Campaign e riceverle nella tua app Android. |
| [!DNL Adobe Campaign] | Video: [creare una notifica push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Crea una notifica push in Adobe Campaign Standard. Puoi inviare notifiche push personalizzate e segmentate ai dispositivi mobili iOS e Android. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [controllare lo stato di un processo di assimilazione di dati](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Scopri come controllare lo stato di un processo di assimilazione di dati e se i dati sono stati assimilati da Adobe Campaign Standard in Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [modificare la mappatura dei dati](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Scopri come controllare lo stato e modificare la mappatura dei dati. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [mappare eventi esperienza](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Scopri come mappare gli eventi esperienza in Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [mappare risorse personalizzate](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Scopri come mappare diversi tipi di dati tra Adobe Campaign Standard e Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [comprendere il connettore dati di Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Scopri come rendere i tuoi dati disponibili su Adobe Experience Platform mappando i dati XTK (dati acquisiti in Campaign) su Experience Data Model (XDM) in Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Connettore dati AEP | Video: [mappare i dati della tabella dei valori iniziali](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Scopri come mappare i dati dei valori iniziali e i profili di prova con Adobe Experience Platform. |
| [!DNL Adobe Campaign]- Audience Destinations | Video: [modificare la dimensione di targeting di una distribuzione per un pubblico di Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Scopri come modificare la dimensione di targeting di una distribuzione per un pubblico di Platform al di fuori della tabella del profilo principale in Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Video: [gestione di big data su Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Sfrutta il connettore Snowflake in Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Audience Destinations | Articolo: [panoramica di Audience Destinations (BETA)](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Scopri come sfruttare dati di profilo centralizzati e consolidati da Adobe Experience Platform per campagne di marketing in Adobe Campaign Standard. |
| [!DNL Adobe Target] - Mobile SDK | Tutorial: [personalizzare le esperienze dell’app con Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implementa Adobe Target nella tua app Android. Convalida la configurazione dell’SDK Mobile Services e implementa richieste [!DNL Target] come preacquisizione di contenuto, richieste di blocco e altro ancora. |
| Adobe Analytics | Video: [super sessione di Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Guarda clip selezionate della “super sessione” high tech al Summit 2019. |
| Adobe Analytics | Video: [introduzione alle metriche calcolate nell’analisi del customer journey](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Apprendi le nozioni di base sulla creazione di [!UICONTROL metriche calcolate] nell’[!UICONTROL analisi del customer journey]. |
| Adobe Analytics | Video: [super sessione di Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Guarda clip selezionate della sessione su viaggi e ospitalità al Summit 2019. |
| Adobe Analytics | Video: [super sessione di Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Guarda clip selezionate della sessione sulla vendita al dettaglio al Summit 2019. |
| Adobe Analytics | Video - [Caso di utilizzo di un cliente: Accent Group investe nella customer experience per stimolare le vendite](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Scopri in che modo Accent Group utilizza Adobe Experience Cloud per creare esperienze digitali impeccabili. |
| Adobe Analytics | Video - [Caso di utilizzo di un cliente: ServiceNow ottiene le informazioni giuste per connettersi con i potenziali clienti](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Scopri come [!DNL ServiceNow] ottiene dati actionable dai suoi canali di marketing e incrementa il Return on Investment (ROI) sulla pubblicità relativa alla ricerca a pagamento con Adobe Advertising Cloud e Adobe Analytics. |
| Adobe Analytics | Video - [Adobe Analytics: sono più che dati, sono informazioni sui clienti](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Scopri il marketing basato sui dati e come trasformare la maturità delle tue analisi da dati a informazioni e infine ad azioni. |
| Adobe Analytics | Video: [Adobe Sensei e Adobe Analytics (versione estesa)](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Visualizza le funzioni chiave di Adobe Analytics fornite da Adobe [!DNL Sensei,], tra cui [!UICONTROL rilevamento anomalie,] [!UICONTROL analisi dei contributi,] [!UICONTROL avvisi intelligenti,] [!UICONTROL clustering,] [!UICONTROL Segment IQ] e [!UICONTROL modellazione delle tendenze.] |
| Adobe Analytics | Video: [come Adobe Analysis Workspace può cambiare la tua azienda](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Scopri come eseguire analisi ad hoc, analisi flessibili, analisi di coorte e analisi di fallout utilizzando [!UICONTROL Analysis Workspace]. Puoi anche condividere l’ambiente di lavoro di analisi con tutti gli utenti dell’azienda e la sua funzione di trascinamento consente a tutti di analizzare i dati in modo semplice e ottenere informazioni rapidamente. |
| Adobe Analytics | Video - [Caso di utilizzo di un cliente: Home Depot innova con la gestione della customer experience](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Scopri come [!DNL Home Depot] utilizza le soluzioni Adobe per creare brand loyalty e soddisfazione dei clienti con un’esperienza di acquisto personalizzata. |
| Adobe Analytics | Presentazione: [comprendere l’analisi del customer journey](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Scopri in che modo l’[!UICONTROL analisi del customer journey] di Adobe, un servizio di applicazione basato su [!DNL Adobe Experience Platform], porta [!UICONTROL Analysis Workspace] nella Experience Platform. Questa funzione consente l’analisi multicanale di qualsiasi set di dati di [!DNL Adobe Experience Platform]. |
| Adobe Analytics | Video: [attribuzione cross-channel nell’analisi del customer journey](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Scopri come utilizzare le visualizzazioni per mostrare l’attribuzione (riconoscere il merito) in tutti i canali nell’[!UICONTROL analisi del customer journey]. |
| Adobe Analytics | Articolo: [suggerimenti dei clienti per continuare il tuo percorso di apprendimento di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Scopri tre clienti Adobe che possono offrirti suggerimenti e consigli su come ottenere il massimo da Adobe Analytics. |
| Adobe Analytics | Video: [creare visualizzazioni cross-channel nell’analisi del customer journey](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Scopri come l’[!UICONTROL analisi del customer journey] ti consente di creare visualizzazioni che includono dati da più set di dati in più canali, inclusa l’unione dei dati per visitatore. |
| Adobe Analytics | Video: [spostare le metriche calcolate da Adobe Analytics all’analisi del customer journey](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Trova suggerimenti per ricreare le [!UICONTROLCmetriche calcolate] da Analytics nell’[!UICONTROL analisi del customer journey]. |
