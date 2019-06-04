---
title: Note sulla versione di Adobe Experience Cloud
description: Modello per le note sulla versione di Experience Cloud
doc-type: note sulla versione
last-update: Maggio 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 8517ef177c10b4a0e5228ccbcb9168d0e35577e0

---


# Note sulla versione di Adobe Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!NOTE]
>>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.


**Data di rilascio: Maggio 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Note sulla versione di Adobe Experience Platform

Versione 1.0, 15 maggio 2019

* Consulta [Note sulla versione della piattaforma Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) su Adobe. io per gli ultimi aggiornamenti della piattaforma Experience Platform.

### Experience Platform Launch

* Per [informazioni aggiornate, consulta la](https://docs.adobelaunch.com/) piattaforma Experience Platform.

### Servizio Experience Cloud ID

In uscita il **13 maggio 2019**

* Supporto API 4.3.0 per i visitatori
* Supporto ITP 2.1.
* È stato risolto un problema relativo alla configurazione di secureCookie.

## Analytics {#analytics}

Nuove funzioni e problemi risolti in Adobe Analytics:

* [Nuove funzioni e problemi risolti in Adobe Analytics](#aa-features)
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)

Per la documentazione sul prodotto, consulta [Home dell&#39;Aiuto di Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nuove funzioni e problemi risolti in Adobe Analytics {#aa-features}

| Funzione | Descrizione |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>Risolti problemi relativi alla gestione dello stato dei parametri del tracciatore quando sono in sospeso più hit. (AN -176931, AN -176629, DTM -12758)</li><li>Aggiornato appmeasurement per includere Visitor. js 4.3.0 (AN -180049)</li></ul> |
| [!DNL Analysis Workspace]: Nuova impostazione con visualizzazione di flusso _Includi istanze di ripetizione_ | L’impostazione del flusso _Includi istanze di ripetizione_ consente di includere o escludere istanze ripetute come per esempio Ricarica pagine. Inoltre, tutte le visualizzazioni di flusso sono ora basate solo su istanze. |
| [!DNL Ad Hoc Analysis]: Compatibilità di con Java 11 | Ad Hoc Analysis è ora compatibile con Java 11. Scoprite come eseguire [Analisi ad hoc su Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Raccolta dati:** Nuovo cookie s_ ecid | È stato aggiunto un nuovo cookie per server di prima parte, s_ecid, in cui la raccolta dati memorizza l’ECID del visitatore. |

**Correzioni in Analysis Workspace**

* È stato corretto un problema che influisce sul **[!UICONTROL tempo trascorso sulla pagina]**. [!DNL Analysis Workspace]I report su non utilizzeranno più il nome della pagina per calcolare la quantità di tempo trascorso, consentendo il conteggio di hit granulari e pertinenti. **[!UICONTROL ]****[!UICONTROL ]** (AN-140479)
* Sono stati risolti i problemi di prestazioni della visualizzazione delle linee nell&#39;ambito di un maggiore sforzo per migliorare [!DNL Analysis Workspace] le prestazioni. (AN-174878)
* È stato risolto un problema di mancanza di codifica UTF-8 nei file.csv scaricati. (AN-178393)
* Sono stati risolti alcuni problemi con le prestazioni lente [!DNL Analysis Workspace] del progetto. (AN-177710)
* Problemi di visualizzazione a linea fissa con piccoli intervalli nella granularità dell’asse y. (AN-176467)

**Altre correzioni apportate ad Analytics**

* [!DNL Audience Analytics]: È stato risolto un problema che si verificava dopo la modifica del nome di un pubblico [!DNL Audience Manager (AAM)] in - Il nome aggiornato non veniva visualizzato in Audience Analytics. (AN-176237)
* È stato risolto un problema che impediva agli utenti di salvare [! Segmenti DNL Analytics in [!DNL Audience Manager]. L’errore è stato causato dalle cartelle AAM esistenti con nomi misti in maiuscolo e minuscolo. Le cartelle verranno ora trattate senza alcuna distinzione tra maiuscole e minuscole così potranno sincronizzarsi. (AN-177934)
* È stato risolto un problema che si verificava quando gli utenti accedevano [!DNL Analytics] a tramite e [!DNL Experience Cloud] quindi la sessione scaduta. Nel riprendere la sessione, l’utente veniva reindirizzato a un URL difettoso. (AN-176812)
* È stato risolto un problema con gli offreimpostamenti del fuso orario nelle [!DNL Data Warehouse] richieste. (AN-177585)

### Avvisi importanti per gli amministratori di Analytics {#aa-notices}

| Avviso | Data di aggiunta  o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Modifiche imminenti del supporto per **[!UICONTROL classificazioni]** **[!UICONTROL numeriche e abilitate per le date]** | Aggiornato 28 maggio 2019 | La capacità di importare classificazioni numeriche e abilitate per le date verrà rimossa dalla codebase di codebase. Questa modifica entrerà in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica imminente dei calcoli per i _totali nei rapporti_ | Aggiornato 2 maggio 2019 | Il **13 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ diventeranno uniformi per tutte le dimensioni e le metriche. Questo comporterà una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 13 giugno 2019, _Non specificato_ sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Inoltre, dopo questa modifica, i segmenti che utilizzano la logica _esiste_ o _non esiste_ possono ottenere risultati diversi per alcune dimensioni. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento dei download CSV da [!DNL Analysis Workspace] | 10 aprile 2019 | A partire dal 11 aprile 2019, sono state apportate diverse modifiche ai **[!UICONTROL download]** CSV (e **[!UICONTORL alla Copia negli Appunti]**) per [!DNL Analysis Workspace] rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore delle migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica al comando [!DNL Analysis Workspace] Debugger | 4 aprile 2019 | Il comando Console per attivare [!DNL Analysis Workspace] il debugger viene sostituito in adobetools. debug. includeoberonxml il **13 giugno 2019**. Dopo tale adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Fine vita [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018, Adobe ha annunciato l&#39;intenzione di terminare il ciclo [!DNL Ad Hoc Analysis]di vita. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Collegamenti per rapporti Analytics brevi | 14 gennaio 2019 | I collegamenti per rapporti Analytics brevi che non sono stati visitati da un anno verranno eliminati a partire da giovedì 17 gennaio 2019, su base continua. |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | A partire dall’11 febbraio 2019 la funzione per rapporti di Adobe Analytics non supporta più la crittografia TLS (Transport Layer Security) 1.0. Questo cambiamento rientra nel nostro impegno continuo nel garantire i massimi standard di protezione e promuovere la sicurezza dei dati dei clienti. Se dopo il 11 febbraio 2019 non riesci a connetterti ad Adobe Analytics, devi aggiornare il browser all&#39; [ultima versione](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> A partire dal 20 febbraio 2019 la funzione di raccolta dati di Adobe Analytics non supporta più TLS 1.0. In seguito a questo cambiamento, Adobe non raccoglie più dati di Analytics dagli utenti finali che utilizzano vecchi dispositivi o browser Web che non supportano TLS 1.1 o una versione successiva. Non è previsto un impatto significativo di tale cambiamento sui dati dei clienti o sulla creazione di rapporti. (Il cambiamento non avrà effetto sui siti web che già non supportano TLS 1.0.) <br/>A partire dall’11 aprile 2019, l’API di Adobe Analytics per la generazione di rapporti non supporterà più la crittografia TLS 1.0. I clienti che accedono all’API devono assicurarsi che questo cambiamento non produca effetti negativi.  <ul><li>I clienti che utilizzano l’API con Java 7 applicando le impostazioni predefinite dovranno [configurare il supporto per TLS 1.2](https://www.java.com/en/configure_crypto.html). (Vedi _Modifica della versione del protocollo TLS predefinito per gli endpoint del cliente: da TLS 1.0 a TLS 1.2_.) </li><li>I client API che utilizzano Java 8 non devono essere influenzati, poiché l&#39;impostazione predefinita è TLS 1.2.</li><li> Per i clienti che utilizzano l’API con altri framework, occorre contattare il fornitore per ottenere informazioni sul supporto per TLS 1.2.</li></ul> |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori evar di merchandising aggiunti a post_ product_ list durante l&#39;elaborazione non comportino il troncamento dei valori dei prodotti e delle entrate. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche alla gestione che interessano [!DNL Analytics Live Stream] endpoint inattivi | 20 dicembre 2018 | A partire dal 1 febbraio 2019, è possibile disabilitare [!DNL Live Stream] gli endpoint senza connessioni attive del consumatore per 90 giorni. Puoi contattare l&#39;Assistenza clienti per ricevere informazioni sugli [!DNL Live Stream] endpoint e, se necessario, per riattivarli. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto per TLS 1.0, si consiglia [!DNL Report Builder] agli utenti di scaricare la versione 5.6.21 prima del 2019 febbraio. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

## Audience Manager {#aam}

| Funzione | Descrizione |
| -----------| ---------- |  
| [Offuscamento dell’indirizzo IP](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | La vostra azienda potrebbe voler offuscare l’indirizzo IP in molti paesi a causa delle normative globali sulla privacy. Audience Manager consente di offuscare gli indirizzi IP dei visitatori su base globale o paese per paese. |
| [Integrazioni di partner personalizzati - Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | Questa pagina elenca le integrazioni personalizzate tra Audience Manager e partner di dati. Audience Manager inserisce cookie e dati di identificazione mobile da Oracle Data Cloud per Audience Marketplace tramite file di dati in entrata. Le specifiche di integrazione personalizzate descritte in questa pagina si riferiscono solo ai file di dati in entrata che contengono ID mobili (IDFA e Android Device ID). |

**Correzioni, miglioramenti ed elementi obsoleti**

* Abbiamo aggiunto due nuove colonne ai report generali sulle destinazioni. Ora è possibile visualizzare la data di inizio e la data di fine di un segmento di mappatura verso una destinazione. (AAM-44781)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, protezione e prestazioni migliori.

### Rilasci di prodotti

**AEM 6.5**

AEM 6.5, disponibile dal 8 aprile 2019, è un upgrade della codebase di AEM 6.4. I nostri ultimi aggiornamenti di AEM 6.5 offrono accesso immediato a interessanti miglioramenti che stimolano il progresso della tua attività ancora più velocemente.

* [Scopri le novità in Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Note sulla versione per Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

L’ultimo rilascio di Cloud Manager (2019.4.0 del 18 aprile 2019) aggiunge un’interfaccia utente localizzata in francese, tedesco e giapponese. Inoltre, sono state ottimizzate le fasi di implementazione.

* [Note sulla versione per Cloud Manager 2019.4.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Manutenzione del prodotto

**AEM 6.4.4.0**

AEM 6.4 Service Pack 4 (6.4.4.0, rilasciato giovedì 4 aprile 2019), è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.4 di aprile 2018.

[Note sulla versione per il Service Pack AEM 6.4 Service Pack](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[Release di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**Connettore AEM S3**

Le istanze AEM con vecchie versioni del connettore S3 Datastore potrebbero non essere disponibili a causa di problemi di accesso all’S3 dopo la fine del supporto per la versione 2 della firma del 24 giugno 2019. Adobe consiglia ai clienti AEM di verificare la versione del connettore S3 Datastore che si sta utilizzando. Se necessario, esegui l’aggiornamento a una versione più recente.

Fai riferimento all’[impatto della firma AWS Versione 2 Deprecation per Amazon S3](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### Aiuto e documentazione

**Modernizza la base di codice per gli AEM Sites**

Scopri come sfruttare la tecnologia AEM più recente per modernizzare la codebase di codebase di AEM Sites. [Modernizzazione della vostra Adobe Experience Manager Sites Codebase esistente](https://expleague.azureedge.net/labs/L761/index.html)

**AEM Rich Text Editor - Deep Dive**

Impara le buone prassi sulle molteplici configurazioni e sull’uso del Rich Text Editor in AEM.

Fai riferimento a [AEM Rich Text Editor (RTE) Deep Dive](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### Risorse aggiuntive 

* [Informazioni e assistenza per AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Informazioni e assistenza per AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Informazioni e assistenza per AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Informazioni e assistenza per AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guida utente di Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Documentazione delle versioni precedenti di AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Note sulla versione di Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Note sulla versione di Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti usando esperienze determinate dalle loro abitudini e preferenze.

* Campaign Classic 18.10.4 - build 8983
* Campaign Classic 18.10.5 - build 8984

Fai riferimento alle [note sulla versione Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) per correzioni e miglioramenti.

Per la documentazione sul prodotto consulta:

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [ Note sulla versione](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Video in evidenza](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video in evidenza](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Funzione | Descrizione |
| -----------| ---------- |  
| Cerca Strumenti | (Inserzionisti con account Google Ads) Advertising Cloud può caricare facoltativamente su Google Ads tutti i dati di conversione che traccia per le campagne pubblicitarie Google Ads che utilizzano il servizio di tracking della conversione Advertising Cloud. I caricamenti giornalieri includono il valore di conversione definito utilizzando il modello di attribuzione a livello di inserzionista. Tutte le conversioni caricate sono precedute da “Adobe_ACS_” (come “Adobe_ACS_Subscriptions” per la conversione “Subscriptions”). <br/> **Nota:** gli upload non includono i dati di conversione caricati su Advertising Cloud dai file di feed. |
| Campagne basate su ricerche | Il menu **in Cerca** &gt; **Campagne** &gt; **Campagne** è ora gerarchico, con Campagne in Account; Gruppi di annunci in Campagne; e parole chiave (con sottomenu), Annunci, Gruppi di prodotti (solo visualizzazioni dal vivo), Posizionamenti (con sottomenu) e Destinazioni automatiche in Gruppi di annunci.<br/>Nelle visualizzazioni Live, Audience ed Estensioni si trovano allo stesso livello degli account, con i rispettivi sottomenu. |

## Target Standard/Premium 19.5.1 {#target}

Questa versione include le seguenti funzionalità, modifiche e miglioramenti:

(Nota: i codici tra parentesi sono per uso interno di Adobe.)

### Aggiornamenti delle funzioni

| Funzionalità/Miglioramento | Descrizione |
| --- | --- |
| Compositore di esperienze visive su una singola pagina (SPA VEC) | Il Compositore di esperienze visive SPA include i seguenti miglioramenti per permetterti di lavorare in modo più rapido ed efficiente:<ul><li>Ora è possibile annullare il caricamento di un sito Web nel Compositore esperienza visivo per sbloccare la modifica di un’attività. Questo miglioramento è utile, ad esempio, se desideri apportare una piccola modifica a un’attività, rivederne le impostazioni o aggiungere del codice personalizzato, senza attendere che il sito venga caricato. (TGT-33872)</li><li>Potrai eseguire molte azioni prima che la pagina si carichi nel VEC, anche nel caso in cui la pagina non riesca a caricarsi completamente (per esempio, il codice personalizzato non è più operativo). Nell’interfaccia utente di Target, le azioni che possono essere modificate solo dopo il caricamento del sito risultano disabilitate. (TGT-33851 e TGT-34149)</li></ul> |
| Attività di Personalizzazione automatizzata (AP) e Targeting automatico | È possibile selezionare un’esperienza da utilizzare come controllo durante la creazione di un’attività AP o Target automatico. Questa caratteristica consente di indirizzare l’intero traffico di controllo a un’esperienza specifica, in base alla percentuale di allocazione del traffico configurata nell’attività. È quindi possibile valutare le prestazioni delle consegne personalizzate rispetto all’esperienza di controllo. (TGT-26572) |
| Consigli | È possibile utilizzare l’opzione Consigliare gli articoli precedentemente acquistati durante la creazione della logica Articoli visualizzati di recente. (TGT-34030) |

### Miglioramenti, correzioni e modifiche

* Le icone della barra degli strumenti vengono visualizzate correttamente dopo aver annullato il caricamento di una pagina nel Compositore esperienza visivo. Se non è possibile eseguire azioni specifiche finché non è stato completato il caricamento della pagina, le icone della barra degli strumenti associate sono disattivate. (TGT-33811)
* Ora è possibile creare elenchi e esplorare le risorse più facilmente attraverso le cartelle delle offerte grazie al selezionatore, invece di navigare attraverso una gerarchia piatta di cartelle. (TGT-33725)

Consulta le [Note sulla versione di Adobe Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) per informazioni aggiornate sulle versioni dei seguenti prodotti:

* Target Standard e Target Premium
* Recommendations Classic


## Magento {#magento}

Magento è una piattaforma di e-commerce che offre agli esercenti online un sistema di carrello flessibile e con controllo su look, contenuto e funzionalità del proprio negozio online. Magento è disponibile in una versione open source e in una versione commerciale dotata di tutte le funzionalità.

Magento Commerce fa parte di Adobe Commerce Cloud e offre una soluzione di e-commerce efficiente per le aziende, con scalabilità illimitata e flessibilità open-source, appositamente per le esperienze B2C e B2B.

Le Note sulla versione per le edizioni Open Source e Commerce si trovano nella pagina [Informazioni](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) sulla versione.

## Primetime {#primetime}

Adobe Primetime è una piattaforma TV multischermo che consente alle media company di creare e monetizzare esperienze di visione coinvolgenti e personalizzate.

[Note sulla versione Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Home dell’Aiuto di Primetime](http://help.adobe.com/en_US/primetime/)