Archiviazione, pubblicazione e preservazione dei dati
=====================================================

Questa sezione descrive le procedure per l'archiviazione, la
pubblicazione e la preservazione a lungo termine dei dati del progetto.

.. _archiviazione_dei_dati:

Archiviazione dei dati ⓘ
------------------------

Nel DMP sono descritte le modalità con cui sono archiviati i dati del
progetto. È sempre consigliabile archiviare i dati in repository
istituzionali. Il MiC dispone di un Centro Elaborazione Dati (CED) che
si occupa dei servizi di *housing* e *hosting* della maggior parte dei
sistemi informativi, dei siti e dei portali del MiC. In coerenza con la
Strategia per la crescita digitale del Paese e il `Piano Triennale per
l’informatica nella
PA <https://docs.italia.it/italia/piano-triennale-ict/pianotriennale-ict-doc/it/2020-2022/index.html>`__ [1]_,
AGID ha delineato una strategia *Cloud* [2]_ che prevede un percorso
di qualificazione per i soggetti pubblici e privati che intendono
fornire servizi *cloud* alla Pubblica amministrazione, affinché queste
ultime possano adottare servizi e infrastrutture di cloud computing
omogenei, che rispettino elevati standard di sicurezza, efficienza e
affidabilità. Inoltre, più recentemente, il Dipartimento per la
trasformazione digitale con l’Agenzia per la cybersicurezza nazionale ha
elaborato la Strategia Cloud Italia [3]_ contenente gli indirizzi
strategici per il percorso di migrazione verso il cloud di dati e
servizi digitali della Pubblica Amministrazione.

.. _Infrastruttura nazionale dei dati del patrimonio culturale: https://docs.italia.it/italia/icdp/icdp-pnd-docs/it/giugno-2022/strategia/tecnologie_abilitanti.html#infrastruttura-nazionale-dei-dati-del-patrimonio-culturale

Coerentemente con questi orientamenti, per garantire l’archiviazione e
la preservazione nel tempo dei dati del patrimonio culturale, il
Ministero nell’ambito dell’investimento M1C3 1.1 “*Digital Strategy
and Platforms for Cultural Heritage*” del Piano Nazionale di Ripresa e
Resilienza (PNRR) ha previsto di sviluppare un'infrastruttura (hardware
e software) per la gestione delle risorse digitali e per
l'orchestrazione di servizi e procedure, finalizzata alla raccolta,
conservazione, organizzazione e distribuzione delle risorse digitali
della cultura, in linea con le strategie europee e con le indicazioni
del piano triennale dell’informatica nella PA. L’infrastruttura software
(cfr. par. `Infrastruttura nazionale dei dati del patrimonio culturale`_ del PND) costituirà il nucleo centrale di una rete di
sistemi, anche esterni, la cui interconnessione aggiunge valore ai
diversi sistemi singolarmente considerati. Allo stesso modo
l’infrastruttura consentirà l’interconnessione trasversale dei contenuti
delle diverse collezioni digitali, superando la logica “a silos” o “ad
aggregazione di silos”, che ha caratterizzato ad oggi la
digitalizzazione delle collezioni digitali e la loro interconnessione. A
questo scopo verranno integrate nell’infrastruttura le logiche più
evolute del Web Semantico e del Web 2.0, ma anche le più promettenti
tecnologie di intelligenza artificiale applicate alla multimedialità.

Si tratterà di un’infrastruttura aperta, congruente con le Linee guida
per la digitalizzazione, adottando quanto verrà man mano stabilito nel
PND. L’infrastruttura metterà a disposizione diversi strumenti di
alimentazione del repository: le collezioni digitali che saranno
contenute nel repository saranno esposte nella Digital Library della
cultura, che ne costituirà il principale portale di accesso, ma anche di
altri sistemi di accesso che intendano utilizzarne i servizi; si
tratterà quindi di un repository aperto anche nella distribuzione delle
collezioni digitali conservate, fatti salvi i vincoli sulla proprietà
intellettuale.

È opportuno pertanto che gli Istituti, nella gestione dell’archiviazione
dei dati del progetto tengano conto di quanto sopra descritto e si
allineino alle indicazioni che verranno fornite dall’ICDP e dallo stesso
MiC.

In relazione alle specifiche informazioni sull’archiviazione dei dati
del progetto, è opportuno comunque definire:

-  la localizzazione (fisica o virtuale) dei dataset

-  le modalità di conferimento dei dataset

-  le modalità di conservazione dei dataset

-  il responsabile della gestione dei dataset.

.. _pubblicazione_dei_dati:

Pubblicazione dei dati ⓘ ⓓ
--------------------------

Se l’istituto ha - o prevede di realizzare - un’interfaccia utente di
fruizione delle informazioni (portale o sito web), in questa sezione è
importante indicare dove e come verranno pubblicati i dati e descrivere
in che modo è garantito il rispetto delle raccomandazioni AgID per la
pubblicazione dei dati [4]_; nella pubblicazione occorrerà in
particolare prestare attenzione ai seguenti aspetti:

-  assegnare ai dataset nomi auto-esplicativi e fornire descrizioni
   testuali degli stessi;

-  mettere in evidenza la licenza in uso;

-  fornire strumenti di ricerca e navigazione dei dati;

-  fornire statistiche di uso, accesso e produzione, notifiche di
   aggiornamento dei dataset e del sito web;

-  fornire strumenti per semplificare le interrogazioni.

Pertanto, in questa sezione del DMP occorre indicare:

-  quale interfaccia utente/portale/sito web verrà utilizzata per la
   pubblicazione dei dati

-  chi avrà in carico la gestione dell’interfaccia utente

-  qual è la localizzazione dell’interfaccia utente (URL o indirizzo IP)

-  se l’interfaccia utente rispetta o meno i requisiti di accessibilità
   previsti dalla legge 9 gennaio 2004, n. 4 (*Disposizioni per favorire
   l’accesso dei soggetti disabili agli strumenti informatici*)

-  se l’interfaccia utente rispetta o meno i requisiti di usabilità
   previsti nel Piano quinquennale per l’informatica nella Pubblica
   Amministrazione [5]_

-  se è prevista o meno la pubblicazione nel portale nazionale
   https://dati.cultura.gov.it (cfr. par. :ref:`open_data`), di quali dati e con
   quali modalità e temporalità (conferimenti manuali o *harvesting*).

Inoltre, poiché ogni interfaccia utente ha generalmente un suo *backend*
di gestione, nel DMP va inoltre indicato:

-  quale struttura di *backend* verrà utilizzata per la pubblicazione
   dei dati e in che modo è integrata all’interfaccia utente
   (portale/sito web)

-  chi avrà in carico la gestione del portale/sito web

-  qual è la localizzazione fisica del portale/sito web (dove si trovano
   fisicamente i server che conservano i dati)

-  qual è la localizzazione virtuale del portale/sito web (URL o
   indirizzo IP)

-  in che modo il portale/sito web si relaziona con l’infrastruttura
   software del patrimonio culturale (cfr. par. :ref:`archiviazione_dei_dati`)

-  in caso di utilizzo dell’infrastruttura software del patrimonio
   culturale gestita dall’ICDP, qual è il modello di interazione
   adottato (modello integrato/modello federato [6]_).

Preservazione dei dati ⓘ
------------------------

Nella gestione di un dataset, è fondamentale garantire la conservazione
a lungo termine del dataset stesso. Il termine “*digital
preservation*” indica le strategie e i metodi adottati per garantire
la conservazione del dato nel corso del tempo [7]_.

Sia i formati utilizzati per i dati e i metadati, sia i supporti sui
quali il dataset risiede, sono soggetti a obsolescenza, pertanto è molto
importante analizzare sin dall’inizio del progetto di digitalizzazione i
rischi in cui è possibile incorrere e le tecniche che possono essere
adottate per garantire la *digital preservation*.

In questa sezione sono descritti i possibili rischi per la preservazione
a lungo termine dei dati, e in particolare:

-  se e quando è prevista una futura obsolescenza delle tecnologie
   utilizzate (ad esempio, un determinato software non più aggiornato)

-  se e quando è prevista una futura obsolescenza dei formati utilizzati
   per rappresentare i dati (ad esempio in seguito a sostituzione con
   nuovi formati)

-  se sono previsti i rischi legati alla conservazione fisica del dato
   (ad esempio perdita di dati in seguito a incidente)

-  quali altri rischi relativi alla preservazione dei dati sono previsti

-  con quali modalità si prevede di far fronte ai rischi di cui sopra.

.. _procedure_di_backup:

Procedure di *backup* ⓘ ⓓ
-------------------------

Oltre alla gestione dei rischi legati alla conservazione, è necessario
individuare e implementare specifiche procedure di duplicazione
(*backup*) per evitare possibili perdite di dati in caso di incidente.
Tali procedure dipendono da come sono strutturati i sistemi di gestione
dei dati utilizzati (sistemi *on-premise*, sistemi in *hosting* o in
*housing*, sistemi in *cloud*).

In questo paragrafo vanno descritte le procedure di *backup* dei dati e
dei metadati e le modalità di recupero previste in caso di incidente. In
particolare, occorre indicare:

-  quali sono le procedure di *backup* dei dati e metadati

-  dove sono conservati i *backup*

-  con quale frequenza vengono eseguiti i *backup*

-  quali modalità di recupero dei dati sono previste in caso di
   incidente

-  chi ha la responsabilità di eseguire i *backup*.

Certificazione per la conservazione a lungo termine ⓘ
-----------------------------------------------------

Le eventuali attività di certificazione previste per la conservazione a
lungo termine possono essere documentate e, in particolare, possono
essere segnalate:

-  quali attività di certificazione sono previste

-  qual è l’ente responsabile della certificazione

-  che tipo di controlli sono previsti

-  chi ha la responsabilità di gestire la certificazione.

.. [1] https://www.agid.gov.it/it/agenzia/piano-triennale

.. [2] https://www.agid.gov.it/it/infrastrutture/cloud-pa

.. [3] https://innovazione.gov.it/dipartimento/focus/strategia-cloud-italia/

.. [4] https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/publdatigov.html

.. [5] https://www.agid.gov.it/it/design-servizi/usabilita

.. [6] I due principali modi per relazionarsi con l’infrastruttura software
   del patrimonio culturale sono: a) *modello integrato*: gli enti
   conferiscono i propri dati all’infrastruttura, condividendone i
   servizi: le risorse digitali sono quindi “ospitate”
   nell’infrastruttura software e vengono memorizzate e conservate sui
   sistemi dell’infrastruttura, laddove il ciclo di vita della risorsa
   digitale viene gestito tramite i servizi dell’infrastruttura; b)
   *modello federato*: gli enti che hanno sistemi informativi in grado
   di esporre in modo stabile ed efficiente le risorse digitali mediante
   API standard, possono condividere con l’infrastruttura solo alcuni
   servizi, in base alle loro specifiche necessità; le risorse digitali
   risiedono nei sistemi di origine e sono “referenziate”
   nell’infrastruttura, mentre il ciclo di vita dei dati è gestito
   dall’ente nei propri sistemi.

.. [7] Lee, K. H., Slattery, O., Lu, R., Tang, X., & McCrary, V. (2002).
   The state of the art and practice in digital preservation. *Journal
   of research of the National institute of standards and technology*,
   *107* (1), 93.
