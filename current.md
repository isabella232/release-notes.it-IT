---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: Settembre 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 3b26af48364509946706cd183c1261ea8c15eab2

---


# Accesso anticipato - Settembre 2019 - Note sulla versione di Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change before to the January 12, 2019 release.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

## Data di rilascio: 12 settembre 2019

* [Interfaccia di Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla guida della soluzione)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla guida della soluzione)

## Interfaccia di Experience Cloud {#ecloud}

Note sulla versione dell'interfaccia di Experience Cloud e amministrazione dei prodotti.

* È stata risolta una vulnerabilità di sicurezza per includere intestazioni HTTP consigliate. (MCUI-9942)
* È stato risolto un problema nel passaggio tra le società di accesso Analytics. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Note sulla versione per i bollettini Experience Platform, Experience Platform Launch, Identity Service e sulla sicurezza.

* [Experience Platform Launch](#launch)
* [Mobile Services e Mobile SDK](#mobile)
* [Bollettini e bollettini sulla sicurezza](https://helpx.adobe.com/security.html) (tutti i prodotti Adobe)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services e Mobile SDK {#mobile}

Release Date: **September 26th**

**iOS (4.18.8)**

* È stato corretto un bug a causa del quale i dati SDK vengono sincronizzati con l'app watchos associata su ogni chiamata Analytics.
* È stato corretto un bug a causa del quale il payload click-through push non poteva essere utilizzato come caratteristica per i messaggi in-app.
* Aggiornato alle API framework di notifica utente invece dell'API uilocalnotification, che è stata rimossa da iOS 10 a partire da iOS.
* Aggiornato a wkwebview invece di uiwebview, che è stato dichiarato obsoleto a partire da iOS 12.

**Android 4.17.10**

* È stato aggiunto il supporto per i tag della lingua BCP 47.

**Unity**

* Plug-in aggiornato a 4.18.7 per iOS e 4.17.9 per Android

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| **IQ viaggio: Analisi cross-device** | A settembre 2019, Adobe Analytics introduce l'accesso rapido per i clienti Analytics Ultimate a una nuova potente funzionalità denominata IQ Path: Analisi cross-device. Analisi cross-device (CDA) trasforma Adobe Analytics da un dispositivo centralizzato in uno strumento di analisi incentrato sulla persona. Utilizzando la CDA potete rispondere a domande quali: <ul><li>Quante persone interagiscono con il mio marchio? Quanti tipi di dispositivi usano? Come si sovrappongono?</li><li>Con quale frequenza le persone iniziano un'attività su un dispositivo mobile e successivamente passano a un PC desktop per completare l'attività? Fai clic su click-through delle campagne che arrivano su un dispositivo per passare da un'altra posizione?</li><li>In che modo la conoscenza dell'efficacia della campagna cambia se si considerano i percorsi cross-device? Come cambia l'analisi funnel?</li><li>Quali sono i percorsi più comuni seguiti dagli utenti per passare da un dispositivo all'altro? Da dove vengono rilasciati? Dove hanno successo?</li><li>In che modo gli utenti con più dispositivi differiscono da quelli con un solo dispositivo?</li></ul><br/>Per ulteriori informazioni, visitate [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/). |
| **Architettura classificazioni aggiornata** | A partire da settembre, un aggiornamento all'architettura delle classificazioni sarà trasferito ai clienti per un periodo di più mesi. Il rilascio di settembre include la migrazione per un numero limitato di primi sviluppatori.<br/>L'aggiornamento riduce in modo significativo il tempo necessario per caricare (inclusa la logica di regola) l'importazione, l'assimilazione e la disponibilità per i rapporti. |

#### Correzioni

* È stato risolto un problema con [!UICONTROL i servizi di base Persone] e [!UICONTROL Offerte] che non erano accessibili dal menu principale Experience Cloud. (AN-184294)
* È stato risolto un problema con la barra a sinistra in [!UICONTROL Analysis Workspace] che oscillava tra una barra di scorrimento e nessuna barra di scorrimento, che causava un effetto di pulsazione. (AN-183904)
* Risolti problemi con la generazione di rapporti sugli errori. Verrà visualizzato un messaggio di errore più specifico, anziché l'indicatore di errore rosso. Più precisamente, è utile comprendere quando il problema è causato da un carico elevato, da un errore o da una richiesta di report troppo complessa. (AN -184135) [Altro…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* È stato risolto un problema che impediva il download riuscito dei report di fallout in `.pdf/.xls/.rtf` formati. (AN-183165)
* Sono stati risolti problemi di accesso tramite Experience Cloud e passaggio a diverse soluzioni Experience Cloud o al passaggio a un'altra società di accesso. (AN-183376)
* È stato corretto un problema a causa del quale il trasferimento delle risorse dei progetti pianificati non funzionava correttamente. I gruppi vengono gestiti in [!UICONTROL Admin Console] ora, pertanto non vengono copiati tra gli utenti al momento del trasferimento delle risorse. (AN-183751)
* È stato corretto un problema di eliminazione dei rapporti pianificati i cui proprietari erano stati eliminati. Da ora in poi, una notifica passa all'amministratore (che ha eseguito l'operazione di eliminazione) quando il proprietario della pianificazione non esiste più. (AN-181000)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Aggiornamento dei totali Tabella freeform di Analysis Workspace | 12 settembre 2019 | A ottobre 2019, le righe totali della tabella a forma libera inizieranno la contabilità dei [filtri per report](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) applicati. Per data, i totali sono stati contati solo per la segmentazione. Con questa modifica, verranno aggiornate le visualizzazioni dipendenti (ad esempio [!UICONTROL visualizzazioni Numero] riepilogo collegate), nonché i dati CSV e PDF esportati. |
| Modifiche imminenti relative `createDate` al campo per gli utenti di Analytics | 30 agosto 2019 | A ottobre o novembre 2019, il `createDate` campo per gli utenti di Analytics verrà aggiornato da Ora del Pacifico a un valore data/ora formattato correttamente con le informazioni sul fuso orario. (AN-183468) |
| Supporto per scostamenti fuso orario nello storico | 8 agosto 2019 | Analytics ora gestirà automaticamente gli scostamenti di fuso orario per gli hit con marca temporale. A seguito di questa modifica implementata l’8 agosto, nei sistemi in cui vengono caricati i dati per elaborazione dello storico non sarà più necessario apportare regolazioni per lo scostamento di fuso orario prima di inviare i dati. |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “_contiene uno di_”, “_non contiene uno di_”, “_contiene tutti_” e “_non contiene tutti_” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica ha avuto effetto con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Change to _Report Total_ calculations | Aggiornato il 9 luglio 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. Ciò comportava una modifica ai totali per alcuni rapporti (in genere, Prop o Attributi del cliente). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da Analysis Workspace | 10 aprile 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di Analysis Workspace | 4 aprile 2019 | Il comando Console per attivare il debugger di Analysis Workspace verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, comprese le versioni di Java compatibili durante questo periodo, visita [[! DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | TLS 1.0 non è più supportato in |

### [!DNL AppMeasurement] {#appm}

Consulta [appmeasurement per le note sulla versione di Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Nuove funzioni, miglioramenti e problemi risolti in Audience Manager.

### Nuove funzioni e miglioramenti {#aam-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| **[Destinazioni basate su persone](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNLPDestinazioni basate su utenti] è un componente aggiuntivo di Audience Manager a pagamento che consente di attivare segmenti di pubblico di prime parti tra ambienti basati su persone, come Facebook, utilizzando identificatori con hash come indirizzi e-mail. |
| **[Configurazione dei tipi di pubblico personalizzati su Twitter come destinazione basata su dispositivo self-service](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Stiamo migrando le destinazioni Twitter in un modello di configurazione self-service. Questo articolo descrive cosa devi fare affinché le integrazioni Twitter esistenti continuino a funzionare dopo la migrazione. |
| **[Esempi di fatturazione di Audience Marketplace](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | Abbiamo aggiunto un nuovo esempio, Case 3, dove abbiamo dettaglio in che modo la fatturazione funziona per segmenti con casi d'uso di attivazione e modellazione. |

**Correzioni e miglioramenti**

* È stato corretto un bug a causa del quale gli utenti non erano in grado di modificare le destinazioni di Adobe Analytics per mappare i segmenti manualmente. (AAM-49323)
* È stato corretto un bug a causa del quale i feed di Audience Marketplace duplicati venivano originati da un singolo ID di origine dati. È necessaria una mappatura 1:1 tra origini dati e [!DNL Marketplace] feed. (AAM-48504)
* Abbiamo apportato un miglioramento al flusso di lavoro per la creazione di caratteristiche e segmenti. Ora puoi filtrare l'origine dati per archiviare il segmento o il segmento, per escludere qualsiasi origine dati di Audience Manager (ad esempio, origini dati suite di rapporti da Adobe Analytics). (AAM-35899)
* Abbiamo risolto un problema nell'API Origini dati in cui l'impostazione del parametro `ExcludeReportSuites=true` query non escludeva le origini dati suite di rapporti da Adobe Analytics. (AAM-48545)
* Sono stati apportati diversi miglioramenti all'accessibilità dell'interfaccia utente di Audience Manager. (AAM -49024) e (AAM -49031)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Rilascio del prodotto

**Cloud Manager 2019.8.0**

La release 2019.8.0 di Experience Manager corregge diversi bug minori, migliora le prestazioni della build e aggiunge il supporto per pacchetti di contenuto selettivi.

* [Note sulla versione per Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenzione del prodotto

**Roadmap sulla versione di manutenzione AEM**

Consulta la roadmap sulla versione di manutenzione AEM come pubblicata [qui](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html).

### Aiuto e documentazione

**Versione prerelease di Asset Link 1.1**

* [Informazioni su Adobe Asset Link Prerelease](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Configurazione di AEM per Adobe Asset Link per prerelease](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**App desktop AEM 2.0**

AEM Desktop App 2.0 per MAC è stato rilasciato il 30 agosto 2019. AEM Desktop App 2.0 per Windows verrà rilasciato all'inizio di settembre.

Accedi alla documentazione e ai download [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html)qui.

**Tag avanzati delle risorse**

Scopri come aggiornare un certificato dopo che è scaduto [qui](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate).

**Guida utente di AEM 6.5 Screens**

È ora disponibile la nuova documentazione sulle _linee guida_ per l'implementazione della rete. Consulta la [Guida utente di ](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Servizio di conversione moduli automatizzati**

È ora disponibile la documentazione relativa al servizio di conversione moduli automatizzati di AEM Forms. Consultate [Introduzione al servizio di conversione moduli automatizzati](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Community

**Webinar di AEM Skills Builder**

* [Adobe Experience Manager Sites](https://forums.adobe.com/thread/2647742)

   | Webinar | Data |
   | -----------| ---------- |  
   | _Creazione di esperienze Web_ | 27 agosto 2019 |
   | _Cercare e navigare nel contenuto_ | 03 settembre 2019 |
   | _Gestire facilmente i contenuti in evoluzione_ | 10 settembre 2019 |
   | _Esperienze fluide_ | 17 settembre 2019 |
   | _Creare e gestire multi-lingual, Multi-National per progettare una struttura globale dei siti Web_ | 24 settembre 2019 |

* [Risorse Adobe Experience Manager](https://forums.adobe.com/thread/2647743)

   | Webinar | Data |
   | -----------| ---------- |  
   | _Struttura delle cartelle e ricerca_ | 29 agosto 2019 |
   | _Metadati_ | 05 settembre 2019 |
   | _Brand Portal_ | 12 settembre 2019 |
   | _Contenuti multimediali dinamici_ | 19 settembre 2019 |
   | _Collegamento risorsa_ | 26 settembre 2019 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | Webinar | Data |
   | -----------| ---------- |  
   | Forms 101_ | 04 settembre 2019 |
   | _Connect Forms a Database, Genera flussi di lavoro e integra Forms con le firme elettroniche_ | 11 settembre 2019 |
   | _Create Mobile-Responsive Web and Print-Ready Interactive Communications_ | 25 settembre 2019 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | Webinar | Data |
   | -----------| ---------- |  
   | _Test delle best practice - Creazione, monitoraggio, controllo e approfondimenti con Cloud Manager_ | 18 settembre 2019 |
   | _Configurazioni del dispatcher con Cloud Manager_ | 16 ottobre 2019 |
   | _Creazione di flussi di lavoro con Cloud Manager e strumenti di terze parti_ | 13 novembre 2019 |

### Risorse aggiuntive

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versioni precedenti della documentazione AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Home dell'Aiuto di Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Note sulla versione di Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### Fine del ciclo di vita del prodotto

[!DNL Digital Publishing Suite Classic] (DPSC) cesserà il ciclo di vita il 31 agosto 2019. Per ulteriori informazioni, vedi [ [! Domande frequenti su DNL Digital Publishing Suite Classic]](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html).

### Risorse aggiuntive

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Note sulla versione di Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Adobe Campaign Classic

* [Aggiornamento Campaign Classic 19.1.4](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - build 9032
* [Aggiornamento Campaign Classic 19.1.5](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) - build 9033

### Adobe Campaign [!UICONTROL Control Panel]

Abbiamo aggiunto nuove funzionalità agli utenti Admin per ricevere notifiche prima della scadenza dei certificati SSL relativi ai loro domini. Per ulteriori informazioni, consulta la [relativa documentazione](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

Inoltre, gli utenti Admin ora possono eliminare le chiavi SSH aggiunte per accedere ai server SFTP.

Il [!UICONTROL pannello di controllo] è disponibile per i clienti Adobe Campaign Classic e Adobe Campaign Standard ospitati su AWS. No upgrades are required to access [!UICONTROL Control Panel].

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
