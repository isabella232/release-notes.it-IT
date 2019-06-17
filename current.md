---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di Experience Cloud, giugno 2019
doc-type: note sulla versione
last-update: Giugno 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 7708f905e8f5baf0843e7ccb6c652a3450dd5d82

---


# Note sulla versione di Adobe Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!NOTE]
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 13 giugno 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Note sulla versione di Adobe Experience Platform

* See [[!DNL Experience Platform] release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) on Adobe.io for the latest updates to [!DNL Experience Platform].

### [!DNL Experience Platform Launch]

* Per [!DNL Experience Platform Launch](https://docs.adobelaunch.com/) informazioni aggiornate, consultate.

## Analytics {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzioni e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)

Per la documentazione sul prodotto, consulta [Home dell&#39;Aiuto di Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nuove funzioni e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| **Segmentazione** | Nuovi modelli di attribuzione per le dimensioni nella segmentazione:<ul><li>Ripetizione (predefinito): Include le istanze + valori costanti per la dimensione.</li><li>Istanza: include le istanze della dimensione.</li><li>Istanza non ripetuta: include istanze univoche (non ripetute) per la dimensione.</li></ul> [Altro](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **Segmentazione** | Nuovi operatori di segmento: **[!UICONTROL Equivale a qualsiasi di]** e **[!UICONTROL Non equivale a nessuno di]**. [Altro...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **Strumento di debug** | Una volta eseguito l&#39;accesso con il tuo Adobe ID, hai l&#39;opzione di recuperare hit post-elaborati in Experience Cloud Debugger. Gli hit post-elaborati sono chiamati al server dopo essere passati attraverso [!UICONTROL Regole di elaborazione] e regole VISTA, consentendo la convalida di [!UICONTROL Regole di elaborazione] e regole VISTA. **Nota**: se utilizzi A4T (SupplementalDataID), i dati di post-elaborazione potrebbero richiedere alcuni minuti per essere recuperati. |
| **Analysis Workspace:** | Sono stati aggiunti nuovi filtri preconfigurati sulla barra di ricerca di sinistra. Oltre a quelli disponibili ora (Dimensioni, Metriche, Approvato, ecc.), sono stati aggiunti nuovi filtri come Metriche calcolate, Attributi del cliente, eVar, Prop, Video e così via. per facilitare la ricerca dei componenti necessari. |
| **Analysis Workspace** | È stato aggiunto un avviso alla visualizzazione Abbandono che comparirà quando aggiungi un segmento come punto di contatto. Alcune combinazioni di contenitori segmento non validi genereranno diagrammi di abbandono non validi, ad esempio <ul><li>Utilizzo di un segmento basato su visitatore come punto di contatto all&#39;interno di una visualizzazione Abbandono in contesto visitatore</li><li>Utilizzo di un segmento basato su visitatore come punto di contatto all&#39;interno di una visualizzazione Abbandono in contesto di visita</li><li>Utilizzo di un segmento basato su visite come punto di contatto all&#39;interno di una visualizzazione Abbandono in contesto di visita</li></ul> <br> [Altro...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html) </br> |
| **Miglioramenti alla documentazione di Analytics** | La documentazione di Analytics è stata riorganizzata e ora include funzioni di collaborazione che consentono di migliorare il contenuto. Potete registrare problemi relativi alla documentazione e suggerire modifiche. Il set di doc è stato spostato in un [nuovo dominio](https://docs.adobe.com/content/help/en/analytics/landing/home.html). Devono essere inseriti reindirizzamenti. |
| **Nuova guida utente Note tecniche** | La [guida](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) utente Note tecniche è ora disponibile. Al momento, si consiglia di aiutare gli utenti più esperti con strumenti di analisi di terze parti, come Google Analytics, a familiarizzare con Adobe Analytics. La guida tecnica delle note tecniche si amplierà nei prossimi mesi per includere altri contenuti. |

**Correzioni in Analysis Workspace**

* È stato risolto un problema relativo alle informazioni localizzate in giapponese nelle visualizzazioni [!DNL Analysis Workspace]. (AN-180114)
* È stato risolto un problema che si verificava dopo aver copiato e incollato gli elementi dimensionali. Si è verificato un errore nelle ricerche successive dell&#39;elemento. (AN-177394)
* È stato risolto un problema relativo all&#39;opzione di modifica mancante nei pannelli dei segmenti nelle tabelle a forma libera. (AN-171703)
* È stato risolto un problema relativo alla **[!UICONTROL funzione Imposta come pagina di destinazione]** che non funzionava se condiviso con un lungo elenco di destinatari. (AN-163922)
* È stato risolto un problema per cui le stringhe venivano ritagliate verticalmente nei report in tempo reale. (AN-175980)

**Altre correzioni apportate ad Analytics**

* È stato risolto un problema che impediva agli utenti amministratore di abilitare **[!UICONTROL Eventi di successo]**. (AN-176689)
* È stato risolto un problema che si verificava durante la creazione di un avviso con la metrica **[!UICONTROL Tasso di uscita]**. (AN-177476)

### Avvisi importanti per gli amministratori di Analytics {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | Questi limiti non sono nuovi, ma sono stati aggiunti alla documentazione [](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html)qui. |
| Limiti dell&#39;operatore nuovo segmento | Aggiunto il venerdì 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori del segmento &quot;contiene qualsiasi di&quot;, &quot;non contiene nessun di&quot;, &quot;contiene tutte&quot; e &quot;non contiene tutte&quot; saranno limitati a 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati durante l&#39;impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica entrerà in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica imminente dei calcoli per i _totali nei rapporti_ | Aggiornato 2 maggio 2019 | Il **13 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ diventeranno uniformi per tutte le dimensioni e le metriche. Questo comporterà una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 13 giugno 2019, _Non specificato_ sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, dopo questa modifica, i segmenti che utilizzano la logica _esiste_ o _non esiste_ possono ottenere risultati diversi per alcune dimensioni. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da [!DNL Analysis Workspace] | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTROL Copia negli Appunti]**) da [!DNL Analysis Workspace] per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di [!DNL Analysis Workspace] | 4 aprile 2019 | Il comando Console per attivare il debugger di [!DNL Analysis Workspace] verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Collegamenti per rapporti Analytics brevi | 14 gennaio 2019 | I collegamenti per rapporti Analytics brevi che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | A partire dall’11 febbraio 2019 la funzione per rapporti di Adobe Analytics non supporta più la crittografia TLS (Transport Layer Security) 1.0. Questo cambiamento rientra nel nostro impegno continuo nel garantire i massimi standard di protezione e promuovere la sicurezza dei dati dei clienti. Se dopo il 11 febbraio 2019 non riesci a connetterti ad Adobe Analytics, devi aggiornare il browser all&#39; [ultima versione](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> A partire dal 20 febbraio 2019 la funzione di raccolta dati di Adobe Analytics non supporta più TLS 1.0. In seguito a questo cambiamento, Adobe non raccoglie più dati di Analytics dagli utenti finali che utilizzano vecchi dispositivi o browser Web che non supportano TLS 1.1 o una versione successiva. Non è previsto un impatto significativo di tale cambiamento sui dati dei clienti o sulla creazione di rapporti. (Il cambiamento non avrà effetto sui siti web che già non supportano TLS 1.0.) <br/>A partire dall’11 aprile 2019, l’API di Adobe Analytics per la generazione di rapporti non supporterà più la crittografia TLS 1.0. I clienti che accedono all’API devono assicurarsi che questo cambiamento non produca effetti negativi. <ul><li>I clienti che utilizzano l’API con Java 7 applicando le impostazioni predefinite dovranno [configurare il supporto per TLS 1.2](https://www.java.com/en/configure_crypto.html). (Vedi _Modifica della versione del protocollo TLS predefinito per gli endpoint del cliente: da TLS 1.0 a TLS 1.2_.) </li><li>I clienti API che utilizzano Java 8 non dovrebbero essere interessati perché l’impostazione predefinita è TLS 1.2.</li><li> Per i clienti che utilizzano l’API con altri framework, occorre contattare il fornitore per ottenere informazioni sul supporto per TLS 1.2.</li></ul> |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dall’1 febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

## Audience Manager {#aam}

**Correzioni, miglioramenti ed elementi obsoleti**

* Audience Manager ora conta solo i modelli algoritmici attivi rispetto al limite di utilizzo.
* È stato risolto un problema che causava la mancata visualizzazione della portata del modello algoritmico per le caratteristiche che utilizzano il modello corrispondente.
* È stato risolto un problema che causava la mancata visualizzazione del contenuto delle cartelle delle caratteristiche, per cui i nomi delle cartelle contenevano parentesi tonde e/o parentesi quadre.
* È stato risolto un problema che causava errori di caratteristiche quando si selezionava un solo tipo di caratteristica.
* È stato risolto un problema che causava la compressione della struttura ad albero delle cartelle di caratteristiche alla vista [!UICONTROL Tutte le caratteristiche] a ogni creazione o aggiornamento di una nuova sottocartella.
* È stato risolto un problema che causava l [!DNL VIEW_DATASOURCES] &#39;autorizzazione necessaria per eliminare un partner.
* È stato risolto un problema che avviava la ricerca della casella [!UICONTROL Ricerca] [!UICONTROL nella] pagina Segmenti in tutte le cartelle al posto della cartella selezionata.
* È stato risolto un problema che impediva l&#39;ordinamento della tabella [!UICONTROL Escludi caratteristiche] tramite i controlli dell&#39;intestazione durante la creazione di un nuovo modello algoritmico.
* È stato risolto un problema che causava l&#39;arresto anomalo di Audience Manager durante l&#39;esecuzione di report con date di intervallo vuote.

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, protezione e prestazioni migliori.

### Rilasci di prodotti

**Cloud Manager 2019.5.0**

La versione più recente di Experience Manager (2019.5.0) non contiene modifiche funzionali significative, ma corregge alcuni bug.

* [Note sulla versione per Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Documentazione XML per AEM**

È ora disponibile la versione 3.3 per la soluzione Documentazione XML. Consulta le seguenti note sulla versione:

***Funzioni Mappa avanzate***
* Aggiungi i riferimenti argomento tramite il trascinamento dalla vista archivio o utilizzando la barra orizzontale e il catalogo degli elementi.
* Aggiungi metadati a un riferimento argomento, come titolo della navigazione, al formato, all&#39;ambito e così via.
* L&#39;argomento viene aperto nell&#39;editor quando si seleziona un riferimento corrispondente (in modalità di anteprima se non selezionato e se è abilitata Disabilita la modifica con checkout).
* Aggiungi intestazione argomento e Gruppo argomenti.
* Aggiungi segnalibri con (Argomenti, Prefazione, elenco di libri, avvisi e così via) e Backmatter (Argomenti, Appendici, glossario e così via).
* In modalità Autore, i collegamenti interrotti vengono evidenziati, le breadcrumb vengono visualizzate e la visualizzazione Tag completa è disponibile.
* Possibilità di impostare gli attributi del livello mappa.
* Possibilità di impostare Title/BookTitle.
* Supporto per Reltables con la possibilità di aggiungere intestazione rel, colonne, trascinamento o rilascio di argomenti dalla mappa e dall&#39;archivio nella tabella rel, impostare collegamenti, ambito e altri parametri per i collegamenti, riordinare i collegamenti all&#39;interno della cella.
* Widget barra degli strumenti da inserire prima, inserire dopo e inserire l&#39;elemento.
* Evidenzia se una condizione viene applicata a un argomento.
* Possibilità di modificare più mappe alla volta (ciascuna mappa si apre come scheda sullo stesso browser).
* Nel pannello Mappa e nella vista archivio, al passaggio del mouse, mostra il titolo e il nome del file completo.

***Vista tag completi***

* Inserire nuovi tag tra due elementi.
* Copiare e incollare tag.
* Trascinamento dei tag nelle posizioni consentite e non consentite all&#39;interno di un file.
* Espandere e comprimere i tag.

***Miglioramenti della ricerca specifici DITA***

* Fornito uno strumento di serializzazione per reindicizzare il contenuto selezionato
* Gli utenti possono utilizzare `contains` e `exact match` nella ricerca. Possono inoltre effettuare ricerche utilizzando i seguenti parametri:
   * Metadati risorsa. Ad esempio `file name`, `title`, o metadati personalizzati definiti dal cliente.
   * Nome attributo DITA e il relativo valore. Ad esempio, `platform=winOS`.
   * Nome elemento DITA e il relativo valore. Ad esempio, `author = Joe Smith`.
   * Nome elemento DITA e attributo applicato. Ad esempio, la tabella con coppia di valore/nome attributo product=SpaceBase ad essa applicata.
   * Argomento DITA e metadati della mappa.
   * Tipo di informazioni DITA. Ad esempio, mappa, argomento, concetto e così via.
   * Percorso cartella principale in cui si trova la risorsa.
   * Stato del documento.
   * Stato ritirato.
   * Intervallo date modificato.
   * Tag CQ.
* È possibile creare query complesse combinando uno o più dei parametri di ricerca sopra indicati.

***Modifiche alla funzione di revisione***

* Suggerimenti per un revisore:
   * Importa tutti i commenti e incorpora le modifiche per le revisioni in corso prima dell&#39;aggiornamento alla build 3.3.
   * Assicurati che non siano aperte più schede per l&#39;editor.
   * Assicurati che la vista Tag completi non sia attivata.
   * Non passare dalla modalità Autore alla modalità Sorgente mentre la revisione è in corso.
* Possibilità di specificare la versione del contenuto da rivedere.
* Possibilità di scegliere le versioni degli argomenti selezionati in base a una linea di base, una data, un&#39;etichetta o alla versione attualmente attiva, oppure di specificare le versioni per ciascuno degli argomenti durante la creazione di una revisione.
* La possibilità di inviare lo stesso argomento/mappa per più volte e possibilità dell&#39;autore di accedere a tutte le revisioni nel pannello di revisione dell&#39;editor.
* In qualità di iniziatore, possibilità di inviare una versione successiva del contenuto per i revisori. I revisori riceveranno una notifica quando viene inviato un nuovo contenuto per la revisione.
* In qualità di autore, l&#39;utente può visualizzare i commenti di revisione per tutte le versioni del contenuto nel pannello di revisione dell&#39;editor. Gli autori potranno filtrare i commenti in base al numero di versione.
* In qualità di autore, l&#39;utente avrà la possibilità di visualizzare e importare commenti su una versione precedente del contenuto nell&#39;editor che era in corso di revisione.

***Varie***

* Crea una nuova cartella, un argomento o una mappa dalla vista Archivio.
* Visualizza nell&#39;interfaccia utente delle risorse - Aggiungi un&#39;opzione di menu sia per le cartelle che per gli argomenti: &quot;Visualizza nell&#39;interfaccia utente delle risorse&quot;. Questa opzione apre l&#39;interfaccia utente di Risorse in cui l&#39;utente può visualizzare la struttura del contenuto a sinistra e tutti i file nella vista Elenco a destra con tutti i menu delle risorse nella parte superiore.
* Un pannello Revisione è ora disponibile come sezione nel progetto DITA che tiene traccia della revisione in un livello di revisore e di un livello attività revisione.
* Possibilità di convertire IDML in DITA.
* Fornire API per applicare l&#39;etichetta data su tutte le versioni specificate in una linea di base.
* Abilita un evento dopo la completa conversione da XHTML/DOCX a DITA. È possibile utilizzare questo evento per aggiungere attributi specifici al contenuto convertito o a qualsiasi altra logica personalizzata che è necessario implementare.
* Sono stati apportati miglioramenti alla scheda Prestazioni linea di base. Per prima cosa, l&#39;utente deve eseguire uno script su tutte le linee di base esistenti.
* Sono stati apportati miglioramenti alla conversione da XHTML a DITA.
* Offload DITA-OT per ottimizzare la pubblicazione.
* Ordinamento corretto nella colonna Tipo nella vista Elenco.
* Possibilità di gestire gli stili con cascata in conversione da Word a DITA.

### Community

**[Serie webinar di Experience Manager Skills Builder](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Ti interessa conoscere come i processi DevOps possono semplificare le attività quotidiane per la gestione Adobe Experience Manager nel cloud? Cloud Manager fornisce la prima generazione di funzionalità cloud-native per Adobe Experience Manager, che offre l&#39;agilità cloud, sia che la vostra organizzazione inizi la trasformazione DevOps sia che ricerchi strategie per incrementare i processi DevOps esistenti.

[In questa serie](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)mensile, puoi imparare direttamente dal team di prodotto di Adobe su come iniziare e utilizzare le funzionalità di Experience Manager per semplificare la gestione di Adobe Experience Manager nel cloud.

Sono disponibili le seguenti informazioni:
* Come iniziare a utilizzare Cloud Manager e impostare la pipeline CI/CD
* In che modo la scalabilità automatica e la fornitura di servizi trasparenti funzionano e possono semplificare la gestione dell&#39;ambiente di Adobe Experience Manager nel cloud
* Come utilizzare l&#39;API di Experience Manager e integrare i processi esistenti DevOps

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

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti usando esperienze determinate dalle loro abitudini e preferenze.

### [!DNL Campaign Classic] 19.1 Rilascio primaverile

| Funzionalità | Descrizione |
| ------------- | ----------- |
| Pannello di controllo | Per aumentare l&#39;efficienza del lavoro come utente amministratore, gestisci le impostazioni dei tuoi server SFTP monitorando l&#39;archiviazione, gli indirizzi IP della whitelist e installando chiavi SSH per ogni istanza. Tieni presente che il Pannello di controllo è disponibile solo per i clienti ospitati su AWS a partire da oggi. [Accedi a Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> Per ulteriori informazioni, consulta la documentazione [dettagliata](https://helpx.adobe.com/campaign/kb/control-panel.html) e il video [di istruzioni](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Traccia di controllo | In qualità di amministratore, aumenta la produttività monitorando e gestendo le modifiche effettuate nell&#39;istanza Adobe Campaign Classic. La traccia audit effettua le azioni effettuate su Schema sorgente, Flusso di lavoro e Opzione. Puoi verificare rapidamente se un elemento è stato creato, modificato o eliminato.<br>Per ulteriori informazioni, consulta la documentazione [dettagliata](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) e il video [di istruzioni](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html). |
| Guardrail, Robustezza e Scalabilità | Una serie di miglioramenti è stata aggiunta a [!DNL Campaign Classic]. I miglioramenti di Scrudrail, rotondità e scalabilità sono elencati nelle [Note sulla versione di Adobe Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Messaggi SMS protetti (TLS) | SMS protetti è ora supportato tramite il connettore generico esteso SMPP. Consente una connessione crittografata al fornitore. <br>Per ulteriori informazioni, consulta la [relativa documentazione](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Aggiornamento matrice di compatibilità | Con questa nuova versione, Adobe Campaign ora supporta i seguenti sistemi di database. Fare riferimento alla [matrice di compatibilità](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>PostgreSQL 11</li></ul> |

Fai riferimento alle [note sulla versione Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) per correzioni e miglioramenti.

### [!DNL Campaign Standard] 19.2 Rilascio primaverile

| Funzionalità | Descrizione |
| ------------- | ----------- |
| Pannello di controllo | Per migliorare l&#39;efficienza del lavoro in qualità di utente amministratore, puoi monitorare facilmente la capacità e gestire le impostazioni delle istanze (a partire dalla gestione dei server SFTP). <br> Per ulteriori informazioni, consulta la documentazione [dettagliata](https://helpx.adobe.com/campaign/kb/control-panel.html) e il video [di istruzioni](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Notifiche locali | I messaggi di notifica locale consentono di informare gli utenti quando nuovi dati diventano disponibili all&#39;interno delle applicazioni mobili, anche senza avere accesso a Internet o all&#39;applicazione mobile in esecuzione in primo piano. Le notifiche locali vengono attivate da un&#39;applicazione mobile in un determinato momento e a seconda di un evento.<br>Per ulteriori informazioni, consulta la [relativa documentazione](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Miglioramento del flusso di lavoro - Aggiunta di un carico utile all&#39;attività di segnale esterno | Avvia un flusso di lavoro con un carico utile quando le condizioni definite vengono soddisfatte correttamente da un altro flusso di lavoro o una chiamata REST API per l&#39;integrazione con i sistemi esterni. Ciò include anche una nuova attività di test in cui puoi eseguire test su questa funzionalità. <br>Per ulteriori informazioni, consulta la documentazione [dettagliata](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) e il video [di istruzioni](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html). |
| Miglioramento delle pagine di destinazione - Google reCAPTCHA | Sfrutta Google reCAPTCHA per impedire spam sulle pagine di destinazione senza che venga richiesto di eseguire operazioni da parte dei clienti. <br>Per ulteriori informazioni, consulta la [relativa documentazione](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Per la documentazione sul prodotto consulta:

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [ Note sulla versione](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Video in evidenza](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video in evidenza](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS 1.0 è stato disabilitato su tutti i server Adobe. Per i dispositivi Android 4.x che collegano ai servizi Adobe tramite SSL, l&#39;SDK forza ora TLS 1.1/TLS 1.2 quando si stabilisce un handshake.

## Advertising Cloud {#adcloud}

Aggiornamento: 5 giugno 2019, per la versione del 8 giugno

| Prodotto | Funzione | Descrizione |
| -----------| ---------- | ----------  |
| Cerca campagne, classificazioni etichette e vincoli | Scelte rapide da tastiera | È ora possibile utilizzare <b>Maiusc+clic</b> per selezionare più righe consecutive e <b>Ctrl+clic</b> per selezionare più righe non consecutive. |
|  | Seleziona tutto e Seleziona tutto sulla pagina | Nelle tabelle di dati, quando si seleziona la casella di controllo in alto per selezionare tutte le righe, la nuova impostazione predefinita consiste nel selezionare tutte le righe sulla pagina (a seconda che vengano visualizzate 25, 50, 100, 200 righe o Scorrimento continuo). È ancora disponibile un&#39;opzione per selezionare tutte le righe disponibili. |
| Viste predefinite, viste personalizzate e impostazioni di personalizzazione delle colonne autonome | Riordinamento delle colonne | I nuovi pulsanti Su e Giù consentono di riordinare le colonne. Puoi comunque trascinare le colonne per riordinarle, come in precedenza. |

## Target Standard/Premium 19.6.1 (25 giugno 2019) {#target}

Per informazioni sull’ultima versione fai riferimento alle Note sulla versione di Adobe Target:

[Note sulla versione di Target (pre-rilascio)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Note sulla versione di Target (corrente)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento è una piattaforma di e-commerce che offre agli esercenti online un sistema di carrello flessibile e con controllo su look, contenuto e funzionalità del proprio negozio online. Magento è disponibile in una versione open source e in una versione commerciale dotata di tutte le funzionalità.

Magento Commerce fa parte di Adobe Commerce Cloud e offre una soluzione di e-commerce efficiente per le aziende, con scalabilità illimitata e flessibilità open-source, appositamente per le esperienze B2C e B2B.

Le Note sulla versione per le edizioni Open Source e Commerce si trovano nella pagina [Informazioni](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) sulla versione.

## Primetime {#primetime}

Adobe Primetime è una piattaforma TV multischermo che consente alle media company di creare e monetizzare esperienze di visione coinvolgenti e personalizzate.

[Note sulla versione Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Home dell’Aiuto di Primetime](http://help.adobe.com/en_US/primetime/)
