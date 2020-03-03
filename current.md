---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Note sulla versione di Adobe Experience Cloud - Marzo 2020

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!NOTE]
>Iscriviti ad [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: marzo 2020**

Le date di rilascio specifiche del prodotto possono variare.

* [Stato del sistema di Adobe](#status)
* [Interfaccia e servizi principali di Experience Cloud](#ecloud)  (Aggiornamento: **26 febbraio 2020**)
* [Experience Platform](#platform)
* [Mobile Services e Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (Aggiornamento: 21 febbraio 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla risoluzione problemi)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla risoluzione problemi)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

Cerchi la pagina iniziale della guida? Consulta la [documentazione di Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

**Novità**

* Utilizzando l’Adobe ID, puoi abbonarti e ricevere le notifiche relative agli eventi in base alle preferenze per prodotti, area geografica, eventi e lingua. Gli utenti che configurano le proprie preferenze di abbonamento ricevono le notifiche degli eventi relativi a problemi e manutenzione dei prodotti in concomitanza all’apertura, all’aggiornamento o alla chiusura degli stessi. Per iniziare, consulta [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| -----------| ---------- |
| Maggiore consapevolezza degli eventi relativi al prodotto | <ul><li>Ricevi con 30 giorni di anticipo le informazioni sulla prossima manutenzione del servizio. Questa funzione fornisce un lead time maggiore per valutare il potenziale impatto sulle operazioni aziendali, consentendo di implementare un piano di mitigazione, se necessario.</li><li>Le notifiche avanzate sono disponibili via web/dispositivi mobili/tablet e tramite notifiche e-mail.</li></ul> |
| Personalizza la tua esperienza in base alla lingua preferita | <ul><li>Scegli una lingua preferita per le notifiche e-mail. La funzione di auto-abbonamento è ora disponibile in diciannove lingue.</li></ul> |
| Miglioramento dell&#39;esperienza utente di abbonamento e notifica | <ul><li>Specifica con un solo clic le preferenze di regione ed evento di tutti i prodotti ai quali vuoi abbonarti.</li><li>Ricevi notifiche quando _potenziali_ problemi vengono trasferiti allo stato di _minori_ o _gravi_.</li><li>La pagina del browser si aggiorna automaticamente quando viene aggiornato lo stato di un prodotto o evento.</li></ul> |

## Interfaccia e servizi principali di Experience Cloud {#ecloud}

Aggiornamento versione: **26 febbraio 2016**

Nuove funzioni e problemi risolti nell’interfaccia Experience Cloud, tra cui gestione e servizi principali (attributi del cliente, pubblico, trigger, cookie e così via).

| Funzione | Descrizione |
| -----------| ---------- |
| Admin Tool - visualizza dettagli utente | Gli amministratori possono visualizzare un elenco ordinabile e filtrabile di tutti gli utenti Experience Cloud e dei relativi dettagli nel nuovo Admin Tool. I dettagli utente includono l’accesso ai prodotti, i ruoli e le informazioni sull’ultimo accesso. Consulta la guida [Admin Tool di Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) per ulteriori dettagli. |

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

Contenuto mobile.

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm) (aggiornato il 21 febbraio 2020)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

* **Più suite di rapporti in Analysis Workspace**: Ora puoi inserire dati da più suite di rapporti in un unico progetto di Analysis Workspace per visualizzarli uno accanto all’altro. A partire dal 12 marzo 2020, la funzionalità verrà distribuita a tutti i clienti nel corso di diverse settimane. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: Questa funzione consente di pubblicare i segmenti in Experience Cloud entro 8 ore (anziché entro 48 ore). [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### Correzioni

* È stato risolto un problema in Reporting e analisi che impediva ai clienti di scaricare i rapporti .xls.(AN-206541, AN-204008)
* L&#39;implementazione di una nuova shell ha risolto diversi problemi dei clienti relativi al passaggio a un&#39;organizzazione Experience Cloud.(AN-200844, AN-186920)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| EOL di impostazione &quot;Livello conversione&quot; | 3 marzo 2020 | L’impostazione del livello [di](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversione non funzionante in Strumenti di amministrazione > Suite di rapporti > Impostazioni account generali verrà rimossa dall’interfaccia utente il 12 marzo 2020. |
| EOL dell&#39;archivio dashboard | 3 marzo 2020 | L&#39;impostazione &quot;Visualizza archivio&quot; in Gestione dashboard in Reporting e analisi non sarà più disponibile dal 12 marzo 2020. |
| Nuovo dominio Adobe Analytics | 18 dicembre 2019 | A partire dal 16 gennaio 2020, Adobe Analytics ha iniziato a spostarsi su un nuovo dominio - `https://experience.adobe.com/analytics.`<br>**Nota:** questa modifica si applica a tutti gli utenti che accedono ad Analytics con il proprio Adobe ID o Enterprise ID.<ul><li>La modifica del dominio potrebbe causare problemi con i cookie durante il caricamento di Analytics in Safari. Deselezionando l’opzione _Impedisci il rilevamento intersito_ nelle preferenze relative alla privacy di Safari, i cookie verranno abilitati per tutti i domini (e tutte le esperienze intersito), permettendo ad Analytics di funzionare su questo nuovo dominio di Adobe Experience Cloud. Potrai utilizzare altri browser senza alcun problema, poiché questa modifica interessa solo gli utenti Safari.</li><li>La modifica del dominio potrebbe impedire il funzionamento di [!UICONTROL Activity Map] per alcuni clienti [in casi specifici](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fine del ciclo di vita - Versioni precedenti delle API di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Visualizza archivio]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per l’opzione **[!UICONTROL Visualizza archivio]** in Dashboard Manager (**[!UICONTROL Componenti > Dashboard]**). |
| Fine del ciclo di vita dell’opzione **[!UICONTROL Enforce IP Login Restrictions]** | 30 ottobre 2019 | Annuncio della data di fine del ciclo di vita, gennaio 2020, per la funzionalità di whitelisting degli accessi IP (**[!UICONTROL Enforce IP Login Restrictions]**), nel menu **[!UICONTROL Amministrazione > Impostazioni società > Sicurezza]**. |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | Entro il 31 marzo 2020, Adobe Analytics rimuoverà il supporto per TLS 1.1. Questo cambiamento fa parte del nostro impegno continuo per mantenere gli standard di sicurezza più elevati e promuovere la sicurezza dei dati dei clienti. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics è stato aggiornato da Ora del Pacifico a un valore di data e ora formattato correttamente con le informazioni sul fuso orario.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulta [AppMeasurement per le note sulla versione di JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versione 2.19.0 è stata rilasciata il 21 febbraio 2020.

## Audience Manager {#aam}

Correzioni e funzioni aggiunte ad Audience Manager.

### Nuove funzioni, miglioramenti e correzioni in Audience Manager {#aam-features}

| Funzione | Descrizione |
|----|----|
|  |  |
|  |  |

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

Correzioni per AAM.

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

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

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)     - [Pianificazione rilascio](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video tutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aggiornato il 10 febbraio 2020 per la versione dell’8 febbraio

## [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

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

**** Centro di successo Marketo: Lancio nel febbraio 2020. Success Center è un centro di assistenza interno al prodotto che consente di effettuare ricerche nei documenti sui prodotti e nella community, avviare guide informative, accedere ai contenuti di adozione e altro ancora. Nota: questa funzionalità verrà lanciata come versione beta in Australia e Nuova Zelanda e verrà implementata nel Nord America in un secondo momento nel corso del trimestre.

### Funzionalità deprecate

* **Parametro “_method” della risorsa API:** dopo settembre 2020, Asset API Endpoints non accetterà più “_method” per passare i parametri di query nel corpo di un POST per disabilitare le limitazioni relative alla lunghezza degli URI.
* **Supporto in Internet Explorer:** a partire dalla versione di luglio del 31 luglio 2020, Internet Explorer non supporterà più l’interfaccia utente di Marketo Engage.

Per leggere le note precedenti e complessive, consulta le [note sulla versione Marketo](https://docs.marketo.com/x/CgA6Ag).