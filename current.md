---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 7ec12529edf495c36cc153028458257939782e41

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Gennaio 2020

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!IMPORTANT]
>Questa pagina contiene contenuti precedenti al rilascio ed è soggetta a modifiche prima della release pianificata di ciascun prodotto.

>[!NOTE]
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 16 gennaio 2020**

* [Stato del sistema Adobe](#status)
* [Interfaccia e servizi di base di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [SDK Mobile Services e Mobile](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti dello stato e notifiche e-mail relative a eventi di interruzione, interruzione e manutenzione di prodotti e servizi cloud Adobe. Consultate [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando il vostro Adobe ID, potete iscrivervi alle notifiche evento in base alle preferenze di prodotto, regione e evento. Gli utenti che configurano le proprie preferenze di iscrizione ricevono una notifica degli eventi rilevanti relativi a incidenti e manutenzione del prodotto non appena vengono aperti, aggiornati o chiusi. Inizia all&#39;indirizzo [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Iscriviti alle notifiche e-mail proattive | <ul><li>Supporto per Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform e Adobe Services</li><li>Supporto delle preferenze per area geografica e tipo di evento</li></ul> |
| Gestione delle preferenze di notifica | <ul><li>Modifica e salva le preferenze per le notifiche in qualsiasi momento</li><li>Annulla l’abbonamento per ricevere le notifiche in qualsiasi momento</li></ul> |
| Ottenimento di e-mail personalizzate e più veloci | <ul><li>Le notifiche degli eventi vengono inviate non appena gli eventi vengono aperti, aggiornati o chiusi</li><li>Ricevi solo le notifiche degli eventi corrispondenti alle preferenze configurate</li><li>Ricevi notifiche localizzate in base alla lingua configurata nelle preferenze dell&#39;account</li></ul> |
| Ottenere notifiche interne al prodotto personalizzate | <ul><li>Gli eventi che corrispondono alle preferenze di notifica e ai diritti sui prodotti vengono visualizzati nel pannello Annunci</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, inclusi i servizi di amministrazione e di base (attributi del cliente, audience, attivatori, cookie e così via).

### Dominio prodotto unificato

Adobe sta aggiornando l&#39;intestazione del dominio e dell&#39;interfaccia per unificare e migliorare la tua esperienza in tutte le applicazioni Experience Cloud. Questi miglioramenti sono stati progettati per semplificare la vostra esperienza in modi piccoli ma importanti. Questi miglioramenti non modificheranno i flussi di lavoro correnti.

Gli aggiornamenti includono:

* Nuovi URL della soluzione: `experience.adobe.com/<application name>.` Tutti i prodotti adotteranno questo pattern URL. Cercate nuovi URL che diventino effettivi per tutto il mese. Note:
   * La modifica del dominio potrebbe causare problemi di cookie in Safari. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain. È possibile utilizzare altri browser senza problemi, perché questo interessa solo gli utenti di Safari.
* Passaggio più semplice tra le organizzazioni o a un&#39;altra applicazione.
* Aiuto sui prodotti migliorato: [!UICONTROL Experience League] è integrato nel prodotto per consentire la ricerca di aiuto anche con i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l&#39;accesso a più contenuti e consente di trarre il massimo da Experience Cloud. Inoltre, fate clic su **[!UICONTROL Aiuto]**>**[!UICONTROL  Feedback]** per segnalare i problemi o condividere le idee con Adobe.
* Notifiche migliorate: Il menu a discesa [!UICONTROL Notifiche] ora include due schede, una per le notifiche dei prodotti e una per gli annunci globali dei prodotti.

**** Nota: La pagina [!UICONTROL Feed] è stata rimossa a gennaio 2020. Nel prodotto verrà visualizzato un avviso di funzione rimossa.

Per la documentazione sul prodotto, consulta [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Cookie di Experience Cloud

Adobe sta regolando l&#39; `same-site` impostazione sui cookie per preparare le modifiche Chrome farà in Chrome 80 (da pubblicare a febbraio 2020).

Non è necessario apportare modifiche a meno che non utilizzi un CNAME per la raccolta dati di prime parti ma utilizzi tale CNAME per più domini (domini di terze parti descrittivi) e non utilizzi il servizio ID di Experience Cloud (Visitor). Con la release di Chrome 80, Chrome assegna automaticamente ai cookie ID visitatore di Analytics un valore SameSite `Lax,` che ne impedisce l’uso sugli altri domini. Se desiderate continuare a utilizzare il CNAME nei vostri domini, contattate l&#39;Assistenza clienti Adobe e richiedete che modifichi il valore SameSite del CNAME in `None.`

Adobe consiglia di utilizzare un CNAME separato per ciascuno dei domini, indipendentemente dal fatto che si utilizzi o meno il servizio Experience Cloud ID.

[Altro…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html) (Tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services and Mobile SDKs {#mobile}

16 gennaio 2020: Versione 4.18.0

* Acquisizione: aggiunta di una nuova API `Analytics.processGooglePlayInstallReferrerUrl(final String url)`per supportare le API [!DNL Google Play] di riferimento installazione.

Per ulteriori informazioni sull&#39;installazione delle API di riferimento, vedere [Still Using InstallBroadcast? Passate all&#39;API Play Referrer entro il 1 marzo 2020](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html).

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- | 
| Analysis Workspace - Generatore tabella a forma libera | Con Generatore di tabelle abilitato, puoi trascinare e rilasciare più dimensioni, suddivisioni, metriche e segmenti per creare tabelle che rispondano a domande aziendali più complesse. I dati non verranno aggiornati immediatamente. Al contrario, gli aggiornamenti si verificano dopo aver fatto clic su **[!UICONTROL Genera]**, risparmiando tempo una volta che si sa quale tabella si desidera creare. Questa funzione offre inoltre:<ul><li>**Anteprima**: È possibile visualizzare in anteprima il formato di una tabella prima di passare il tempo necessario per eseguire il rendering dei dati reali.</li><li>**Impostazioni** di riga e suddivisione flessibili: Puoi impostare i livelli di riga e suddivisione per ogni riga dimensione. In precedenza, Workspace impostava i valori predefiniti che non potevano essere modificati fino a quando non venivano restituiti i dati.</li><li>**Suddivisione per posizione**: È possibile impostare le righe delle dimensioni in modo da _suddividere sempre per posizione_ anziché _per elemento_ specifico (impostazione predefinita).</li><li>**Ordine** manuale delle righe statiche: È possibile ordinare manualmente le righe statiche in modo che vengano visualizzate esattamente come necessario. In precedenza, le righe statiche potevano essere ordinate solo in base a una colonna di metrica o in ordine alfabetico.</li></ul>La documentazione associata verrà pubblicata quando questa funzione verrà rilasciata più avanti nel mese di gennaio. |
| Nuova dimensione dello stato  identificato per Analytics tra dispositivi (CDA) | Stiamo aggiungendo una nuova dimensione denominata Stato  identificato alle suite di rapporti virtuali CDA. La dimensione ha due possibili valori: _Identificato_ e _Non identificato_. _Identificato_ significa che la persona è stata identificata dal grafico del dispositivo. _Non identificato_ significa che la persona non è stata identificata dal grafico del dispositivo.<br>Ciò significa che gli utenti CDA ora possono creare metriche calcolate, come [!UICONTROL Device Graph Coverage], che descrive quante delle persone nella suite di rapporti virtuali sono note dal grafico del dispositivo. Questa metrica è utile per la risoluzione dei problemi relativi alle percentuali di compressione CDA. Se vengono identificate poche persone, il livello di cucitura sarà basso. |
| Supporto VRS nell&#39;API di Data Warehouse | Le suite di rapporti virtuali saranno ora disponibili per l&#39;utilizzo tramite l&#39;API Data Warehouse. Precedentemente, erano disponibili solo tramite l’interfaccia utente di Data Warehouse. Quando si utilizza l&#39;API Data Warehouse, ora è possibile visualizzare ed eseguire query sulle suite di rapporti virtuali, ma solo se i segmenti applicati a una suite di rapporti virtuale sono compatibili con Data Warehouse. |
| API per i Servizi per la privacy: CCPA | Il California Consumer Privacy Act (CCPA) migliora i diritti alla privacy e la protezione dei consumatori per i residenti in California, Stati Uniti. La legge è entrata in vigore il 1° gennaio 2020.<br><br/>Il CCPA conferisce ai residenti della California nuovi diritti sulla privacy dei dati, come il diritto di accesso e cancellazione dei propri dati personali, di sapere se i propri dati personali vengono venduti o divulgati (e a chi), e di rifiutare la vendita degli stessi.<br><br/>Il Servizio Privacy supporta le richieste di rifiuto della vendita di dati personali.<br><br/>Il servizio Privacy era già il servizio GDPR e conserva tutte le funzionalità precedenti, ora estese per supportare CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Panoramica del servizio sulla privacy](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### Correzioni

* È stato risolto un problema che impediva la consegna delle notifiche di avviso ai numeri di telefono in Egitto. (AN-197079)
* Sono stati risolti diversi problemi relativi all’ [!DNL DFA Data Connector]. (AN-193281, AN-193075, AN-193484, AN-193737)
* [!UICONTROL Reporting e analisi]: È stato corretto un problema a causa del quale il report Product Conversion Funnel (Funnel conversione prodotto) veniva disattivato e mostrava numeri non chiari. (AN-186901)
* È stato risolto un problema che impediva agli utenti di cambiare suite di rapporti in progetti Workspace basate su suite di rapporti con la nuova architettura Classificazioni. (AN-199076)
* È stato risolto un problema che impediva il corretto funzionamento della funzione [!UICONTROL Cumulativa] in Metriche  calcolate. (AN-184257)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | Il 16 gennaio 2020, Adobe Analytics inizierà a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota **: Questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi di cookie durante il caricamento di Analytics in Safari. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. È possibile utilizzare altri browser senza problemi, perché questo interessa solo gli utenti di Safari.</li><li>La modifica del dominio potrebbe impedire il funzionamento della Mappa  attività per alcuni clienti [in casi](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)specifici.</li></ul> |
| Fine del ciclo di vita - API Analytics legacy | 9 gennaio 2020 | Nel novembre 2020, i seguenti servizi API Analytics Legacy termineranno e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>1.3 API di Analytics</li><li>1.4 API SOAP Analytics</li><li>Autenticazione OAuth legacy (OAuth e JWT)</li></ul>Abbiamo fornito una [Legacy API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per aiutare a rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle API [REST di Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) 1.4 o alle API [di Analytics](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)2.0. Gli account OAuth legacy possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API Analytics 1.4 che alle API Analytics 2.0. |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per l’opzione **[!UICONTROL Visualizza archivio]** in Dashboard Manager (**[!UICONTROL  Componenti > Dashboard]**). |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Enforce IP Login Restrictions]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per la funzionalità di whitelisting degli accessi IP (**[!UICONTROL Enforce IP Login Restrictions]**), nel menu **[!UICONTROL  Amministrazione > Impostazioni società > Sicurezza]**. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Correzioni e funzionalità aggiunte ad Audience Manager.

### Nuove funzioni, miglioramenti e correzioni in Audience Manager {#aam-features}

| Funzione | Descrizione |
| -----------| ---------- |
| [Aggiornamento della documentazione relativa al supporto e alla privacy dell&#39;Atto sulla privacy dei consumatori della California](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | La [California Consumer Privacy Act (CCPA)](https://www.caprivacy.org/about), entrata in vigore il 1° gennaio 2020, conferisce ai residenti californiani nuovi diritti in merito alle loro informazioni personali e impone loro responsabilità in materia di protezione dei dati a determinate entità che svolgono attività commerciali in California. <br><br> Audience Manager ti aiuta a rispettare gli obblighi previsti dalle normative sulla privacy, attraverso strumenti per la privacy come il servizio [per la privacy di](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) Adobe Experience Platform per l’accesso ai dati e l’eliminazione delle richieste. <br><br> Abbiamo aggiornato l&#39;attuale processo di gestione [della](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) rinuncia per includere la rinuncia a qualsiasi ID dichiarato (ad esempio, ID CRM). In caso di rifiuto tramite ID dichiarato, l’ID dichiarato e l’ultimo dispositivo collegato verranno esclusi dalla raccolta dati di Audience Manager. Le richieste di rifiuto ora inviano anche richieste di segmento ai partner [di](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) destinazione che supportano questa funzione, in batch e in tempo reale. <br><br> Inoltre, abbiamo riprogettato la nostra documentazione [sulla sicurezza](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html)dei dati, sulla privacy [dei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)dati e sulla governance [dei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) dati, per facilitare la ricerca delle informazioni necessarie per conformarsi alle normative sopra citate. |

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* È stato risolto un problema nel flusso di lavoro [!UICONTROL Crea destinazione] per il quale, selezionando Piattaforme ****integrate come[!UICONTROL categoria], la sezione Informazionidi base scompariva e il flusso di lavoro non poteva essere completato. (AAM-52397, AAM-52414)
* We fixed a bug where the [!UICONTROL Create/edit] destinations page would not load in the Apple Safari and Mozilla Firefox browsers. (AAM-51784)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Manutenzione del prodotto

* **AEM 6.5.3.0** AEM 6.5, Service Pack 3.0 (6.5.3.0 rilasciato il 12 dicembre 2019) è un aggiornamento importante che include correzioni di problemi fondamentali per il cliente, introdotte successivamente alla data di disponibilità generale di AEM 6.5, aprile 2019.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4, Service Pack 7.0 (6.4.7.0 rilasciato il 12 dicembre 2019) è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.4, aprile 2018.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 rilasciato il 12 dicembre 2019) è un aggiornamento importante che include correzioni di problemi fondamentali per il cliente, introdotte successivamente alla data di disponibilità generale di AEM 6.3, aprile 2017.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **App desktop AEM 2.0.1.1**

   AEM Desktop App 2.0.1.1 fornisce un aggiornamento per Single Sign-On con Okta e la possibilità di specificare il percorso dei file temporanei nelle Preferenze. Con questa versione, il supporto per AEM 6.3.x non è più supportato per Desktop App 2.x.
   * [Note sulla versione](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 termina il supporto per AEM 6.3.x**

   Il supporto per AEM 6.3.x è stato dichiarato obsoleto in Adobe Asset Link da aprile 2019. Adobe Asset Link 1.1 rimuove il supporto per AEM 6.3.x a partire dal 13 gennaio 2020.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Rilasci di prodotti

* **NOVITÀ:AEM come servizio cloud**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM) ora è disponibile come servizio cloud.

   * [Introduzione](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [Informazioni sulla versione](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [Documentazione](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **Servizio automatizzato di conversione moduli**

   Automated Forms Conversion Service, il servizio che consente di convertire automaticamente i moduli PDF in bellissimi moduli HTML pronti per dispositivi mobili, è stato reso disponibile per l&#39;uso generale il 12 dicembre 2019.

   * [Introduzione](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [Configurare il servizio](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [Conversione di moduli PDF in moduli adattivi](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### Aiuto e documentazione

* **Anteprima delle risorse 3D**

   AEM 6.5 supporta il caricamento, la distribuzione e l’anteprima interattiva di risorse 3D come parte del processo di authoring. Il visualizzatore 3D interattivo è disponibile dalla pagina dei dettagli delle risorse in AEM. Il visualizzatore include, tra le altre cose, una raccolta di controlli interattivi per la videocamera che consentono di orbitare, ingrandire e scorrere la risorsa 3D.
Consultate [Anteprima delle risorse](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html)3D.

* **Componenti di base**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Archetipo di progetto AEM**

   Il modulo [](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) ui.frontend di [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) è uno strumento utile e flessibile per facilitare lo sviluppo front-end del progetto AEM.

### Risorse aggiuntive

* [AEM come servizio cloud](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### Campaign Classic 19.2

| Funzionalità | Descrizione |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | CCPA è la nuova legge sulla privacy dello Stato della California che armonizza e aggiorna i requisiti di protezione dei dati in vigore dal 1° gennaio 2020. CCPA si applica ai clienti di Adobe Campaign che detengono i dati per i soggetti dati residenti in California. <br> Oltre alle funzionalità per la privacy già disponibili (compresa la gestione del consenso, le impostazioni di conservazione dei dati e i ruoli utente), Adobe Campaign ti aiuta a semplificare la tua preparazione all&#39;adozione dell&#39;APP: <ul><li>__ Diritto di accesso _e_ Diritto di eliminazione: stiamo sfruttando le funzionalità aggiunte per il GDPR. [Per saperne di più](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>È possibile verificare se un consumatore ha rinunciato alla vendita di Informazioni personali. A questo scopo, è necessario estendere la tabella [!UICONTROL Profili] e aggiungere un campo **[!UICONTROL Rifiuto per CCPA]**.[Per saperne di più](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> Fate riferimento al [video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)dimostrativo. |
| Monitoraggio live del flusso di lavoro | Ora puoi monitorare lo stato di esecuzione di tutti i flussi di lavoro sulla tua istanza utilizzando viste predefinite. <br> Per ulteriori informazioni, consultate [Filtrare i flussi di lavoro in base al loro stato](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status). |
| Contenuto interattivo con AMP | Adobe Campaign consente di provare il nuovo formato [AMP per e-mail](https://amp.dev/about/email/) interattivo, che consente agli esperti di marketing di includere componenti AMP nei messaggi per migliorare l&#39;esperienza e-mail con contenuti avanzati, dinamici e interattivi, direttamente utilizzabili nel messaggio stesso. <br> Questa funzionalità viene rilasciata come versione beta pubblica. <br> Per ulteriori informazioni, consultate la documentazione [](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) dettagliata e il video [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html)dell&#39;esercitazione. |
| Messaggi SMS protetti (TLS) | La funzione per SMS protetti è ora supportata tramite il connettore generico esteso SMPP. Consente di stabilire una connessione crittografata con il provider. <br> **Avviso**: questa funzione richiede un certificato aggiornato su tutti i server. I certificati non validi, revocati o scaduti generano errori che influiscono sulle capacità di invio SMS complessive. <br>Per ulteriori informazioni, consulta la [documentazione dettagliata](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |

Fai riferimento alle [note sulla versione Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) per correzioni e miglioramenti.

### Campaign Standard 19.4

| Funzionalità | Descrizione |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | CCPA è la nuova legge sulla privacy dello Stato della California che armonizza e aggiorna i requisiti di protezione dei dati in vigore dal 1° gennaio 2020. CCPA si applica ai clienti di Adobe Campaign che detengono i dati per i soggetti dati residenti in California. <br> Oltre alle funzionalità per la privacy già disponibili in Adobe Campaign (compresa la gestione del consenso, le impostazioni di conservazione dei dati e i ruoli utente), stiamo colgendo l&#39;opportunità di includere funzionalità aggiuntive per facilitare la disponibilità dell&#39;APP: <ul><li> Diritto di accesso e Diritto di eliminazione: stiamo sfruttando le funzionalità aggiunte per il GDPR. [Per saperne di più](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> Durante la creazione di una richiesta per la privacy, il tipo di regolamento (GDPR o CCPA) è stato aggiunto al Servizio di base per la privacy. Questo metodo è quello da utilizzare per tutte le richieste di accesso ed eliminazione. L&#39;utilizzo dell&#39;API e dell&#39;interfaccia di Campaign per le richieste di accesso ed eliminazione è obsoleto. Consultate l&#39;articolo [Funzioni](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html)obsolete e rimosse. </li><li> Alla risorsa Profili è stato aggiunto un campo di rifiuto **** CCPA per consentire agli utenti di Adobe Campaign di verificare se un consumatore ha rinunciato alla vendita di Informazioni personali. [Per saperne di più](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> Fate riferimento al [video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html)dimostrativo. |
| Integrazione di Microsoft Dynamics 365 (GA) | È ora disponibile l&#39;integrazione tra Adobe Campaign Standard e Microsoft Dynamics 365. Potrai trasferire i tuoi record di contatti e entità personalizzati da Dynamics 365 a Campaign e recuperare i dati degli eventi e-mail da Campaign a Dynamics 365 per migliorare l&#39;allineamento vendite/marketing. <br> Fate riferimento alla documentazione [](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) dettagliata per configurare questa integrazione e visualizzare il video [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)dimostrativo. |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Pannello di controllo di Adobe Campaign

Sono state aggiunte nuove funzionalità per consentire agli utenti Admin di delegare i sottodomini e rinnovare i certificati SSL dal Pannello di controllo.

Per ulteriori informazioni, consulta le pagine seguenti:

* Impostazione di un nuovo sottodominio - [Ulteriori informazioni](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* Rinnovo del certificato SSL di un sottodominio - [Ulteriori informazioni](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>Queste funzioni saranno disponibili in versione beta entro la fine di gennaio e saranno soggette a frequenti aggiornamenti e modifiche senza preavviso.

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - Note sulla [versione](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aggiornato per la release dell’11 gennaio 2020

| Visualizzazione | Funzione |
|------|---------|
| Monitoraggio delle conversioni | Tutti i cookie Advertising Cloud sono stati aggiornati per soddisfare i nuovi requisiti di controllo dei cookie per Google Chrome 80, che verrà rilasciato il 4 febbraio. Le modifiche sono state implementate dai server Adobe utilizzando i cookie esistenti, senza alcun effetto sulle metriche dei visitatori. Non sono necessari aggiornamenti per gli inserzionisti. |
| Insights > Alert Beta, Search > Campaigns | (Funzione Beta solo per gli account di ricerca) Una nuova funzione Alert Beta consente di creare modelli di avvisi per identificare quando una campagna di ricerca, un gruppo di annunci, una parola chiave o un annuncio soddisfa condizioni specifiche — ad esempio, metriche delle prestazioni durante un periodo specificato, quindi generare un avviso. Gli avvisi sono disponibili per un singolo inserzionista. |
| Rapporti | I dati per gli annunci di elenco prodotti ora sono inclusi nei report Label Classification (Classificazione etichetta), Label Value (Valore etichetta), Bid Rule (Regola offerta) e Constraint (Vincolo). |
