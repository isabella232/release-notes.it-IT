---
title: Note sulla versione di Adobe Experience Cloud
description: Note sulla versione di luglio 2019 di Experience Cloud
doc-type: note sulla versione
last-update: Luglio 2019
author: mfrei
translation-type: tm+mt
source-git-commit: b4a91b853cfb5d228fc2195d65b4370e607475f2

---


# Anteprima - Note sulla versione di Adobe Experience Cloud

Nuove funzioni e correzioni in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Questa pagina contiene informazioni precedenti al rilascio ed è soggetta a modifiche prima dell’effettivo rilascio pianificato.

>[!NOTE]
>
>Iscriviti ad [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) (Aggiornamento prioritario sui prodotti Adobe) per ricevere le notifiche via e-mail sulle nuove versioni. Riceverai un avviso nei tre/cinque giorni lavorativi che precedono il rilascio della versione. Le nuove informazioni pubblicate dopo il rilascio saranno contrassegnate dalla data di pubblicazione.

**Data di rilascio: 18 luglio 2019**

* [Servizi di base e amministrazione di Experience Cloud](#experiencecloud)
* [!DNL Analytics](#analytics)**(Aggiornato il 15 luglio)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Note sulla versione dell’interfaccia Experience Cloud, inclusi i servizi di base e l’amministrazione della [!UICONTROL piattaforma].

* [Servizio Experience Cloud ID](#ecid)
* [Mobile Services e Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [Bollettini e bollettini sulla sicurezza](#security)

### Servizio Experience Cloud ID {#ecid}

**Problemi risolti e aggiornamenti**

* `cookieDomain` aggiornamento di configurazione: La libreria assegna automaticamente un dominio cookie di livello principale quando `cookieDomain` non `initConfig` viene impostato. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Risolto un problema di vulnerabilità in jquery 3.2.1. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services e Mobile SDK {#mobile}

iOS e Android sono stati aggiornati come segue:

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target: È stata risolta una perdita di memoria.
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. La doppia codifica causava la segnalazione dei valori restituiti da tali API da parte di alcune recensioni sulla protezione.

**Android**

* Target: Tutte le richieste ora includono il client e sessionid nei parametri di query URL.
* Messaggistica in-app: È stato corretto un problema a causa del quale, quando un messaggio veniva attivato con un URL a clic vuoto, si verificava un arresto anomalo delle app Android.
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. La doppia codifica causava la segnalazione dei valori restituiti da tali API da parte di alcune recensioni sulla protezione.

Per la documentazione sul prodotto, consulta [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Per maggiori informazioni sugli SDK di Mobile, consulta [SDK 4.x per Android per le soluzioni Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) e [SDK 4.x per iOS per le soluzioni Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Nuove funzioni e problemi risolti in Adobe Analytics](#aa-features) **(aggiornato il 15 luglio)**
* [Avvisi importanti per gli amministratori di Analytics](#aa-notices)

### Nuove funzioni in [!DNL Analytics] {#aa-features}

Per la documentazione sul prodotto, consulta [Home dell&#39;Aiuto di Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Componente | Descrizione |
| -----------| ---------- |   
| Analysis Workspace - Miglioramenti per Analisi per coorte | Sono state aggiunte nuove impostazioni Analisi per coorte: <ul><li>Mostra solo %</li><li>Round % to nearest entire</li><li>Mostra una riga % nella parte superiore</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. In precedenza, il periodo di lookback era un massimo di 6 mesi. Questo semplifica il confronto con pagine o campagne dell&#39;anno scorso, fino a 18 mesi fa. |
| Nuovo modello Analysis Workspace | Abbiamo aggiunto un nuovo modello denominato «Magento: Marketing e commerce» ad Analysis Workspace. È progettato appositamente per i clienti di e-commerce Magento, ma qualsiasi rivenditore può utilizzarlo per ottenere informazioni univoche sulle attività di commerce. |

#### [!DNL Analysis Workspace] correzioni

* È stato risolto un problema che causava la visualizzazione capovolta dei caratteri multibyte durante la suddivisione delle dimensioni. (AN-180112)
* È stato risolto un problema relativo agli errori di visualizzazione. Ora viene visualizzata una barra di errore rossa quando si verifica un errore di visualizzazione.(AN-175542)
* È stato risolto un problema per il quale i nomi delle dimensioni venivano visualizzati come inglese in ambienti localizzati.(AN-178695)

#### [!DNL Analytics] correzioni

* È stato corretto un problema a causa del quale il grafico a linee in un report di drill-down in tempo reale risultava vuoto. (AN-181690)
* È stato risolto un problema a causa del quale, in alcuni casi, parti della cronologia dei feed di dati non venivano visualizzate nell&#39;interfaccia utente di Admin Console. (AN-176219)

### Avvisi importanti per [!DNL Analytics] amministratori {#aa-notices}

| Avviso | Data di aggiunta o aggiornamento | Descrizione |
| -----------| ---------- | ---------- |
| Limiti del generatore di regole di classificazione | Aggiunto il 5 giugno 2019 | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nuovi limiti per gli operatori di segmenti | Aggiunto il 31 maggio 2019 | A partire dal 18 luglio 2019, gli operatori di segmenti “contiene uno di”, “non contiene uno di”, “contiene tutti” e “non contiene tutti” avranno un limite di 100 parole per campo di input. Il limite verrà applicato a tutti i segmenti nuovi e modificati dopo tale data. I segmenti esistenti che superano il limite continueranno a essere supportati, ma non possono essere modificati o salvati finché il campo di input non viene ridotto. Questi limiti vengono applicati nell’ambito dell’impegno continuo per migliorare le prestazioni delle query. |
| Prossime modifiche relative al supporto delle **[!UICONTROL classificazioni Abilitate per data]** e **[!UICONTROL Numeriche 2]** | Aggiornato il 28 maggio 2019 | La possibilità di importare le classificazioni Numeriche 2 e Abilitate per data è stata rimossa dal codebase. Questa modifica entrerà in vigore con la versione di manutenzione di luglio 2019. Se nel file di importazione sono presenti colonne numeriche o abilitate per data, tali celle verranno automaticamente ignorate e gli altri dati del file verranno importati come di consueto. <br/>Le classificazioni esistenti possono ancora essere esportate attraverso il flusso di lavoro di classificazione standard e continueranno a essere disponibili nei rapporti. |
| Modifica imminente dei calcoli per i _totali nei rapporti_ | aggiornato il 9 luglio 2019 | Il **18 giugno 2019**, in Adobe Analytics i calcoli per i _totali nei rapporti_ diventeranno uniformi per tutte le dimensioni e le metriche. Questo comporterà una modifica nei totali per alcuni rapporti (in particolare per i rapporti sulle proprietà o gli attributi dei clienti). Prima di tale modifica, alcuni totali nei rapporti includevano o escludevano la voce di riga _Non specificato_ nel totale, a prescindere dalla presenza o meno di _Non specificato_ nel rapporto. <br/>A partire dal 18 giugno 2019, _Non specificato_ sarà sempre incluso nei totali dei rapporti, anche se non compare come voce di riga nel rapporto stesso. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the &quot;Typed/Bookmarked&quot; line item for Referrer Type dimension or the &quot;Other&quot; line item for the Device Type dimension. Questa modifica interessa Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e le API di reporting. |
| Aggiornamento a Download CSV da [!DNL Analysis Workspace] | 10 aprile 2019 | A partire dall’11 aprile 2019 sono state apportate diverse modifiche ai **[!UICONTROL download in formato CSV]** (e **[!UICONTORL Copia negli Appunti]**) da [!DNL Analysis Workspace] per rimuovere la formattazione dai dati esportati.  <ul><li>Il separatore di migliaia non è più incluso. Il separatore decimale continua a essere incluso e si attiene al formato definito in **[!UICONTROL Componenti &gt; Impostazioni report &gt; Separatore delle migliaia]**. Nota: i valori numerici che utilizzano una virgola come separatore decimale continuano a essere inclusi nel file CSV esportato.</li><li>Non viene visualizzato alcun simbolo di valuta.</li><li>Non viene visualizzato alcun simbolo di percentuale. Le percentuali sono in formato decimale. Ad esempio, il 75% viene rappresentato come 0,75.</li><li>Il tempo è visualizzato in secondi.</li><li>Le tabelle coorte mostrano solo i valori originali, mentre le percentuali vengono rimosse.</li><li>Se un numero non è valido, viene visualizzata una cella vuota.</li></ul> |
| Prossima modifica del comando Debugger di [!DNL Analysis Workspace] | 4 aprile 2019 | Il comando Console per attivare il debugger di [!DNL Analysis Workspace] verrà modificato in adobeTools.debug.includeOberonXml il **13 giugno 2019**. Dopo tale data, adobe.tools.debug.includeOberonXml cesserà di funzionare. |
| Numeri di versione del browser mobile | 7 febbraio 2019 | A partire dall’8 gennaio 2019, i numeri di versione del browser mobile sono riportati fino a 1 livello secondario e non più 2. A partire da tale data, le versioni presentano solo i primi due livelli (esempio: _Firefox 64.0.2_ viene ora riportato come _Firefox 64.0_). |
| Terminazione di [!DNL Ad Hoc Analysis] | 29 gennaio 2019 | Il 6 agosto 2018 Adobe ha annunciato l’intenzione di terminare [!DNL Ad Hoc Analysis]. Non appena disponibile, verrà comunicata la data di fine del ciclo di vita.<br/>Per ulteriori informazioni, tra cui quali versioni di Java saranno compatibili durante questo periodo, visita [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | 14 gennaio 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Fine del supporto per TLS 1.0 | Aggiornato il 10 gennaio 2019 | A partire dall’11 febbraio 2019 la funzione per rapporti di Adobe Analytics non supporta più la crittografia TLS (Transport Layer Security) 1.0. Questo cambiamento rientra nel nostro impegno continuo nel garantire i massimi standard di protezione e promuovere la sicurezza dei dati dei clienti. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics] A partire dal 20 febbraio 2019 la funzione di raccolta dati di Adobe non supporta più TLS 1.0. In seguito a questo cambiamento, Adobe non raccoglie più dati di Analytics dagli utenti finali che utilizzano vecchi dispositivi o browser Web che non supportano TLS 1.1 o una versione successiva. Non è previsto un impatto significativo di tale cambiamento sui dati dei clienti o sulla creazione di rapporti. (Il cambiamento non avrà effetto sui siti web che già non supportano TLS 1.0.) <br/>A partire dall’11 aprile 2019, l’API di Adobe Analytics per la generazione di rapporti non supporterà più la crittografia TLS 1.0. I clienti che accedono all’API devono assicurarsi che questo cambiamento non produca effetti negativi. <ul><li>I clienti che utilizzano l’API con Java 7 applicando le impostazioni predefinite dovranno [configurare il supporto per TLS 1.2](https://www.java.com/en/configure_crypto.html). (Vedi _Modifica della versione del protocollo TLS predefinito per gli endpoint del cliente: da TLS 1.0 a TLS 1.2_.) </li><li>I clienti API che utilizzano Java 8 non dovrebbero essere interessati perché l’impostazione predefinita è TLS 1.2.</li><li> Per i clienti che utilizzano l’API con altri framework, occorre contattare il fornitore per ottenere informazioni sul supporto per TLS 1.2.</li></ul> |
| Feed di dati: nuova dimensione per la colonna post_product_list | 9 gennaio 2019 | Il 7 febbraio 2019 Adobe ha aumentato la dimensione della colonna post_product_list da 64 KB a 16 MB. Questa modifica assicura che i valori eVar per merchandising aggiunti a post_product_list durante l’elaborazione non provochino il troncamento dei valori di prodotto e ricavo. Se in alcuni dei tuoi processi vengono inseriti i valori post_product_list, assicurati che i processi possano gestire valori fino a una lunghezza massima di 16 MB oppure che possano troncare tali valori a 16 KB per evitare errori durante l’inserimento dei dati. |
| Modifiche di gestione che interessano gli endpoint inattivi [!DNL Analytics Live Stream] | 20 dicembre 2018 | A partire dal 1° febbraio 2019, gli endpoint [!DNL Live Stream] privi di comunicazioni consumer attive per 90 giorni potranno essere disattivati. Puoi rivolgerti all’Assistenza clienti per informazioni sugli endpoint [!DNL Live Stream] e, se necessario, farli riattivare. In aggiunta, assicurati che i processi consumer mantengano una connessione persistente come previsto dalla progettazione del servizio e che vengano implementati in modo da riconnettersi quando la connessione viene disconnessa o interrotta. |
| Aggiornare Adobe [!DNL Report Builder] a causa della fine del supporto per TLS 1.0 | 7 settembre 2018 | A causa della fine del supporto di TLS 1.0, abbiamo consigliato agli utenti di [!DNL Report Builder] scaricare la versione v5.6.21 prima di febbraio 2019. Dopo tale data, le versioni precedenti di [!DNL Report Builder] non funzioneranno più. |

### AppMeasurement {#appm}

Rilascio 15 luglio 2019

**JavaScript 2.15.0**

* Aggiunto DIL 7.2 ad appmeasurement rememt. (AN-175142)
* È stato risolto un problema che si verificava quando il servizio Experience Cloud ID Service optin veniva impostato su true e l&#39;identificatore MID non veniva generato nella chiamata s. t () senza ricaricare la pagina. (CORE-30890)

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

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

Per informazioni aggiornate, consulta le [note sulla versione di Data Workbench](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/).

## Audience Manager {#aam}

**Correzioni di problemi e miglioramenti**

* On the [!UICONTROL Segments Overview] page, the width of the segment storage folder is now flexible. Questo consente di distinguere tra segmenti con nomi più lunghi. (AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model&#39;s reach or accuracy. (AAM-47996)
* È stato risolto un problema nelle destinazioni di Analytics a causa del quale il pulsante per scaricare un file. csv di segmenti in conflitto con i controlli sull&#39;esportazione dei dati e/o i criteri di condivisione dei dati di terze parti risultava danneggiato. (AAM-48100)
* È stato risolto un problema che causava la visualizzazione casuale degli errori &quot;Accesso negato&quot; durante l&#39;accesso nell&#39;interfaccia utente di Audience Manager. (AAM-47632)

## Experience Manager {#aem}

Nuove funzioni, problemi risolti e aggiornamenti di Adobe Experience Manager (AEM). Ai clienti con distribuzioni locali, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, protezione e prestazioni migliori.

### Rilasci di prodotti

Nuove informazioni sulle funzioni per i seguenti prodotti:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Note sulla versione per Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### Documentazione XML 3.4

È ora disponibile la soluzione Documentazione XML 3.4.

***Note sulla versione***

* Supporto aggiunto per AEM 6.5.
* Modifiche apportate all&#39;editor:
   * Anteprima livello mappa.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * Tabelle: fornisce un&#39;opzione per selezionare più celle in una colonna e scorrere o unire le celle.
   * Tabelle: fornisce un modo per impostare le proprietà delle colonne della tabella nella modalità Autore dell&#39;editor Web.
   * Tabelle: fornisce un modo per regolare le proporzioni delle colonne e le dimensioni in una tabella standard.
   * Tabelle - Selezione di righe e colonne nella vista Autore.
   * Tabelle - Stili e proprietà attivati (align, valign) nell&#39;editor Web per l&#39;allineamento delle celle della tabella.
   * Correzioni di bug nella visualizzazione tag completi, che includono scenari per copiare e incollare e trascinare contenuti.
   * Mostra titoli argomento nelle schede Editor.
   * Risolti problemi di prestazioni nell&#39;editor Web.
* Trasferimento della linea di base al contenuto convertito durante la conversione.
* Predefinito di condizione di trasferimento durante il flusso di lavoro di traduzione.
* Possibilità di applicare etichette a tutti gli utenti dipendenti di una mappa dalla linea di base.
* È stato fornito un pulsante per scaricare la mappa con tutte le dipendenze come un file ZIP.
* Miglioramenti della conversione da XHTML a DITA:
   * Il nome del ditamap generato è ora identico al nome del file ZIP caricato.
   * È stato aggiunto il supporto per elementi e attributi HTML aggiuntivi.
   * Supporto per l&#39;assimilazione di file html-zip simultanei.
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Sono stati forniti registri di controllo per vedere chi è stato ripristinato a quale versione e perché.
* Rigenerazione del sito AEM:
   * Disattiva la rigenerazione per le mappe secondarie.
   * Flussi di lavoro di post generazione abilitati per i casi d&#39;uso rigenerati.
   * Disattivate l&#39;opzione Rigenerata per un argomento senza blocchi e rendete disponibile l&#39;opzione per l&#39;argomento principale in cui viene applicato l&#39;attributo chunked.
* La ricerca DITA ora funziona sulla logica AND nella ricerca di Risorse AEM.
* Risultati per non visualizzare i file temporanei memorizzati nella cartella di output della conversione.
* Scheda Linea di base:
   * Miglioramenti delle prestazioni quando si apre una linea di base.
   * Scelta degli argomenti per data per lavorare sulla marca temporale del client.
* API per l&#39;eliminazione delle etichette.

#### Manutenzione del prodotto

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1 - Cumulative Fix Pack 20 (6.2.1.20), rilasciato il 6 giugno 2019, è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.2 SP 1 dicembre 2016.

* [Note sulla versione](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5, rilasciato il 3 luglio 2019, è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.3 aprile 2017.

* [Note sulla versione](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0, rilasciato il 3 luglio 2019, è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.4 ad aprile 2018.

* [Note sulla versione](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0, rilasciato il 3 luglio 2019, è un aggiornamento importante che include correzioni di problemi fondamentali per i clienti, introdotte successivamente alla data di disponibilità generale di AEM 6.5 ad aprile 2019.

* [Note sulla versione](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [Versioni CFP di AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Aiuto e documentazione

**Aggiornamento annullamento validità cache AEM**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

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

Per le note sulla versione, vedi:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Per la documentazione sul prodotto consulta:

* Adobe Campaign Standard: [Documentazione](https://helpx.adobe.com/support/campaign/standard.html) - [ Note sulla versione](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Video in evidenza](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentazione](https://helpx.adobe.com/support/campaign/classic.html) - [Note sulla versione](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Video in evidenza](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Per informazioni sulle note sulla versione Magento Commerce e Magento Open source, vedi:

* [Note sulla versione di Magento Open Source 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce 2.3.2 - Note sulla versione](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
