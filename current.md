---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di Adobe Experience Cloud
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 64307f885074b216956a8711384b60a4806a13a3
workflow-type: tm+mt
source-wordcount: '4373'
ht-degree: 94%

---


# Accesso in anteprima - Note sulla versione di Adobe Experience Cloud - Luglio 2020

![Banner](/assets/experience-cloud-banner-3.png)

Questa pagina descrive nuove funzioni, correzioni e avvisi importanti in [!DNL Adobe Experience Cloud]. Inoltre mette in evidenza documentazione, corsi di formazione ed esercitazioni video farti per ottenere il massimo da Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima del rilascio ufficiale.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni.

**Data di rilascio: 16 luglio 2020**

Le date di rilascio del prodotto possono variare. Controlla spesso la disponibilità di aggiornamenti.

Ultimo aggiornamento: **14 luglio 2020**

* [Stato del sistema di Adobe](#status)
* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey) (Aggiornato il 14 luglio 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (link alla guida di Primetime)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/#home) per trovare documentazione tecnica e dei prodotti, corsi curati da Adobe, esercitazioni video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Data di rilascio: **21 maggio 2020**

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Per velocizzare l’iscrizione, il processo di autoabbonamento ora consiglia una selezione di prodotti e offerte in base alle adesioni dei prodotti. Questo dovrebbe ridurre il numero di e-mail che ricevi e far sì che le notifiche nell’inbox siano più pertinenti. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Miglioramento dell’esperienza utente di abbonamento e notifica | <ul><li>Le posizioni regionali di [!DNL Marketo Engage] ora vengono filtrate in base all’elenco delle offerte di prodotti selezionate.</li><li>Le notifiche e-mail di [!DNL Marketo Engage] sono pertinenti all’area geografica, alla posizione e alle preferenze di ambiente dell’utente.</li></ul> |
| Conferma dell’abbonamento agli eventi | <ul><li>Ora puoi ricevere una conferma e-mail quando effettui un abbonamento agli aggiornamenti per un singolo evento in corso.</li></ul> |
| Miglioramenti dell’usabilità della navigazione globale | <ul><li>Esperienza utente coerente con `Adobe.com` nel menu di navigazione di livello principale.</li></ul> |

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Aggiornamenti generali all’interfaccia di Experience Cloud.

**Menu dell’interfaccia aggiornato**

Con la versione di Experience Cloud del **16 luglio 2020** è stato aggiornato il menu a discesa per cambiare applicazione. Per semplificarlo, sono stati rimossi i loghi della soluzione e vengono visualizzati solo i servizi e le applicazioni a cui hai accesso.

Per un esempio dell’interfaccia di Experience Cloud, consulta la [documentazione del prodotto](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

**Dominio di prodotto unificato**

Adobe sta aggiornando l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza su tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, e che non modificano il flusso di lavoro attuale.

Gli aggiornamenti includono:

* Nuovi URL dell’applicazione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** anche se l’interfaccia Experience Cloud supporta questi browser, le singole applicazioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
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

Note sulla versione per [!DNL Experience Platform] e per i servizi dell’applicazione, tra cui [!DNL Experience Platform Launch,] [!UICONTROL Offerte], [!UICONTROL Persone], [!UICONTROL Places], [!UICONTROL Mobile Services] e bollettini di sicurezza.

Latest release date: **June 10, 2020**

Consultate [note](https://docs.adobe.com/content/help/it-IT/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) sulla versione di Experience Platform per informazioni aggiornate su  Experience Platform.

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

### Risorse aggiuntive per Journey Orchestration

[Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **16 luglio 2020**

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni in Customer Journey Analytics](#cust-journey)
* [Nuove funzioni di Media Analytics](#media-aa)
* [Problemi risolti in Adobe Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices) (Aggiornato il 13 luglio 2020)
* [Nuovi corsi ed esercitazioni di Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-------|
| Workspace: nuovi predefiniti per intervalli di date | 16 luglio 2020 | Sono stati aggiunti 4 nuovi intervalli di date (_Questa settimana, Questo mese, Questo trimestre, Quest’anno_, escluso oggi) per consentire agli utenti di scegliere un intervallo di date che non includa i dati relativi ai giorni parziali a partire dalla data odierna. |
| Versione beta pubblica API di ripristino dati | 14 luglio 2020 | L&#39;API  Data Repair offre un meccanismo per eliminare o modificare alcuni dati Adobe  Analytics esistenti. [!UICONTROL Le richieste di ripristino] dei dati vengono effettuate inviando una definizione di processo all&#39;API [!UICONTROL di ripristino dei]dati, che include la suite di rapporti, l&#39;intervallo di date, le variabili e le azioni da applicare ai dati. Upon commencement of the public beta, the [!UICONTROL Data Repair API] will support deletion of [!UICONTROL Activity Map] data. Le funzioni aggiuntive verranno implementate in un secondo momento. Contatta l’Assistenza clienti per partecipare alla versione beta pubblica dell’API di ripristino dei dati. [Ulteriori informazioni...](https://github.com/AdobeDocs/analytics-2.0-apis/blob/master/data-repair.md) |

### Nuove funzioni in Customer Journey Analytics {#cust-journey}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- |-----|
| Nessuna nuova funzionalità questo mese |  |  |

### Nuove funzioni di [!UICONTROL Media Analytics] {#media-aa}

Data di rilascio: **16 luglio 2020**

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| -----------| ---------- | ---------- |
| [Piattaforme e dispositivi supportati](https://docs.adobe.com/content/help/it-IT/media-analytics/using/supported-devices.html) | 18 giugno 2020 | L’estensione Media Launch con SDK di AEP ora supporta i seguenti dispositivi OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Piattaforme e dispositivi supportati](https://docs.adobe.com/content/help/it-IT/media-analytics/using/supported-devices.html) | 18 giugno 2020 | L’estensione Media Launch con SDK di AEP ora supporta i seguenti dispositivi OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Tracciamento dello stato del lettore](https://docs.adobe.com/content/help/it-IT/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 maggio 2020 | I clienti [!UICONTROL Media Analytics] possono visualizzare le interazioni dei visualizzatori durante la riproduzione facendo uso di un set standard di variabili della soluzione per visualizzazione a schermo intero, sottotitoli, modalità muto, immagine nell’immagine e messa a fuoco. È inoltre possibile creare degli stati del lettore personalizzati. Le variabili di tracciamento dello stato del lettore sono ora disponibili per il reporting in [!UICONTROL Analysis Workspace]. Questa funzione richiede uno dei seguenti elementi: <ul><li>SDK di [!DNL JavaScript] Media 3.0 o versione successiva</li><li>Per l’utilizzo con l’SDK di [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Estensione Media Analytics] (per il web): [!UICONTROL Adobe Media Analytics] (3.x SDK) for Audio and Video v1.0 o versione successiva</li><li>[!UICONTROL Estensione Media Analytics] (per dispositivi mobile): [!UICONTROL Adobe Media Analytics for Audio] and Video v2.0 o versione successiva</li><li>[!UICONTROL Media Collection]</li></ul> |

### Problemi risolti in Adobe Analytics {#aa-fixes}

* È stato risolto un problema che si verificava dopo il passaggio a una suite di rapporti con una valuta diversa. Il grafico a linee [!UICONTROL Workspace] non rispecchiava la valuta corretta. (AN-216655)
* Sono stati risolti dei problemi a causa dei quali le visualizzazioni risultavano illeggibili nei PDF scaricati. (AN-217949)
* È stato risolto un problema a causa del quale si verificava un errore durante l’aggiunta di una variabile Gerarchia a una suite di rapporti. (AN-211974)
* È stato risolto un problema che si verificava durante la modifica di un feed di dati associato a una suite di rapporti con un fuso orario diverso da quello della suite di rapporti [!UICONTROL Reports &amp; Analytics]. (AN-222474)
* È stato risolto un problema che impediva il corretto funzionamento del [!UICONTROL Generatore di regole di classificazione]. (AN-219662)
* Sono stati risolti diversi problemi relativi alle classificazioni e alle regole di classificazione. (AN-223492, AN-220654, AN-219662, AN-223260)
* È stato risolto un problema a causa del quale lo stesso segmento restituiva dati diversi in una suite di rapporti virtuale rispetto alla suite di rapporti principale. (AN-201074)
* È stato risolto un problema che impediva il download delle impostazioni della suite di rapporti. (AN-223690)
* È stato risolto un problema in [!UICONTROL Avvisi intelligenti] che impediva il funzionamento del collegamento nell’e-mail per _ritirarsi dalla pianificazione_. (AN-223875)
* È stato risolto un problema a causa del quale veniva visualizzata una valuta errata per una suite di rapporti virtuale. (AN-224781)
* È stato risolto un problema relativo a errori di _dati mancanti_ nelle suite di rapporti virtuali. (AN-224782)
* È stato corretto un problema in seguito al quale, suddividendo una classificazione di una dimensione per un’altra, venivano restituiti risultati vuoti se utilizzati con una metrica calcolata con allocazione partecipazione impostata. (AN-214089)

#### Ulteriori correzioni di Adobe Analytics

AN-222672, AN-222813; AN-222892; AN-223272, AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| EOL di Adobe Data Connectors | 13 luglio 2020 | I Connettori dati Adobe sono dotati di tecnologia legacy non più disponibile o supportata. Abbiamo un nuovo standard nel programma [per i partner di](https://partners.adobe.com/exchangeprogram/experiencecloud) Adobe Exchange che dovrebbe essere adottato per tutte le integrazioni che desiderano continuare a essere offerte e supportate. La data ufficiale di fine del ciclo di vita deve ancora essere determinata, ma prevediamo che sarà nei prossimi 12-18 mesi (metà 2021 a fine 2021). [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mappatura delle suite di rapporti per organizzazioni IMS | Luglio 2020 | Lo strumento di mappatura delle suite di rapporti verrà terminato a novembre 2020. Questa funzione consente integrazioni quali la pubblicazione di segmenti Advertising Analytics e Experience Cloud in Adobe Analytics. Una suite di rapporti deve essere mappata su un’organizzazione IMS per abilitare questi e altri servizi. Le nuove suite di rapporti vengono mappate automaticamente al momento della creazione. Tuttavia, le suite di rapporti meno recenti devono essere mappate manualmente su un’organizzazione IMS. Per accertarti che tutte le suite di rapporti appartengano a un’organizzazione IMS, consulta la sezione su come [mappare le suite di rapporti su un’organizzazione](https://docs.adobe.com/content/help/it-IT/core-services/interface/about-core-services/report-suite-mapping.html), nella guida utente dei servizi core. |
| Migrazione a un dominio di prodotto unificato | Data di validità: 28 maggio 2020 | La migrazione a un dominio di prodotto unificato per Adobe Analytics, iniziata a gennaio 2020, è stata completata il 28 maggio 2020. Adobe Analytics si impegna a rimuovere dalla propria architettura tutti i riferimenti al dominio `omniture.com`, ma è importante inserire `omniture.com` nell’elenco Consentiti in quanto cookie di terze parti. A breve, quando verrà portata a termine la migrazione dell’architettura, riceverai una notifica tramite le note sulla versione e non sarà più necessario compiere questo passaggio. [Qui](https://helpx.adobe.com/it/analytics/kb/adobe-ip-addresses.html) puoi trovare un elenco completo degli indirizzi IP consigliati e dei domini che dovresti inserire nell’elenco dei consentiti.<br>Se l’organizzazione blocca i cookie di terze parti, contatta l’assistenza clienti per recuperare l’accesso ad Adobe Analytics. |
| Nuova pagina di destinazione predefinita di Adobe Analytics | Data di validità: 18 giugno 2020 | Il 18 giugno 2020 la pagina di destinazione predefinita per Adobe Analytics passerà da [!UICONTROL Reports] a [!UICONTROL Workspace]. Questa modifica verrà applicata agli utenti che non hanno precedentemente impostato una pagina di destinazione personalizzata. |
| Elenco delle tecnologie di terze parti consentite | 12 marzo 2020 (data effettiva) | Adobe Analytics ha iniziato a sfruttare tecnologie di terze parti per la gestione del rollout delle funzioni e per il supporto integrato nel prodotto. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti per assicurare l’accesso a tutte le funzioni:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Miglioramento della ridondanza per la disponibilità di [!UICONTROL Analysis Workspace] | 21 maggio 2020 | Per assicurare la disponibilità di [!UICONTROL Analysis Workspace], verrà aggiunta una rete per la distribuzione di contenuti (CDN) secondaria per migliorare la ridondanza. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Poiché ora in [!UICONTROL Analysis Workspace] è possibile attivare e disattivare i valori _None_, viene applicato il valore _None_ dopo l’entrata o l’uscita, mentre per le eVar veniva applicato prima dell’entrata o dell’uscita. Ad esempio, si supponga che il primo risultato di una visita non presenti alcun valore per le eVar, ma il secondo sì. In [!UICONTROL Reports &amp; Analytics] il primo risultato verrà visualizzato come _non specificato_ per l’Entrata, ma in [!UICONTROL Analysis Workspace] verrà visualizzato come valore per il secondo risultato. |
| Fine del ciclo vita di **[!UICONTROL Archivio dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL Visualizza archivio]** nella sezione **[!UICONTROL Gestione dashboard]** in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| EOL di  Analytics Legacy API | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Per gli ultimi aggiornamenti sulle versioni di AppMeasurement, fare riferimento alle [note sulla versione di AppMeasurement per JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html).

#### Risorse dell’Aiuto di Analytics

* [Esercitazioni di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentazione dei prodotti Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html)

## ![Icona](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuove funzioni, correzioni, documentazione ed esercitazioni in Audience Manager.

Data di rilascio: **16 luglio 2020**

### Nuove funzioni e correzioni in Adobe Audience Manager

* È stato risolto un problema che impediva ai clienti di mappare alcuni segmenti su destinazioni Amazon. (AAM-54373)
* È stato risolto un problema a causa del quale la schermata del browser si bloccava quando i clienti aprivano un segmento in una nuova scheda. (AAM-55213)
* È stato risolto un problema relativo al [rapporto sullo stato di onboarding](https://docs.adobe.com/help/it-IT/audience-manager/user-guide/reporting/onboarding-status-report.html) a causa del quale poteva verificarsi una mancata corrispondenza tra la data nella tabella e la data visualizzata facendo clic su una barra nel grafico. (AAM-55235)
* È stato corretto un bug nella sezione Amministrazione a causa del quale veniva visualizzata un’icona di errore invece di un messaggio di conferma quando i clienti tentavano di eliminare degli utenti. (AAM-55186)
* È stato risolto un problema relativo all’API Swagger, a causa del quale l’intestazione `x-api-key` non veniva aggiunta alla richiesta curl. (AAM-55392)
* È stato migliorato l’ordinamento predefinito per i segmenti mappati su destinazioni nella visualizzazione Destinazioni. I segmenti mappati ora sono ordinati per data di inizio della mappatura dei segmenti, quindi per ID segmento. (AAM-38494)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-48956, AAM-49012, AAM-49364, AAM-49363, AAM-49374, AAM-49579, AAM-55037).

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **Dynamic Media Classic**

   Gli utenti di Dynamic Media Classic ora hanno accesso a una nuova esperienza di app desktop che non si basa più sulla tecnologia Adobe Flash nel browser. La nuova app è disponibile per Windows e macOS.

   Consulta [App Adobe Dynamic Media Classic Desktop - Ora disponibile](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/new-ui-2020.html).

* **Supporto per risorse 3D aggiunto ad Dynamic Media**

   Dynamic Media in AEM 6.5 e in AEM as a Cloud Service ora consente di caricare, gestire, visualizzare e distribuire risorse 3D come esperienze immersive.

   * Per AEM as a Cloud Service, consulta [Utilizzo di risorse 3D in Dynamic Media](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html).
   * Per AEM 6.5, consulta [Utilizzo di risorse 3D in Dynamic Media](https://docs.adobe.com/content/help/it-IT/experience-manager-65/assets/dynamic/assets-3d.html).

### Aiuto e documentazione

* **Aggiornamenti alla documentazione di AEM 6.5.5 Forms**

   * Nuove funzioni e miglioramenti introdotti nella versione 6.5.5:

      * [Possibilità di personalizzare le colonne della casella in entrata di Adobe Experience Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control).
      * [Possibilità di salvare le comunicazioni interattive come bozza.](https://docs.adobe.com/content/help/it-IT/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Supporto del server applicazioni Oracle WebLogic per installazioni con [server singolo](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf) e [cluster](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf).
      * [Miglioramenti all’accessibilità](https://docs.adobe.com/content/help/it-IT/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [Autenticazione basata su certificato X-509 per i servizi web basati su SOAP nel modello per dati modulo.](https://docs.adobe.com/content/help/it-IT/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Supporto di Oracle RAC.](https://docs.adobe.com/content/help/it-IT/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [Registrazione migliorata degli errori nella generazione di rapporti sulle transazioni.](https://docs.adobe.com/content/help/it-IT/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * Nuove funzioni e miglioramenti introdotti nella versione 6.4.8.1:
      * [Autenticazione basata su certificato X-509 per i servizi web basati su SOAP nel modello per dati modulo.](https://docs.adobe.com/content/help/it-IT/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Registrazione migliorata degli errori nella generazione di rapporti sulle transazioni.](https://docs.adobe.com/content/help/it-IT/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **Community**

* **Discussione della Community AEM**

   Ora puoi consultare tutti gli annunci relativi ad AEM e interessanti riferimenti ai blogger interni ed esterni in un’unica posizione. Consulta la [sezione Discussione](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions) della community AEM.

### Nuovi corsi ed esercitazioni di Experience Manager

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 25 giugno 2020 | [Guida introduttiva ai moduli adattivi](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | Video | Queste esercitazioni descrivono come creare moduli adattivi con più schede. Scopri come usare le tabelle, il layout a soffietto e l’editor di regole per la creazione di regole aziendali. |
| 25 giugno 2020 | [Creazione di un flusso di lavoro di revisione in AEM Forms](https://video.tv.adobe.com/v/35821/quality=9?captions=ita) | Video | Scopri come creare un flusso di lavoro per la revisione dei dati inviati tramite un modulo attivo. |
| 23 giugno 2020 | [Profili di elaborazione](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | Video | I profili di elaborazione definiscono le rappresentazioni da creare per le risorse in AEM as a Cloud Service. |
| 23 giugno 2020 | [Best practice per Dynamic Media Classic](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | Articolo | Gli utenti nuovi e attuali possono scoprire Dynamic Media Classic, le sue funzionalità principali e il flusso di lavoro di _creazione_, _authoring_ e _distribuzione_. |
| 23 giugno 2020 | [Debug delle build e implementazioni di AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | Articolo | Scopri come eseguire il debug delle build e delle implementazioni di AEM as a Cloud Service. |
| 16 giugno 2020 | [Debug di AEM as a Cloud Service tramite i registri](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | Articolo | Scopri come utilizzare i registri per eseguire il debug di AEM as a Cloud Service. I registri fungono da strumenti di prima linea per il debug delle applicazioni AEM, ma dipendono dalla registrazione appropriata nell’applicazione AEM implementata. |
| 10 giugno 2020 | [Utilizzo di Dynamic Media 3D con AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | Video | Il supporto di Dynamic Media 3D in Adobe Experience Manager consente di personalizzare e distribuire su grande scala esperienze interattive basate su 3D. |
| 5 giugno 2020 | [Progetto per l’editor di applicazioni a pagina singola](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | Articolo | Scopri come utilizzare l’archetipo di progetto Adobe Experience Manager (AEM) per generare un progetto Maven con più moduli come punto di partenza per un’applicazione React integrata con l’editor di applicazioni a pagina singola di AEM. |
| 3 giugno 2020 | [Gestione dell’invio di moduli HTML5 - Tutorial](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | Articolo | Scopri come accedere ai dati inviati nel gestore di invio personalizzato. |

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

* Nuova build Gold Standard stabile. [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Pannello di controllo Campaign

* Audit per recapito del sottodominio - [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* Gestione delle chiavi GPG - [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/control-panel/using/instances-settings/gpg-keys-management.html)

### Nuovi corsi e tutorial su Campaign

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| ----------- | ----------- | ---------- | ---------- |  
| 26 giugno 2020 | [Interfaccia utente di Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | Questo video illustra l’interfaccia utente principale di Adobe Campaign Classic e mostra come accedere alle funzioni principali. |
| 8 luglio 2020 | [Installazione e configurazione del client Adobe Campaign](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | Scopri come scaricare e installare la console client di Adobe Campaign, creare e gestire le connessioni a più ambienti e verificare l’accesso alla console client di Adobe Campaign. |
| 19 giugno 2020 | [Introduzione ad Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | Scopri come Adobe Campaign Classic si inserisce nel portfolio Adobe Digital Experience e le sue funzionalità principali. |
| 12 giugno 2020 | [Implementazione di un modello di consegna e-mail ad hoc](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | Scopri come implementare un modello e-mail ad hoc. |
| 12 giugno 2020 | [Configurazione di un modello di consegna](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | Scopri come configurare un modello e-mail. |
| 12 giugno 2020 | [Impostazione delle proprietà del modello di consegna](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | Scopri come impostare le proprietà del modello e-mail. |
| 12 giugno 2020 | [Gestione delle chiavi GPG](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/Pannello di controllo | Scopri come generare e installare una coppia di chiavi GPG pubblica/privata per la crittografia dei dati e come importare e installare una chiave pubblica per la decrittografia dei dati. |
| 26 giugno 2020 | [Introduzione all’interfaccia di Adobe Campaign Standard](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | Questo video offre una panoramica dell’interfaccia di Adobe Campaign Standard e spiega come accedere alle funzioni chiave e di base. |
| 26 giugno 2020 | [Gestione delle chiavi GPG](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/Pannello di controllo | Scopri come generare e installare una coppia di chiavi GPG pubblica/privata per la crittografia dei dati e come importare e installare una chiave pubblica per la decrittografia dei dati. |

### Risorse di supporto

* Adobe Campaign Standard: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/campaign-standard-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/overview.html) - [Piano delle versioni future](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-planning.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/campaign-classic-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/documentation-updates.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html) - Video introduttivi per [Campaign Standard](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Note sulla versione di Adobe Advertising Cloud.

### Nuove funzioni di [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Ultimo aggiornamento: **8 luglio 2020** per la versione dell’11 luglio.

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Avvisi beta] | Ora è possibile aprire una visualizzazione filtrata di sola lettura contenente i dati per qualsiasi avviso, e quindi aprire una visualizzazione filtrata delle entità nella vista di gestione di una specifica campagna in cui è possibile modificare i record delle entità. |
| [!UICONTROL Portfolio] | Le metriche basate sulla posizione nei vincoli e nelle impostazioni dei portfolio diventeranno obsolete l&#39;8 agosto. |

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
