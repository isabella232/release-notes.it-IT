---
title: Note sulla versione più recente
description: Scopri le note sulla versione più recente, le nuove funzioni e la nuova documentazione dei prodotti e servizi Experience Cloud. Trova nuove guide e tutorial su Experience Cloud, Creative Cloud for Enterprise e Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8adc3fe8f3f4b174d1c41cc7c3162d38a984d661
workflow-type: tm+mt
source-wordcount: '5062'
ht-degree: 50%

---

# Note sulla versione di Adobe Experience Cloud - giugno 2021

![Banner](assets/experience-cloud-banner-3.png)

Le applicazioni di Experience Cloud vengono aggiornate ogni mese. Su questa pagina puoi trovare gli aggiornamenti, la documentazione e i tutorial più recenti per [!DNL Experience Cloud] ed [!DNL Experience Platform]. Trovi inoltre la nuova documentazione di [!DNL Creative Cloud for Enterprise] e [!DNL Document Cloud].

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche mensili via e-mail sugli aggiornamenti a questa pagina. La pagina viene aggiornata nell’arco di tutto il mese, quindi controlla regolarmente se ci sono aggiornamenti sui prodotti aziendali di Adobe e sulla documentazione di Experience League.

Ultimo aggiornamento: **11 giugno 2021**

* [Componenti dell’interfaccia centrale di Experience Cloud](#ecloud)
* [Stato di Adobe](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) e  [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home) per trovare documentazione tecnica e sui prodotti, corsi curati da Adobe, esercitazioni video, risposte rapide, insight sulla community e corsi di formazione tenuti da istruttori.

## ![](/assets/ec_appicon_24.png) IconaComponenti dell’interfaccia utente centrale di Experience Cloud {#ecloud}

Experience Cloud Central Interface Components include aggiornamenti a cui è possibile accedere dall’intestazione del prodotto unificata, ad esempio preferenze di supporto autonomo, ricerca e account utente. Gli aggiornamenti a Persone, Luoghi (Posizione) e gestione dei prodotti si trovano qui.

| Funzione | Data | Descrizione |
| ------- | ------- | ------- |
| Supporto per single sign-on per Adobe Federated ID | 17 giugno 2021 | Se utilizzi Federated ID, puoi accedere ad Experience Cloud senza dover immettere un indirizzo e-mail o una password. Per utilizzare questa funzione, aggiungi **#/sso:@domain** all&#39;URL dell&#39;Experience Cloud. <br><br>Ad esempio, si supponga di essere il proprietario del dominio  **adobecustomer.** comand e di voler accedere ad Adobe Analytics. L’URL sarebbe: **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Ricerca Experience League | 1 giugno 2021 | La ricerca nella documentazione di Experience League è stata migliorata. Passa a [Experience League](https://experienceleague.adobe.com/docs/?lang=en) e utilizza il campo **[!UICONTROL Ricerca]** per individuare esercitazioni, documentazione, corsi e altro ancora. |

{style=&quot;table-layout:auto&quot;}

**Altre risorse dell’Aiuto**

* Aiuto per l&#39;amministrazione di [Componenti dell&#39;interfaccia centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) e gestione degli utenti
* Note sulla versione e sulla guida per [Luoghi - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Aiuto su [Persone - Attributi del cliente e libreria del pubblico](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
Per la documentazione sul prodotto relativa a queste funzioni, consulta [Componenti di interfaccia centrale di Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en).

## ![Icona](/assets/adobe.png) Stato di Adobe {#status}

[!UICONTROL Stato di Adobe] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi cloud di Adobe. Consulta [status.adobe.com](https://status.adobe.com/).

Per gli ultimi aggiornamenti sullo Stato di Adobe, visita la pagina [Stato di Adobe - 21 maggio 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=it).

## ![Icona](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Include informazioni sull’aggiornamento della versione e una nuova documentazione per Experience Platform e Experience Platform Launch.

* **26 maggio 2021:** [note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it)
* **17 maggio 2021:** [note sulla versione di Experience Platform Data Collection](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=it)  (precedentemente disponibili in Experience Platform Launch)

### Tutorial e corsi su Experience Platform {#tutorials-platform}

Nuovi video, esercitazioni o corsi pubblicati per Experience Platform e Services.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Giugno 2021 | [Preparare i dati](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Video | Scopri come pulire, preparare e combinare dati da più set di dati per creare un set di dati utilizzando le funzioni Create Table AS (CTAS) e Spark SQL per il reporting e il dashboarding. |
| Giugno 2021 | [Copiare schemi tra sandbox](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Video | Scopri come copiare uno schema da una sandbox a un&#39;altra in Adobe Experience Platform utilizzando l&#39; [!UICONTROL API Export/Import Schema]. Crea e verifica i tuoi schemi nelle sandbox di sviluppo, quindi copiali in produzione. |
| Giugno 2021 | [Aggiorna schemi](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Video | Scopri le cose di base di cui tenere conto durante l’aggiornamento degli schemi esistenti in Adobe Experience Platform. |
| Giugno 2021 | [Blocchi di creazione dello schema](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Video | Scopri gli elementi costitutivi chiave degli schemi Experience Data Model (XDM), compresi campi, tipi di dati, gruppi di campi di schema, classi e comportamenti. |
| Giugno 2021 | [Creare classi](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Video | Scopri come creare classi in Adobe Experience Platform da utilizzare negli schemi Experience Data Model (XDM). |
| Giugno 2021 | [Configurare le relazioni tra schemi](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Video | Scopri come configurare una relazione tra due schemi in Adobe Experience Platform. Le relazioni consentono di utilizzare un set di dati come tabella di ricerca per un altro. |
| Giugno 2021 | [Creazione di tipi di dati](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Video | Scopri come creare tipi di dati personalizzati in Adobe Experience Platform da utilizzare negli schemi Experience Data Model (XDM). |
| Giugno 2021 | [Convertire il modello dati in un modello dati esperienza](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Video | Scopri come gli architetti di dati possono prendere il loro modello di dati transazionali esistente e convertirlo in un Experience Data Model. Questo video mostra la differenza negli approcci di modellazione che utilizzano diagrammi di entità-relazione. |
| Giugno 2021 | [Pianificare il modello dati](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Video | Scopri cosa fare prima di iniziare a creare i tuoi schemi in Adobe Experience Platform. Documentare i casi d’uso aziendali, comprendere la licenza Platform, conoscere le protezioni del prodotto e identificare i dati da acquisire prima di finalizzare il modello dati. |
| Giugno 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Video | Scopri come connettersi a [!UICONTROL Query Service] da varie applicazioni client desktop che supportano il protocollo `PostgreSQL` e come utilizzare gli strumenti e i driver `PostgreSQL` per connettersi e scrivere query. |
| Giugno 2021 | [Funzioni definite dall&#39;Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Video | Scopri come utilizzare le funzioni definite da Adobe in Adobe Experience Platform [!UICONTROL Query Service] per eseguire attività comuni relative all’attività aziendale sui dati di Experience Event. |
| Giugno 2021 | [Esplorazione dei dati](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Video | Scopri come convalidare i dati acquisiti, visualizzare in anteprima i dati ed esplorare le proprietà statistiche e analitiche dei dati utilizzando le funzioni SQL. |
| Giugno 2021 | [Panoramica del servizio query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Video | Scopri Query Service in Adobe Experience Platform e come aiuta a comprendere il comportamento dei clienti e generare informazioni di impatto. |
| Giugno 2021 | [Panoramica dell’interfaccia utente del servizio query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Video | Scopri come scrivere ed eseguire le query, visualizzare le query eseguite in precedenza e accedere alle query salvate da altri utenti all’interno dell’organizzazione IMS in Adobe Experience Platform Query Service. |
| Giugno 2021 | [API Query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Video | Scopri come scrivere ed eseguire query, creare query di pianificazione e creare un modello di query utilizzando Adobe Experience Platform [!UICONTROL API del servizio query]. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilizza l’Experience Platform per orchestrare il percorso di un cliente su vasta scala tra i vari canali dell’esperienza, anticipando in modo intelligente e in tempo reale le esigenze di ogni individuo.

* Aggiornato giugno 2021 - [Note sulla versione del Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it)

**Risorse aggiuntive per Journey Orchestration**

[Documentazione](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [Video tutorial](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] è un servizio applicativo integrato con Adobe Experience Platform. Utilizza [!UICONTROL Offer decisioning] per offrire ai clienti l’offerta e l’esperienza migliore al momento giusto, in tutti i punti di contatto.

* Aggiornato aprile 2021 - [Note sulla versione di Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=it#new)

**Altre risorse per Offer Decisioning**

[Documentazione](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [Video tutorial](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=it)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **17 giugno 2021**

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni di Customer Journey Analytics](#cust-journey)
* [Correzioni in Adobe Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [Corsi ed esercitazioni su Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | [Disponibilità generale](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=it) - data di Target | Descrizione |
| ----------- | ---------- | ------- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni di Customer Journey Analytics {#cust-journey}

| Funzione | [Disponibilità generale](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - data di Target | Descrizione |
| ----------- | ---------- | ----- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Correzioni in Adobe Analytics {#aa-fixes}

* È stato risolto un problema a causa del quale la valuta errata veniva visualizzata nel rapporto Ricavo in tempo reale. (AN-254649)
* È stata aggiornata la documentazione relativa alla [sensibilità alle maiuscole/minuscole eVar nel reporting](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html). (AN-246438)
* È stata aggiornata la documentazione per spiegare meglio [Implementazione feed dati](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) e [qui](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Sono stati risolti dei problemi a causa dei quali alcuni dati non venivano inviati nel rapporto Data Warehouse (AN-259951; AN-259712; AN-260107; (AN-259953)

#### Correzioni aggiuntive in Adobe Analytics o CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| ----------- | ---------- | ---------- |
| Gli agenti utenti del browser riflettono le versioni errate del sistema operativo per macOS | 19 maggio 2021 | Tutti i principali browser al momento segnalano erroneamente che gli utenti di macOS X 11 e versioni successive utilizzano macOS 10, come registrato nella stringa dell’agente utente del browser. Questo influisce sulla funzione di generazione rapporti di Adobe Analytics, che utilizza l’agente utente per determinare le informazioni sul dispositivo, tra cui il sistema operativo. Sembra che questa imprecisione sia presente per evitare problemi di compatibilità con alcuni siti Web. Consulta questo [ticket di Bugzilla](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) come riferimento. Non è chiaro quando o se questo problema verrà risolto.<br>Alcuni browser all’inizio registravano correttamente macOS 11, quindi parte del traffico potrebbe corrispondere a questo valore. Tuttavia, a causa della generazione rapporti imprecisa, il filtro per il sistema operativo macOS 11 non è attendibile.<br>Questo problema è importante perché a partire da Safari su macOS 11, Apple ha aggiornato le limitazioni di scadenza dei cookie ITP da applicare alle implementazioni CNAME (consulta il [post sul blog WebKit](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Prima di questo aggiornamento, le limitazioni si applicavano solo ai cookie “lato client” impostati tramite JavaScript. Questa imprecisione renderà difficile valutare la quantità di traffico che utilizza macOS 11 e che è quindi interessata da tali modifiche ITP. Ulteriori informazioni sui cookie e su Adobe Analytics sono disponibili [qui](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=it#cookies). |
| Fine del ciclo di vita per tre servizi API di Analytics | 19 maggio 2021 | Il 18 agosto 2021, i seguenti servizi API legacy di Analytics hanno raggiunto la data di fine del ciclo di vita e sono stati chiusi. In tale data tutte le integrazioni correnti create utilizzando questi servizi hanno cessato di funzionare.<ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Adobe ha pubblicato una sezione di [domande frequenti sulla fine del ciclo di vita delle API legacy](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere a tali domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |
| Aggiornamenti per l’area geografica ISO 2021 | 13 maggio 2021 | Il 21 maggio 2021 Adobe eseguirà gli aggiornamenti per l’area geografica ISO 2021. Dopo questa versione, sono previsti aggiornamenti meno frequenti. |
| Fine del ciclo vita delle origini dati a elaborazione completa | 12 aprile 2021 | Adobe prevede di rendere obsolete le origini dati con elaborazione completa il 31 luglio 2021. A partire dal 25 marzo 2021 non sarà più possibile creare nuove importazioni di questo tipo. Per importare questo tipo di dati, utilizza l’[API per l’inserimento di dati in blocco](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). |
| Aggiornamento dell’accesso a [!UICONTROL Report Builder] | 9 aprile 2021 | Il 14 gennaio 2021, l’accesso a [!UICONTROL Report Builder] è stato aggiornato con la rimozione delle dipendenze da tecnologie obsolete, allineando il processo di accesso con Experience Cloud. Experience Cloud utilizza l’Enterprise ID (e-mail e password). Per garantire un accesso ininterrotto a [!UICONTROL Report Builder], aggiorna il componente aggiuntivo [!UICONTROL Report Builder] alla versione 5.6.47 o successiva entro il 22 luglio 2021. A partire dalla versione 5.6.47, Report Builder supporta solo l’accesso Experience Cloud e non supporta più il single sign-on. |
| Modifiche agli indirizzi IP del feed di dati e Data Warehouse | 6 aprile 2021 | A partire dal 17 giugno, il sistema di consegna dei feed di dati e di Data Warehouse verrà spostato all’interno dei data center di Adobe, e potrebbe quindi causare un cambiamento degli indirizzi IP esterni visibili all’utente. Adobe consiglia di verificare che tutti i blocchi CIDR IP per il data center in cui vengono originati i rapporti e i feed siano presenti in tutti i firewall, per tutti i sistemi di destinazione controllati. [Elenco completo degli intervalli di indirizzi IP da inserire negli elenchi di indirizzi consentiti del firewall](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=it#data-collection-and-ftp-ip-address-blocks). |
| Modifiche imminenti al menu di Analytics | 24 marzo 2021 | Il 22 aprile 2021 Adobe ha aggiornato i menu a discesa **[!UICONTROL Componenti]**, **[!UICONTROL Strumenti]** e **[!UICONTROL Amministratore]** per ottenere alcuni miglioramenti delle prestazioni. Queste pagine saranno ancora disponibili mediante i collegamenti **[!UICONTROL Tutti i componenti]**, **[!UICONTROL Tutti gli strumenti]** e **[!UICONTROL Tutti gli amministratori]**, ma verranno rimosse dal menu a discesa. Di seguito sono elencate le voci di menu che verranno rimosse dal menu a discesa e posizionate sulla rispettiva pagina di collegamento:<br><br> [!UICONTROL Componenti]<ul><li>[!UICONTROL Segnalibri]</li><li>[!UICONTROL Dashboard]</li><li>[!UICONTROL Target]</li><li>[!UICONTROL Eventi calendario]</li><li>[!UICONTROL Rapporti programmati]</li><li>[!UICONTROL Impostazioni dei rapporti]</li></ul>[!UICONTROL Strumenti]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Amministrazione]<ul><li>[!UICONTROL Gestione utente]</li><li>[!UICONTROL Importatore di classificazione]</li><li>[!UICONTROL Generatore regole di classificazione]</li><li>[!UICONTROL Origini dati]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Impostazioni aziendali]</li><li>[!UICONTROL Registri]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Gestore codici]</li><li>[!UICONTROL Escludi per indirizzo IP]</li><li>[!UICONTROL Gestione traffico]</li></ul> |
| Elaborazione VISTA Same-as-SiteCatalyst ON | 17 marzo 2021 | Il 17 giugno 2021 tutte le suite di rapporti verranno aggiornate in modo che l’impostazione [!UICONTROL Elaborazione VISTA Same-as-SiteCatalyst] sia impostata su ON. Questa modifica influisce sui rapporti di Data Warehouse elaborando i dati in modo che corrispondano alle regole di elaborazione. Per domande o chiarimenti, contatta l’Assistenza clienti. |
| Opzioni della pagina di destinazione di Reports &amp; Analytics | 19 febbraio 2021 | Il 25 marzo 2021 sono state rimosse le opzioni per impostare nuovi dashboard di Reports &amp; Analytics o altro contenuto come pagina di destinazione personale di Adobe Analytics. Se in precedenza avevi impostato una pagina Reports &amp; Analytics come pagina di destinazione personalizzata, questa rimane funzionante fino a quando la pagina di destinazione non viene modificata in [!UICONTROL Preferenze utente]. |
| Fine del ciclo di vita di Adobe Data Connectors | 13 luglio 2020 | Adobe [!UICONTROL Data Connectors] si basa su una tecnologia legacy, che non è più disponibile o supportata. Un nuovo standard è disponibile in [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). Puoi utilizzare questo standard per continuare a offrire e supportare qualsiasi integrazione. La data ufficiale di fine del ciclo di vita è il 1° agosto 2021. [Ulteriori informazioni...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=it) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Per gli ultimi aggiornamenti sulle versioni di AppMeasurement, fai riferimento alle [note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=it).

### Nuovi corsi ed esercitazioni di Analytics {#tutorials-analytics}

Nuovi corsi, esercitazioni e articoli in [!DNL Analytics] e [!UICONTROL Customer Journey Analytics].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Giugno 2021 | [Guida introduttiva di Customer Journey Analytics per gli amministratori](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Corso | Scopri come configurare, configurare e amministrare il Customer Journey Analytics. Scopri alcuni concetti di base per fornire una base, quindi passa a ulteriori passaggi di configurazione. Il corso viene quindi interrotto con alcune raccomandazioni sulla migrazione di metriche calcolate e segmenti da Adobe Analytics al Customer Journey Analytics. |
| Giugno 2021 | [Configurare i rapporti sulla ricerca interna del sito](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Video | Crea e configura tabelle a forma libera in Analysis Workspace per analizzare le funzionalità di ricerca interna sul sito. |
| Giugno 2021 | [Mappare le variabili Web SDK in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Video | Scopri come mappare le variabili di analisi dall’SDK per web ad Adobe Analytics utilizzando le Regole di elaborazione. |
| Giugno 2021 | [Implementare le variabili di ricerca interna tramite Web SDK](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Video | Scopri come utilizzare l’SDK per web per implementare le variabili Adobe Analytics per un caso di utilizzo del tracciamento dei termini di ricerca interno. Visualizza il flusso di dati dalla pagina a Experience Edge e quindi ad Adobe Analytics. |
| Giugno 2021 | [Implementare le variabili di ricerca interna utilizzando AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Video | In questo video, scopri i passaggi necessari per implementare variabili di ricerca interne del sito per Adobe Analytics utilizzando Raccolta dati di Experience Platform/Launch, incluso il termine di ricerca, il numero di risultati e altri. |
| Giugno 2021 | [Definizione dei requisiti aziendali interni per la ricerca del sito](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Video | Quando decidi di tenere traccia della ricerca interna sul tuo sito, è importante prima decidere quali aspetti della ricerca desideri monitorare e quali azioni possono essere intraprese dall’analisi dei risultati. Questo video illustra la documentazione dei requisiti aziendali. |

{style=&quot;table-layout:auto&quot;}

### Risorse dell’Aiuto di Analytics

* [Documentazione e tutorial del prodotto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=it)

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Correzioni e miglioramenti in Audience Manager.

### Correzioni e miglioramenti {#aam-fixes-and-improvements}

* È stato rilasciato un miglioramento al [Report sull&#39;utilizzo dell&#39;attività](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) che ora ti consente di rivedere i dati con più di un anno. (AAM-58268)
* Adobe fornisce ai clienti di Audience Manager le chiavi di accesso utente per i bucket Audience Manager Amazon S3. Per motivi di sicurezza, le chiavi vengono ora disattivate automaticamente dopo 100 giorni di inattività. Per ulteriori informazioni, consulta la domanda nella parte inferiore della pagina nelle [Domande frequenti sulla raccolta dei dati e l’integrazione dei prodotti](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Experience Manager (AEM). Ai clienti con implementazioni on-premise, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, protezione e prestazioni migliori.

>[!NOTE]
>
>Per gli ultimi aggiornamenti sulle varie versioni, visita regolarmente la pagina [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it).

### Aggiornamenti dei prodotti AEM

* **Experience Manager 6.5.9.0**

   AEM 6.5 Service Pack 9.0 (6.5.9.0, rilasciato il 27 maggio 2021), è un aggiornamento importante che include nuove funzionalità, miglioramenti chiave richiesti dai clienti, prestazioni, stabilità e sicurezza migliorate, rilasciato dopo la disponibilità generale di AEM 6.5 di aprile 2019.

   * [Note sulla versione](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=it)
   * [Rilascio delle versioni finali di AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### Rilasci di prodotti AEM

* **Experience Manager as a Cloud Service**

   Nuove funzioni di Experience Manager as a Cloud Service:

   * **Fondamenti di Adobe Experience Manager as a Cloud Service**

      * [Canale](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en) pre-rilascio: Anteprima delle prossime funzionalità un mese prima che diventino live in produzione!
      * [Obsolescenza API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en): Elenco delle API obsolete più recenti.
      * [Experience Manager di plug-in Maven di Cloud Service SDK Build Analyzer](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en): Aggiorna i progetti Maven all&#39;ultima versione, che include un controllo Java™ API obsoleto e altri miglioramenti.
   * **Experience Manager Sites as a Cloud Service**

      * **Endpoint GraphQL:** è ora possibile abilitare l’API GraphQL di Experience Manager per le configurazioni di Experience Manager Sites individuali e creare endpoint GraphQL personalizzati per tali configurazioni utilizzando una nuova interfaccia utente della console GraphQL. L’interfaccia utente consente inoltre di gestire gli endpoint GraphQL.
      * **Modelli di contenuto, tipo di dati Data e ora avanzato:** è ora possibile configurare il tipo di data e ora per consentire l’authoring solo di informazioni su data, ora o data e ora.
      * **Modelli di contenuto, tipo di dati di tag avanzati:** è ora possibile configurare il tipo di dati Tag per consentire la creazione di uno o più tag.
      * **Modelli di contenuto, nuovo tipo di dati segnaposto tabulazione:**  il nuovo tipo di dati segnaposto per tabulazione consente di raggruppare i tipi di dati in sezioni sottoposte a rendering in schede nell’editor frammento di contenuto.
   * **Experience Manager Assets as a Cloud Service**

      Ora puoi verificare il contenuto in un nuovo [livello anteprima](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) per simulare l’aspetto e l’aspetto dell’esperienza finale come nel livello di pubblicazione. Questa nuova funzionalità è abilitata dalla procedura guidata Pubblicazione gestita in Experience Manager Sites , che consente di scegliere una destinazione di pubblicazione tra [!UICONTROL Pubblica] o [!UICONTROL Anteprima]. Le esperienze su [!UICONTROL Preview] sono quindi accessibili tramite un URL dedicato. Dopo la convalida su [!UICONTROL Anteprima], il contenuto può essere pubblicato come di consueto da [!UICONTROL Autore] a [!UICONTROL Pubblica]. L&#39;abilitazione del servizio [!UICONTROL Preview] in Experience Manager as a Cloud Service sta gradualmente scomparendo nelle prossime settimane.

   * **Experience Manager di risorse come Cloud Service**

      Nuove funzioni nel canale prerelease:

      * Gli schemi di metadati possono essere applicati direttamente alle proprietà della cartella.
      * Lo strumento [!UICONTROL Asset Bulk Ingestor] consente di aggiungere metadati durante un’acquisizione in blocco.
      * Un miglioramento dell’esperienza utente visualizza il numero di risorse presenti in una cartella. Per più di 1000 risorse in una cartella, Risorse di Experience Manager ne visualizza più di 1000.

      Nuove funzioni in [!UICONTROL Dynamic Media]:

      * Le funzioni DPR (Smart Imaging Device Pixel Ratio) e di ottimizzazione della larghezza di banda della rete consentono di fornire immagini di alta qualità in modo efficiente su dispositivi con display ad alta risoluzione e larghezza di banda limitata della rete. Consulta [domande frequenti sull&#39;imaging intelligente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).




### **Community AEM**

* [One-Stop-Shop per tutti i blog di Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Linee guida per la presentazione di una nuova idea Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Summit Adobe 2021 Sneaks con Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865): Una volta all&#39;anno, ogni dipendente Adobe, da ingegneri e scienziati dei dati a designer e product manager UX, ha la possibilità di condividere idee innovative per evolvere il modo in cui i marchi interagiscono con i loro clienti. Unisciti a noi per Adobe Sneaks, dove condividiamo i primi sette progetti, toccando le ultime tecnologie in aree come l’intelligenza artificiale e app a basso codice.

### Informazioni sulla versione di Experience Manager

Nelle pagine seguenti trovi tutte le note sulla versione di Experience Manager:

* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Note sulla versione di Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=it)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Note sulla versione di Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Note sulla versione di Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=it)
* [Note sulla versione di Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=it)
* [Note sulla versione dell’app desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Note sulla versione di Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=it)
* [Note sulla versione di Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=it)

### Nuovi corsi ed esercitazioni su Experience Manager  {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Giugno 2021 | [Implementare i metodi dell’interfaccia](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Articolo | Scopri come implementare i metodi di interfaccia per creare PDF utilizzando l’API REST di Document Cloud. |
| Giugno 2021 | [Crea interfaccia servizio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Articolo | Definisci i metodi nell’interfaccia da esporre. |
| Giugno 2021 | [Creare una configurazione OSGi personalizzata](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Articolo | Scopri la configurazione OSGi personalizzata per acquisire i dettagli del progetto Adobe I/O. |
| Giugno 2021 | [Creare un’analisi del contenuto](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Articolo | Scopri come creare la parte JSON contenente le informazioni sui parametri di input per la chiamata Create PDF REST . |
| Giugno 2021 | [Crea passaggio di processo personalizzato](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Articolo | Visualizzare il codice completo del passaggio del processo personalizzato che converte e sostituisce i file nativi con i PDF convertiti. Questo passaggio personalizzato cerca tutti gli allegati sotto il nome della cartella, fornito come argomento di processo nel flusso di lavoro. Questo passaggio del processo personalizzato utilizza i metodi del `DocumentCloudSDKService` personalizzato per la creazione di PDF. |
| Giugno 2021 | [Query persistenti GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Video | Scopri come abilitare, creare, aggiornare ed eseguire query persistenti in Experience Manager. |
| Giugno 2021 | [Creazione del primo servlet in AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Articolo | Crea il tuo primo servlet sling in modo da poter unire i dati con un modello di modulo. |
| Giugno 2021 | [Creazione del primo servizio OSGi con Experience Manager forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Articolo | Crea il tuo primo servizio OSGi con AEM Forms in modo da poter generare PDF unendo i dati con il modello. |

{style=&quot;table-layout:auto&quot;}

### Altre risorse di assistenza per Experience Manager

* [Guide di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Formazione e supporto per Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=it)
* [Formazione e supporto per Experience Manager 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Formazione e supporto per Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it#previous-updates)
* [Documentazione delle versioni precedenti di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Guida utente di Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
* [Pagina iniziale della guida di Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=it)
* [Documentazione di Experience Manager: ultimi aggiornamenti](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=it#aem-as-a-cloud-service)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Ultime versioni dei prodotti

Scopri le funzionalità, i miglioramenti e le correzioni più recenti:

* **Nuovo Adobe Campaign v8** con miglioramenti significativi a livello di infrastruttura, sicurezza, recapito messaggi e monitoraggio. Utilizzando [!DNL Snowflake], una tecnologia di database cloud, Adobe Campaign ne migliora notevolmente la scala e la velocità, con la possibilità di gestire un numero più significativo di profili cliente, oltre a tassi di consegna e transazioni molto più elevati all’ora. Ulteriori informazioni sono disponibili nella [documentazione di Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Adobe Campaign Classic v7 versione** 21.1.3: Ulteriori informazioni sono disponibili nelle note sulla versione di  [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Versione** di Adobe Campaign Standard 21.2: Ulteriori informazioni sono disponibili nelle note sulla versione di  [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html).

### Nuovi corsi ed esercitazioni [!UICONTROL Campaign]{#tutorials-campaign}

| Data di pubblicazione | Nome | Soluzione | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Giugno 2021 | [Integra Campaign Standard con Analytics per ottimizzare il tuo marketing via e-mail](https://experienceleague.adobe.com/?lang=it#dashboard/learning) | Campaign Standard | (Corso) Scopri come integrare Campaign Standard con Adobe Analytics e ottimizzare le strategie di marketing e-mail utilizzando dati in tempo reale. Questo corso illustra come creare un rapporto Campaign Standard in Adobe Analytics. Poi, scopri come utilizzare Experience Cloud Triggers e Platform launch per configurare messaggi di marketing e messaggi transazionali in base all’attività del cliente. |
| Giugno 2021 | [Tutorial su Adobe Campaign V8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | La presente guida utente contiene video e tutorial sulle numerose funzioni e caratteristiche di Adobe Campaign V8. |
| Giugno 2021 | [Creare e progettare gli invii di e-mail](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campagna V8 | (Video) Comprendi il processo di creazione di una consegna e-mail e impara a progettare e personalizzare il contenuto delle e-mail. |
| Giugno 2021 | [Creare e-mail per il recapito](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campagna V8 | (Video) Scopri come applicare le best practice sul recapito messaggi alle consegne e-mail. |
| Giugno 2021 | [Gestire l’affaticamento utilizzando le regole di tipologia](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campagna V8 | (Video) Scopri come implementare la gestione dell’affaticamento applicando le regole di tipologia. |
| Giugno 2021 | [Configurare la gestione dell’affaticamento utilizzando i filtri](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Video) Scopri come implementare la gestione dell’affaticamento in Adobe Campaign utilizzando i filtri. |

{style=&quot;table-layout:auto&quot;}

### Risorse per Campaign

* Adobe Campaign Standard: [Centro assistenza](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Piano delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* Adobe Campaign Classic: [Centro assistenza](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en)  - Video introduttivi per [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=it) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=it)

## ![Icona](/assets/advertising-cloud.png) Advertising {#adcloud}

Note sulla versione di [!DNL Adobe Advertising].

* [Nuove funzioni di Advertising DSP](#adcloud-dsp)
* [Nuove funzioni di Advertising Search](#adcloud-search)

### Nuove funzioni di [!DNL Advertising DSP] {#adcloud-dsp}

Ultimo aggiornamento: **10 giugno 2021 per la versione del 16 giugno**

| Funzione | Descrizione |
| -----------| ---------- |
| Gestione delle campagne | La previsione è disponibile per posizionamenti di visualizzazione standard con velocità a livello di posizionamento e budget (rilascio del 16 giugno). |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni di [!DNL Advertising Search] {#adcloud-search}

Ultimo aggiornamento: **19 maggio 2021, per la versione del 18 maggio**

| Funzione | Descrizione |
| -----------| ---------- |
| [!UICONTROL Centro notifiche Beta] | Il [!UICONTROL Centro notifiche Beta] è disponibile per tutti gli utenti. Utilizzalo per ricevere e-mail e notifiche Web sugli errori di autenticazione dell’account, avvisi personalizzati attivati e per conoscere quando gli [!UICONTROL Insight sulla pubblicità] che hai generato sono completi.<br>Puoi visualizzare le notifiche da:<ul><li>Il pannello [!UICONTROL Notifiche], che si apre dal collegamento Notifiche nell’angolo superiore destro di qualsiasi pagina.</li><li>Il [!UICONTROL Centro notifiche], che si trova sotto [!UICONTROL Insights e report > Centro notifiche Beta].</li></ul><br><b>Nota:</b> a causa dei miglioramenti alla modalità di memorizzazione delle notifiche, tutte le notifiche esistenti sono state cancellate. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/magento.png) [!DNL Magento] {#magento}

Per informazioni sull’ultima versione, consulta le [note sulla versione](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) di Magento Commerce e Open Source.

## ![Icona](/assets/target.png)[!DNL Target] {#target}

Per informazioni sempre aggiornate, consulta le [[!DNL Target] note sulla versione](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it).

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per chi si occupa di lead management e B2B e intende trasformare le esperienze dei clienti coinvolgendoli in ogni fase di complessi percorsi d’acquisto.

### Aggiornamenti principali di Marketo Engage

Per informazioni aggiornate sulla pianificazione delle versioni e sulle relative note sulla versione, consulta [!DNL Marketo Engage] [pianificazione delle versioni](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) .

## ![Icona](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] è un&#39;applicazione unificata di gestione del lavoro per condividere idee, creare contenuti, gestire processi complessi e lavorare al meglio.

Consulta la pagina [[!DNL Workfront] release](https://one.workfront.com/s/product-releases) per una raccolta delle informazioni più recenti per tutti i prodotti.

## ![Icona](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nuovi video, tutorial o corsi pubblicati per Adobe Document Cloud.

### Corsi ed esercitazioni di Document Cloud {#tutorials-doc-cloud}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Giugno 2021 | [Adobe Acrobat per Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Video | Accedi agli strumenti PDF e ai flussi di lavoro di firma elettronica che consentono di risparmiare tempo direttamente nell’app Google Drive. |

{style=&quot;table-layout:auto&quot;}

Per Document Cloud, consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/it/support/document-cloud.html)

## ![Icona](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| ----------| --------- | --------- | --------- |
| Giugno 2021 | [Prova la tua mano al Fresco sull&#39;iPad (e iPhone)](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Video | Scopri un nuovo mondo di disegno e pittura digitale con Adobe Fresca in questo workshop pratico di 15 minuti. Imparare rapidamente a lavorare con livelli e maschere di ritaglio per adattare la vernice e le texture a una forma base. |
| Giugno 2021 | [Decodificazione della zuppa di Alfabeti di Formati Grafici](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Video | I file PG, PNG, SVG, GIF ed EPS sono tutti comunemente utilizzati nella progettazione, alcuni per pagine web, altri per presentazioni, pubblicazioni e progetti creativi. Ma... cosa vogliono dire, e quale dovreste scegliere? Scoprite in questo workshop pratico di 15 minuti. |

{style=&quot;table-layout:auto&quot;}

Per i tutorial più recenti, consulta i [tutorial Creative Cloud for Enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=it).
