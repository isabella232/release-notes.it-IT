---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: Agosto 2019
author: mfrei
translation-type: ht
source-git-commit: bf128d5ab0d16a15935f73fd8b80c7eab12b4e1f

---


# Note sulla versione di Adobe Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) per ricevere notifiche e-mail sulle prossime versioni. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 8 agosto 2019**

* [Experience Cloud ed Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**aggiornato il 23 agosto 2019**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Ad Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/it-IT/target/using/release-notes/target-release-notes.html) (collegamenti alla documentazione della soluzione)
* [!DNL Primetime](https://helpx.adobe.com/it/primetime/user-guide.html) (collegamenti alla documentazione della soluzione)

## [!DNL Experience Cloud] ed [!DNL Experience Platform] {#platform}

Note sulla versione per [!UICONTROL Experience Platform], l’interfaccia di Experience Cloud, l’amministrazione del prodotto, Experience Platform Launch, il servizio ID e bollettini sulla sicurezza.

* [Interfaccia di Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Bollettini sulla sicurezza e avvisi](https://helpx.adobe.com/it/security.html) (tutti i prodotti Adobe)

### Interfaccia di Experience Cloud {#core-services}

* È stato risolto un problema critico nell’accesso a Experience Cloud che per alcuni utenti causava l’uscita dalla sessione. (MCUI-6908)
* È stato aggiornato l’accesso a Experience Cloud per migliorarne le prestazioni e ridurne la latenza. (MCUI-6854, MCUI-6869, MCUI-6883)
* Sono state apportate modifiche cosmetiche all’interfaccia. (MCUI-6861, MCUI-6911, MCUI-6862)
* È stato risolto un problema a causa del quale la funzione [!UICONTROL Triggers] di Experience Cloud generava un’interpretazione errata della clausola _Like_ nella definizione dell’[!UICONTROL attivatore]. (MCUI-6611)

Per la documentazione del prodotto, visita [Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

Per le note sulla versione e la documentazione del prodotto, consulta [Experience Platform Launch](https://docs.adobe.com/content/help/it-IT/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics](#aa-features)  (**aggiornato il 20 agosto 2019**)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)
* [AppMeasurement](#appm) (**aggiornato il 23 agosto 2019**)

Per la documentazione del prodotto, consulta l’[Aiuto di Adobe Analytics](https://docs.adobe.com/content/help/it-IT/analytics/landing/home.html).

### Nuove funzionalità, miglioramenti e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| Supporto per le impostazioni per cookie SameSite | L’[impostazione per cookie SameSite](https://web.dev/samesite-cookies-explained) verrà aggiunta a tutti i cookie impostati da Analytics. Questa modifica consente di rispettare i nuovi requisiti di Chrome, in cui il campo cookie SameSite è ora richiesto. L’impostazione predefinita dei cookie di Analytics sarà `none`. Se hai utilizzato esclusivamente un dominio di prima parte (ad es. stats.domain.com) puoi chiedere ad Adobe Customer Care di impostarlo su `lax` per i domini di raccolta di prima parte. |
| Workspace: limite di elementi per filtro a discesa aumentato da 50 a 200 | Il limite di elementi che possono essere inseriti in un filtro a discesa è stato aumentato da 50 a 200. Questo miglioramento è utile per una serie di casi d’uso, ad esempio per poter aggiungere a un filtro tutti i paesi (195), oppure tutti gli stati e le province degli Stati Uniti (52). |
| Impression attività e Conversione attività di A4T abilitati per Attribution IQ | Abbiamo abilitato due metriche di Analytics for Target (A4T) per Attribution IQ: Impression attività e Conversione attività. In precedenza, in Analysis Workspace queste metriche risultavano superiori rispetto a quelle di Reports &amp; Analytics. Con questa modifica, gli utenti possono ora applicare un modello di attribuzione di tipo “stesso punto di contatto”, per allineare Analysis Workspace a Reports &amp; Analytics. |

#### Correzioni

* È stato risolto un problema relativo alla visualizzazione del testo nei rapporti in tempo reale, in modalità a schermo intero. (AN-183168)
* (**Aggiornato il 20 agosto 2019**) La raccolta dati ora rifiuta gli URL di reindirizzamento contenenti il simbolo “@” per impedire attacchi basati sul reindirizzamento verso siti dannosi tramite domini registrati in elenchi di whitelisting.
* (**Aggiornato il 20 agosto 2019**) La migrazione dei visitatori ora è disabilitata per tutti gli hit provenienti da browser che non supportano l’attributo per cookie SameSite e per quelli contenenti un cookie di terze parti.
* (**Aggiornato il 20 agosto 2019**) È stato risolto un problema a causa del quale ai primi hit non veniva inviato il cookie s_vi per un nuovo visitatore.

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Supporto per scostamenti fuso orario nello storico | 8 agosto 2019 | Analytics ora gestirà automaticamente gli scostamenti di fuso orario per gli hit con marca temporale. A seguito di questa modifica implementata l’8 agosto, nei sistemi in cui vengono caricati i dati per elaborazione dello storico non sarà più necessario apportare regolazioni per lo scostamento di fuso orario prima di inviare i dati. |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | Questi limiti non sono nuovi, ma sono stati aggiunti alla documentazione [qui](https://docs.adobe.com/content/help/it-IT/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “_contiene uno di_”, “_non contiene uno di_”, “_contiene tutti_” e “_non contiene tutti_” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica entrerà in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica imminente dei calcoli per i _totali nei rapporti_ | Aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ diventeranno uniformi per tutte le dimensioni e le metriche. Questo comporterà una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Unspecified_ (Non specificato) sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, i segmenti che usano gli operatori logici _exists_ (esiste) o _does not exist_ (non esiste) possono produrre risultati diversi per alcune dimensioni dopo questa modifica, in particolare le dimensioni in cui _Unspecified_ (Non specificato) ha un nome speciale, ad esempio la riga “Typed/Bookmarked” (Digitato/contrassegnato) per la dimensione “Tipi di riferimento” o “Other” (Other) per la dimensione “Tipo dispositivo”. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da [!DNL Analysis Workspace] | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL Copia negli Appunti]**) da [!DNL Analysis Workspace] per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di [!DNL Analysis Workspace] | 4 aprile 2019 | Il comando Console per attivare il debugger di [!DNL Analysis Workspace] verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Collegamenti brevi per [!DNL Analytics] rapporti | 14 gennaio 2019 | I collegamenti brevi per [!DNL Analytics] rapporti che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | A partire dall’11 febbraio 2019 la funzione per rapporti di Adobe Analytics non supporta più la crittografia TLS (Transport Layer Security) 1.0. Questo cambiamento rientra nel nostro impegno continuo nel garantire i massimi standard di protezione e promuovere la sicurezza dei dati dei clienti. Se dopo l’11 febbraio 2019 non riesci più a collegarti alla funzione per rapporti di Adobe Analytics, devi aggiornare il browser all’[ultima versione](https://docs.adobe.com/content/help/it-IT/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> A partire dal 20 febbraio 2019 la funzione di raccolta dati di Adobe Analytics non supporta più TLS 1.0. In seguito a questo cambiamento, Adobe non raccoglie più [!DNL Analytics] dati di dagli utenti finali che utilizzano vecchi dispositivi o browser web che non supportano TLS 1.1 o versione successiva. Non è previsto un impatto significativo di tale cambiamento sui dati dei clienti o sulla creazione di rapporti. (Il cambiamento non avrà effetto sui siti web che già non supportano TLS 1.0.) <br/>A partire dall’11 aprile 2019, l’API di Adobe Analytics per la generazione di rapporti non supporterà più la crittografia TLS 1.0. I clienti che accedono all’API devono assicurarsi che questo cambiamento non produca effetti negativi. <ul><li>I clienti che utilizzano l’API con Java 7 applicando le impostazioni predefinite dovranno [configurare il supporto per TLS 1.2](https://www.java.com/en/configure_crypto.html). (Vedi _Modifica della versione del protocollo TLS predefinito per gli endpoint del cliente: da TLS 1.0 a TLS 1.2_.) </li><li>I clienti API che utilizzano Java 8 non dovrebbero essere interessati perché l’impostazione predefinita è TLS 1.2.</li><li> Per i clienti che utilizzano l’API con altri framework, occorre contattare il fornitore per ottenere informazioni sul supporto per TLS 1.2.</li></ul> |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### AppMeasurement {#appm}

[!UICONTROL AppMeasurement] 2.17.0, versione rilasciata il 23 agosto 2019.

| Funzione/Correzione | Descrizione |
| -----------| ---------- |
| Supporto Baidu aggiunto | È stato aggiunto un supporto per il riordino delle stringhe di query Baidu. |
| Correzione | È stato corretto un errore che generava valori dei visitatori non aggiornati nei riscontri messi in coda in attesa di consenso. |

[!UICONTROL AppMeasurement] 2.16.0, versione rilasciata l'8 agosto 2019.

| Funzione | Descrizione |
| -----------| ---------- |
| Supporto di `sendBeacon` per i collegamenti in uscita | In [!UICONTROL AppMeasurement] è stato implementato il supporto di `sendBeacon` per i collegamenti di uscita. Questo migliorerà il tracciamento dei collegamenti in uscita e determinerà probabilmente un aumento del traffico. |
| Valori ECID/fid | I valori ECID/fid ora sono memorizzati nella cache al primo hit anche se le impostazioni Opt-In cambiano. |
| DIL 9.3 | Il modulo Gestione dell'audience è stato aggiornato a DIL 9.3 |
| Tracciamento della portata di scorrimento | È stato esposto uno switch in s.ActivityMap.trackScrollReach per attivare o disattivare il tracciamento della portata di scorrimento. |
| Servizio ID visitatori 4.4.0 | AppMeasurement è stato aggiornato per utilizzare il servizio ID visitatori 4.4.0. |

#### Correzioni

* È stato corretto un bug nella coda di AppMeasurement che si verificava prima che isReadyToTrack diventasse True.

Consulta la [cronologia di rilascio di AppMeasurement](https://docs.adobe.com/content/help/it-IT/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) per le seguenti piattaforme:

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

* La scheda Amministrazione ora è disponibile solo per gli account utente con privilegi di amministratore (AAM-48557).
* L’API Elenco utenti ora restituisce i dettagli utente completi (AAM-48662).
* Ora è possibile ridimensionare l’elenco delle cartelle di caratteristiche (AAM-48800).
* Sono state apportate varie ottimizzazioni a livello di accessibilità dell’interfaccia utente (AAM-48865, AAM-48933).
* È stato ottimizzato il caricamento delle pagine Amministrazione e Origini dati (AAM-48514).

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, sicurezza e prestazioni migliori.

### Fine del ciclo di vita del prodotto

La data di fine del ciclo di vita di Digital Publishing Suite Classic (DPSC) è il 31 agosto 2019. Per ulteriori informazioni, consulta le [Domande frequenti sul fine del ciclo di vita di Digital Publishing Suite Classic](https://helpx.adobe.com/it/digital-publishing-suite/help/eol-statement-for-dpsc.html).

### Risorse aggiuntive

* [Informazioni e supporto per AEM 6.5](https://helpx.adobe.com/it/support/experience-manager/6-5.html)
* [Informazioni e supporto per AEM 6.4](https://helpx.adobe.com/it/support/experience-manager/6-4.html)
* [Informazioni e supporto per AEM 6.3](https://helpx.adobe.com/it/support/experience-manager/6-3.html)
* [Informazioni e supporto per AEM 6.2](https://helpx.adobe.com/it/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/it/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/it/experience-manager/aem-previous-versions.html)
* [Note sulla versione di Scene7 Publishing System](https://marketing.adobe.com/resources/help/it_IT/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Adobe Campaign Standard

[Campaign Standard 19.3](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html)

| Funzione | Descrizione |
| -----------| ---------- |  
| Attività API esterna (versione beta pubblica) | Per una personalizzazione più approfondita, l’attività API esterna consente di inserire dati da sistemi esterni in un flusso di lavoro tramite una chiamata API REST. Un endpoint REST può essere un sistema di gestione clienti, Adobe I/O Runtime o un endpoint REST di Adobe Experience Cloud (ad es. Data Platform, Target, Analytics, Campaign). Questa funzionalità è attualmente disponibile come versione beta pubblica. Per ulteriori informazioni, consulta la [documentazione dettagliata](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) e guarda i [video descrittivi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Rapporto sui segmenti nei flussi di lavoro | Questa funzione consente agli addetti al marketing di suddividere le prestazioni di distribuzione in base al codice dei segmenti. Se crei un flusso di lavoro e utilizzi un’attività di segmentazione per assegnare segmenti al pubblico a cui verrà consegnata l’attività, tali segmenti possono ora essere inseriti nella stessa consegna. Questo consente di visualizzare le statistiche di apertura e clic basate su più segmenti all’interno di una singola consegna. Per ulteriori informazioni, consulta la [documentazione dettagliata](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) e guarda il [video descrittivo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Aggiornamento Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9031

### Pannello di controllo di Adobe Campaign

Le [funzionalità del nuovo pannello di controllo](https://helpx.adobe.com/it/campaign/kb/control-panel-instance-settings.html) includono la capacità di aggiungere URL a cui Campaign Classic si connette per i trasferimenti di dati e file.

Il [!UICONTROL pannello di controllo] è disponibile per i clienti Adobe Campaign Classic e Adobe Campaign Standard ospitati su AWS. Per accedere al Pannello di controllo non è richiesto alcun aggiornamento.

### Risorse aggiuntive

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/it/support/campaign/standard.html) - [Note sulla versione](https://docs.adobe.com/content/help/it-IT/campaign-standard/using/release-notes/release-notes.html) - [Video descrittivi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/it/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video descrittivi](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

Data di aggiornamento: 9 agosto 2019 per la release del 10 agosto

* (Inserzionisti con il servizio di conversion tracking di Advertising Cloud) Con l’Intelligent Tracking Prevention (ITP) 2.2 di Apple, rilasciato a maggio, i cookie di conversion tracking di Advertising Cloud vengono eliminati automaticamente dai browser Apple Safari dopo 24 ore. Advertising Cloud dispone, tuttavia, di una nuova soluzione ITP che consente di monitorare le conversioni che si verificano in Safari per oltre 24 ore dal clic originale. La soluzione utilizza l’archiviazione locale e la tecnologia iframe. Contatta l’account manager di Advertising Cloud Search per le istruzioni sull’implementazione.
* In Ricerca &gt; Avanzate (ACM), è ora possibile configurare i suffissi URL finali a livello di campagna per i modelli di annunci di Google text e per annunci sugli acquisti.
* Gli inserzionisti con account Google Ads idonei a Customer Match possono ora effettuare le seguenti operazioni:
   * Crea un audience customer match di Google Ads utilizzando gli ID utente provenienti da un segmento di audience Adobe. Per visualizzare questa funzione, l’account dell’inserzionista deve essere configurato per consentirlo.
   * Crea un audience customer match di Google Ads per un cliente caricando un file di dati del cliente. Il file può contenere informazioni di contatto (indirizzi e-mail, indirizzi postali o numeri di telefono), ID utente o ID dispositivo mobile. Per alcuni tipi di informazioni di contatto è necessario eseguire l’hashing utilizzando l’algoritmo SHA -256.
   * Aggiorna qualsiasi audience di Google Match ad eccezione di audience create da un pubblico Adobe. Puoi caricare dati per aggiungere, eliminare o sostituire tutti i dati esistenti per l’audience. Per tutte le informazioni di contatto è necessario eseguire l’hashing utilizzando l’algoritmo SHA -256.
* Le viste Audiences &gt; Target e Audiences &gt; Esclusioni includono la colonna “Tipo”.