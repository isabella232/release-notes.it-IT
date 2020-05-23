---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1784b66efbcd85c25145fbf5b84f95c0285412ab
workflow-type: tm+mt
source-wordcount: '4997'
ht-degree: 36%

---


# Note sulla versione di Adobe Experience Cloud - Maggio 2020

![Banner](/assets/experience-cloud-banner-3.png)

Questa pagina contiene nuove funzioni, correzioni e note importanti in [!DNL Adobe Experience Cloud]. Le date di rilascio della soluzione possono variare. Controllate spesso la disponibilità di aggiornamenti più recenti.

>[!NOTE]
>
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni.

**Data di rilascio: 2020 maggio**

Ultimo aggiornamento: **21 maggio 2020**

* [Stato del sistema di Adobe](#status)
* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Aggiornato il 21 maggio 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (link alla guida di Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (link alla guida di Primetime)

Hai bisogno di aiuto? Visita [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) per trovare corsi specifici per Adobe, documentazione tecnica, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Data di rilascio: **21 maggio 2020**

**Novità**

* Utilizzando il tuo Adobe ID, puoi abbonarti alle notifiche degli eventi con maggiore granularità, fino al livello dell’offerta dei prodotti e dei componenti aggiuntivi. Per semplificare la configurazione dell&#39;iscrizione, il processo di autoiscrizione ora consiglia una selezione di prodotti e offerte in base alle adesioni dei prodotti. Questo dovrebbe ridurre il numero di e-mail che ricevete e inviare notifiche più pertinenti nella inbox. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Miglioramento dell&#39;esperienza utente di abbonamento e notifica | <ul><li>[!DNL Marketo Engage] le posizioni regionali ora vengono filtrate in base all&#39;elenco delle offerte di prodotti selezionate.</li><li>[!DNL Marketo Engage] le notifiche e-mail sono pertinenti all&#39;area geografica, alla posizione e alle preferenze dell&#39;utente per l&#39;ambiente.</li></ul> |
| Conferma sottoscrizione evento | <ul><li>Ora potete ricevere una conferma e-mail quando effettuate la sottoscrizione agli aggiornamenti per singolo evento in corso.</li></ul> |
| Miglioramenti all&#39;usabilità della navigazione globale | <ul><li>Esperienza utente coerente con `Adobe.com` il menu di navigazione di livello principale.</li></ul> |

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Aggiornamenti generali all&#39;interfaccia di Experience Cloud.

**Dominio di prodotto unificato**

Adobe ha aggiornato l’intestazione del dominio e dell’interfaccia per unificare e migliorare la tua esperienza in tutte le applicazioni Experience Cloud. Si tratta di miglioramenti progettati per semplificare la tua esperienza grazie a dettagli piccoli, ma importanti, Questi miglioramenti non modificano i flussi di lavoro correnti.

Gli aggiornamenti includono:

* Nuovi URL dell’applicazione: `experience.adobe.com/<application name>`:
   * Tutti i prodotti adotteranno questo pattern per i propri URL. Cerca i nuovi URL che diventeranno validi nel corso del mese.
   * Supporto browser: i browser supportati includono [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] e [!DNL Opera] (versioni più recenti). **Nota:** sebbene l’interfaccia di Experience Cloud supporti questi browser, le singole applicazioni potrebbero non supportare tutti i browser. Ad esempio, [Analytics](https://docs.adobe.com/content/help/it-IT/analytics/admin/sys-reqs.html) non supporta [!DNL Opera] e [Target](https://docs.adobe.com/help/it-IT/target/using/implement-target/before-implement/supported-browsers.html) non supporta [!DNL Safari].
   * (Solo per [!DNL Safari]) La modifica del dominio potrebbe causare problemi di cookie in [!DNL Safari]. Deselezionando l’opzione _Impedisci il tracciamento intersito_ nelle preferenze relative alla privacy di [!DNL Safari], i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Experience Cloud di funzionare su questo nuovo dominio.
* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* Guida di prodotto migliorata: [!UICONTROL Experience League] è stato integrato nel prodotto, in modo tale che la ricerca nella guida includa anche i risultati dei forum e dei contenuti video della community. Questa modifica semplifica l’accesso a più contenuti e ti consente di ottenere il massimo da Experience Cloud. Fai clic inoltre su **[!UICONTROL Guida]** > **[!UICONTROL Feedback]** per segnalare i problemi o condividere le tue idee con Adobe.

Le app seguenti utilizzano il nuovo dominio experience.adobe.com:

| App o servizio | Dominio |
| -----------| ---------- |
| Pagina principale di Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch  | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Gestione del percorso | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Pannello di controllo di Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribuzione software | `experience.adobe.com/downloads` |
| Strumenti di amministrazione (versione beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Bacheca e raccolte]**, un filtro legacy nel selettore [!UICONTROL Marketing Cloud Assets] , è in fase di disattivazione.

## ![Icona](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Note sulla versione [!DNL Experience Platform,] che includono [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offerte], [!UICONTROL Persone], [!UICONTROL Places], [!UICONTROL Mobile Services] e bollettini sulla sicurezza.

### Miglioramenti dell&#39;interfaccia

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] rilascia aggiornamenti al dominio e alla barra di intestazione per migliorare la tua esperienza e unificarsi con altre applicazioni Experience Cloud. Gli aggiornamenti includono:

* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* È stata migliorata l’Aiuto degli utenti, inclusi gli articoli contenuti e la documentazione pertinente al contesto nel menu Aiuto.
* Possibilità di fornire feedback sulla piattaforma Experience e sui biglietti per il supporto dei file.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Attributi del cliente - nuova documentazione

Updated: **May 15, 2020**

* [Supporto degli attributi del cliente per l&#39;applicazione CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Supporto degli attributi del cliente per il GDPR](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (General Data Protection Regulation, Regolamento generale sulla protezione dei dati)

### Journey Orchestration {#journey}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

* [Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html)
* [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html)
* [Video sulle procedure](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Informazioni aggiuntive sulla versione di Experience Platform

* [Note sulla versione di Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html)
* [Note sulla versione di Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html) (Tutti i prodotti Adobe)

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nuove funzioni nell&#39;analisi del percorso cliente](#cust-journey)
* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori](#aa-notices) di Analytics (**aggiornato il 21 maggio 2020**)
* [Correzioni](#aa-fixes) di Adobe Analytics (**aggiornato il 21 maggio 2020**)
* [AppMeasurement](#appm)
* [Nuove esercitazioni per Analytics](#tutorials-analytics)

### Nuove funzioni nell&#39;analisi del percorso cliente {#cust-journey}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Analisi]percorso cliente: Disponibilità globale | Rende [!UICONTROL Customer Journey Analytics] disponibile ai clienti nei paesi EMEA e APAC. |
| [!UICONTROL Analisi]percorso cliente: Supporto per sandbox della piattaforma [!UICONTROL Adobe Experience] | Consente di selezionare sandbox [!UICONTROL specifiche della piattaforma] Adobe Experienceper creare connessioni CJA. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Nuove funzioni di Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Funzione | Descrizione |
| -----------| ---------- |
| Supporto di Analytics per [!UICONTROL Adobe Experience Platform Edge Network] | Consente di utilizzare un singolo tag per inviare dati a più soluzioni Adobe, come Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile e Experience Cloud ID Service. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Dashboard di Adobe Analytics] | [!UICONTROL Le dashboard] di Adobe Analytics sono un&#39;app mobile che consente agli utenti di accedere in qualsiasi momento e ovunque alle informazioni provenienti da Adobe Analytics. Questa app è destinata ai dirigenti che cercano l&#39;accesso in movimento alle metriche chiave. Consente l&#39;accesso a scorecard interattive curate e saranno disponibili per i sistemi operativi iOS e Android. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL : creazione automatica di tabelle a forma libera da uno stato vuoto] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. Sono stati inoltre apportati miglioramenti al modo in cui i tipi di componenti misti (come dimensioni e metriche) vengono gestiti quando vengono rilasciati insieme in una tabella a forma libera vuota. |
| [!UICONTROL Pacchetto] Adobe Analytics aggiunto alla pagina [!UICONTROL Livello] di accesso alle funzioni | Ora puoi vedere a quale pacchetto [!UICONTROL di] Adobe Analytics (SKU) la tua azienda ha diritto in **[!UICONTROL Admin]** > **[!UICONTROL Company Settings]** > **[!UICONTROL Feature Access Level]**(Amministratore> ImpostazioniSocietà > Livello di accesso allefunzioni). |
| Miglioramenti all&#39;accessibilità | Il team di Adobe Analytics ha apportato diversi miglioramenti in termini di accessibilità ad Analysis Workspace, tra cui la navigazione tramite tastiera, il contrasto del colore e il supporto degli assistenti vocali. |

#### Correzioni di Adobe Analytics {#aa-fixes}

* Adobe ha modificato la metrica [!UICONTROL Tempo trascorso] in modo da non includere mai &quot;Non specificato&quot; nel calcolo. Ciò significa che, indipendentemente dal fatto che l&#39;interfaccia utente dica di includere &quot;Non specificato&quot;, facciamo un&#39;eccezione speciale per escludere sempre &quot;Non specificato&quot; nel calcolo del [!UICONTROL Tempo trascorso] . Pertanto, anche se hai configurato un report contenente la metrica [!UICONTROL Tempo trascorso] per includere &quot;Non specificato&quot;, restituirà sempre 0 volte per l&#39;elemento di riga &quot;Non specificato&quot;. Questo potrebbe modificare i report storici in Reporting e analisi, nonché nell&#39;API di reporting v1.4. (AN-197958)
* È stato corretto un problema in seguito al quale l&#39;istanza/visita/visitatore non veniva conteggiata nel denominatore per le metriche [!UICONTROL Tempo trascorso] .  Ciò si verifica quando un hit senza valore per la dimensione (ad esempio, [!UICONTROL Pagename]) viene seguito nello stesso secondo. (AN-211074)
* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* È stato risolto un problema nell’elaborazione di [!UICONTROL Origini dati] che causava la visualizzazione di date errate. (AN-213604)
* È stato risolto un problema a causa del quale i file di classificazione non venivano caricati correttamente su FTP. (AN-214102)
* È stato risolto un problema nel metodo API `Segments.Get` a causa del quale non veniva restituita una risposta completa. (AN-206210)
* È stato risolto un problema che causava la conversione degli elementi di riga delle tabelle in caratteri speciali nel download PDF di [!DNL Workspace]. (AN-196153)
* È stato risolto un problema che causava il funzionamento errato della chiamata `visattrcustomeridcustomerattributes` di Adobe Analytics API 1.4. (AN-186873)
* È stato risolto un problema a causa del quale i dati venivano visualizzati nei report ma non nel [!UICONTROL Feed dati]. (AN-211923)
* È stato risolto un problema a causa del quale non era possibile copiare le autorizzazioni [!UICONTROL Profilo prodotto]. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* È stato risolto un problema che impediva la visualizzazione dei dati [!UICONTROL AdWords] in [!UICONTROL Advertising Analytics]. (AN-213249)
* È stato risolto un problema a causa del quale i dati di classificazione non venivano visualizzati nella vista delle tendenze. (AN-212761)
* È stato risolto un problema a causa del quale in [!UICONTROL Segment Manager] veniva riportato un numero errato di segmenti pubblicati. (AN-213374)
* È stato risolto un problema con **[!UICONTROL Mostra tendenza verso l’alto come...]** nell&#39;Editor [!UICONTROL metrica] calcolata non funzionava quando si applicavano i filtri. (AN-214223)
* Sono stati risolti diversi problemi relativi a Importazione ed Esportazione [!UICONTROL classificazione] . (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Sono stati risolti diversi problemi con Generatore [!UICONTROL regole di]classificazione. (AN-213826, AN-213550, AN-213095)
* Sono stati risolti i problemi relativi all&#39;elaborazione di [!UICONTROL Origini] dati. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551,-217947, AN-219018, AN-214691, AN-218401)
* Sono stati corretti i problemi di connettività FTP. (AN-115525)
* Sono stati risolti diversi problemi relativi ai feed [!DNL Analytics] di  dati. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080,-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Sono stati risolti i problemi relativi alle richieste [!UICONTROL Data Warehouse] . (AN-181836)
* Sono stati risolti dei problemi relativi ai progetti [!UICONTROL Workspace] scaricati in PDF, in cui i valori venivano convertiti in caratteri speciali. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* È stato risolto un problema per il quale i formati ora nelle metriche calcolate venivano interrotti per i valori negativi. (AN-210900)
* È stato risolto un problema che impediva agli utenti di modificare il modello di [!UICONTROL attribuzione] sulle metriche delle righe statiche. (AN-207872)
* È stato risolto un problema che causava il blocco in coda del generatore di report  pianificati. (AN-215317)
* È stato corretto il connettore [!UICONTROL dati]ExactTarget. (AN-210794)
* Sono stati risolti i problemi di latenza nell’API [!UICONTROL di]ingestione in blocco. (AN-210165)
* È stato risolto un problema che impediva agli utenti di accedere al Generatore [!UICONTROL di] report con un Federated ID. (AN-207750)
* È stato risolto un problema in [!UICONTROL Advertising Analytics] che impediva la visualizzazione [!DNL Google AdWords] dei dati. (AN-213249)
* È stato risolto un problema che impediva la visualizzazione degli eventi [!UICONTROL Workspace] [!UICONTROL Project Viewed] nei registri. (AN-214134)
* È stato risolto un problema che si verificava modificando l’intervallo di date in [!UICONTROL Workspace] e selezionando **[!UICONTROL Applica a tutti i pannelli]**. La data non è cambiata in alcuni pannelli. (AN-214944)
* È stato risolto un problema che impediva la creazione o la modifica degli avvisi. (AN-215920)
* È stato corretto un problema a causa del quale tutti gli intervalli di date dinamici in [!UICONTROL Workspace] mostravano date non corrette a causa del primo giorno della settimana, che veniva occasionalmente sostituita da una domenica da un lunedì. (AN-218835)

#### Correzioni aggiuntive per Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Miglioramento della ridondanza per la disponibilità di Analysis Workspace | 21 maggio 2020 | Per garantire la disponibilità di Analysis Workspace, stiamo aggiungendo un CDN secondario (Content Delivery Network) per migliorare la ridondanza. I seguenti URL devono essere aggiunti alle whitelist del firewall di rete necessarie:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Ad esempio, si supponga che il primo hit di una visita non abbia alcun valore per le eVar, ma il secondo hit lo sia. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
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
| [Modello delle esercitazioni di formazione in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | L’esercitazione [!UICONTROL Analysis Workspace] Training illustra la terminologia e i passaggi comuni per la creazione del primo progetto in [!UICONTROL Workspace]. |
| [Aggiunta di confronti tra mesi e anni precedenti alle tendenze](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Scopri come applicare intervalli di date personalizzati per creare confronti di tendenze mensili e annuali per qualsiasi metrica in [!UICONTROL Analysis Workspace]. |
| [Estensione modalità scura per Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Abilita l’estensione Dark Reader Chrome per rendere Analysis Workspace buio. |
| [Estensione contagocce colore per definire le palette personalizzate](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Scopri come utilizzare l’estensione ColorPick EyeDropper Chrome per trovare facilmente i valori esadecimali necessari per una tavolozza di colori personalizzata nei progetti [!UICONTROL Workspace] . |

#### Risorse dell’Aiuto di Analytics

* [Esercitazioni di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentazione prodotto Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html)

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni, problemi risolti, documentazione ed esercitazioni in Audience Manager.

### Aggiornamenti dell&#39;interfaccia utente

Audience Manager sta rilasciando aggiornamenti al dominio e alla barra di intestazione per migliorare la tua esperienza e unificarsi con altre applicazioni Experience Cloud.

* Un passaggio più semplice tra le organizzazioni o verso un’altra applicazione.
* È stata migliorata l’Aiuto degli utenti, inclusi gli articoli contenuti e i video pertinenti al contesto nel menu Aiuto.
* Possibilità di fornire feedback sulla piattaforma Experience e sui biglietti per il supporto dei file.
* Un nuovo pattern URL più semplice. Aggiorna i segnalibri nel nuovo URL: `experience.adobe.com/audience-manager`.

Questi aggiornamenti sono disponibili solo per gli utenti che accedono utilizzando l&#39;Adobe ID. Per passare a un accesso ID Adobe, consulta [Gestione di utenti e prodotti](https://docs.adobe.com/content/help/it-IT/core-services/interface/manage-users-and-products/admin-getting-started.html)Experience Cloud.

### Nuove funzioni e correzioni in Adobe Audience Manager

| Funzione | Descrizione |
| -----------| ---------- |  
| [Strumenti di gestione di massa (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Abbiamo caricato un nuovo foglio di lavoro per gli strumenti di gestione di massa che: <br><br><ul><li>Consente di elencare le sottocartelle nella gerarchia delle caratteristiche (AAM-51528)</li><li>Recupera le metriche quando richiesto per le caratteristiche associate agli ID CRM (ID cross-device) (AAM-52135)</li><li>È stato risolto un problema di codifica della lingua per i caratteri coreani (AAM-AAM-54006)</li></ul> |

**Correzioni**

* È stato risolto un problema che causava il timeout dei report sulle tendenze per le cartelle con un numero elevato di caratteristiche. (AAM-54457)
* È stato risolto un problema che impediva ai clienti di visualizzare il generatore [!UICONTROL di] espressioni nel flusso di lavoro di creazione/modifica delle caratteristiche. (AAM-54255)
* È stato corretto un problema a causa del quale i messaggi di errore nell’interfaccia utente venivano visualizzati solo per un breve periodo di tempo, scomparendo prima che i clienti potessero leggerli. Ciò si verificava, ad esempio, durante il tentativo di eliminare un segmento mappato a una destinazione. (AAM-54031)
* È stato risolto un problema a causa del quale i clienti che non utilizzano più [!UICONTROL Audience Marketplace] ricevevano e-mail di fatturazione mensili. (AAM-54602)
* È stato risolto un problema che causava la visualizzazione di collegamenti interrotti invece delle caratteristiche da parte dei clienti che facevano clic su determinate caratteristiche da altre aree dell&#39;interfaccia utente. (AAM-54768)
* È stato risolto un problema a causa del quale, in modalità di espressione delle caratteristiche di modifica, premendo INVIO si aggiornava la pagina e l&#39;espressione delle caratteristiche andava persa. (AAM-54210)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nuove esercitazioni di Audience Manager {#tutorials-aam}

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Concetti e termini di base in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Questo video illustra alcuni dei termini e concetti di base per iniziare a utilizzare Audience Manager, inclusi segnali, caratteristiche, segmenti e così via. |
| [Informazioni sul flusso di dati in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Questo video ti aiuta a comprendere Adobe Audience Manager descrivendo il flusso di dati in entrata, in uscita e fuori dall’applicazione. |
| [Audience Manager - Panoramica di un DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Comprendi le sfide principali con la personalizzazione tra canali e come Adobe Audience Manager aumenta il potenziale del percorso del cliente. Scopri anche quali tipi di dati possono essere caricati in Audience Manager e quali sono i partner di sistemi eco-tecnologici integrati con Audience Manager. |
| [Casi di utilizzo di Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | In questo video identifichiamo quattro casi d’uso comuni di Audience Manager e descriviamo le best practice ad essi associate. |
| [Metriche tra dispositivi in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | Questo video illustra la differenza tra i profili dei dispositivi e i profili dei diversi dispositivi e mostra dove i numeri nell’interfaccia corrispondono a questi diversi tipi di profili. |
| [Informazioni sulle audience predittive in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | In questo video, discutiamo di cosa sono i tipi di pubblico predittivo di Audience Manager, presentiamo i dettagli sul loro funzionamento e segnaliamo i casi di utilizzo. |
| [Configurare e includere nei rapporti audience predittive in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | In questo video passiamo alla configurazione Predictive Audiences (Audience predittiva) nell&#39;interfaccia Audience Manager. Vediamo anche i rapporti che mostrano i risultati del modello. |

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **AEM come Cloud Service**

   * Miglioramenti e correzioni nell’elaborazione delle risorse. La finestra di dialogo di rielaborazione delle risorse offre all’utente maggiore controllo, consente di selezionare un profilo di elaborazione specifico e se attivare il flusso di lavoro di post-elaborazione.
   * Miglioramenti delle prestazioni di assimilazione delle risorse multimediali dinamiche.

### Aiuto e documentazione

* **Automated Forms Conversion Service - rilascio AFC-2020.03.1**

   Una nuova opzione è disponibile quando si installa il connettore più recente:

   **[!UICONTROL Rilevamento automatico delle sezioni]** logiche: è possibile utilizzare l&#39;opzione Rilevamento [!UICONTROL automatico sezioni] logiche per rilasciare i pannelli a livello di pagina (pannelli basati sul numero di pagina) e creare solo pannelli logici. Vengono inoltre raggruppati in un&#39;unica sezione logica i campi che non appartengono ad alcuna sezione con sezioni logiche e campi precedenti di una sezione logica che si estende su due pagine adiacenti. Ad esempio, se alcuni campi di una sezione logica si trovano alla fine della pagina uno e alcuni si trovano all&#39;inizio della pagina due, tutti questi campi sono raggruppati in una singola sezione logica.

* **Formati immagine non supportati in Dynamic Media**

   Informazioni sui sottotipi di formati di file immagine raster non supportati in [!UICONTROL Dynamic Media].

   Consultate Formati immagine raster [non supportati in Contenuti multimediali](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media)dinamici.

* **Frammenti di contenuto**

   Informazioni sul supporto dei frammenti di [contenuto nell’API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)HTTP di AEM Assets, nonché sulla [personalizzazione e l’estensione dei frammenti](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)di contenuto e sulla configurazione dei componenti per il rendering [dei frammenti di](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html)contenuto.

* **Community di AEM Experience League**

   Connetti con la community [AEM Experience](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)League: Fai domande a colleghi studenti ed esperti di AEM, sfogliate i thread e condividi i tuoi suggerimenti e le tue competenze!

* **Newsletter AEM**

   La newsletter AEM di [!UICONTROL Experience League] è stata progettata per aiutarvi a imparare a usare AEM in modo da poter iniziare subito a realizzare dei valori. Ecco la newsletter più recente:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager è ora disponibile come servizio cloud.
   * [Iscriviti](https://adobeeventsonline.com/AEM/2017/NL/Optin/) alla newsletter Experience Insider.
   * Gli archivi delle newsletter vengono visualizzati nella sezione Risorse [](https://helpx.adobe.com/it/support/experience-manager/6-5.html) AEM della pagina Informazioni e supporto di Adobe Experience Manager 6.5.

### Nuove esercitazioni per Experience Manager

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Configurare AEM Runtime locale](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Guida introduttiva di Risorse AEM](https://video.tv.adobe.com/v/33624?captions=ita) | Video introduttivo su Risorse AEM per gli utenti aziendali. |
| [Schemi delle cartelle di metadati](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Gli schemi di cartelle di metadati consentono agli utenti di gestire e rivedere i metadati associati alle cartelle di risorse, anziché direttamente sulle risorse. |
| [Assegnazione tag](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | I tag sono uno strumento integrale per la gestione delle risorse nella gerarchia delle cartelle delle risorse. La definizione di una tassonomia dei tag è fondamentale per consentire agli utenti di scoprire e organizzare le risorse in AEM. |
| [Profili metadati](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | I profili di metadati consentono l’applicazione automatica dei metadati predefiniti alle risorse nelle cartelle delle risorse. Questo consente di ridurre il carico di gestione dei metadati per gli utenti AEM e di aumentare la coerenza dei metadati. |
| [Schemi metadati](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Gli schemi di metadati definiscono l’interfaccia che espone i metadati delle risorse in AEM. Questo video illustra la combinazione di approcci utilizzati per applicare le risorse. |

### Risorse aggiuntive

* [Note sulla versione di AEM come servizio cloud](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM come documentazione del servizio cloud](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/landing/home.html)
* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Note sulla versione di AEM Cloud Manager](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Pagina iniziale della guida di Dynamic Media Classic](https://docs.adobe.com/content/help/it-IT/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media](https://docs.adobe.com/content/help/it-IT/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Note sulla versione di Livefyre](https://docs.adobe.com/content/help/it-IT/livefyre/using/release-notes/c-rn.html)

## ![Icona](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Campaign Standard

* [Versione di Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Pannello di controllo campagna

| Funzione | Descrizione |
| -----------| ---------- |  
| Gestione chiavi GPG | Installa e/o genera chiavi GPG in un&#39;istanza di marketing, per cifrare i dati inviati da Campaign e decifrare i dati in arrivo. |
| Gestione certificati per i sottodomini CNAME | Il Pannello di controllo ora consente di rinnovare i certificati SSL dei sottodomini delegati con il metodo CNAME. |

### Esercitazioni sulle nuove campagne

* Nuove esercitazioni per Campaign Standard

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Pannello di controllo - Gestione record Google TXT](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Scopri come aggiungere i record di verifica del sito Google TXT a tutti i tuoi sottodomini utilizzati per inviare e-mail agli indirizzi GMAIL con il Pannello di controllo della campagna. |
| [Configurare ed eseguire un flusso di lavoro con l&#39;attività API esterna](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Scoprite come chiamare un endpoint REST API esterno utilizzando l&#39;attività API esterna. |
| [Guida introduttiva alle notifiche push per Android-Tutorial](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Questa esercitazione spiega i passaggi necessari per impostare le notifiche push con Campaign Standard e Android App. |

* Esercitazioni sulla nuova campagna Classic

| Contenuto | Descrizione |
| -----------| ---------- |  
| [Gestione dei grandi dati su Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Scopri come sfruttare il connettore Snowflake in Adobe Campaign Classic. |
| [Pannello di controllo - Gestione record Google TXT](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Scopri come aggiungere i record di verifica del sito Google TXT a tutti i tuoi sottodomini utilizzati per inviare e-mail agli indirizzi GMAIL con il Pannello di controllo della campagna. |

### Risorse di aiuto per le campagne

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/campaign-standard-home.html) - [Note](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) sulla versione - Video [](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) How-to - [Release Planning](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/campaign-classic-home.html) - [Note](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) sulla versione - Video [introduttivi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- Aggiornamenti [più recenti della documentazione](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nuove funzioni in Advertising Cloud DSP](#adcloud-dsp)
* [Nuove funzionalità in Advertising Cloud Search](#adcloud-search)

### Nuove funzioni in Advertising Cloud DSP {#adcloud-dsp}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Campagne Classic] e [!UICONTROL Campagne Beta] | Le impostazioni di misurazione IAS per la frode e la sicurezza del marchio, che puoi configurare facoltativamente per ogni campagna, ora includono opzioni per misurare le scorte VAST e VPAID. |
| [!UICONTROL Campaigns Beta] | Sono state migliorate le visualizzazioni dei dati e i tempi di caricamento delle pagine. |
|  | Su tutte le pagine è ora possibile scaricare rapporti Excel basati sui filtri e sulle viste correnti. |
|  | (Nella release del 22 maggio) Le nuove metriche includono le metriche All-time, Current Interval Delivery, Date Specific OTS. |
| [!UICONTROL Blacklist] | Il sistema di previsione ora utilizza automaticamente la blacklist a livello di inserzionista o account. Gli utenti non devono più incollare la blacklist nelle impostazioni di posizionamento. |
| [!UICONTROL Offerte sulle scorte] | (Versione beta chiusa) Un nuovo modulo semplificato consente di configurare, modificare e risolvere rapidamente le offerte della piattaforma di fornitura (SSP) che non sono disponibili nella Casella in entrata ID transazione. |
|  | Quando si accetta un pacchetto di offerte garantite a livello di programmazione nella Posta in arrivo dell&#39;ID dell&#39;offerta, viene visualizzato un avviso che segnala la necessità di creare un posizionamento predefinito per ciascun ID dell&#39;offerta. |

### Nuove funzioni in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Campagne] | (account Google Ads; servizio beta) A partire dalla fine di maggio, Advertising Cloud Search sarà in grado di sincronizzare i dati per le campagne di visualizzazione Google Gmail e le campagne Google Smart Shopping con le conversioni Google per il monitoraggio e il reporting. Il servizio consente inoltre di modificare le impostazioni della campagna e del gruppo di annunci per le campagne esistenti dalle visualizzazioni Campagne e Gruppi di annunci. Il servizio sarà facoltativo. Una volta che il servizio è disponibile, si applicherà una tariffa aggiuntiva.<br>Per ulteriori informazioni sul servizio, compreso il programma beta e l&#39;ambito futuro, contatta il tuo account manager Adobe. |

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per lead management e marketer B2B che intendono trasformare le esperienze dei clienti impegnandosi in ogni fase dei percorsi d’acquisto complessi.

### Aggiornamenti principali di Marketo Engage

Per informazioni aggiornate sulla versione, consultate le note [!DNL Marketo] sulla [versione](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

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
