---
title: Note sulla versione più recente
description: Scopri le ultime note sulla versione, le nuove funzioni e la nuova documentazione per  [!DNL Experience Cloud] prodotti e servizi. Trova nuove guide ed esercitazioni su [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: d2d02b2130c11f1971220646ac19f4fa6f0ab5da
workflow-type: tm+mt
source-wordcount: '5553'
ht-degree: 38%

---

# Note sulla versione di Adobe Experience Cloud - Ottobre 2021

![Banner](assets/experience-cloud-banner-3.png)

Le applicazioni di [!DNL Experience Cloud] vengono aggiornate ogni mese. Su questa pagina puoi trovare gli aggiornamenti, la documentazione e i tutorial più recenti per [!DNL Experience Cloud] ed [!DNL Experience Platform]. Trovi inoltre la nuova documentazione di [!DNL Creative Cloud for enterprise] e [!DNL Document Cloud].

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche mensili via e-mail sugli aggiornamenti a questa pagina. La pagina viene aggiornata nell’arco di tutto il mese, quindi controlla regolarmente se ci sono aggiornamenti sui prodotti aziendali di Adobe e sulla documentazione di Experience League.

Ultimo aggiornamento: **13 ottobre 2021**

* [[!DNL Experience League] Eventi live](#events)
* [[!DNL Experience Cloud Central Interface Components] e amministrazione](#ecloud)
* [[!UICONTROL Stato dei sistemi] Adobe](#status)
* [[!DNL Adobe Analytics]](#analytics) e [Customer Journey Analytics](#cust-journey)  **Aggiornato il 7 ottobre 2021**
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem) (aggiornato il 13  **ottobre 2021**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home) per trovare documentazione tecnica e sui prodotti, corsi curati da Adobe, esercitazioni video, risposte rapide, insight sulla community e corsi di formazione tenuti da istruttori.

## ![Icona](/assets/experience-league.png) [!DNL Experience League] Eventi live {#events}

[!DNL Experience League] Gli eventi live sono incontri con esperti Adobe e ospiti speciali, utili per portare la tecnologia Adobe al pubblico. Visualizza la programmazione seguente e unisciti a noi in diretta o guarda gli eventi registrati in precedenza.

| Data evento | Tempo | Nome evento | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |---------- |
| 21 ottobre 2021 | 12 (EST) | [Chi l&#39;ha cliccato? Generazione di rapporti avanzati sui clic sui collegamenti con Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | Evento video live | Il reporting sull’interazione dell’utente con la proprietà web o mobile rappresenta un elemento fondamentale per comprendere il percorso del cliente. Con Adobe Analytics puoi capire chi, cosa, perché e dove di ogni clic nell’applicazione. Gli esperti di Adobe Analytics possono imparare a utilizzare le classificazioni Activity Map e l’attribuzione personalizzata per comprendere meglio il coinvolgimento degli utenti. |
| 23 settembre 2021 | Su richiesta | [Suggerimenti degli esperti per dare risalto alle campagne per le vacanze](https://www.youtube.com/watch?v=bsU1lAv0xes) | Evento video live | Proprio come non è mai troppo presto per iniziare a fare acquisti per le vacanze, non è mai troppo presto per iniziare a pianificare una campagna di marketing per vacanze di successo. Con Adobe Campaign puoi progettare, pianificare ed eseguire campagne che concretizzano tutti i desideri per le vacanze della tua azienda.<br>Ma conosci tutti i suggerimenti per l&#39;esecuzione di campagne che finiscono l&#39;anno con un colpo? Partecipa a Sandra per una discussione dal vivo con tre esperti Adobi che hanno eons di esperienza collettiva nel fare proprio questo. |
| 26 agosto 2021 | Su richiesta | [Rendi il tuo prossimo segmento di pubblico più in gamba che mai](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=it) | Registrazione di eventi | Il successo di ogni buona campagna di marketing dipende dal targeting preciso del pubblico. Con il nuovo [!UICONTROL generatore di segmenti] di Adobe Experience Platform, puoi creare il tuo prossimo segmento di pubblico utilizzando i dati di profilo e il comportamento degli utenti basato sul tempo tra i canali. Non c’è modo migliore di garantire che i tuoi messaggi raggiungano chi ha bisogno di ascoltarli di più. |
| 29 luglio 2021 | Su richiesta | [I miei tre suggerimenti preferiti per l’implementazione di Adobe Analytics](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=it) | Registrazione di eventi | L’hai visto sul palco al Summit. L’hai sentito condividere consigli di esperti all’Adobe Insider Tour. Potresti anche aver avuto l’opportunità di lavorare con lui sulla tua implementazione di Adobe Analytics. Adesso, Eric Matisoff porta i suoi tre suggerimenti preferiti per l’implementazione di Adobe Analytics in questo incontro esclusivo live di Experience League. |

{style=&quot;table-layout:auto&quot;}

Per ulteriori video, visita il [canale Adobe Experience League](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) su YouTube.

## ![Icona](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] e amministrazione {#ecloud}

| Funzione | Descrizione |
| ------- | ------- |
| Ricerca unificata | La ricerca unificata continua ad aggiungere tipi di oggetti all&#39;indice di ricerca. In questo aggiornamento, la ricerca globale ora cerca tra il contenuto di Experience League e i seguenti tipi di oggetti Journey Optimizer: <ul><li>Set di dati</li><li>Destinazioni</li><li>Query</li><li>Schemi</li><li>Segmenti</li><li>Fonti</li><li>Offerte</li><li>Componenti</li><li>Messaggi</li><li>Percorsi</li></ul> |
| Consenso dei dati di utilizzo del prodotto | Dopo un accesso iniziale, ti viene chiesto di inviare preferenze su come Adobe puoi fornire contenuti utili e personalizzati, come esercitazioni, guide, suggerimenti rapidi, consigli, video di apprendimento e altro ancora, in base ai dati di utilizzo del prodotto di Experience Cloud. Questa richiesta include anche un aggiornamento delle tue preferenze per la raccolta e l&#39;utilizzo di questi dati in <https://experience.adobe.com/preferences>. |
| Experience Cloud [!UICONTROL Navigazione trigger] | [Experience Cloud ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) Attivazione disponibile per la navigazione diretta dallo switcher dell&#39;applicazione nell&#39;intestazione per gli utenti con provisioning. |
| **Avviso:** pianificazione dell&#39;aggiornamento della navigazione nell&#39;interfaccia | A novembre 2021, la funzione di navigazione _[!UICONTROL Vai a Launch / Raccolta dati]_ verrà rimossa da <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Altre risorse di aiuto su [!DNL Experience Cloud Central UI Components] e amministrazione**

* Aiuto per l’amministrazione di [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=it) e gestione degli utenti
* Note sulla versione e guida di [Places: servizio di geolocalizzazione](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=it)
* Guida di [People: Attributi del cliente e Libreria tipi di pubblico](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icona](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi di Adobe. Consulta [status.adobe.com](https://status.adobe.com/it).

(Per informazioni aggiornate sulla versione [!DNL Adobe System Status], consulta le note sulla versione del [21 maggio 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=it).)

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **7 ottobre 2021**

* [Nuove funzioni di Adobe Analytics](#aa-features)
* [Nuove funzioni in Customer Journey Analytics](#cust-journey)  **Aggiornato il 7 ottobre 2021**
* [Correzioni in Adobe Analytics](#aa-fixes)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [Corsi ed esercitazioni su Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nuove funzioni di Adobe Analytics {#aa-features}

| Funzione | Descrizione | [Disponibilità generale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=it) - data di Target |
| ----------- | ---------- | ------- |
| Visualizzazioni per le dashboard di Analytics | Analytics [!UICONTROL Dashboard] introduce tre nuove visualizzazioni per consentire ai dirigenti e ai responsabili decisionali di comprendere meglio a colpo d&#39;occhio i propri dati. I nuovi grafici a barre [!UICONTROL Dado], [!UICONTROL Linea] e [!UICONTROL Orizzontale] semplificano la visualizzazione dei dati per singoli elementi dimensionali, senza dover aprire una visualizzazione dei dettagli. [Ulteriori informazioni](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/create-scorecard.html?lang=en#apply-visualizations) | 7 ottobre 2021 |
| [!UICONTROL Tempo di riproduzione dei contenuti multimediali trascorso] | Adobe Streaming Media Playback [!UICONTROL Time Spent] fornisce informazioni utili sul coinvolgimento dei visualizzatori e consente alle organizzazioni dei media di ottenere informazioni più approfondite e dettagliate con un coinvolgimento degli utenti minuto per minuto attraverso un&#39;analisi avanzata del tempo trascorso con funzionalità di ripartizione giornaliera. È possibile osservare il tempo impiegato per visualizzare i flussi multimediali in un determinato momento. È possibile suddividere la durata della riproduzione in base a granularità diverse, tra cui nuove granularità di 5 minuti, 15 minuti e 30 minuti. [Ulteriori informazioni](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18 ottobre 2021 |
| Generatore di segmenti [!UICONTROL rapido] | Consente agli utenti aziendali di applicare rapidamente i segmenti di base in un flusso di lavoro di progetto semplificato e in linea. Non è necessario passare al [!UICONTROL Generatore di segmenti]. [Ulteriori informazioni](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21 ottobre 2021 |
| Miglioramenti alla ricerca per barra a sinistra in Analysis Workspace | La ricerca a sinistra della barra 1) dà priorità alle corrispondenze esatte al di sopra delle grandi corrispondenze, oltre a continuare a tenere conto della recency dei componenti e della loro rilevanza. 2) Evidenzia i caratteri corrispondenti per rendere i risultati della ricerca più comprensibili. 3) È più facile trovare le classificazioni relative a una dimensione. 4) Infine, supporta la ricerca di caratteri jolly (`*`) per trovare più facilmente i componenti specifici necessari. Nota: La ricerca con caratteri jolly non funziona ancora a livello di elemento dimensionale. | 21 ottobre 2021 |
| Tema scuro Analysis Workspace | Il tema scuro è disponibile come opzione di visualizzazione. | 21 ottobre 2021 |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni di Customer Journey Analytics {#cust-journey}

| Funzione | Descrizione | [Disponibilità generale](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - data di Target |
| ----------- | ---------- | ----- |
| Finestra continua per la conservazione dei dati [!UICONTROL Connection] | **Nota: Contatta l’Assistenza clienti o il tuo responsabile commerciale Adobe per far sì che questa impostazione sia implementata. Non è ancora disponibile tramite l’interfaccia utente di CJA.**<p>Consente di definire un’impostazione di conservazione dei dati CJA come finestra continua in mesi (3 mesi, 6 mesi, ecc.), a un livello [!UICONTROL connessione] (non a un livello [!UICONTROL dataset]). La conservazione dei dati si basa sulle marche temporali dei set di dati dell’evento e si applica solo ai set di dati dell’evento. Non esiste alcuna impostazione di conservazione dei dati per i set di dati di profilo o di ricerca, in quanto non sono disponibili marche temporali applicabili. Il vantaggio principale consiste nell’archiviare o creare rapporti solo sui dati applicabili e utili, nonché nell’eliminare i dati meno recenti che non sono più utili. Ti aiuta a rimanere sotto i limiti del tuo contratto e riduce il rischio di sovraccosti. | 7 ottobre 2021 |
| Supporto Report Builder | Report Builder è un componente aggiuntivo Microsoft® [!DNL Excel] che consente di creare, modificare e aggiornare facilmente i rapporti personalizzati utilizzando i dati di Customer Journey Analytics. Con Report Builder ed Excel, puoi utilizzare l’interfaccia utente semplice ma flessibile con trascinamento della selezione per creare facilmente richieste di dati complesse. Con Report Builder per Customer Journey Analytics, puoi:<ul><li>Fai riferimento alle celle del foglio di lavoro esistenti per ottenere l&#39;ordine di riga, l&#39;intervallo di date o il filtro perfetti</li><li>Crea date personalizzate utilizzando calendario, riferimenti di cella o matematica della data</li><li>Progettazione di tabelle e visualizzazioni con strumenti di formattazione di Excel</li><li>Disponibile per Excel su macOS, Microsoft 365 per il Web e Microsoft Windows</li></ul>[Ulteriori informazioni](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-reportbuilder/report-buider-overview.html#) | 7 ottobre 2021 |
| Visualizzazioni per le dashboard di Analytics | Analytics [!UICONTROL Dashboard] introduce tre nuove visualizzazioni per consentire a dirigenti e responsabili decisionali di comprendere meglio a colpo d&#39;occhio i propri dati. I nuovi grafici a barre ad anello, a linee e orizzontali semplificano la visualizzazione dei dati per i singoli elementi dimensionali, senza dover aprire una visualizzazione dei dettagli. [Ulteriori informazioni](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html?lang=en#apply-visualizations) | 7 ottobre 2021 |
| API dei registri di controllo del Customer Journey Analytics | L&#39;endpoint API [Registro di controllo](https://adobe.io/cja-apis/docs/endpoints/auditlogs/) consente di richiedere ad Adobe i dati del registro di controllo. È una parte importante della conformità in materia di sicurezza e per il controllo dei dati o delle azioni degli utenti. | 7 ottobre 2021 |
| Generatore di filtri [!UICONTROL rapido] | Consente agli utenti aziendali di applicare rapidamente i segmenti di base in un flusso di lavoro di progetto semplificato e in linea. Non è necessario passare al [!UICONTROL Generatore di filtri]. [Ulteriori informazioni](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21 ottobre 2021 |
| Miglioramenti alla ricerca per barra a sinistra in Analysis Workspace | La ricerca a sinistra della barra 1) dà priorità alle corrispondenze esatte al di sopra delle grandi corrispondenze, oltre a continuare a tenere conto della recency dei componenti e della loro rilevanza. 2) Evidenzia i caratteri corrispondenti per rendere i risultati della ricerca più comprensibili. 3) È più facile trovare le classificazioni relative a una dimensione. 4) Infine, supporta la ricerca di caratteri jolly (`*`) per trovare più facilmente i componenti specifici necessari. Nota: La ricerca con caratteri jolly non funziona ancora a livello di elemento dimensionale. | 21 ottobre 2021 |
| Tema scuro Analysis Workspace | Il tema scuro è disponibile come opzione di visualizzazione. | 21 ottobre 2021 |

{style=&quot;table-layout:auto&quot;}

### Correzioni in Adobe Analytics e CJA {#aa-fixes}

* È stato corretto un errore del rapporto pianificato in Customer Journey Analytics. (AN-271721)
* Sono stati risolti dei problemi relativi a [!UICONTROL Componenti di ricerca] in [!UICONTROL Area di lavoro] che non determinavano corrispondenze esatte. (AN-253937; AN-271707)

#### Ulteriori correzioni in Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| ----------- | ---------- | ---------- |
| Fine del ciclo di vita per tre servizi API di Analytics | 16 settembre 2021 | Il **20 ottobre 2021**, i seguenti servizi API legacy di Analytics raggiungeranno la data di fine del ciclo di vita e verranno chiusi. In tale data tutte le integrazioni correnti create utilizzando questi servizi cesseranno di funzionare.<ul><li>API di Analytics 1.3</li><li>API di Analytics SOAP 1.4</li><li>Autenticazione per la versione precedente di OAuth (OAuth e JWT)</li></ul>Adobe ha pubblicato una sezione di [domande frequenti sulla fine del ciclo di vita delle API legacy](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) per rispondere a tali domande e fornire indicazioni su come procedere. Le integrazioni API che utilizzano questi servizi possono eseguire la migrazione alle [API REST di Analytics 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o alle [API di Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). I precedenti account OAuth possono migrare a un account di integrazione [Adobe I/O](https://developer.adobe.com/console) Analytics, che può essere utilizzato per accedere sia alle API di Analytics 1.4 che alle API di Analytics 2.0. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Per gli ultimi aggiornamenti sulle versioni di AppMeasurement (versione 2.22.2), fai riferimento alle [note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=it).

### Corsi ed esercitazioni su Analytics {#tutorials-analytics}

Corsi, esercitazioni e articoli più recenti in [!DNL Analytics] e [!UICONTROL Customer Journey Analytics].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [Utilizzo delle visualizzazioni per raccontare le tue storie di dati](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Corso | Chi vuole eliminare una tabella dopo una tabella solo per cercare di estrarre informazioni dai dati? Non tu! In questo corso, scopri le nozioni di base sulle visualizzazioni, tra cui come aggiungerle a un progetto, inserire i dati in esso e cosa ciascuna visualizzazione può mostrarti. Scopri come configurare le impostazioni per ottenere i dati esatti necessari. Inoltre, scopri alcuni suggerimenti e casi d’uso per aiutarti a rendere le visualizzazioni pratiche per la tua analisi regolare. |

{style=&quot;table-layout:auto&quot;}

### Risorse dell’Aiuto di Analytics

* [Documentazione e tutorial del prodotto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=it)

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Nuove funzioni di Audience Manager (aggiornato il **14 settembre 2021**):

| Funzione | Descrizione |
| ------- | ------- |
| Consenso alla raccolta dati per ID da dispositivi mobili | È stato aggiunto il supporto per il consenso alla raccolta dati per ID da dispositivi mobili. Per beneficiare di questo aggiornamento, i clienti devono effettuare l’aggiornamento a [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) o successivo. |

## ![Icona](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Include informazioni sull&#39;aggiornamento della versione e nuova documentazione per Experience Platform e [!UICONTROL Mobile SDK].

**29 settembre 2021**

| Funzione | Descrizione |
| ------- | ------- |
| [[!UICONTROL Zona di destinazione dei dati]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL Data Landing ] Zoneè un  [!DNL Platform]Azure Blob   Store predisposto che consente a un unico archivio protetto e temporaneo per sandbox di portare i file in Experience Platform. |
| Supporto delle origini di streaming per [preparazione dei dati](https://www.adobe.com/go/monitor-streaming-dataflows-en) | Le origini di streaming ora supportano la preparazione dei dati, che consente di fornire uno schema di origine JSON per mappare dati di origine non compatibili con XDM su uno schema XDM di destinazione. |
| [Credenziali non in scadenza](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | Le credenziali non in scadenza per gli utenti [!UICONTROL Query Service] consentono connessioni più permanenti ai client esterni invece di rinnovare le credenziali ogni 24 ore. |
| [[!UICONTROL SDK per la destinazione]](https://www.adobe.com/go/destination-sdk-overview-en) | Utilizza [!UICONTROL SDK di destinazione] per l&#39;integrazione con [!DNL Platform] e contribuire al catalogo delle destinazioni in continua crescita. L’accesso a questa funzione è disponibile solo per i clienti di Experience Platform Activation . |

Per i dettagli, consulta le [note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it).

### Tutorial e corsi su Experience Platform {#tutorials-platform}

Video, esercitazioni o corsi più recenti pubblicati per Experience Platform e servizi.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [[!DNL Platform] Amministrazione](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Corso | Scopri le attività di amministrazione, ad Experience Platform la gestione di autorizzazioni e sandbox. |

{style=&quot;table-layout:auto&quot;}

### SDK di Adobe Mobile

Consulta le [note sulla versione e registri di modifica](https://aep-sdks.gitbook.io/docs/release-notes) per gli SDK di Adobe Experience Platform Mobile.

## ![Icona](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [Note sulla versione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it).

### Esercitazioni e corsi su Journey Optimizer {#tutorials-ajo}

Esercitazioni più recenti su Journey Optimizer:

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [Configurare e gestire i dati  [!DNL Journey Optimizer] in per data engineer](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Corso | Scopri come configurare e gestire i dati necessari per la gestione dei percorsi in Journey Optimizer. |
| Ottobre 2021 | [Guida introduttiva  [!DNL Journey Optimizer] per amministratori di Percorso e manager](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Corso | Scopri tutto quello che devi sapere per creare il tuo primo percorso. |
| Ottobre 2021 | [ [!DNL Journey Optimizer] Configurazione per gli amministratori di Percorso](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Corso | Scopri l’architettura [!DNL Journey Optimizer] e i punti di integrazione. Scopri come configurare [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### Altre risorse su [!DNL Journey Optimizer]

[Centro assistenza](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Utilizza Experience Platform per orchestrare il percorso di un cliente su grande scala tra i diversi canali di esperienza, anticipando in modo intelligente le esigenze di ogni cliente in tempo reale.

### Versioni più recenti dei prodotti [!DNL Journey Orchestration]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [[!DNL Journey Orchestration] Note sulla versione di ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it).

#### Altre risorse su [!DNL Journey Orchestration]

[Centro assistenza](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer ] Decisioningè un servizio integrato con Adobe Experience Platform. Utilizza [!UICONTROL Offer decisioning] per offrire ai clienti l’offerta e l’esperienza migliore al momento giusto, in tutti i punti di contatto.

### Versioni più recenti dei prodotti Offer Decisioning

Ulteriori informazioni sulle funzionalità, sui miglioramenti e sulle correzioni più recenti in [Note sulla versione di Offer Decisioning](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Altre risorse per [!UICONTROL Offer Decisioning]

[Centro assistenza](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Icona](/assets/aem.png) Experience Manager {#aem}

Per gli ultimi aggiornamenti sulle varie versioni, visita regolarmente la pagina [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it).

**Aggiornamento 13/10/2021:** guarda il video di  [panoramica sulla versione di ](https://video.tv.adobe.com/v/337381) settembre 2021 per una panoramica delle nuove funzioni.

### Community

* [Sviluppatori Adobe live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 4-5 ottobre 2021, 7:00 PDT

   Adobe Developers Live riunisce sviluppatori di Adobi e sviluppatori di esperienze con background diversi e con un unico scopo, per creare esperienze end-to-end incredibili. Questa conferenza di due giorni presenta importanti aggiornamenti per gli sviluppatori, sessioni tecniche e opportunità di rete per la community.

   I team di prodotti Adobe di Adobe Experience Cloud, Document Cloud e Creative Cloud presentano i più recenti progressi tecnologici e gli strumenti per sviluppatori che supportano la progettazione, i flussi di lavoro per la creazione di contenuti, i servizi di documentazione e la gestione dell’esperienza dei clienti nei diversi settori.

   Adobe prevede 20 sessioni Experienci Manager. Diffondete la parola!

   * [Elenco completo delle sessioni](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Registrazione gratuita - Accedere alla risposta](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Community live per sviluppatori di Adobe](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Nuovi corsi ed esercitazioni su Experience Manager {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [Guida introduttiva alla documentazione XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Corso | Scopri come creare, organizzare, creare e pubblicare contenuti con la documentazione XML per Adobe Experience Manager. |
| Ottobre 2021 | [Gestione dei flussi di lavoro creativi  [!DNL Workfront] tramite e Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Corso | Scopri come Adobe [!DNL Workfront] e Experience Manager. |
| Ottobre 2021 | [Guida introduttiva ad AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Corso | Scopri come AEM Assets Essentials può semplificare la gestione delle risorse per la tua organizzazione. |
| Ottobre 2021 | [[!UICONTROL Strumento Content Transfer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Video | Scopri come [!UICONTROL Strumento Content Transfer (Trasferimento contenuti)] consente di migrare i contenuti a AEM as a Cloud Service da AEM 6.3+. |
| Ottobre 2021 | [[!UICONTROL Servizio di importazione in blocco]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Video | Scopri come AEM come Cloud Services [!UICONTROL Servizio di importazione in blocco] possono essere utilizzati per importare risorse da origini non AEM. |
| Ottobre 2021 | [Comunicazioni (servizio di uscita)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Video | Scopri in che modo AEM Forms as a Cloud Service supporta il caso di utilizzo delle comunicazioni. |
| Ottobre 2021 | [Registrazione digitale](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Video | Scopri in che modo AEM Forms as a Cloud Service supporta il caso di utilizzo dell’iscrizione digitale. |
| Ottobre 2021 | [Utilizzo degli strumenti  [!UICONTROL Cloud Acceleration ] Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Video | Una descrizione dettagliata dell&#39;utilizzo degli strumenti [!UICONTROL Cloud Acceleration Manager]. |
| Ottobre 2021 | [Navigazione in  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Video | Esplora l&#39;esperienza di navigazione di [!UICONTROL Cloud Acceleration Manager], ad Experience Manager as a Cloud Service. |
| Ottobre 2021 | [Strumento Asset Workflow Migration (Migrazione flussi di lavoro per risorse) ](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Video | Scopri in che modo lo strumento [!UICONTROL Asset Workflow Migration] consente di migrare i flussi di lavoro AEM Assets esistenti a AEM as a Cloud Service. |
| Ottobre 2021 | [[!UICONTROL Convertitore indice]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Video | Scopri in che modo il [!UICONTROL Convertitore indice] converte automaticamente le definizioni di indice AEM esistenti in AEM compatibile. |
| Ottobre 2021 | [[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Video | Scopri in che modo [!UICONTROL Dispatcher Converter] aggiorna automaticamente le configurazioni di Dispatcher AEM esistenti affinché siano AEM compatibili. |
| Ottobre 2021 | [[!UICONTROL Modernizzatore dell&#39;archivio del codice]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Video | Scopri in che modo [!UICONTROL Core Repository Modernizer] aggiorna automaticamente i progetti AEM Maven esistenti affinché siano AEM compatibili. |
| Ottobre 2021 | [[!UICONTROL Strumenti di refactoring del codice]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Video | Scopri in che modo gli AEM [!UICONTROL Strumenti di refactoring del codice] consentono di automatizzare la conversione dei progetti AEM esistenti per essere AEM compatibili con l&#39;as a Cloud Service. |
| Ottobre 2021 | [[!UICONTROL Strumento Content Transfer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Video | Scopri come lo [!UICONTROL strumento Content Transfer (Trasferimento contenuti)] consente di spostare in modo efficiente il contenuto da AEM 6.5 a AEM as a Cloud Service. |
| Ottobre 2021 | [Le fasi di implementazione di  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Video | Rivedi e comprendi le principali fasi di implementazione o passa a AEM as a Cloud Service utilizzando [!UICONTROL Cloud Acceleration Manager]. |
| Ottobre 2021 | [Preparazione e  [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Video | Scopri in che modo [!UICONTROL Best Practice Analyzer] può aiutarti a prepararti a passare da AEM on-premise o Adobe Managed Services ad Experience Manager as a Cloud Service. |
| Ottobre 2021 | [Introduzione a Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Video | Scopri in che modo [!UICONTROL Cloud Acceleration Manager] può aiutarti a passare rapidamente e facilmente all&#39;Experience Manager as a Cloud Service. |
| Ottobre 2021 | [AEM Forms as a Cloud Service - Passaggio a AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Video | Scopri i casi d’uso e le funzioni supportate da AEM Forms as a Cloud Service. |
| Ottobre 2021 | [Risoluzione dei problemi AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Video | Scopri come risolvere i problemi e eseguire il debug dell’SDK AEM, AEM as a Cloud Service e, il processo di compilazione e distribuzione. |
| Ottobre 2021 | [AEM  [!UICONTROL Assets Microservices]  - Passaggio a AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Video | Scopri in che modo i microservizi di asset compute di AEM Assets as a Cloud Service ti consentono di generare automaticamente ed efficacemente rendering per le risorse, sostituendo questo ruolo del flusso di lavoro AEM tradizionale. |
| Ottobre 2021 | [Ricerca e indicizzazione](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Video | Scopri AEM indici di ricerca as a Cloud Service, come convertire le definizioni AEM 6 per essere AEM compatibili con l’as a Cloud Service e come distribuire gli indici in AEM as a Cloud Service. |
| Ottobre 2021 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Video | Scopri AEM [!UICONTROL Dispatcher] per AEM as a Cloud Service, concentrandoti sulle modifiche di rilievo apportate da [!UICONTROL Dispatcher] per AEM 6, dallo strumento di conversione [!UICONTROL Dispatcher] e su come utilizzare l’SDK degli strumenti di Dispatcher. |
| Ottobre 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Video | Scopri Cloud Manager per AEM as a Cloud Service e le sue differenze con Cloud Manager per AEM in Adobe Manage Services (AMS). |
| Ottobre 2021 | [Onboarding in AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Video | Scopri come effettuare l’onboarding per AEM as a Cloud Service a partire dalla fase del contratto fino alla configurazione degli ambienti utilizzando [!UICONTROL Cloud Manager]. |
| Ottobre 2021 | [Modernizzazione archivio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Video | Scopri la modernizzazione dell’archivio, il contenuto mutabile e immutabile, la struttura del pacchetto e lo strumento CLI del modernizzatore dell’archivio. |
| Ottobre 2021 | [[!UICONTROL Strumenti di modernizzazione AEM]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Video | Scopri come AEM [!UICONTROL Strumenti di modernizzazione] vengono utilizzati per aggiornare un progetto AEM esistente e il contenuto per essere AEM compatibile con l’as a Cloud Service. |
| Ottobre 2021 | [Strumenti di modernizzazione AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Video | Scopri come pensare diversamente alle implementazioni as a Cloud Service AEM. |
| Ottobre 2021 | [Best practice Analyzer e Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Video | Scopri come Best Practice Analyzer (BPA) e Cloud Acceleration Manager (CAM) forniscono una guida personalizzata per la migrazione a AEM as a Cloud Service. |
| Ottobre 2021 | [Manutenzione della cronologia delle versioni](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Video | Scopri in che modo Adobe Workfront e Experience Manager [!UICONTROL Assets Essentials] consentono di gestire le versioni dei documenti [!DNL Workfront] e delle risorse Assets Essentials. |
| Ottobre 2021 | [Invio di documenti e collegamento di risorse](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Video | Scopri come inviare documenti Workfront ad Assets Essentials e collegare risorse Assets Essentials a Workfront. |
| Ottobre 2021 | [Configurazione dell’integrazione](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Video | Scopri come configurare l’integrazione di Adobe Workfront e Assets Essentials. |
| Ottobre 2021 | [Cos’è una firma digitale](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Scopri le firme digitali basate su certificati, conformi alle più severe normative vigenti in tutto il mondo e che offrono il massimo livello di garanzia per l’identità del firmatario. |
| Ottobre 2021 | [Segment Builder in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Video | Vai a fondo nei tuoi dati con la segmentazione in Adobe Analytics. Questo video illustra il [!UICONTROL Generatore di segmenti] e offre una panoramica di base. |
| Ottobre 2021 | [Metadati mappatura](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Video | Scopri come configurare la mappatura dei metadati tra campi Workfront e proprietà Assets Essentials e come configurare Assets Essentials per visualizzare i valori mappati. |

{style=&quot;table-layout:auto&quot;}

### Informazioni sulla versione di Experience Manager {#aem-links}

Le note sulla versione e altri collegamenti alle informazioni sulla versione di Experience Manager, sono disponibili qui:

* [[!DNL Experience Manager as a Cloud Service]  Note sulla versione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=it)
* [[!DNL Experience Manager as a Cloud Service] Informazioni sulla versione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=it)
* [[!DNL Experience Manager Cloud Manager]  Note sulla versione](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=it)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=it)
* [[!DNL Experience Manager Assets Dynamic Media]  Note sulla versione](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=it)
* [[!DNL Experience Manager Brand Portal]  Note sulla versione](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=it)
* [Note sulla versione dell’app desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=it)
* [[!DNL Experience Manager Dispatcher]  Note sulla versione](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=it)
* [Note sulla versione di Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=it)
* [Note sulla versione di Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=it)

### Altre risorse di assistenza per Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Guide](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=it)
* [Formazione e supporto per Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it)
* [Formazione e supporto per Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it#previous-updates)
* [Documentazione delle versioni precedenti di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] Guida utente](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
* [[!DNL Dynamic Media Classic] Home di Aiuto](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=it)
* [Documentazione di Experience Manager: ultimi aggiornamenti](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=it#aem-as-a-cloud-service)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Ultime versioni di Campaign

Scopri le funzionalità, i miglioramenti e le correzioni più recenti:

* [Note sulla versione di Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=it)
* [Note sulla versione di Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it)
* [Note sulla versione di Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it)

### Nuovi corsi e tutorial su [!UICONTROL Campaign] {#tutorials-campaign}

Esercitazioni e corsi più recenti per Adobe Campaign.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [Creazione di campagne avanzate con Adobe Campaign V8 per gli utenti aziendali](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Corso | Scopri come configurare ed eseguire campagne di marketing avanzate utilizzando Adobe Campaign V8. Scopri i prerequisiti, crea e configura campagne avanzate, consegne e gestione di abbonamenti. |
| Ottobre 2021 | [Utilizzare le API SOAP nei flussi di lavoro - Introduzione](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | Tutorial | Scopri come utilizzare le API Soap di Adobe Campaign e creare un flusso di lavoro di consegna avanzato basato sui dati ricevuti tramite l’API. |
| Ottobre 2021 | [Creare eventi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Tutorial | Scopri come configurare un evento, specificare l’endpoint di streaming e il payload di un evento. |
| Ottobre 2021 | [Configurare origini dati](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Tutorial | Scopri cos’è un’origine dati e come configurare origini dati Experienci Platform ed esterne. |
| Ottobre 2021 | [Caso di utilizzo: messaggi burst](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Tutorial | Comprendi i casi d’uso applicabili ai messaggi burst. Scopri come configurare un percorso per i messaggi burst e quali best practice applicare. |

{style=&quot;table-layout:auto&quot;}

### Risorse per Campaign

* Adobe Campaign v8: [Centro assistenza](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=it) - [Guide all’implementazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=it)
* Adobe Campaign Standard: [Documentazione Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Piano delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* Adobe Campaign Classic: [Documentazione Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=it) - Video introduttivi per [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=it) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=it)

## ![Icona](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Note sulla versione di [!DNL Adobe Advertising Cloud].

* [Nuove funzioni in  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nuove funzioni in  [!DNL Advertising Cloud Search]](#adcloud-search)

### Nuove funzioni in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Ultimo aggiornamento: **28 settembre 2021**

| Funzione | Descrizione |
| ------- | ----------- |
| Visualizzazioni di gestione delle campagne | Una colonna &quot;[!UICONTROL Data di creazione]&quot; è ora disponibile nei set di colonne personalizzati per le viste [!UICONTROL Campagne], [!UICONTROL Pacchetti], [!UICONTROL Posizionamenti] e [!UICONTROL Annunci]. Puoi anche filtrare le visualizzazioni [!UICONTROL Posizionamenti] e [!UICONTROL Annunci] per [!UICONTROL Data di creazione]. |
| Offerte garantite programmatiche | È ora possibile modificare l’ [!UICONTROL Offerta massima] per il posizionamento predefinito di un’offerta programmatica garantita (PG). Tuttavia, poiché le offerte PG hanno sempre un CPM fisso, solo i clienti internazionali devono modificare la [!UICONTROL Offerta massima] per tenere conto delle commissioni di cambio. |
|  | Gli utenti con l’autorizzazione &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; possono ora inviare un annuncio alla visualizzazione [!DNL FreeWheel Programmatic Creative API] dalla visualizzazione [!UICONTROL Ads] o alla visualizzazione [!UICONTROL Placements] . Puoi comunque inviare un annuncio dalla vista [!UICONTROL Offerte] . |

{style=&quot;table-layout:auto&quot;}

### Nuove funzioni in [!DNL Advertising Cloud Search] {#adcloud-search}

Ultimo aggiornamento: **28 settembre 2021**

| Funzione | Descrizione |
| ------- | ----------- |
| Approfondimenti sulla pubblicità | Ulteriori informazioni sono disponibili in modalità beta. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Consulta i seguenti collegamenti per le note sulla versione di Adobe Commerce:

* [Adobe Commerce e Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Suite cloud per Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icona](/assets/target.png) [!DNL Target] {#target}

Ultimo aggiornamento: **3 agosto 2021**

Per informazioni sempre aggiornate, consulta le [[!DNL Target] note sulla versione](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it).

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per chi si occupa di lead management e B2B e intende trasformare le esperienze dei clienti coinvolgendoli in ogni fase di complessi percorsi d’acquisto.

### Aggiornamenti principali di Marketo Engage

Per informazioni aggiornate sulla pianificazione delle versioni e sulle relative note sulla versione, consulta [!DNL Marketo Engage] [- Pianificazione delle versioni](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=it).

## ![Icona](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] è un’applicazione unificata di gestione del lavoro per condividere idee, creare contenuti, gestire processi complessi e lavorare al meglio.

Per una raccolta delle informazioni più recenti per tutti i prodotti, consulta la pagina delle versioni di [[!DNL Workfront] ](https://one.workfront.com/s/product-releases).

## ![Icona](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nuovi video, tutorial o corsi pubblicati per Adobe Document Cloud.

### Corsi e tutorial su Document Cloud {#tutorials-doc-cloud}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Ottobre 2021 | [Che cos’è una firma digitale?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Scopri come utilizzare gli ID digitali da tutto il mondo con Adobe Sign. |
| Ottobre 2021 | [Guida introduttiva di Adobe Sign per i nuovi mittenti](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Video | Se non usi ancora Adobe Sign, questa esercitazione è un ottimo punto di partenza. Questa esercitazione completa si concentra su tutte le nozioni di base per aiutarti a iniziare rapidamente a usare Adobe Sign. |
| Ottobre 2021 | [Caricare commenti di PDF in InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Video | In questa esercitazione video di 60 secondi, scopri come caricare nuovamente i commenti di PDF in InDesign dopo una revisione condivisa da Acrobat. Questo flusso di lavoro digitale consente di completare le revisioni in fase di registrazione. |
| Ottobre 2021 | [Ottieni un ID digitale da [!DNL Intesi Group]  (qualificato)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Video | Scopri come ottenere un certificato di firma digitale qualificato dal gruppo [!DNL Intesi]. Dopo la registrazione e la verifica dell’identità, [!DNL Intesi] il gruppo ti rilascia un ID digitale utilizzato per applicare una firma cloud Adobe Sign. |
| Ottobre 2021 | [Firma con [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Video | Scopri come utilizzare il tuo ID digitale Intesi Group per autenticare la tua identità e autorizzare una firma digitale remota (firma cloud) su un documento. |
| Ottobre 2021 | [Ottieni un ID digitale da [!DNL Intesi Group]  (Avanzato)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Video | Scopri come ottenere un certificato di firma digitale avanzato da Intesi Group. Dopo la registrazione e la verifica dell’identità, Intesi Group ti rilascia un ID digitale utilizzato per applicare una firma cloud Adobe Sign. |
| Ottobre 2021 | [Firma con [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Video | Scopri come utilizzare il tuo ID digitale [!DNL Digidentity] per autenticare la tua identità e autorizzare una firma digitale remota (firma cloud) su un documento. |
| Ottobre 2021 | [Ottieni un ID digitale da [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Video | Scopri come ottenere un certificato di firma digitale da [!DNL Digidentity]. Dopo la registrazione e la verifica dell’identità, [!DNL Digidentity] ti rilascia un ID digitale utilizzato per applicare una firma cloud Adobe Sign. |
| Ottobre 2021 | [Rilevare differenze tra due PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Video | Non commettere mai l&#39;errore di lavorare con la versione errata di un file. Rilevare in modo rapido e preciso le differenze tra due file PDF per migliorare i flussi di lavoro di revisione dei documenti. |
| Ottobre 2021 | [Creare contenuti PDF durante la navigazione con Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Video | Scopri come archiviare al volo le pagine web in PDF con l’estensione Adobe Acrobat per Microsoft® Edge. Questo strumento solo per Windows è prezioso per progetti di ricerca e visualizzazione offline di informazioni basate sul web. |
| Ottobre 2021 | [Conversione di messaggi e-mail e allegati in PDF in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Video | Scopri come archiviare i messaggi e-mail e gli allegati ad PDF in Outlook per i tuoi progetti. Scopri come distribuire le informazioni in modo più professionale e sicuro convertendo automaticamente gli allegati in PDF. Questo strumento è disponibile solo per Windows. |

{style=&quot;table-layout:auto&quot;}

Per Document Cloud, consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/it/support/document-cloud.html)

## ![Icona](/assets/creative-cloud-24.png) Creative Cloud for Enterprise {#creative-cloud}

Per le esercitazioni più recenti, consulta [Creative Cloud per esercitazioni aziendali](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=it) .
