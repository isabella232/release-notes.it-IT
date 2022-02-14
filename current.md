---
title: Note sulla versione più recente
description: Scopri le note sulla versione più recente, le nuove funzioni e la nuova documentazione dei  [!DNL Experience Cloud]  prodotti e servizi. Trova nuove guide e tutorial su [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] e [!DNL Document Cloud].
doc-type: release notes
last-update: February 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 85a73da3f5957c5d073d9b0018d1758f14432252
workflow-type: tm+mt
source-wordcount: '4933'
ht-degree: 49%

---

# Note sulla versione di Adobe Experience Cloud - febbraio 2022

![Banner](assets/experience-cloud-banner-3.png)

In qualità di Experience Maker, il percorso per il successo inizia con [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home). Trova una vasta libreria di documentazione, esercitazioni guidate, video dimostrativi e corsi per tutti i livelli e i ruoli, una community online di colleghi e supporto esperto quando necessario.

Pronti per iniziare? [Quiz di 5 minuti e vinci](https://exploreadobe.com/experience-league-quiz/)!

>[!NOTE]
>
>Per ricevere una notifica e-mail mensile sugli aggiornamenti di questa pagina, abbonati ad [Aggiornamento sui prodotti priority Adobe](https://www.adobe.com/subscription/priority-product-update.html). Torna spesso a controllare per essere sempre al corrente delle novità di Experience League.

**Febbraio 2022**

Ultimo aggiornamento: **11 febbraio 2022**

* [Eventi [!DNL Experience League]](#events)
* [[!UICONTROL Stato dei sistemi] Adobe](#status)
* [[!DNL Experience Cloud Central Interface Components] e amministrazione](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target) (Aggiornato il **3 febbraio 2022**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprint - tutorial](#blueprints)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home) per trovare documentazione tecnica e di prodotto, corsi curati da Adobe, tutorial video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/experience-league.png) Eventi [!DNL Experience League] {#events}

Gli eventi di Experience League offrono l’occasione di ricevere risposte dagli esperti di prodotto di Adobe. Tre tipi di eventi includono:

| Tipo evento | Descrizione |
| -----------|---------- |
| [Experience League LIVE ](#exl-live) | Streaming live prodotto dal team di Experience League e ospitato su YouTube. Offre l’opportunità di entrare in contatto con gli esperti dei prodotti Adobe. Impara suggerimenti, trucchi e strategie da mettere in pratica nelle applicazioni Adobe Experience Cloud.<br> Scorri verso il basso per ulteriori informazioni sui prossimi eventi e guarda gli eventi passati ospitati su [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=it). |
| [Community Q&amp;A Coffee Breaks ](#coffee) | Trascorri un’ora con un ospite speciale e invia le tue domande in Experience League Communities! Risposte alle domande degli esperti di prodotto di Adobe Prendi un caffè e chiacchierare con i responsabili di prodotto di Experience League Communities.<br>Scorri verso il basso per saperne di più. Non dimenticarti di registrarti prima che sia troppo tardi! |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=it) | Eventi video on-demand disponibili ad Experience League. |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE {#exl-live}

| Data evento | Ora | Nome evento | Formato | Descrizione |
| -----------| ---------- | ---------- | ---------- |---------- |
| 3 febbraio 2022 | On-demand | [Presentazione di demo di riferimento completamente nuove su AEM](https://www.youtube.com/watch?v=FEREXV826NQ) | Evento video live | Scopri il modo più veloce per eseguire il provisioning, la dimostrazione e l’esplorazione delle funzionalità di AEM as a Cloud Service. |

{style=&quot;table-layout:auto&quot;}

### Community Q&amp;A Coffee Breaks {#coffee}

| Nome evento | Data | Applicazioni | Formato | Descrizione |
| -----------| ---------- | ---------- | ---------- |---------- |
| Adobe Target Community Q&amp;A Coffee Break | 23 febbraio 2022 @ 8 am PST | Adobe Target, Experience Platform, RTCDP | Forum domande e risposte | [Registrati ora](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)! Entra a far parte della community Adobe Target dalle 8.00 alle 9.00 PT per ricevere risposte da Vishal Chordia, Senior Product Manager. Risponderà a tutte le tue domande relative a Adobe Experience Platform (AEP), Personalizzazione basata su pubblico, Integrazione Real-time Customer Data Platform (RTCDP) con Target e a Adobe Target generale |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer’s Live {#dev-live}

| Evento | Data e ora | Tipo | Descrizione |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | On-demand | Video | [!DNL Developers Live] presenta i progressi tecnologici più recenti e strumenti per sviluppatori che supportano la progettazione, i flussi di lavoro per la creazione di contenuti, i servizi di documentazione e la gestione dell’esperienza dei clienti nei vari settori. Visualizza l’indirizzo della nota chiave, scopri le API di Analytics, il livello dati client, i progetti open source di Adobe I/O e molto altro. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi di Adobe. Consulta [status.adobe.com](https://status.adobe.com/it).

Data di rilascio: **16 novembre 2021**

**Novità**

* Lo stato Adobe ora segnala gli incidenti a livello di prodotto. Le pagine di stato Cloud e prodotto hanno un nuovo aspetto e filtri migliorati in base alla segnalazione a livello di prodotto degli incidenti. In questo modo è più facile comprendere in che modo il prodotto è influenzato [status.adobe.com](https://status.adobe.com/) e nelle notifiche e-mail. Se non sei iscritto, utilizza questo collegamento per impostare le preferenze di abbonamento personalizzate [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage).

* La home page dello stato ora è personalizzata con eventi filtrati in base alle adesioni e agli abbonamenti ai prodotti. Per favore, controlla all&#39;indirizzo **status.adobe.com** > **[!UICONTROL Eventi personali]** scheda .

**Nuove funzioni e miglioramenti disponibili oggi**

| Funzione | Descrizione |
| ------- | -------|
| Segnalazione di incidenti a livello di prodotto | <ul><li>Ogni prodotto ha un banner su [!UICONTROL Stato] che include gli ultimi aggiornamenti, cronologia e attributi di impatto del prodotto</li><li>Le e-mail ora seguono lo stesso formato di reporting dell’impatto a livello di prodotto anziché di reporting a livello di incidente</li></ul> |
| Vista personalizzata del [!UICONTROL Stato] home page | <ul><li>Presentazione di una nuova visione, **[!UICONTROL Eventi personali]** sulla [!UICONTROL Panoramica] pagina. Questa visualizzazione filtra gli eventi in base alle adesioni e agli abbonamenti</li><li>I diritti possono essere per organizzazioni o singoli individui. Gli abbonamenti possono essere per prodotti o eventi</li></ul> |
| Esperienza utente migliorata | <ul><li>Le pagine cloud presentano un riepilogo della disponibilità di tutti i prodotti e della possibilità di filtrare per prodotto, area geografica, date e tipi di evento</li><li>Le pagine dei prodotti presentano un riepilogo della disponibilità di tutte le funzionalità e una visualizzazione dettagliata degli eventi e della cronologia</li><li>I filtri migliorati sono disponibili per funzionalità, data center/ambienti (se applicabile), area geografica, data, tipo di evento e stato di incidente/manutenzione</li></ul> |
| Aggiornamenti delle sottoscrizioni migliorate con l’aggiornamento delle offerte di prodotti | <ul><li>Le offerte Adobe Analytics vengono aggiornate a una visualizzazione semplice per il cliente (esistenti [!DNL Analytics] gli abbonamenti vengono trasferiti alle nuove offerte)</li><li>Offerte granulari per [!DNL Customer Journey Analytics]</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] e amministrazione {#ecloud}

| Funzione | Descrizione |
| ------- |-------|
| **[!UICONTROL Recenti]** (collegamenti) aggiunti a [Experience Cloud](https://experience.adobe.com/home) atterraggio | Puoi accedere alle scelte rapide per l’attività Journey Optimizer e Experience Platform più recente sotto il nuovo **[!UICONTROL Recenti]** intestazione. Questo aggiornamento include anche miglioramenti generali del layout e della reattività nella pagina di destinazione. |
| **[!UICONTROL Sandbox]** spostati nella barra dell’intestazione | L’indicatore Sandbox è ora integrato nell’intestazione di tutte le applicazioni dell’interfaccia di Experience Platform. Vedi [Sandbox](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=it) in Experience Platform per ulteriori informazioni. |

{style=&quot;table-layout:auto&quot;}

**Altre risorse di aiuto su [!DNL Experience Cloud Central UI Components] e amministrazione**

* [Note sulla versione](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) ad Experience Cloud i componenti dell’interfaccia utente centrale
* [Gestione di utenti e prodotti](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=it) ad Experience Cloud (amministrazione)
* Places Service [note sulla versione](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=it)
* Documentazione del prodotto per [Persone - Attributi del cliente e libreria del pubblico](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Informazioni aggiornate sulla versione e nuova documentazione per Experience Platform e [!UICONTROL SDK per dispositivi mobili]:

Data di rilascio: **26 gennaio 2022**

* [Note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it)

### Nuovi tutorial e corsi su Experience Platform {#tutorials-platform}

Nuovi video, tutorial o corsi pubblicati su Experience Platform.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2022 | [Implementare Adobe Experience Cloud con Web SDK](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html) | Esercitazione multipagina | Scopri come implementare le applicazioni Experience Cloud utilizzando Adobe Experience Platform Web SDK. Questa esercitazione mostra come implementare l’SDK per web di Platform utilizzando un sito Web di esempio per la vendita al dettaglio denominato _Luma_. La [Luma](https://luma.enablementadobe.com/content/luma/us/en.html) il sito dispone di un livello dati e funzionalità avanzati che consentono di realizzare un’implementazione realistica. Inizia ora! |
| Febbraio 2022 | [Personalizzazione con hit successivo con Real-time CDP e Adobe Target](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html) | Video | Scopri come personalizzare l’hit successivo con [!UICONTROL Real-time Customer Data Platform] e Adobe Target. La destinazione Adobe Target in Real-time CDP consente di utilizzare i segmenti di Experience Platform in Adobe Target per la personalizzazione della stessa pagina e della pagina successiva con governance e supporto per la privacy. |

{style=&quot;table-layout:auto&quot;}

### SDK di Adobe Mobile

Consulta le [note sulla versione e registri di modifica](https://aep-sdks.gitbook.io/docs/release-notes) per gli SDK di Adobe Experience Platform Mobile.

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **16 febbraio 2022**

* Adobe Analytics [note sulla versione](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en) (**nuova posizione**)
* Adobe Analytics [documentazione ed esercitazioni del prodotto](https://experienceleague.adobe.com/docs/analytics.html?lang=it)

### [!DNL Customer Journey Analytics] {#cja}

Data di rilascio: **16 febbraio 2022**

* Customer Journey Analytics [note sulla versione](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)  (**nuova posizione**)
* Customer Journey Analytics [documentazione ed esercitazioni del prodotto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### AppMeasurement {#appm}

Versione di rilascio: **2.22.4**

* [Note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### Nuovi corsi e tutorial di Analytics {#tutorials-analytics}

Nuovi video, tutorial o corsi pubblicati su Adobe Analytics.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2022 | [Manipolazione dei dati in arrivo con regole di elaborazione](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=it) | Video | Ottieni una panoramica delle regole di elaborazione in Adobe Analytics e scopri a cosa servono. Scopri alcuni suggerimenti, esempi e persino un avviso. |
| Febbraio 2022 | [Configurazione delle variabili elenco](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=it) | Video | Quando devi inserire più di un valore in un eVar (una variabile di conversione) contemporaneamente, cosa farai? Elenca le variabili al salvataggio! Scopri come e perché configurare e utilizzare le variabili elenco in Adobe Analytics. |
| Febbraio 2022 | [Configurare le classificazioni del traffico](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=en) | Video | Scopri come configurare le classificazioni per le variabili di traffico, spesso denominate _proprietà_ e anche _nomepagina_ e così via. |
| Febbraio 2022 | [Configurare le classificazioni di conversione](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=en) | Video | Scopri come configurare le classificazioni per le variabili di conversione, note anche come _eVar_. Questa configurazione si applica anche ai prodotti e alle variabili elenco. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Correzioni e miglioramenti in Audience Manager.

* È stato risolto un problema che causava la restituzione da parte delle chiamate di API di un `Undocumented` errore durante l’esecuzione tramite l’interfaccia Swagger. (AAM-59190)
* È stato risolto un problema che in alcune situazioni causava l’assegnazione di ruoli utente errati ai partner. (AAM-59451)
* È stato risolto un problema che causava la richiesta da parte dell’API di intestazioni di autenticazione con distinzione tra maiuscole e minuscole. (AAM-58528)

Per le risorse di supporto autonomo, consulta [Documentazione ed esercitazioni di Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) Experience League

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Per gli ultimi aggiornamenti sulle varie versioni, visita regolarmente la pagina [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it).

### Rilasci di prodotti Experience Manager

* **Experience Manager as a Cloud Service**

   Guarda il [Video introduttivo sulla versione di gennaio 2022](https://video.tv.adobe.com/v/340120) per un riepilogo delle funzioni aggiunte nella versione 2022.1.0 (gennaio 2022).

   * [](https://video.tv.adobe.com/v/339278)Panoramica sulla versione di dicembre 2021 video sulle nuove funzioni.
   * [Video di panoramica della versione di ottobre 2021](https://video.tv.adobe.com/v/338253) sulle nuove funzioni.
   * [Video di panoramica della versione di settembre 2021](https://video.tv.adobe.com/v/337381) sulle nuove funzioni.

   * **Experience Manager Assets as a Cloud Service**

      _Nuove funzioni in Experience Manager Assets_

      * Dynamic Media - È ora possibile utilizzare l’interfaccia Experience Manager - Dynamic Media per configurare [Impostazioni generali](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html) e [Pubblica installazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html) invece di dover passare attraverso l&#39;applicazione desktop Dynamic Media Classic.
      * Dynamic Media ora supporta l’acquisizione, l’anteprima, la riproduzione e la pubblicazione di video MXF. L’annotazione e il video acquistabili per i video MXF non sono ancora supportati.
      * Dopo aver configurato una connessione tra le implementazioni remote di DAM e Sites, le risorse in DAM remoto sono rese disponibili nell’implementazione di Sites. È ora possibile eseguire le [operazioni di aggiornamento, eliminazione, ridenominazione e spostamento](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=it) su risorse o cartelle DAM remote. Gli aggiornamenti, con un certo ritardo, sono disponibili automaticamente nell’implementazione di Sites.

      _Nuova funzione nel canale prerelease di Experience Manager Assets_

      * Dynamic Media offre ora la flessibilità di [configura un account alias società](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=en) nell’interfaccia utente di , in modo che gli URL predefiniti di Dynamic Media e il codice di incorporamento del visualizzatore vengano aggiornati. Questa azione influisce positivamente sull’ottimizzazione SEO (Search Engine Optimization), per riflettere gli aggiornamenti apportati al contesto aziendale, ad esempio il rebranding.
      * È ora possibile utilizzare l’interfaccia utente di Experience Manager Assets per:

         * Configura il rilevamento delle risorse duplicate in un archivio.
         * Configura l’aggiunta di watermark digitali alle immagini.
      * Gli amministratori possono ora configurare il servizio e-mail per i download di grandi dimensioni. Consente agli utenti di [abilitare le notifiche e-mail per i download di grandi dimensioni](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) dall’interfaccia di Experience Manager Assets. Al termine del processo di download, l’utente riceve una notifica e-mail contenente il collegamento di download della cartella zip archiviata.
      * La [Gestisci pubblicazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) viene migliorata con un’interfaccia utente migliorata. Gli utenti possono pubblicare o annullare la pubblicazione dei contenuti da e verso la destinazione selezionata, e [Aggiungi contenuto](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) all’elenco di pubblicazione dall’archivio DAM. Possono inoltre [Includi impostazioni cartella](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) per pubblicare il contenuto delle cartelle selezionate e applicare i filtri, e [pianificazione della pubblicazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) a una data o un&#39;ora successiva.

      _Correzione bug_

      * Le risorse non elaborate senza rendering originale vengono inviate ad Asset compute per l’elaborazione durante la migrazione delle risorse da Experience Manager On-Premise ai Cloud Services.
   * **Experience Manager Forms as a Cloud Service**

      _Novità in Forms_

      * **Experience Manager Forms as a Cloud Service - Comunicazioni** — [API di comunicazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=it) consente di combinare un modello e dati XML per generare documenti di stampa in vari formati. Il servizio consente di generare documenti in modalità sincrona e batch. Le API consentono di creare applicazioni che consentono di effettuare le seguenti operazioni:

         * Generare i documenti compilando i file modello con dati XML.
         * Generare moduli di in vari formati, compresi flussi di stampa PDF non interattivi.
         * Genera PDF di stampa da PDF modulo XFA.
         * Generare in blocco documenti PDF, PostScript, PCL e ZPL unendo più set di dati con modelli di origine.
      * **Font personalizzati per documenti Record e PDF creati con API di comunicazione** — È ora possibile utilizzare font approvati dal marchio nei documenti PDF generati utilizzando le API di comunicazione per allinearli ai requisiti organizzativi.

      _Novità del canale prerelease di Forms_

      * [API Assembler](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) API Assembler per combinare, ridisporre, integrare e ottenere informazioni sui documenti PDF.
   * **Cloud Manager**

      _Data di rilascio_

      La data di rilascio per Cloud Manager in Experience Manager as a Cloud Service 2022.01.0 è il 20 gennaio 2022.
La prossima versione è prevista per il 10 febbraio 2022.

      _Nuove funzioni_

      * Cloud Manager [evita di ricostruire la base di codice quando rileva che viene utilizzato lo stesso commit git](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=en#build-artifact-reuse) in più esecuzioni di pipeline full-stack.
      * Per accedere al registro dell’ambiente di Experience Manager è ora necessario **[!UICONTROL Gestione distribuzione]** profilo di prodotto. Gli utenti senza questo profilo visualizzano un pulsante disabilitato nell&#39;interfaccia utente.
      * L’interfaccia utente non consente la configurazione della pipeline front-end per un programma in cui Sites non è abilitato come soluzione.
      * Al momento della generazione di una password git, viene visualizzata la data di scadenza.








### Community

* **Webinar Experience Manager GEMs: _Creare siti più rapidamente con Experience Manager Headless e App Builder_**

   **Data**: Mercoledì 23 marzo 2022
   **Time**: 8:00 A.M. (PST) o 5:00 (CET) o 9:00 (IST)
   **Speaker**: Duy Nguyen, ingegnere per lo sviluppo di software Adobe
   [Registrati al webinar all&#39;indirizzo https://adobe.ly/3oCkEsh](https://adobe.ly/3oCkEsh)
   [Domande frequenti sul webinar](https://adobe.ly/3LkSWdm)

* Riproduci il Webinar Experience Manager GEMs del gennaio 2022: [_Revisione di Experience Manager as a Cloud Service 2021 e prospettive per il 2022_](https://adobe.ly/3rqbSOz)

### Nuovi corsi ed esercitazioni su Experience Manager {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazione |
| ------| ------| ----- | -----| ----|
| Febbraio 2022 | [Crea credenziali del servizio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html) | Video | Scopri come creare le credenziali del servizio per garantire l’autenticazione sicura per le integrazioni con AEM as a Cloud Service. | AEM Forms CS |
| Febbraio 2022 | [Creare un token web JSON (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) | Articolo | Scopri i token Web JSON, un metodo RFC 7519 standard aperto e di settore per rappresentare le richieste in modo sicuro tra due parti. `JWT.io` in questo esempio vengono utilizzate le librerie per generare il codice JWT. | AEM Forms CS |
| Febbraio 2022 | [Exchange JWT per token di accesso](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html) | Articolo | Il JWT creato nel [Creare un token web JSON (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) Questo passaggio viene scambiato con le API Adobe IMS per un token di accesso, che può quindi essere utilizzato per accedere AEM as a Cloud Service. Scopri come richiedere un token di accesso per inviare una richiesta POST contenente JWT, client_id, client_secret al servizio di autenticazione IMS. | AEM Forms CS |
| Febbraio 2022 | [Incorporazione di font nel pdf generato](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=en#add-the-fonts-module) | Articolo | Scopri come installare [!DNL IntelliJ] edizione comunitaria. | AEM Forms CS |
| Febbraio 2022 | [Effettua la chiamata POST](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html) | Video | Scopri come effettuare una chiamata HTTP POST all’endpoint con i parametri necessari. Il modello e i file di dati vengono forniti come file di risorse. | Forms CS |
| Febbraio 2022 | [Migrazione dal vecchio archetipo AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=en) | Video | Desc. | Forms CS |
| Febbraio 2022 | [Esternalizzare lo storage dei dati del flusso di lavoro in AEM Forms CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=en) | Video | Scopri come memorizzare i dati del flusso di lavoro nell’archiviazione di Azure. AEM Forms CS dispone di una nuova funzionalità per memorizzare i dati del flusso di lavoro, ad esempio variabili, allegati e così via, in un account di archiviazione esterno. | AEM Forms CS |
| Febbraio 2022 | [Integrare Adobe Analytics con Experience Cloud Setup Automation](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html) | Video | Scopri come Experience Cloud Setup Automation fornisce un modo semplice e automatizzato per integrare e dotare Experience Manager Sites di strumenti con Experience Platform Launch e Adobe Analytics. | AEM Sites |
| Febbraio 2022 | [Recommendations di prodotto](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html) | Video | Scopri come inserire dinamicamente questi consigli di prodotto in una vetrina Adobe Experience Manager (AEM). Adobe Commerce dispone di un motore di raccomandazione basato su Adobe Sensei. | AEM e Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

### Informazioni sulla versione di Experience Manager

Nelle pagine seguenti trovi tutte le note sulla versione di Experience Manager:

* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=it)
* [Note sulla versione di Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=it)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=it)
* [Note sulla versione di Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=it)
* [Note sulla versione dell’app desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=it)
* [Note sulla versione di Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=it)
* [Note sulla versione di Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=it)

### Altre risorse di assistenza per Experience Manager

* [Guide di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=it)
* [Guida utente di Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
* [Formazione e supporto per Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=it)
* [Formazione e supporto per Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it)
* [Formazione e supporto per Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it#previous-updates)
* [Documentazione delle versioni precedenti di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Pagina iniziale della guida di Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=it)
* [Documentazione di Experience Manager: ultimi aggiornamenti](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=it#aem-as-a-cloud-service)

## ![Icona](/assets/ec_appicon_24.png) Documentazione XML per Adobe Experience Manager {#xml-doc}

La documentazione XML per Adobe Experience Manager è un’applicazione distribuita su AEM. Si tratta di una potente soluzione di gestione dei contenuti per componenti di livello aziendale (CCMS) che consente il supporto DITA nativo in Adobe Experience Manager, permettendo ad AEM di gestire la creazione e la distribuzione di contenuti basati su DITA.

Ulteriori informazioni sulla [Documentazione XML per AEM](https://www.adobe.com/it/products/xml-documentation-for-experience-manager/features.html).

### Nuovi tutorial per la documentazione XML per Adobe Experience Manager {#tutorials-xml-doc}

Nuovi video, tutorial o corsi pubblicati per la documentazione XML per Adobe Experience Manager.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Gennaio 2022 | [Versioni della documentazione XML](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=it) | Video | Scopri la Documentazione XML per Adobe Experience Manager, una potente soluzione di gestione dei contenuti dei componenti di livello enterprise (CCMS). Abilita il supporto DITA nativo in Adobe Experience Manager, consentendo ad AEM di gestire la creazione e la distribuzione di contenuti basati su DITA. |
| Gennaio 2022 | [Generazione di output con documentazione XML per AEM](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=it) | Video e articoli | Scopri Map Dashboard, i rapporti, la pubblicazione con linee di base e condizioni e altro ancora. |

{style=&quot;table-layout:auto&quot;}

### Risorse aggiuntive

* [Documentazione XML per Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=it) - Esercitazioni sull’Experience League
* [Documentazione XML per informazioni e supporto su Adobe Experience Manager](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - documentazione del prodotto

## ![Icona](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

Consulta i seguenti collegamenti per le note sulla versione di Adobe Commerce:

* [Adobe Commerce e Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Suite cloud per Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nuove esercitazioni di Adobe Commerce {#tutorials-commerce}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2022 | [Aggiorna Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html) | Guida utente | Ottieni tutto l&#39;aiuto necessario per procedere attraverso il processo di aggiornamento. |
| Febbraio 2022 | [Workshop sull&#39;aggiornamento ad Adobe Commerce 2.4](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=en) | Video | Scopri i passaggi e le best practice da seguire per preparare il tuo prossimo aggiornamento alla versione 2.4.4 o successiva. |
| Febbraio 2022 | [Utilizzo dello strumento di compatibilità per l’aggiornamento su PhpStorm](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=en) | Video | Scopri come utilizzare il `PhpStorm` plugin |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/target.png) [!DNL Adobe Target] {#target}

Ultimo aggiornamento: **1 febbraio 2022**

* Per informazioni pre-release, vedi [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it)
* Per informazioni aggiornate, consulta [Note sulla versione di Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Ultime versioni di Campaign

Scopri le funzionalità, i miglioramenti e le correzioni più recenti:

* (Nuova!) [Versione di Campaign Standard 2.2.1](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=it)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Campaign] {#tutorials-campaign}

Nuovi video, tutorial o corsi pubblicati su Adobe Campaign.

| Data di pubblicazione | Nome | Tipo | Descrizione | Versione |
| ------| ----- | -----| ------ | --- |
| Febbraio 2022 | [Nozioni di base sulla gestione dei dati con i flussi di lavoro Adobe Campaign](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=en) | Video | Scopri le dimensioni di targeting e le tabelle di lavoro e come Adobe Campaign gestisce i dati tra diverse origini dati. | Campaign v8 |
| Febbraio 2022 | [Modificare l’origine dati](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=en) | Video | Scopri come modificare l’origine dati di una tabella di lavoro del flusso di lavoro utilizzando l’attività Cambia origine dati per gestire in modo flessibile i dati tra diverse origini dati, come FDA, FFDA e database locale. | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Risorse per Campaign

* Adobe Campaign v8: [Documentazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=it) - [Guide all’implementazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=it)
* Adobe Campaign Standard: [Documentazione Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Piano delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* Adobe Campaign Classic: [Documentazione Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=it) - Video introduttivi per [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=it) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer puoi gestire campagne omnichannel pianificate e momenti “uno a uno” per milioni di clienti da una singola applicazione, ottimizzando l’intero percorso con decisioni intelligenti e informazioni approfondite.

### Ultime versioni del prodotto Journey Optimizer

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [Note sulla versione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it).

### Altre risorse per [!DNL Journey Optimizer]

* [Documentazione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=it)
* [Documentazione di Decision Management](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilizza Experience Platform per orchestrare il percorso di un cliente su grande scala tra i diversi canali di esperienza, anticipando in modo intelligente le esigenze di ogni cliente in tempo reale.

### Ultime versioni dei prodotti [!DNL Journey Orchestration]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle note sulla versione di [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it).

#### Altre risorse per [!DNL Journey Orchestration]

* [Documentazione di Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=it)

## ![Icona](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per chi si occupa di lead management e B2B e intende trasformare le esperienze dei clienti coinvolgendoli in ogni fase di complessi percorsi d’acquisto.

### Aggiornamenti principali di Marketo Engage

Per informazioni aggiornate sulla pianificazione delle versioni e sulle relative note sulla versione, consulta [!DNL Marketo Engage] [- Pianificazione delle versioni](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=it).

## ![Icona](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] è un’applicazione unificata di gestione del lavoro per condividere idee, creare contenuti, gestire processi complessi e lavorare al meglio.

Per una raccolta delle informazioni più recenti per tutti i prodotti, consulta la pagina delle versioni di [[!DNL Workfront] ](https://one.workfront.com/s/product-releases).

## ![Icona](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Note sulla versione di [!DNL Adobe Advertising Cloud].

* [Nuove funzioni in  [!DNL Advertising Cloud]](#adcloud-all)
* [Nuove funzioni in  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nuove funzioni in  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Nuovi tutorial su [!DNL Advertising Cloud] ](#tutorials-ad-cloud)

### Nuove funzioni in [!DNL Advertising Cloud] {#adcloud-all}

Ultimo aggiornamento: **27 ottobre 2021**

| Funzione | Descrizione |
| ------- | ----------- |
| Analytics per Advertising Cloud | Se la tua organizzazione desidera disattivare l’utilizzo di Adobe Analytics legacy `visitorAPI.js` alla libreria Adobe Experience Platform (`alloy.js`) per la raccolta dati, devi apportare modifiche per abilitare la combinazione degli ID. Consulta [Utilizzo della Libreria JavaScript  [!DNL Last Event Service]  con Adobe Experience Platform  [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=it). |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Ultimo aggiornamento: **27 ottobre 2021**

| Funzione | Descrizione |
| ------- | ----------- |
| Rapporti personalizzati | Ora puoi creare e gestire [!DNL Amazon S3] e diversi tipi di posizioni di consegna FTP, denominate *[!DNL report destinations]*, per i rapporti personalizzati. Dopo aver configurato le destinazioni dei rapporti, puoi impostare ciascuno dei nuovi rapporti personalizzati da consegnare a una o più posizioni di un singolo tipo di destinazione o a destinatari e-mail. Gli aggiornamenti alle credenziali [!DNL Amazon S3] e FTP e non interrompono la consegna del rapporto.<br><br>I rapporti esistenti vengono comunque inviati ai destinatari e-mail specificati. Per configurare la consegna a una diversa destinazione di rapporto, crea un rapporto con la nuova destinazione. |
| Visualizzazioni [!UICONTROL Pacchetti], [!UICONTROL Posizionamenti] e [!UICONTROL Annunci] | i grafici di tendenza nella visualizzazione per un singolo giorno, ora includono dati orari. Tenere il cursore su un punto qualsiasi per visualizzare i dati relativi a quell’ora. |
| [!UICONTROL Posizionamenti] | Il posizionamento [!UICONTROL Ispettore] ora include una scheda [!UICONTROL Inventario], che mostra tutte le offerte e le relative metriche associate. Utilizza le informazioni per apportare regolazioni rapide o per risolvere eventuali problemi senza generare un rapporto personalizzato. |
| [!UICONTROL Annunci] | (Utenti autorizzati a includere i numeri Clearcastclock nei loro annunci) DSP non mostra più un errore se utilizzi un numero di orologio allegato a un altro annuncio. **Nota:** la best practice prevede l’utilizzo di un numero di orologio univoco per ogni annuncio video. In caso contrario, l’editore non approva tutti gli annunci. |
| [!UICONTROL ID offerta] | Le impostazioni [!UICONTROL ID offerta] e altre posizioni nell’interfaccia utente riflettono il nuovo branding per [!DNL Magnite] SSP:<br><ul><li>La SSP [!DNL Tremor] ([!DNL Telaria]) è ora [!DNL Magnite CTV].</li><li>Nelle prossime settimane, [!DNL Rubicon] cambierà in [!DNL Magnite DV+], dove [!DNL DV+] sta per display, video e altri formati come l’audio.</li></ul> |
| Offerte di [!DNL Freewheel] garantite da programma | Ora puoi trovare lo stato degli annunci per offerte garantite da programma di [!DNL Freewheel] dalla vista [!UICONTROL Annunci]. In precedenza, era possibile controllare lo stato solo dalla visualizzazione [!UICONTROL Offerte]. |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni in [!DNL Advertising Cloud Search] {#adcloud-search}

Ultimo aggiornamento: **4 febbraio 2022**

| Funzione | Descrizione |
| ------- | ----------- |
| [!UICONTROL Bulksheet], [!UICONTROL Centro notifiche] | (Data di rilascio: 22 gennaio) Tutte le notifiche e-mail per i bulksheet, inviate da Advertising Cloud Search al completamento o al fallimento di un’operazione del bulksheet, vengono ora gestite da [!UICONTROL Centro notifiche].<br><br>[!UICONTROL Bulksheet] è un nuovo tipo di notifica, con le proprie preferenze di notifica, in [!UICONTROL Centro notifiche]. Le notifiche e-mail e le notifiche web sono abilitate per impostazione predefinita, ma è possibile modificare facoltativamente le impostazioni di notifica.<br><br>Il formato e il contenuto delle notifiche e-mail utilizzano il [!UICONTROL Centro notifiche] e include un collegamento di download diretto per il file bulksheet o il file di errore associato. |

{style=&quot;table-layout:auto&quot;}

### Nuovi tutorial su Advertising Cloud {#tutorials-ad-cloud}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Gennaio 2022 | [Tutorial su Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=it) | Video | Sono disponibili cinque nuovi tutorial video su Advertising Cloud DSP. |

## ![Icona](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuovi video, tutorial o corsi pubblicati per Adobe Document Cloud.

### Nuovi corsi e tutorial su Document Cloud {#tutorials-doc-cloud}

Nuovi video, tutorial o corsi pubblicati per Adobe Document Cloud.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2022 | [Uso dei campi modulo](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=en) | Video | Scopri come aggiungere vari tipi di campi modulo, impostare le proprietà dei campi modulo e aggiungere protezione per creare moduli professionali di alta qualità. |
| Febbraio 2022 | [Optimize PDF per SEO (Ottimizzazione dei motori di ricerca)](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html) | Video | Scopri come ottimizzare un PDF per migliorare la reperibilità e la classificazione dei motori di ricerca sul web. |

{style=&quot;table-layout:auto&quot;}

Per Document Cloud, consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/support/document-cloud.html)

## ![Icona](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

Per i tutorial più recenti, consulta i [tutorial Creative Cloud for enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=it).

## Digital Experience Blueprint - tutorial {#blueprints}

[Blueprint di esperienza digitale](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) sono implementazioni ripetibili che ti consentono di affrontare la strategia e di risolvere rapidamente i problemi aziendali esistenti. Ogni Blueprint fornisce una serie di artefatti che spiegano il problema aziendale di alto valore, le architetture, le fasi di implementazione, le considerazioni tecniche e i collegamenti alla documentazione pertinente.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2022 | [Percorsi cliente](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en) | Video | I Percorsi dei clienti si occupano della possibilità per i brand di interagire e comunicare in modo proattivo con i propri clienti attraverso canali quali e-mail, SMS e avvisi mobili. |
| Febbraio 2022 | [Blueprint di Campaign v7](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=en) | Video | Adobe Campaign v7 è uno strumento di campagna generato per i canali di marketing tradizionali come e-mail e direct mail. Fornisce solide funzionalità di ETL e gestione dei dati per aiutare a creare e curare la campagna perfetta. |

{style=&quot;table-layout:auto&quot;}
