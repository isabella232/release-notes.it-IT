---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: Agosto 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2229815ac75b0a7bd60571b39bd0f2780f20195e

---


# Anteprima - Note sulla versione di Adobe Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: agosto 2019**

* [Piattaforma Experience Platform e amministrazione](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (collegamenti alla guida della soluzione)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (collegamenti alla guida della soluzione)

## [!UICONTROL Piattaforma Experience Platform] e amministrazione {#platform}

Note sulla versione per [!UICONTROL Experience Platform], Experience Cloud interface, Administration Administration, Experience Platform Launch, Identity Service e bollettini sulla sicurezza.

* [Interfaccia di Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/security.html) (Tutti i prodotti Adobe)

### Interfaccia di Experience Cloud {#core-services}

* È stato risolto un problema critico in Experience Cloud login che causava il logout della sessione per alcuni utenti. (MCUI-6908)
* Accesso aggiornato a Experience Cloud per migliorare le prestazioni e ridurre la latenza. (MACT -6854, MLA -6869, MLA -6883)
* Interfaccia aggiornata in modo cosmetico. (MACT -6861, MLA -6911, MLA -6862)
* È stato risolto un problema con Experience Cloud [!UICONTROL Triggers] che generava un'interpretazione errata della clausola _Like_ (Mi) nella definizione [!UICONTROL Trigger] (Attivatore). (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzioni, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| Supporto per le impostazioni cookie samesite | L' [impostazione](https://web.dev/samesite-cookies-explained) cookie samesite verrà aggiunta a tutti i cookie dei cookie da Analytics. Questa modifica consente di essere conforme alle modifiche a Chrome che richiedono il campo cookie samesite. I cookie di Analytics verranno predefiniti `none`. Se hai utilizzato esclusivamente un dominio 1 st party (ad es. stats.domain.com) puoi impostare Adobe clientcare su `lax` per i domini di raccolta 1 st-party. |
| Area di lavoro: Aumenta limite di elementi per filtro a discesa da 50 a 200 | È stato aumentato il limite di elementi che possono essere inseriti in un filtro a discesa da 50 a 200. Questo miglioramento fornisce una serie di casi d'uso, ad esempio l'aggiunta di tutti i paesi (195) a un filtro, oppure tutti gli stati e le province degli Stati Uniti (52). |
| IQ attribuzione abilitato per le metriche A 4 T | Abbiamo abilitato due metriche Analytics for Target (A 4 T) per IQ attribuzione: Impression attività e Conversione attività. In Analysis Workspace, queste metriche sono state ingrandite rispetto a Reporting e analisi. Con questa modifica, gli utenti possono ora applicare un modello di attribuzione "lo stesso tocco", che porterà Analysis Workspace in linea con Reporting e analisi. |

#### Correzioni

* È stato risolto un problema relativo alla visualizzazione del testo nei report in tempo reale, in modalità a schermo intero. (AN-183168)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | These limits are not new, but have been added to the documentation [here](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica entrerà in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica imminente dei calcoli per i _totali nei rapporti_ | Aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ diventeranno uniformi per tutte le dimensioni e le metriche. Questo comporterà una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da [!DNL Analysis Workspace] | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL Copia negli Appunti]**) da [!DNL Analysis Workspace] per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di[!DNL Analysis Workspace] | 4 aprile 2019 | Il comando Console per attivare il debugger di [!DNL Analysis Workspace] verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | A partire dall’11 febbraio 2019 la funzione per rapporti di Adobe Analytics non supporta più la crittografia TLS (Transport Layer Security) 1.0. Questo cambiamento rientra nel nostro impegno continuo nel garantire i massimi standard di protezione e promuovere la sicurezza dei dati dei clienti. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> A partire dal 20 febbraio 2019 la funzione di raccolta dati di Adobe Analytics non supporta più TLS 1.0. In seguito a questo cambiamento, Adobe non raccoglie più [!DNL Analytics] dati di dagli utenti finali che utilizzano vecchi dispositivi o browser web che non supportano TLS 1.1 o versione successiva. Non è previsto un impatto significativo di tale cambiamento sui dati dei clienti o sulla creazione di rapporti. (Il cambiamento non avrà effetto sui siti web che già non supportano TLS 1.0.) <br/>A partire dall’11 aprile 2019, l’API di Adobe Analytics per la generazione di rapporti non supporterà più la crittografia TLS 1.0. I clienti che accedono all’API devono assicurarsi che questo cambiamento non produca effetti negativi. <ul><li>I clienti che utilizzano l’API con Java 7 applicando le impostazioni predefinite dovranno [configurare il supporto per TLS 1.2](https://www.java.com/en/configure_crypto.html). (Vedi _Modifica della versione del protocollo TLS predefinito per gli endpoint del cliente: da TLS 1.0 a TLS 1.2_.) </li><li>I clienti API che utilizzano Java 8 non dovrebbero essere interessati perché l’impostazione predefinita è TLS 1.2.</li><li> Per i clienti che utilizzano l’API con altri framework, occorre contattare il fornitore per ottenere informazioni sul supporto per TLS 1.2.</li></ul> |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi[!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### AppMeasurement {#appm}

[!UICONTROL Appmeasurement] 2.16.0: release del 8 agosto 2019.

| Funzione | Descrizione |
| -----------| ---------- |
| `sendBeacon` supporto per i collegamenti exit | È stato implementato `sendBeacon` il supporto in [!UICONTROL appmeasurement] per i collegamenti di uscita. Questo migliorerà il tracciamento dei collegamenti e determinerà probabilmente un aumento del traffico. |
| Valori ECID/fid | I valori ECID/fid ora sono memorizzati nella cache al primo hit anche se le impostazioni optin cambiano. |
| DIL 9.3 | Modulo aggiornato Gestione dell'audience su DIL 9.3 |
| Tracciamento della portata di scorrimento | Switch esposto in s. activitymap. trackscrollreach per attivare o disattivare il tracciamento della portata di scorrimento. |
| Servizio ID visitatori 4.4.0 | Appmeasurement aggiornato per utilizzare il servizio ID visitatore 4.4.0. |

#### Correzioni

* È stato corretto un bug nella coda appmeasurement che si verificava prima che isreadytotrack fosse true.

Consulta la [cronologia delle versioni di AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) per una cronologia del rilascio di AppMeasurement per le seguenti piattaforme:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight e .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**Correzioni e miglioramenti**

* La scheda Amministrazione ora viene visualizzata solo con gli account utente con privilegi di amministratore (AAM -48557).
* L'API Elenco utenti ora restituisce i dettagli utente completi (AAM -48662).
* Ora potete ridimensionare l'elenco delle cartelle di caratteristiche (AAM -48800).
* Ottimizzazioni multiple per l'accessibilità dell'interfaccia utente (AAM -48865, AAM -48933).
* Ottimizzazione delle ottimizzazioni per le pagine Amministrazione e Origini dati (AAM -48514).

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Adobe Campaign Standard

[Versione standard di Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Funzione | Descrizione |
| -----------| ---------- |  
| Attività API esterna (versione beta pubblica) | Per una personalizzazione più approfondita, l'attività API esterna consente di portare dati da sistemi esterni in un flusso di lavoro tramite una chiamata REST API. Gli endpoint REST possono essere un sistema di gestione clienti, Adobe I/O Runtime o un endpoint REST di Adobe Experience Cloud (ad es. Piattaforma dati, Target, Analytics, Campaign). Questa funzionalità è attualmente in versione beta pubblica. Per ulteriori informazioni, consulta la documentazione [dettagliata](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) e il video [di istruzioni](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Rapporto sul segmento del flusso di lavoro | Questa funzione consente agli esperti di marketing di suddividere le prestazioni di distribuzione in base al codice del segmento. Quando crei un flusso di lavoro e utilizzi un'attività di segmentazione per assegnare segmenti alla popolazione di consegna, questi segmenti possono ora entrare nella stessa consegna. Questo consente di visualizzare le statistiche di apertura/clic basate su più segmenti all'interno di una singola consegna. Per ulteriori informazioni, consulta la documentazione [dettagliata](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) e il video [di istruzioni](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Aggiornamento Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - build 9031

### Pannello di controllo Adobe Campaign

[Le nuove funzionalità del Pannello di controllo](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) includono la capacità di aggiungere URL a cui Campaign Classic si connette per i trasferimenti di dati/file.

Tieni presente che [!UICONTROL il Pannello] di controllo è disponibile per i clienti Adobe Campaign Classic e Adobe Campaign Standard ospitati su AWS. Per accedere al Pannello di controllo non sono necessari aggiornamenti.

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)