---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di Adobe Experience Cloud
doc-type: release notes
last-update: September 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 113528f8e43d06e75d9fbb9db8bc229056e6f0f2
workflow-type: tm+mt
source-wordcount: '6762'
ht-degree: 39%

---


# Accesso anticipato - Note sulla versione di Adobe Experience Cloud - Settembre 2020

![Banner](/assets/experience-cloud-banner-3.png)

Questa pagina descrive nuove funzioni, correzioni e avvisi importanti in [!DNL Adobe Experience Cloud]. Inoltre mette in evidenza documentazione, corsi di formazione ed esercitazioni video farti per ottenere il massimo da Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima del rilascio ufficiale.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni.

**Data di rilascio: 10 settembre 2020**

Le date di rilascio del prodotto possono variare. Controlla spesso la disponibilità di aggiornamenti.

Ultimo aggiornamento: **4 settembre 2020**

* [Stato del sistema di Adobe](#status)
* [Interfaccia di Experience Cloud](#ecloud) 
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) e [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Primetime]](https://docs.adobe.com/content/help/it-IT/primetime/release-notes/home.html)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/#home) per trovare documentazione tecnica e dei prodotti, corsi curati da Adobe, esercitazioni video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/adobe.png) Stato del sistema di Adobe {#status}

[!UICONTROL Stato del sistema di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Consulta [Adobe Stato del sistema - 21 maggio 2020](https://docs-stg.corp.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) per le informazioni sulla versione più recente.

## ![Icona](/assets/ec_appicon_24.png) Interfaccia di Experience Cloud {#ecloud}

Consultate [Note](https://docs.adobe.com/content/help/en/core-services/interface/release-notes/release-notes.html) sulla versione cumulative per informazioni aggiornate sulla versione dell&#39;interfaccia del Experience Cloud  (Attributi del cliente, Pubblico, Amministrazione di utenti e prodotti).

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Note sulla versione per [!DNL Experience Platform] e per i servizi dell’applicazione, tra cui [!DNL Experience Platform Launch,] [!UICONTROL Offerte], [!UICONTROL Persone], [!UICONTROL Places], [!UICONTROL Mobile Services] e bollettini di sicurezza.

Data di rilascio: **12 agosto 2020**

Aggiornamenti alle funzionalità esistenti in Adobe Experience Platform:

* [Area di lavoro Data Science](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#dsw)
* [Destinazioni](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#destinations)
* [Origini](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#sources)

Per informazioni aggiornate su Experience Platform, consulta le [Note sulla versione di Experience Platform](https://docs.adobe.com/content/help/it-IT/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

###  Experience Platform e servizi esercitazioni e corsi

Nuovi video, esercitazioni o corsi pubblicati per  Experience Platform e servizi.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 17 agosto 2020 | [Debug di un&#39;implementazione di Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | Video | Introduzione ad alcuni strumenti e tecniche comuni per eseguire il debug di un&#39;implementazione di Launch. Scopri come utilizzare la console per sviluppatori del browser e l’estensione del debugger di Experience Platform  per identificare e risolvere problemi relativi agli aspetti chiave di un’implementazione di Launch. |
| 17 agosto 2020 | [Creare una configurazione di Cloud Service lancio](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | Video | Scopri come creare una nuova configurazione per Cloud Services di lancio. La configurazione del Cloud Service Launch può quindi essere applicata a un sito esistente e le librerie Launch possono essere osservate durante il caricamento sia negli ambienti Author che in quello Publish. |
| 17 agosto 2020 | [AEM Connect con Launch mediante  I/O Adobe](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | Video | Scoprite come creare una configurazione IMS con  I/O Adobe per l&#39;autenticazione AEM con l&#39;API Launch. Una volta implementata l&#39;integrazione, AEM sarà in grado di comunicare tramite l&#39;API Launch per accedere alle proprietà Launch. |
| 17 agosto 2020 | [Gestione del consenso - Supporto Google IAB TCF 2.0](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-iab-transparency-and-consent-framework-2.html) | Video | Questo video mostra come  Adobe  Piattaforma dati cliente in tempo reale aiuta i marchi a rispettare il consenso dei consumatori quando si dedicano a proprietà digitali. Grazie al supporto del framework 2.0 per la trasparenza e il consenso di IAB, i marchi ottengono una maggiore flessibilità sulle modalità di interazione con i consumatori, fornendo al contempo ai consumatori un maggiore controllo sul loro consenso. |
| 17 agosto 2020 | [Google Customer Match](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-google-customer-match.html) | Video | Questo video mostra come  capacità del Adobe CDP in tempo reale e di Google Customer Match possano aiutare i marchi a interagire con i propri clienti sulle proprietà possedute e gestite da Google con l&#39;obiettivo aziendale di aumentare le campagne di sensibilizzazione. |
| 17 agosto 2020 | [Introduzione al corso per la Guida introduttiva ad Adobe Experience Platform per gli sviluppatori di dati](https://video.tv.adobe.com/v/39478?captions=ita) | Video | Un video introduttivo per il [corso Guida introduttiva ad Adobe Experience Platform per i tecnici](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) dei dati. |
| 17 agosto 2020 | [Guida introduttiva ad Adobe Experience Platform per i tecnici dei dati](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) | Corso | Scopri come eseguire le attività chiave di Data Engineer in Adobe Experience Platform. Questo corso introduttivo utilizza video ed esercitazioni pratiche per iniziare a assimilare dati batch, assimilare dati in streaming con SDK Web, eseguire query e molto altro. |
| 17 agosto 2020 | [Introduzione al corso per iniziare con Adobe Experience Platform per gli architetti di dati](https://video.tv.adobe.com/v/39477?captions=ita) | Video | Questo video offre una panoramica del [corso Guida introduttiva ad Adobe Experience Platform per Architetti](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) dati. |
| 17 agosto 2020 | [Guida introduttiva ad Adobe Experience Platform per gli architetti di dati](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) | Video | Scopri come eseguire le attività chiave di Data Architect in Adobe Experience Platform.  Questo corso introduttivo utilizza video ed esercitazioni pratiche per iniziare a modellare i dati nello schema XDM, etichettare le identità per unire i dati in profili cliente in tempo reale, creare segmenti e altro. |

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Usando Adobe Experience Platform, coordina i percorsi dei singoli clienti su vasta scala attraverso i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ciascuno di essi, ovunque li porti il loro percorso.

### Nuove versioni del prodotto

* August release - [Read more](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#august-release)

### [!UICONTROL Corsi ed esercitazioni per Journey Orchestration]

Nuovi video, esercitazioni e corsi pubblicati per l’ [!UICONTROL Journey Orchestration].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 10 agosto 2020 | [Utilizzo degli eventi di qualificazione dei segmenti](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/using-segment-qualification-events.html) | Video | This video gives you a brief introduction on how to create a journey with a [!UICONTROL Segment Qualification] event as entry or exit point. |

### Risorse aggiuntive per Journey Orchestration

[Documentazione](https://docs.adobe.com/content/help/it-IT/journeys/using/journey-orchestration-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/journeys/using/release-notes/release-notes.html) - [Video tutorial](https://docs.adobe.com/content/help/it-IT/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni in Customer Journey Analytics](#cust-journey)
* [Nuove funzioni di Media Analytics](#media-aa)
* [Problemi risolti in Adobe Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices) 
* [Corsi ed esercitazioni di Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| ----------- | ---------- | ------- |
| [!UICONTROL Analisi multidispositivo]: disponibilità in EMEA e APAC | 31 agosto 2020 | [Analisi](https://docs.adobe.com/content/help/it-IT/analytics/components/cda/overview.html) cross-device e grafico privato sono disponibili per i clienti nell&#39;area EMEA e in APAC. |
| Miglioramento dell&#39;unione basata sul campo in Analytics  multi-dispositivo (disponibile in tutto il mondo) | 31 agosto 2020 | Questa implementazione semplificata per i nuovi clienti di [!UICONTROL Analisi multidispositivo] consente di eseguire unioni in base a un ID utente memorizzato in un campo Analytics (prop o eVar) invece di utilizzare i grafici dei dispositivi (co-op o privati). Questo miglioramento elimina il requisito di implementare l’ECID e la sincronizzazione ID ai fini del CDA. L’ECID e la sincronizzazione ID rimangono necessarie per altre funzioni. |
| Raccolta dati in Cina, fase 2 | 1 settembre 2020 | Supporto esteso per SSL di prime parti. |
| Nuovi intervalli di date in Workspace | 10 settembre 2020 | Stiamo aggiungendo 5 nuovi intervalli di date in modo da poter scegliere tra intervalli di date che non includono dati di giorno parziali da oggi: Ultimi 7 giorni interi, Ultimi 14 giorni interi, Ultimi 30 giorni interi, Ultimi 60 giorni interi, Ultimi 90 giorni interi |
| Workspace: scarica 50.000 elementi per una singola dimensione | 17 settembre 2020 | Potrai scaricare 50.000 elementi per una singola dimensione in una tabella a forma libera, con segmenti e filtri applicati. Potrai quindi accedere a più di 400 righe di dati all’esterno di Analysis Workspace. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/curate-share/download-send.html#download-items) |
| Area di lavoro: Miglioramenti alla visualizzazione [!UICONTROL Linea] | 17 settembre 2020 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/visualizations/line.html) |

### Nuove funzioni in Customer Journey Analytics {#cust-journey}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| ----------- | ---------- | ----- |
| Modifiche alle autorizzazioni del Customer Journey Analytics | 9 settembre 2020 | CJA non tratterà più tutti gli utenti come amministratori. Solo gli utenti che sono stati designati come amministratori di prodotto nell’ [Adobe Admin Console](https://docs.adobe.com/content/help/it-IT/core-services/interface/manage-users-and-products/admin-getting-started.html) saranno in grado di effettuare le seguenti operazioni:<ul><li>Creare/aggiornare/eliminare [!UICONTROL connessioni] o visualizzazioni [!UICONTROL dati]</li><li>Aggiornare/eliminare progetti, filtri o metriche di calcolo create da altri utenti</li><li>Condivisione di un progetto Workspace con tutti gli utenti</li></ul>[Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-overview/cja-overview.html#admin-access-permissions) |
| Supporto per il [!UICONTROL rilevamento anomalie] | 10 settembre 2020 | [!UICONTROL Il rilevamento] delle anomalie consente di identificare quali fluttuazioni statistiche contano e quali no. Questa funzione è ora supportata nel [!UICONTROL Customer Journey Analytics]. |
| Nuovi intervalli di date in Workspace | 10 settembre 2020 | Stiamo aggiungendo 5 nuovi intervalli di date in modo da poter scegliere tra intervalli di date che non includono dati di giorno parziali da oggi: [!UICONTROL Ultimi 7 giorni]completi, [!UICONTROL Ultimi 14 giorni]completi, [!UICONTROL Ultimi 30 giorni]completi, [!UICONTROL Ultimi 60 giorni]completi, [!UICONTROL Ultimi 90 giorni interi] |
| Area di lavoro: Miglioramenti alla visualizzazione [!UICONTROL Linea] | 17 settembre 2020 | <ul><li>You can show or hide the x-axis and y-axis of any [!UICONTROL Line] visualization. This can be especially helpful when your [!UICONTROL Line] visualizations are more compact.</li><li>You can overlay a minimum and maximum value label on any [!UICONTROL Line] visualization to quickly highlight the peaks and valleys in a metric.</li><li>You can overlay different regression trend lines on any [!UICONTROL Line] visualization to more easily see the trend in the data. Options include [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] and [!UICONTROL Quadratic].</li></ul> [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/visualizations/line.html) |

### Nuove funzioni di [!UICONTROL Media Analytics] {#media-aa}

| Funzione | [Disponibilità generale](https://docs.adobe.com/content/help/it-IT/analytics/landing/an-releases.html) - data di Target | Descrizione |
| ----------- | ---------- | ---------- |
| Pannello Visualizzatori simultanei di contenuti multimediali in Workspace | 17 settembre 2020 | The [!UICONTROL Media Concurrent Viewers] panel enables you to understand where peak concurrency occurred or where drop-offs happened. Fornisce informazioni utili sulla qualità dei contenuti e sul livello di coinvolgimento dei visualizzatori e aiuta nella risoluzione dei problemi o nella pianificazione di volumi/scala. [Ulteriori informazioni...](https://docs.adobe.com/content/help/en/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Problemi risolti in Adobe Analytics {#aa-fixes}

* È stato risolto un problema che impediva il filtraggio delle colonne di [!UICONTROL Workspace] in base alla dimensione &quot;non specificata&quot;. (AN-222393)
* È stato risolto un problema di timeout di connessione che impediva la distribuzione di progetti  pianificati. (AN-223916)
* È stato risolto un problema con i segmenti [!UICONTROL Visita] nelle suite [!UICONTROL di rapporti] virtuali che non funzionavano correttamente. (AN-225719)
* È stato risolto un problema relativo alla versione del browser Chrome in Adobe Report Builder. (AN-226718)
* È stato risolto un problema relativo alle suite [!UICONTROL di rapporti] virtuali curate che potevano ancora essere suddivise per qualsiasi dimensione/metrica nella VRS. (AN-228035)
* È stato risolto un problema con la funzionalità di ricerca nella scheda Gestione  segmenti che funzionava correttamente. (AN-226954)
* È stato risolto un problema relativo agli errori di timeout in [!UICONTROL Workspace] quando si tentava di condividere progetti con più utenti. (AN-229443)
* È stato risolto un problema con le richieste API che generavano un errore di sistema. (AN-229537)
* È stato risolto un problema di Generatore [!UICONTROL regole di] classificazione che impediva la classificazione dei valori chiave. (AN-229786, AN-230300, AN-230563)
* È stato risolto un problema con l&#39;API [!UICONTROL Data Insertion] che impediva la generazione di rapporti su alcuni dati. (AN-230587)
* È stato risolto un problema che impediva alla richiesta di [!UICONTROL Data Warehouse] di ottenere e verificare un file con nome di base. (AN-230642)
* ([!UICONTROL Customer Journey Analytics]) È stato risolto un problema di autorizzazioni per la condivisione di progetti in CJA. (AN-226592)

#### Ulteriori correzioni di Adobe Analytics

AN-215683; AN-216894; AN-226370; AN-227138; AN-227154; AN-227328; AN-227486; AN-227672; AN-228264; AN-228960; AN-229031; AN-229274; AN-229319; AN-229353; AN-229537; AN-229610; AN-229975; AN-230008; AN-230015; AN-230347; AN-230468; AN-230473; AN-231326; AN-231329; AN-231345; AN-231509; AN-231795; AN-231901

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| ----------- | ---------- | ---------- |
| Migrazione del dominio da `omniture.com` a `adobe.com` | 21 agosto 2020 | Il 13 agosto 2020, l’architettura front-end di Adobe Analytics è stata migrata dal dominio `omniture.com|http://omniture.com/` al dominio `adobe.com|http://adobe.com/`. Questa modifica dovrebbe attenuare i problemi relativi ai cookie di terze parti derivanti dal cambio iniziale del dominio unificato del prodotto del 28 maggio 2020. As a result of this update, the browser may prompt users to trust the new an `.adobe.com|http://an.adobe.com/` or `experience.adobe.com|http://experience.adobe.com/` domain. |
| Aggiornamento sulla compatibilità con Java 8 di Ad Hoc Analysis | 21 agosto 2020 | Ad Hoc Analysis non è attualmente compatibile con Java 8 versioni 1.8.0_261 e successive. Per evitare problemi nell’accesso a questo strumento prima del raggiungimento della [data di fine del ciclo di vita](https://spark.adobe.com/page/S9Bhp66VJ2fEn/), si consiglia di mantenere una versione di Java 8 precedente alla versione 1.8.0_261. |
| Fine del ciclo di vita di Adobe Data Connectors | 13 luglio 2020 | Adobe [!UICONTROL Data Connectors] si basano su una tecnologia legacy, che non è più disponibile o supportata. Per continuare a offrire e supportare le integrazioni, si consiglia di adottare il nuovo programma standard [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). La data ufficiale di fine del ciclo di vita è ancora da definire, ma è prevista nei prossimi 12-18 mesi, nella seconda metà del 2021. [Ulteriori informazioni...](https://docs.adobe.com/content/help/it-IT/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mappatura delle suite di rapporti per organizzazioni IMS | Luglio 2020 | Lo strumento di mappatura delle suite di rapporti verrà terminato a novembre 2020. Questa funzione consente integrazioni quali la pubblicazione di segmenti Advertising Analytics e Experience Cloud in Adobe Analytics. Una suite di rapporti deve essere mappata su un’organizzazione IMS per abilitare questi e altri servizi. Le nuove suite di rapporti vengono mappate automaticamente al momento della creazione. Tuttavia, le suite di rapporti meno recenti devono essere mappate manualmente su un’organizzazione IMS. Per accertarti che tutte le suite di rapporti appartengano a un’organizzazione IMS, consulta la sezione su come [mappare le suite di rapporti su un’organizzazione](https://docs.adobe.com/content/help/it-IT/core-services/interface/about-core-services/report-suite-mapping.html) nella guida utente dell’interfaccia di Experience Cloud (Servizi core). |
| Migrazione a un dominio di prodotto unificato | Data di validità: 28 maggio 2020 | La migrazione a un dominio di prodotto unificato per Adobe Analytics, iniziata a gennaio 2020, è stata completata il 28 maggio 2020. Adobe Analytics si impegna a rimuovere dalla propria architettura tutti i riferimenti al dominio `omniture.com`, ma è importante inserire `omniture.com` nell’elenco Consentiti in quanto cookie di terze parti. A breve, quando verrà portata a termine la migrazione dell’architettura, riceverai una notifica tramite le note sulla versione e non sarà più necessario compiere questo passaggio. [Qui](https://helpx.adobe.com/it/analytics/kb/adobe-ip-addresses.html) puoi trovare un elenco completo degli indirizzi IP consigliati e dei domini che dovresti inserire nell’elenco dei consentiti.<br>Se l’organizzazione blocca i cookie di terze parti, contatta l’assistenza clienti per recuperare l’accesso ad Adobe Analytics. |
| Nuova pagina di destinazione predefinita di Adobe Analytics | Data di validità: 18 giugno 2020 | Il 18 giugno 2020 la pagina di destinazione predefinita per Adobe Analytics passerà da [!UICONTROL Reports] a [!UICONTROL Workspace]. Questa modifica verrà applicata agli utenti che non hanno precedentemente impostato una pagina di destinazione personalizzata. |
| Elenco delle tecnologie di terze parti consentite | 12 marzo 2020 (data effettiva) | Adobe Analytics ha iniziato a sfruttare tecnologie di terze parti per la gestione del rollout delle funzioni e per il supporto integrato nel prodotto. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti per assicurare l’accesso a tutte le funzioni:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Miglioramento della ridondanza per la disponibilità di [!UICONTROL Analysis Workspace] | 21 maggio 2020 | Per assicurare la disponibilità di [!UICONTROL Analysis Workspace], verrà aggiunta una rete per la distribuzione di contenuti (CDN) secondaria per migliorare la ridondanza. Gli URL seguenti devono essere aggiunti a eventuali elenchi di firewall di rete consentiti:<ul><li>`https://aaui-879784980514.s3.us-east-2.amazonaws`</li><li>`https://d30ln29764hddd.cloudfront.net`</li><li>`https://awaascicdprodva7.blob.core.windows.net`</li><li>`https://aauicdnva7.azureedge.net`</li></ul> |
| Modifica del metodo di calcolo di [!UICONTROL Entrate/Uscite] in [!UICONTROL Workspace] | 7 aprile 2020 | A partire da marzo 2020, in [!UICONTROL Analysis Workspace] è stato modificato il modo in cui il valore _None_ interagisce con [!UICONTROL Entrate/Uscite]. Poiché ora in [!UICONTROL Analysis Workspace] è possibile attivare e disattivare i valori _None_, viene applicato il valore _None_ dopo l’entrata o l’uscita, mentre per le eVar veniva applicato prima dell’entrata o dell’uscita. Ad esempio, si supponga che il primo risultato di una visita non presenti alcun valore per le eVar, ma il secondo sì. In [!UICONTROL Reports &amp; Analytics] il primo risultato verrà visualizzato come _non specificato_ per l’Entrata, ma in [!UICONTROL Analysis Workspace] verrà visualizzato come valore per il secondo risultato. |
| Fine del ciclo vita di **[!UICONTROL Archivio dashboard]** | 27 marzo 2020 | L’impostazione **[!UICONTROL Visualizza archivio]** nella sezione **[!UICONTROL Gestione dashboard]** in [!UICONTROL Reports &amp; Analytics] non sarà più disponibile da ottobre 2020. |
| Fine del ciclo di vita delle API legacy di Analytics | 9 gennaio 2020 | A partire da novembre 2020, i seguenti servizi appartenenti alle versioni precedenti delle API di Analytics termineranno il loro ciclo di vita e saranno chiusi. Le integrazioni esistenti create utilizzando questi servizi cesseranno di funzionare. <ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Abbiamo messo a disposizione una [FAQ per le versioni precedenti dell’API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere alle tue domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe IO](https://console.adobe.io/home?mv=email) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| San Jose FTP Broker in scadenza per Londra e Singapore | Luglio 2020 | Per i clienti di Londra e Singapore, non supporteremo più il brokering dei dati tra Londra o Singapore e il data center di San Jose [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Per Londra, utilizzare [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Per Singapore, utilizzare [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Fine del ciclo di vita di Ad Hoc Analysis | 6 agosto 2018 | Adobe ha annunciato l’intenzione di terminare Ad Hoc Analysis. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita. Per ulteriori informazioni, visita [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### AppMeasurement {#appm}

Per gli ultimi aggiornamenti sulle versioni di AppMeasurement, fare riferimento alle [note sulla versione di AppMeasurement per JavaScript](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-updates.html).

### Analytics courses and tutorials {#tutorials-analytics}

New courses, tutorials, and articles in [!DNL Analytics] and [!UICONTROL Customer Journey Analytics].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 30 agosto 2020 | [Salvataggio, condivisione e collaborazione su progetti in  Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/saving-sharing-and-collaborating-on-projects-in-analysis-workspace.html) | Video | In [!UICONTROL Analysis Workspace], scopri come aggiungere spiegazioni di testo a una tabella, creare un collegamento diretto per il progetto e condividerlo. |
| 28 agosto 2020 | [Introduzione al corso - Attribuzione del valore ai punti di contatto digitali nel percorso del cliente](https://video.tv.adobe.com/v/39380?captions=ita) | Video | In questo video introduttivo, scopri i prerequisiti e i contenuti del corso per il valore [attribuito ai punti di contatto digitali nel corso Percorso](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) del cliente. |
| 28 agosto 2020 | [Attribuzione del valore ai punti di contatto digitali nel percorso del cliente](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) | Corso | Scopri i visitatori del tuo sito, capendo cosa li ha portati sul tuo sito, come allocare crediti per la conversione sul tuo sito a canali diversi, e anche come altri elementi del tuo sito guidano la conversione. Questo corso illustra le principali visualizzazioni che mostrano questa analisi e come utilizzare [!UICONTROL Attribution IQ] per assegnare i modelli di attribuzione nell’analisi. |
| 21 agosto 2020 | [Utilizzo dell&#39;analisi interscheda per esplorare le attribuzioni di marketing di base in  Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/attribution-iq/using-cross-tab-analysis-to-explore-basic-marketing-attribution-in-analysis-workspace.html) | Video | Esistono molti modi per portare la metodologia di attribuzione al livello successivo con  Adobe Analytics. In questo video, viene evidenziato come ottenere informazioni più approfondite dal rapporto [!UICONTROL Marketing Channels (Canali] di marketing) mediante l’analisi a schede in [!UICONTROL Workspace]. |
| 21 agosto 2020 | [Fare clic con il pulsante destro del mouse per migliorare l&#39;efficienza dell&#39;area di lavoro](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/right-click-for-workspace-efficiency.html) | Video | Scopri tutti i nostri clic  Analysis Workspace preferiti e come usarli. Dalle tabelle a forma libera alle visualizzazioni Abbandono, facendo clic con il pulsante destro del mouse potrai essere più efficiente e competente in Workspace. |

### Risorse dell’Aiuto di Analytics

* [Esercitazioni di Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentazione dei prodotti Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html)

## ![Icona](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuove funzioni, correzioni, documentazione ed esercitazioni in Audience Manager.

Data di rilascio: **20 settembre 2020**

### Nuove funzioni e correzioni in Adobe Audience Manager

* È stato risolto un problema in [!UICONTROL Audience Lab] a causa del quale una popolazione di segmenti di test non era disponibile in [!UICONTROL Aggregate Reporting (Generazione rapporti]aggregati). (AAM-54553)
* È stato risolto un problema a causa del quale i segmenti che utilizzano modelli algoritmici di terze parti non venivano visualizzati nella visualizzazione Uso  segmento in [!UICONTROL Audience Marketplace]. (AAM-54595)
* È stato risolto un problema che causava errori in alcuni utenti durante il tentativo di eliminazione delle origini dati, anche se non erano state mappate caratteristiche o segmenti alle origini dati. (AAM-55609)
* È stato risolto un problema che impediva la visualizzazione dei segmenti nel rapporto Visualizzatore profilo visitatore. (AAM-55780)
* È stato risolto un problema nella pagina dell&#39;elenco Destinazioni, a causa del quale dopo aver selezionato **[!UICONTROL Durata]** nel filtro **[!UICONTROL Look Back Window for Metrics]** , veniva restituita una pagina vuota. (AAM-49732)
* È stato risolto un problema nel dashboard delle caratteristiche in cui, filtrando da **[!UICONTROL Tutte le caratteristiche]** a qualsiasi filtro (basato su **[!UICONTROL regole]**, **[!UICONTROL Configurato]**, ecc.), le metriche venivano aggiornate, ma il nome e l&#39;ID della caratteristica non lo erano. (AAM-55823)
* È stato risolto un problema nelle destinazioni [!UICONTROL basate su]Persone, a causa del quale i segmenti mappati su Facebook non venivano aggiornati a causa di un campo mancante `traitAlias` in una chiamata API. (AAM-55952)
* È stato risolto un problema nei report [!UICONTROL sulle] tendenze per cui il grafico non veniva aggiornato quando si selezionava tra caratteristiche e segmenti (AAM-54736)
* È stato risolto un problema in Modellazione [!UICONTROL simile a] Look: premendo il controllo **[!UICONTROL Pausa]** il modello non veniva messo in pausa, ma chiuso. (AAM-56121)
* Miglioramenti di accessibilità in tutta l’interfaccia. (AAM-48950, AAM-48957, AAM-49022, AAM-49026, AAM-49044, AAM-49069, AAM-49370, maturo-55989, 5990).

### Audience Manager courses and tutorials {#tutorials-aam}

Nuovi video, esercitazioni o corsi pubblicati per  Audience Manager.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 17 agosto 2020 | [Mappatura  segmenti di Audience Manager alle destinazioni](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/mapping-audience-manager-segments-to-destinations.html) | Video | Scopri i diversi tipi di destinazioni nel  Audience Manager e i dettagli della mappatura dei segmenti su ciascun tipo di destinazione. |
| 14 agosto 2020 | [Ottenere il massimo dalle regole di unione dei profili - Suggerimenti, trucchi e strategie](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/customer-tips-getting-the-most-out-of-profile-merge-rules.html) | Articolo | Varun Kalra, Consulente per più soluzioni di [!DNL Accordant], fornisce suggerimenti sulla scelta e l&#39;utilizzo delle regole [!UICONTROL di unione]dei profili. |
| 14 agosto 2020 | [Best practice per caratteristiche e segmenti](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/customer-tips-traits-and-segments-best-practices.html) | Articolo | Matt Vittorioso, Senior Marketing Specialist di [!DNL Ally Financial], fornisce suggerimenti sulla gestione delle caratteristiche. |
| 12 agosto 2020 | [Informazioni e configurazione della destinazione basata sulle persone di corrispondenza dei clienti Google](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-google-customer-match-pbd.html) | Video | Questo video illustra i dettagli e il caso di utilizzo della destinazione [!UICONTROL Google Customer Match basata sulle]persone e include una procedura dettagliata per creare un segmento e mapparlo a una destinazione. Mostra anche l&#39;audience che ha avuto inizio in Google Ad Console. |
| 13 agosto 2020 | [Introduzione al corso - Creazione di segmenti di pubblico e strategie](https://video.tv.adobe.com/v/39091?captions=ita) | Video | In questo video, scopri cosa ti aspetta all’interno del corso Creazione di segmenti di pubblico e Strategie. |
| 13 agosto 2020 | [Utilizzo della vista Codice durante la creazione di segmenti ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-when-building-segments.html) | Video | Scopri come utilizzare la vista codice per definire i segmenti, consentendo di creare combinazioni di caratteristiche complesse, compreso l’utilizzo di frequenza e rettitudine. |
| 21 agosto 2020 | [Creazione e strategie di segmenti di pubblico](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.2) | Corso | In questo corso, impara i segmenti da A a Z. Scopri come crearli, gestirli e attivarli nei partner di destinazione. Consulta alcuni utili casi di utilizzo e ottieni persino suggerimenti e trucchi dai clienti. |

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Aggiornamenti dei prodotti

* **AEM 6.5.6.0** AEM 6.5, Service Pack 6 (6.5.6.0 rilasciato il 3 settembre 2020) è un aggiornamento importante che include nuove funzioni, miglioramenti chiave per i clienti, prestazioni migliorate, stabilità e sicurezza, rilasciato a partire dalla data di disponibilità generale del AEM 6.5, aprile 2019.
   * [Note sulla versione](https://helpx.adobe.com/it/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Rilascio delle versioni finali di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.2** AEM 6.4, Service Pack 8, Cumulative Fix Pack 2 (6.4.8.2 rilasciato il 3 settembre 2020) è un aggiornamento importante che include diverse correzioni interne e per i clienti, a partire dalla disponibilità generale di AEM 6.4, Service Pack 8 (6.4.8.0), marzo 2020.
   * [Note sulla versione](https://docs.adobe.com/content/help/it-IT/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Rilascio delle versioni finali di AEM Forms](https://helpx.adobe.com/it/aem-forms/kb/aem-forms-releases.html)

### Rilasci di prodotti

* **[!UICONTROL AEM as a Cloud Service]**

   What is new on [!UICONTROL AEM as a Cloud Service]? Le novità principali includono:

   * Possibilità di [!UICONTROL AEM come Cloud Service] per [ripristinare pagine e sottopagine (strutture ad albero pagina) in una versione](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/features/page-versions.html#reinstating-versions)precedente.
   * La transcodifica video è ora supportata con i micro-servizi delle risorse, con una nuova sezione [!UICONTROL Video] nella schermata Profili [!UICONTROL di] elaborazione che supporta la configurazione del bitrate e delle dimensioni video (il formato di output è MP4 con il codec H.264). Per informazioni dettagliate, consultate [Gestione delle risorse video.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/manage-video-assets.html#transcode-video) Per ulteriori opzioni di transcodifica e distribuzione di video è possibile utilizzare il componente aggiuntivo [!UICONTROL Contenuti multimediali] dinamici.
   * Una nuova esperienza di download delle risorse consente di:
      * Download asincrono per i download di grandi dimensioni in modo che gli utenti non debbano attendere.
      * Una nuova API modulare per l&#39;estensibilità degli sviluppatori.
   * Ora potete annullare la validità della cache CDN (Content Delivery Network) direttamente da [!UICONTROL Dynamic Media] in [!UICONTROL AEM come Cloud Service] (anziché utilizzare [!UICONTROL Dynamic Media Classic]) per garantire che le risorse più recenti vengano servite in pochi minuti invece che in poche ore. Consultate [Annullamento della validità della cache CDN per mezzo di elementi multimediali dinamici.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)
   * Il supporto per l’accesso facilitato è stato aggiunto ai controlli dell’interfaccia utente, alla navigazione, alla navigazione e all’esperienza di ricerca nelle risorse.
   * AEM versione 2.0.3 dell&#39;app desktop è ora disponibile, migliorando la compatibilità con AEM 6.5, Service Pack 5 (AEM 6.5.5) e aggiornando l&#39;elenco di compatibilità del sistema operativo client (rimuovendo le versioni di Windows 7 e MacOS precedenti alla 10.14).
   * [!UICONTROL La funzionalità della console] prodotto è ora disponibile in AEM [!UICONTROL Commerce come Cloud Service]. Questo consente agli esperti di marketing e agli autori di AEM di visualizzare e navigare tra le categorie e i prodotti memorizzati nel back-end del commercio. È inoltre disponibile il supporto per le proprietà di categorie e prodotti nella console  Prodotti.
   * [!UICONTROL Sono stati migliorati i selettori prodotti] e [!UICONTROL categorie] per consentire agli addetti al marketing di selezionare il prodotto tramite SKU o di selezionare la categoria in base all&#39;ID categoria.
   * [!UICONTROL Content Audit] è una funzione abilitata nelle pipeline [!UICONTROL di produzione di]Cloud Manager Sites. La configurazione [!UICONTROL della pipeline] di produzione per i programmi con [!UICONTROL Siti] ora include una terza scheda denominata **[!UICONTROL Controllo]** contenuto. Ogni volta che viene eseguita una pipeline di produzione, nella pipeline verrà incluso un nuovo passaggio di controllo  dei contenuti dopo il test funzionale personalizzato, che valuterà il sito in base a una serie di dimensioni, tra cui prestazioni, SEO (ottimizzazione motore di ricerca), accessibilità, best practice e PWA (app Web progressiva).
Consultate Test di controllo [del contenuto.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/content-audit-testing.html)
   * Gli ambienti creati di recente nei programmi [!UICONTROL Assets] ora verranno configurati automaticamente con [!UICONTROL Smart Content Services].
   * Gli ambienti con sospensione possono essere disattivati dalla pagina **[!UICONTROL Panoramica]** di Cloud Manager.
   * Possibilità di eseguire controlli dell’esperienza sulle pagine, basati su [!DNL Google Lighthouse]. Come parte della pipeline di [!UICONTROL Cloud Manager] , è possibile controllare e convalidare fino a 25 pagine in base ai KPI dell&#39;esperienza e visualizzare i punteggi nell&#39;interfaccia utente di [!UICONTROL Cloud Manager] .
   * See the [AEM as a Cloud Service release notes.](https://docs.adobe.com/content/help/it-IT/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

* **Experience Manager Appdesktop 2.0.3.2**

   Questa versione secondaria includeva quanto segue:
   * È stato risolto un problema per cui l&#39;app desktop versione 2.0.2 per Windows non funzionava con l&#39;istanza AEM 6.5.5.
   * Aggiornamento delle piattaforme OS supportate a Win 10 con il service pack più recente e Mac OS 10.14 o versione successiva.
   * See the [release notes.](https://docs.adobe.com/content/help/it-IT/experience-manager-desktop-app/using/release-notes.html)

* **[!UICONTROL AEM Assets Brand Portal]**

   Questa versione include quanto segue:
   * Visualizzatore di documenti per un’esperienza di visualizzazione PDF avanzata.
   * Miglioramenti nella configurazione e nell’esperienza di download delle risorse.
   * Correzioni ai problemi critici dei prodotti.
   * See the [release notes.](https://docs.adobe.com/content/help/it-IT/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### **Aiuto e documentazione**

* **Nuovi strumenti per[!UICONTROL AEM come transizione di Cloud Service]**

   * Plug-in AIO-CLI rilasciato per unificare gli strumenti di refactoring del codice per consentire agli sviluppatori di richiamare ed eseguire strumenti di refactoring del codice da un&#39;unica posizione. Per ulteriori informazioni, consulta la sezione GitHub resource [aio-cli-plugin-aem-cloud-service-migration](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) .
   * [!UICONTROL AEM Dispatcher Converter] esteso per supportare le conversioni delle configurazioni del Dispatcher  Managed Services in AEM di Adobe e locale  come configurazioni del Dispatcher compatibili con il Cloud Service. Per ulteriori informazioni, consulta GitHub resource [AEM Cloud Service Dispatcher Converter](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/dispatcher-converter) .
   * AEM Dispatcher Converter riscritto in node.js e integrato con il plug-in AIO-CLI.

* **Annullamento della validità CDN nel supporto[!UICONTROL dinamico]**

   Ora potete inviare una richiesta dall’interno di [!UICONTROL Dynamic Media] affinché la cache CDN scada in pochi minuti. Questa funzione è utile quando apportate aggiornamenti alle risorse e desiderate che tali modifiche diventino attive immediatamente sul sito Web.

   Consultate [Annullamento della validità della cache CDN per mezzo di file multimediali dinamici.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)

* **Tempi di attivazione e disattivazione per la pubblicazione delle pagine**

   Quando si pubblicano le pagine utilizzando i tempi di [attivazione e disattivazione](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/page-properties.html#basic), vedere la scheda Base di Proprietà pagina, è ora possibile [preconfigurare la replica](https://docs.adobe.com/help/en/experience-manager-cloud-service/operations/replication.html#on-and-off-times-trigger-configuration)automatica.

* **[!UICONTROL Componenti core]**

   [!UICONTROL La release 2.11.0 dei componenti] core supporta AMP ed è ora disponibile insieme alla documentazione [sull’](https://docs.adobe.com/content/help/it-IT/experience-manager-core-components/using/introduction.html) authoring e ai dettagli per [gli sviluppatori e al download del progetto disponibili su GitHub.](https://github.com/adobe/aem-core-wcm-components)

* **[!UICONTROL Forms]**

   * Sono disponibili procedure guidate per siti di riferimento [Gov e We.Finance aggiornati](https://docs.adobe.com/content/help/it-IT/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) . È possibile utilizzare questi siti di riferimento per apprendere flussi di lavoro end-to-end per creare e distribuire moduli per i vertici governativi e finanziari.
   * È disponibile un’implementazione [di esempio di Salva come SPI](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#sample-ccrDocumentInstance-spi) bozza. Potete utilizzare l’esempio per implementare la funzione [!UICONTROL Salva come bozza] nell’interfaccia utente [!UICONTROL dell’agente di comunicazione]interattiva. Consente agli agenti di salvare e recuperare le bozze per accelerare la generazione delle comunicazioni interattive.
   * Istruzioni per [installare e convalidare l&#39;installazione di Visual C++ redistributable](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/installing-configuring-aem-forms-osgi.html#automatic-installation-visual-studio-redistributables) durante l&#39;installazione [!UICONTROL pacchetto aggiuntivo AEM Forms] è disponibile. Questo aiuta a ridurre gli errori relativi all&#39;installazione e alla configurazione redistribuibili di Visual C++.
   * [La configurazione  Adobe Sign con la documentazione relativa ai moduli](https://docs.adobe.com/content/help/en/experience-manager-65/forms/adaptive-forms-advanced-authoring/adobe-sign-integration-adaptive-forms.html) adattivi è stata testata e rinnovata. Include ora ulteriori istruzioni per configurare  Adobe Sign con moduli adattivi in modo più semplice.
   * ([!UICONTROL AEM Forms] solo su JEE) È disponibile la documentazione per [creare un gestore di utenti esterni per l&#39;invito per il servizio](https://docs.adobe.com/content/help/en/experience-manager-65/forms/developer-reference/programming-aem-forms-jee/developing-spis-aem-forms/creating-invite-external-users-handler.html) di Rights Management.

### **Community**

* **Ultimi contenuti AEM su Experience League**

   Questa è la fonte ufficiale dei contenuti tecnici di Digital Experience prodotti da Adobe. Vedi l’elenco completo [qui.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156)

### Nuovi corsi ed esercitazioni di Experience Manager

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| 31 agosto 2020 | [Configurare i modelli XDP per utilizzare  integrazione AEM Forms e  Adobe Sign](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/using-xdp-templates-with-adobe-sign.html) | Video | Sfruttare i modelli XDP esistenti con l&#39;integrazione [!UICONTROL AEM Forms] e Sign. |
| 17 agosto 2020 | [Revisione e configurazione del modulo adattivo convertito](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-converted-adaptive-form.html) | Video | Configurare il modulo adattivo creato dal servizio moduli automatizzati per utilizzare &#39;integrazione Adobe Sign. Modificate i titoli del pannello e riorganizzate alcuni campi in base alle vostre esigenze. |
| 25 agosto 2020 | [Configurazione del modulo adattivo per due firmatari](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-adaptive-form-for-two-signers.html) | Video | Configura più firmatari e specifica l’ordine (sequenziale o parallelo) tramite l’interfaccia Forms adattiva. |
| 17 agosto 2020 | [Configurazione dell&#39;accesso a AEM](https://video.tv.adobe.com/v/39230?captions=ita) | Video | Scoprite in che modo gli utenti si autenticano utilizzando  Adobe IMS per [!UICONTROL AEM come Cloud ServiceAdobe], e in che modo  utenti IMS, gruppi [!UICONTROL di]utenti e profili [!UICONTROL di] prodotto vengono utilizzati per controllare l&#39;accesso a AEM e alle relative funzioni e funzionalità. |
| 17 agosto 2020 | [Configurazione dell&#39;accesso alla AEM dettagliata](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/walk-through.html) | Video | Procedura dettagliata per la configurazione  Adobe IMS Users, [!UICONTROL User Groups]e [!UICONTROL Product Profiles] in  Adobe [!UICONTROL Admin Console]. Inoltre, scoprite come sfruttare questi  Adobi di astrazioni IMS in [!UICONTROL AEM Author] per definire e gestire autorizzazioni specifiche basate su gruppi. |
| 17 agosto 2020 | [AEM utenti, gruppi e autorizzazioni](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/aem-users-groups-and-permissions.html) | Video | Adobe Experience Manager si basa  utenti IMS, gruppi [!UICONTROL di]utenti e profili [!UICONTROL di] prodotto di Adobe per fornire l&#39;accesso personalizzabile a AEM. Scoprite come definire AEM gruppi e autorizzazioni e come interagire con  astrazioni IMS del Adobe per fornire un accesso diretto e personalizzabile alle AEM. |
| 17 agosto 2020 | [Debug di un&#39;implementazione di Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | Video | Introduzione ad alcuni strumenti e tecniche comuni per eseguire il debug di un&#39;implementazione di Launch. Scoprite come utilizzare la console per sviluppatori del browser e l&#39;estensione [!UICONTROL Debugger] di Experience Platform per identificare e risolvere problemi relativi ad aspetti chiave di un&#39;implementazione di Experience Platform Launch. |
| 17 agosto 2020 | [Creare una configurazione di Cloud Service lancio](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | Video | Scoprite come creare una nuova configurazione di Cloud Services di Experience Platform Launch. La configurazione del Cloud Service Launch può quindi essere applicata a un sito esistente e le librerie Launch possono essere osservate durante il caricamento sia negli ambienti Author che in quello Publish. |
| 17 agosto 2020 | [AEM Connect con Launch mediante  I/O Adobe](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | Video | Scoprite come creare una configurazione IMS con  I/O Adobe per l&#39;autenticazione AEM con l&#39;API Experience Platform Launch. Una volta implementata l&#39;integrazione, AEM sarà in grado di comunicare tramite l&#39;API Launch per accedere alle proprietà Launch. |
| 17 agosto 2020 | [Creare una proprietà Launch](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-property.html) | Video | Scopri come creare una proprietà Launch con la configurazione minima necessaria per impostare il resto dell’integrazione. Gli utenti verranno presentati all’interfaccia utente di Launch e verranno fornite informazioni su estensioni, regole e flussi di lavoro di pubblicazione. |
| 17 agosto 2020 | [Integrazione di Experienci Platform Launch e AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/overview.html) | Video | Il Experience Platform Launch è  piattaforma di gestione tag  di nuova generazione e il modo migliore per distribuire  Adobe Analytics, [!DNL Target],  Audienci Manager e molte altre soluzioni. Ottenete una panoramica dell&#39;Experience Platform Launch e dell&#39;integrazione consigliata con Adobe Experience Manager. |
| 17 agosto 2020 | [Configurazione di AEM Assets per gli amministratori](https://video.tv.adobe.com/v/37647?captions=ita) | Video | In questo video, gli amministratori possono imparare a configurare [!UICONTROL AEM Assets]. |
| 12 agosto 2020 | [Sviluppo locale con SDK di AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/develop.html) | Video | Scopri come impostare un ambiente di sviluppo locale per [!UICONTROL AEM Commerce] e il [!UICONTROL AEM come Cloud Service SDK di] . |
| 17 agosto 2020 | [Precompilazione dei moduli adattivi mediante il modello dati del modulo](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.forms) | Corso | È possibile precompilare i campi di un modulo adattivo utilizzando i dati esistenti. In questo corso, imparare a precompilare i campi utilizzando l&#39;attributo di richiesta del modello dati del modulo. |
| 17 agosto 2020 | [Profili di prodotto IMS  Adobe](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-product-profiles.html) | Video |  profili di prodotto IMS di Adobe consentono agli utenti di accedere a un servizio AEM Author e forniscono una linea di base di accesso, a seconda del profilo di prodotto a cui vengono aggiunti. |
| 17 agosto 2020 | [Gruppi di utenti  Adobe IMS](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-user-groups.html) | Video |  Adobe di gruppi di utenti IMS stabiliscono set logici di utenti esposti a AEM, in cui possono essere utilizzati per definire le autorizzazioni di ottimizzazione per AEM utenti. |
| 17 agosto 2020 | [utenti IMS Adobe](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-users.html) | Video | Scoprite  utenti IMS di Adobe, come accedervi e gestirli in  Admin Console e come utilizzarli per accedere a AEM come Cloud Service. |
| 17 agosto 2020 | [Guida introduttiva ad HTML5 Forms per gli sviluppatori](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.forms) | Corso | I moduli HTML5 offrono il rendering dei modelli di modulo XFA in formato HTML5. Questa funzionalità consente il rendering dei moduli su dispositivi mobili e browser desktop su cui non è supportato PDF basato su XFA. |

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
* [Note sulla versione di Adobe Primetime](https://docs.adobe.com/content/help/it-IT/primetime/release-notes/home.html)
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

* Versione 20.2.2 - [Ulteriori informazioni](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Nuovi corsi e tutorial su Campaign

Nuovi video, tutorial o corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| ----------- | ----------- | ---------- | ---------- |
| 10 agosto 2020 | [Ottimizzazione delle destinazioni combinando i risultati delle query](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-combining-query-results.html) | Campaign Classic | Scoprite come perfezionare la destinazione combinando i risultati della query in un flusso di lavoro utilizzando l&#39;intersezione o le attività dell&#39;unione. |
| 10 agosto 2020 | [Utilizzo dell&#39;attività di aggiornamento elenco per creare un elenco con un flusso di lavoro](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/using-the-update-list-activity.html) | Campaign Classic | Comprendere il concetto di elenchi in Adobe Campaign Classic e imparare a creare un elenco utilizzando l&#39;attività dell&#39;elenco di aggiornamenti in un flusso di lavoro. |
| 20 agosto 2020 | [Ottimizzazione delle destinazioni mediante l&#39;esclusione dei risultati delle query](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-excluding-query-results.html) | Campaign Classic | Scoprite come perfezionare la destinazione applicando un&#39;esclusione standard a un flusso di lavoro. Inoltre verrà illustrato come creare filtri predefiniti e come interrompere le riprese del flusso di lavoro. |
| 25 agosto 2020 | [Creazione di invii Direct Mail](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | Scopri come funziona la posta diretta in  Adobe Campaign e come creare, formattare ed eseguire una consegna diretta per posta. |  | 25 agosto 2020 | [Creazione di consegne dirette](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | Scopri come funziona la posta diretta in  Adobe Campaign e come creare, formattare ed eseguire una consegna diretta per posta. |

### Risorse di supporto

* Adobe Campaign Standard: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/campaign-standard-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/overview.html) - [Piano delle versioni future](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-planning.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro assistenza](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/campaign-classic-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://docs.adobe.com/content/help/it-IT/campaign-classic-learn/tutorials/overview.html) - [Ultimi aggiornamenti della documentazione](https://docs.adobe.com/content/help/it-IT/campaign-classic/using/documentation-updates.html)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/control-panel/using/release-notes.html)  - Video introduttivi per [Campaign Standard](https://docs.adobe.com/content/help/it-IT/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/it-IT/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Note sulla versione di Adobe Advertising Cloud.

* [Nuove funzioni in Advertising Cloud DSP](#adcloud-dsp)
* [Nuove funzioni in Advertising Cloud Search](#adcloud-search)

### Nuove funzioni in [!UICONTROL Advertising Cloud DSP] {#adcloud-dsp}

| Funzione | Descrizione |
| -----------| ---------- |
| Pre-roll interattivo esteso per includere l’inventario VAST | Ciascun posizionamento e annuncio pre-roll interattivo può ora supportare inventario VPAID e VAST. **Nota:** Se l’indicatore KPI principale è una capacità di visualizzazione, puoi continuare a creare posizionamenti VPAID e VAST separati e annunci, perché le impression visualizzabili non sono disponibili per gli annunci VAST. |

### Nuove funzioni di [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Release dell’**8 agosto**

| Funzione | Descrizione |
| ----------- | ---------- |
| [!UICONTROL Portfolio] | I limiti di posizione a livello di portfolio non sono più disponibili nelle impostazioni del portfolio. Eventuali limiti di posizione creati in precedenza sono stati rimossi. |
| [!UICONTROL Vincoli] | I vincoli basati sulla posizione e le condizioni dei vincoli non sono più supportati: <br/> <ul><li>[!UICONTROL I vincoli Pos] minimi e Pos  massimi non sono più disponibili e sono stati rimossi da tutti i vincoli [!UICONTROL Offerta e Posizione] precedentemente creati e dai vincoli [!UICONTROL Condivisione] impression.</li><li>Existing [!UICONTROL Bid &amp; Position] constraints that included position constraints but no bid constraints were paused. Sono ancora disponibili nell’interfaccia utente e nei rapporti.</li><li>[!UICONTROL I vincoli di offerta e posizione sono stati rinominati vincoli di offerta.]</li><li>All position-based conditions (using [!UICONTROL Average Position], [!UICONTROL Weighted Average Position], or [!UICONTROL Last Known Pos] metrics) in any type of constraint were removed.</li></ul> <br/> **Nota:** i dati di posizione continueranno a essere compilati finché saranno accessibili dai motori di ricerca. Microsoft Ads ritirerà la posizione a settembre 2020. |
| [!UICONTROL Campagne] | (Campagne Google Ads) Advertising Cloud Search ora supporta le personalizzazioni degli annunci negli annunci adattabili della rete di ricerca (RSA). In precedenza erano supportate in tutti i tipi di annunci eccetto gli RSA. |

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per le note sulla versione, consulta:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per lead management e marketer B2B che intendono trasformare le esperienze dei clienti impegnandosi in ogni fase dei percorsi d’acquisto complessi.

### Aggiornamenti principali di Marketo Engage

Consulta le [note sulla versione](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720) di [!DNL Marketo] per informazioni aggiornate.

### Funzionalità in arrivo

Nel corso del trimestre verranno presentate le seguenti funzionalità:

| Funzione | Descrizione |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nuova segmentazione basata sugli account</li><li>Possibilità di salvare filtri specifici per dashboard</li><li>Esportazione dashboard Bizible in formato PDF</li></ul> |
| Sales Connect | Aggiornamenti/miglioramenti relativi a finestre di composizione e centri di comando |

### Funzionalità deprecate

* **Parametro “_method” di Asset API:** dopo settembre 2020, gli endpoint di Asset API non accetteranno più `_method` per trasmettere i parametri di query nel corpo di un POST per aggirare le limitazioni relative alla lunghezza degli URI.
* **Supporto in Internet Explorer:** a partire dalla versione di luglio del 31 luglio 2020, Internet Explorer non supporterà più l’interfaccia utente di Marketo Engage.

Per leggere le note precedenti e complessive, consulta le [note sulla versione Marketo](https://docs.marketo.com/x/CgA6Ag).
