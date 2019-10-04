---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: ottobre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 6efac6a7bd4bac8b9ee42a743761e2ea1fb82e82

---


# Early Access - Experience Cloud Release Notes - October 2019

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

## Data di rilascio: 10 ottobre 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Note sulla versione di Experience Platform, Experience Platform Launch, Servizio identità e bollettini sulla sicurezza.

* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| Privacy Service API: CCPA | The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br/>In anticipation of the CCPA, the Privacy Service will support requests to opt out of the selling of personal data.<br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: Privacy Service Overview`[Link to new CCPA page in Analytics]()`<br/>[](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | Enabling Privacy Reporting for Analytics adds a set of reserved variables to a report suite.  Le variabili sono progettate per assistere nella raccolta dei dati di consenso dei consumatori a livello di hit.<br/>Nuove dimensioni:<br/><ul><li>Rifiuto gestione consenso</li><li>Consenso della gestione</li><li>Variabili di gestione del consenso: `[Link to new Consent Variables page in Analytics]()`</li></ul> |
| Analisi audio e video: Supporto per la privacy | Sono state aggiunte due nuove variabili all'API di Media Collection:<br/><ul><li> analytics.optOutServerSideForwarding</li><li> analytics.optOutShare</li></ul>Si tratta di variabili facoltative che possono essere utilizzate per acquisire lo stato del consenso di un consumatore al momento dell’hit.<br/>[Documentazione API di Media CollectionAl modulo Federated Analytics sono state aggiunte le nuove variabili di dati contestuali](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>di Analytics. Queste variabili sono ora disponibili per l’utilizzo nei casi in cui si contrassegna l’opzione Rifiuta condivisione o Vendi hit per federazione.<br/>[Download del modulo federativo](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: Aggiornamento dei totali delle tabelle a forma libera | Le tabelle a forma libera ora includono due totali, un totale **[!UICONTROL di]** tabella e un **[!UICONTROL totale]** complessivo. I conti delle righe totali della tabella per i filtri [dei](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) rapporti applicati. Precedentemente, solo la segmentazione interessava i totali. [Per](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>saperne di piùInoltre, **[!UICONTROL le opzioni Mostra totali]** e **[!UICONTROL Mostra totale]** complessivo sono state aggiunte alle impostazioni **[!UICONTROL delle]** colonne.<br/>Con questa modifica ai totali a forma libera, le visualizzazioni dipendenti verranno aggiornate (ad es. visualizzazioni **[!UICONTROL Summary Number]** collegate), nonché i dati CSV e PDF esportati. |
| Analysis Workspace: Opzione per rimuovere Non specificato/Nessuno | La possibilità di rimuovere facilmente ‘Non specificato (Nessuno)’ è stata aggiunta come opzione per segnalare i filtri. |
| Analysis Workspace: Deprecazione dei componenti di granularità viola | I componenti tempo per granularità viola (Minuto, Ora, Giorno, Settimana, Mese, Trimestre, Anno) sono stati dichiarati obsoleti. I componenti del tempo viola si sono sempre comportati esattamente come quelli della dimensione arancione, pertanto questa modifica semplificherà l’esperienza. **Non è necessario eseguire alcuna azione** se in precedenza è stato utilizzato uno dei componenti tempo viola.<br/>Con questa modifica, anche la sezione **[!UICONTROL Ora]** viola è stata rinominata **[!UICONTROL Intervalli]** di date. |

#### Correzioni

* Analysis Workspace: È stato risolto un problema che causava risultati di ricerca non corretti durante la ricerca di elementi dimensione nella barra a sinistra. (AN-185065)
* Sono stati risolti dei problemi che impedivano di eliminare o annullare la pubblicazione dei segmenti condivisi in Adobe Audience Manager (AAM). The fix is to not delete the segment if AAM is unresponsive. (AN-185882, AN-185883, AN-184607)
* È stato risolto un problema di timeout che impediva di caricare segmenti in Analisi ad hoc. (AN-184654)
* È stato risolto un problema che si verificava quando la suite di rapporti utilizzata per l'ultima volta era nascosta o non disponevi più delle autorizzazioni necessarie per accedere alla suite di rapporti. In questo caso, non è più possibile accedere a Experience Cloud. (AN-181777)
* Fixed a timeout issue in segments that made it difficult to create a VRS based on a segment. (AN-179684)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Fine del supporto per TLS 1.1 | 3 ottobre 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. |
| San Jose FTP Broker Ending for London and Singapore | Luglio 2020 | For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center ftp.omniture.com.[](ftp://ftp.omniture.com/)<br/>For London use ftp3.omniture.comFor Singapore use ftp4.omniture.com[](ftp://ftp3.omniture.com/)<br/>[](ftp://ftp4.omniture.com/) |
| Aggiornamento dei totali della Tabella freeform di Analysis Workspace | 12 settembre 2019 | A ottobre 2019, le righe totali delle tabelle a forma libera inizieranno a conteggiare i filtri [dei](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) rapporti applicati. Ad oggi, i totali hanno tenuto in considerazione soltanto la segmentazione. Con questa modifica verranno aggiornate le visualizzazioni dipendenti (ad esempio le visualizzazioni [!UICONTROL Numero di riepilogo]), nonché i dati CSV e PDF esportati. |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics verrà aggiornato da Ora del Pacifico a un valore data/ora formattato correttamente con le informazioni sul fuso orario. (AN-183468) |
| Supporto per scostamenti fuso orario nello storico | 8 agosto 2019 | Analytics ora gestirà automaticamente gli scostamenti di fuso orario per gli hit con marca temporale. A seguito di questa modifica implementata l’8 agosto, nei sistemi in cui vengono caricati i dati per elaborazione dello storico non sarà più necessario apportare regolazioni per lo scostamento di fuso orario prima di inviare i dati. |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “_contiene uno di_”, “_non contiene uno di_”, “_contiene tutti_” e “_non contiene tutti_” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica è entrata in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica dei calcoli per i _totali nei rapporti_ | Aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ sono diventati uniformi per tutte le dimensioni e le metriche. Questo ha comportato una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da Analysis Workspace | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL Copia negli Appunti]**) da Analysis Workspace, per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di Analysis Workspace | 4 aprile 2019 | Il comando Console per attivare il debugger di Analysis Workspace verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### [!DNL AppMeasurement] {#appm}

See AppMeasurement for Javascript release notes.[](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)

## Audience Manager {#aam}

Nuove funzioni, miglioramenti e correzioni in Audience Manager.

**Correzioni e miglioramenti**

* All customer accounts created after July 1st, 2019, will automatically be assigned a  license, providing them access to their reports. [!DNL Tableau] If your account was created before July 1st, 2019, and you still do not have access to your  reports, please contact Customer Care.[!DNL Tableau]
* We've removed incorrectly generated activity trait memberships for visitor profiles that did not have an ID synchronization with the trait data source (AAM-45371).
* We've removed invalid global device IDs from global data sources. See Global Data Sources to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)
* Fixed a bug causing the Segments page to stop responding when you attempt to delete a protected segment (AAM-49881).
* When editing destinations for Twitter Tailored Audiences, the Account selector is now active only if the destination does not have a  account assigned (AAM-49975).[!DNL Twitter Ads]
* È stato corretto un bug che impediva agli utenti di disattivare i feed di dati di [!UICONTROL Audience Marketplace] quando le iscrizioni venivano disattivate (AAM-49640).
* Sono stati apportati diversi miglioramenti all'accessibilità dell'interfaccia utente di Audience Manager.

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Manutenzione del prodotto

* **AEM 6.3.3.6**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 released September 25, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.3, April 2017.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6.0 (6.4.6.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.4, April 2018.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
AEM 6.5, Service Pack 2.0 (6.5.2.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.5, April 2019.
   * [Note sulla versione](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Aiuto e documentazione

* **Scene7: Reprocess Assets workflow**

   Ora potete rielaborare le risorse in una cartella che dispone già di un profilo di elaborazione già modificato.
Consultate [Rielaborazione delle risorse in una cartella dopo aver modificato il profilo](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)di elaborazione.

* **Integrazione dei visualizzatori per contenuti multimediali dinamici con Adobe Analytics e Adobe Launch**

   L’estensione per Adobe Launch dei visualizzatori per contenuti multimediali dinamici e il rilascio dei visualizzatori per contenuti multimediali dinamici 5.13 consentono ai clienti di Dynamic Media, Adobe Analytics e Adobe Launch di utilizzare eventi e dati specifici per i visualizzatori per contenuti multimediali dinamici nella configurazione Adobe Launch.
Consultate [Integrazione dei visualizzatori per contenuti multimediali dinamici con Adobe Analytics e Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **AEM desktop app**

   L’app desktop AEM 2.0 è ora disponibile per gli utenti creativi, esperti di marketing e addetti al marketing che desiderano lavorare con Risorse AEM.
Consultate le note sulla versione dell'app desktop [AEM.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Componenti di base**
   * Scopri le funzioni di localizzazione dei componenti core e come funzionano con i modelli AEM.
      [Vedere l'esempio](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Core Components 2.6.0 introduce un componente frammento esperienza. Il componente è ora disponibile insieme alla documentazione [di](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) authoring e ai dettagli per [gli sviluppatori e al download del progetto, disponibile su GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * Nuova documentazione per la funzionalità di ricerca visiva/similare.
Consultate [Trovare immagini](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)simili.
   * La funzionalità Risorse collegate ora utilizza i documenti disponibili per la distribuzione remota di DAM, oltre ai formati di file immagine.
Consultate [Utilizzo di risorse collegate per condividere risorse DAM in AEM Sites](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html).
   * Nuovo contenuto per la ricerca e l’individuazione delle risorse. Le risorse di _ricerca in AEM_ sono argomenti di riferimento per l’utilizzo, la configurazione, la risoluzione dei problemi, le limitazioni e i suggerimenti.
Consultate [Cercare risorse in AEM](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

### Risorse aggiuntive

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versioni precedenti della documentazione AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Guida di Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

<!-- ### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL Control Panel]

Text

### Additional resources -->

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
