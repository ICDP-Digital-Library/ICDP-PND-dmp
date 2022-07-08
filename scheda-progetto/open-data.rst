.. _open_data:

Open data
=========

La pubblicazione dei dati in formato aperto è una delle fasi del ciclo
di vita dell’informazione pubblica. Nella redazione del DMP, occorre
seguire le strategie per la produzione, pubblicazione e conservazione di
dati di qualità definite dal Ministero e gli obiettivi previsti per il
prossimo triennio.

La strategia del Ministero espressa nel PND, in coerenza con la
normativa nazionale e con gli orientamenti generali della pubblica
amministrazione, prevede che i dati raccolti siano aperti *by default*;
qualora un *dataset* non possa essere pubblicato in formato aperto, è
necessario motivare le ragioni ostative. In questa sezione vengono
descritti gli standard adottati per gli open data, la licenza
selezionata per la pubblicazione dei dati e il rispetto dei principi
FAIR (*Findable*, *Accessible*, *Interoperable*, *Reusable*) [1]_ che
garantiscono la reperibilità, accessibilità, interoperabilità e
riutilizzabilità dei dati. I *dataset* del Ministero saranno metadatati
e descritti secondo le indicazioni e i profili applicativi forniti da
AgID e resi disponibili in un registro dei metadati appositamente
costruito.

Il MiC prevede la pubblicazione dei dati aperti nel portale
https://dati.cultura.gov.it, che costituisce il repository dei dati
aperti del Ministero. I dati pubblicati nel portale saranno
automaticamente conferiti al portale nazionale dei dati aperti
(dati.gov.it) e da qui all'equivalente portale europeo. 

Di seguito sono indicati gli aspetti relativi agli open data che è
opportuno descrivere nel DMP, e quali sono i responsabili della
compilazione. Per una specifica di tutti i termini utilizzati si rimanda
alle *FAQ per la pubblicazione di dati aperti* in calce al presente
documento.

Livello open data ⓘ
-------------------

Le **Linee guida AgID**, che riprendono la definizione di Open Data del
W3C [2]_, prevedono cinque possibili livelli di open data, come mostrato
nella voce corrispondete delle FAQ.

Il MiC pubblicherà i dati in formato aperto almeno di livello 3\*
mirando, nel tempo, a pubblicare solo dati di livello a 4\* e 5\*
(*Linked Open Data*). Si consiglia in ogni caso di adottare il livello
più alto che è tecnicamente possibile implementare.

Nel DMP deve essere indicato se i dati saranno pubblicati in formato
aperto e a che livello.

Identificatori ⓘ ⓓ
------------------

In caso di *Open Data* di livello 4\* o 5*, è opportuno indicare nel DMP
le metodologie adottate per la costruzione di URI (*Uniform Resource
Identifier*) o IRI (*Internationalized Resource Identifier*) univoci e
persistenti, facendo riferimento alle linee guida del W3C [3]_.

Nel DMP è importante descrivere in che modo vengono assegnati questi
identificatori, come vengono costruiti e qual è il nome di dominio di
riferimento.

.. _Infrastruttura nazionale dei dati del patrimonio culturale: https://docs.italia.it/italia/icdp/icdp-pnd-docs/it/giugno-2022/strategia/tecnologie_abilitanti.html#infrastruttura-nazionale-dei-dati-del-patrimonio-culturale

Nel caso che il sistema locale adotti un modello “integrato” con
l’infrastruttura dati nazionale (cfr. par. :ref:`pubblicazione_dei_dati` del presente documento
e par. `Infrastruttura nazionale dei dati del patrimonio culturale`_ del PND) gli URI verranno definiti nell’infrastruttura
stessa; nel caso dell’adozione di un modello “federato” gli URI dovranno
essere indicati dal singolo istituto.

Standard per gli open data ⓘ ⓒ
------------------------------

Un altro aspetto importante che va descritto nel DMP riguarda gli
standard adottati per la produzione degli open data; va quindi
registrato nel DMP quale versione è stata adottata di quale standard e
per quale tipologia di dati viene utilizzato.

Ontologie e vocabolari di riferimento ⓘ ⓒ
-----------------------------------------

Allo stesso modo, è opportuno documentare nel DMP le ontologie e
vocabolari di riferimento adottati nel progetto, descrivendo le finalità
per cui verranno utilizzati. Si raccomanda di modellare i dati sulla
base dei vocabolari e delle ontologie di OntoPiA (cfr. voce specifica
nelle FAQ allegate) in larga parte allineati a standard aperti del Web e
disponibili in formati aperti standard sulla piattaforma
https://github.com/italia/. Gli uffici del MiC, per il tramite degli
Istituti centrali, sono incoraggiati ad avviare un processo di
standardizzazione sia per la rappresentazione di dati ricorrenti,
indipendenti dallo specifico dominio applicativo, come per esempio i
dati sulle persone, sulle organizzazioni pubbliche e private, sui luoghi
e gli indirizzi usando le ontologie di OntoPiA. In particolare, nel DMP
andranno elencati le specifiche ontologie e vocabolari adottati, quale
versione di ciascuno è stata utilizzata e per quale finalità. Nel caso
si scegliesse di adottare ontologie o vocabolari non standard in
alternativa a standard di dominio, è utile descrivere il perché di
questa scelta. Inoltre, se nel corso del progetto vengono prodotti delle
ontologie o dei vocabolari, è opportuno descriverli nel DMP, in modo da
facilitarne il più possibile il riuso.

Framework e protocolli per l’interoperabilità delle risorse digitali: IIIF (International Image Interoperability Framework) ⓘ ⓒ
-------------------------------------------------------------------------------------------------------------------------------

Per la gestione e la metadatazione delle immagini digitali, lo sviluppo
di framework applicativi come il IIIF ha giocato un ruolo cruciale per
l’adozione delle tecnologie proprie del Web e dei Linked Open Data per
migliorare l’interoperabilità e il riuso delle immagini. Il IIIF
consiste in un insieme di documenti che compongono il *framework*. La
definizione di questo ambiente si concentra al momento su sei documenti
di specifica per la creazione di API [4]_ destinate alla descrizione,
manipolazione e presentazione delle immagini, al controllo degli
accessi, e a meccanismi per la ricerca e diffusione delle stesse. Tutti
i documenti di specifica riusano e/o adattano data model esistenti per
rendere interoperabili i metadati descrittivi delle immagini seguendo il
paradigma degli Linked Open Data, che includono il Web Annotation Data
Model (http://w3.org/TR/annotation-model/) e Shared Canvas
(https://iiif.io/api/model/shared-canvas/1.0/). Inoltre, esistono
fornitori (https://iiif.io/get-started/vendors/) e software per la
visualizzazione (https://iiif.io/get-started/iiif-viewers/), il
salvataggio e l’esposizione (https://iiif.io/get-started/image-servers/)
delle immagini secondo gli standard del IIIF.

Il progetto dovrebbe mettere almeno a disposizione delle API conformi
alle specifiche Image API e Presentation API di IIIF. Tuttavia,
l’implementazione di API conformi anche agli altri documenti di
specifica è altamente consigliata per garantire la massima
interoperabilità e riuso delle immagini, anche tra diversi progetti e
istituti culturali.

Ci sono, inoltre, due possibili modalità di adozione del IIIF, che non
si escludono a vicenda. La prima riguarda un ente che espone il proprio
patrimonio di riproduzioni facsimilari usando IIIF. La seconda, invece,
di progetti che riutilizzano i dati esposti da altri Istituti mediante
gli standard di IIIF.

Importante è fornire indicazioni dell’identificatore persistente della
risorsa e indicare il tracciato descrittivo dei beni digitali, delle
proprietà utilizzate e valorizzate all’interno del file JsonLD,
chiamato, nel framework, “manifest”. In questo contesto può essere
esplicitata la provenienza, la proprietà dell'immagine e la relativa
licenza d'uso (vedi *Linee guida per l’acquisizione, la circolazione e
il riuso delle riproduzioni dei beni culturali in ambiente digitale*)

Licenze open data ⓘ ⓓ
---------------------

La scelta di una licenza è indispensabile per determinare come poter
riutilizzare il dataset. È quindi opportuno indicare nel DMP il nome e
la versione delle licenze aperte adottate nel progetto, specificando a
quali dati si applicano e fornendo anche un riferimento al testo
completo della licenza (cfr. voce specifica nelle FAQ allegate).

Integrazione con altri dataset ⓘ
--------------------------------

Uno dei principali vantaggi dell’adozione degli *open data* e dell’uso
degli standard del Semantic Web è la facilità di integrazione o
*linking* del dataset che viene prodotto con altri dataset già esistenti
e che seguono i medesimi standard. Ciò costituisce un valore aggiunto
per il progetto stesso, che potrà riutilizzare e integrare i dati
prodotti in precedenza, e al tempo stesso facilita l’interoperabilità e
il futuro riuso dei nuovi dati che vengono prodotti. Esistono oggi
molteplici basi di conoscenza che sono facilmente integrabili con un
nuovo dataset. Ciò può essere fatto riutilizzando direttamente gli URI
esterni, oppure importando i dati (nel rispetto delle rispettive
licenze), o ancora eseguendo un *linking* tramite il linguaggio OWL
(proprietà *owl:sameAs*). Infine, può essere anche prevista la
ripubblicazione diretta dei dati prodotti nel progetto in una base di
conoscenza esistente, andando ad arricchirla. Sarebbe opportuno ai fini
anche dell’interoperabilità se è prevista l’integrazione con dataset
esistenti, e per ognuno di questi dataset, qual è la tipologia di
integrazione (es. riuso, *linking*, pubblicazione nella base dati
esistente). In caso di *linking* o riuso diretto di URI, è utile
indicare quali sono le modalità con cui avviene il *linking* o riuso, e
se si tratta di un riuso diretto, quali sono le modalità di importazione
dei dati e in che modo è stata valutata la compatibilità delle licenze.
Infine, in caso di pubblicazione dei dati prodotti nel progetto in una
base di conoscenza esistente, è opportuno descrivere in che modo è
prevista la pubblicazione e in che modo è stata valutata la
compatibilità delle licenze.

.. [1] Wilkinson, M., Dumontier, M., Aalbersberg, I. et al. The FAIR
   Guiding Principles for scientific data management and stewardship.
   Sci Data 3, 160018 (2016). https://doi.org/10.1038/sdata.2016.18

.. [2] https://dvcs.w3.org/hg/gld/raw-file/default/glossary/index.html#x5-star-linked-open-data

.. [3] https://www.w3.org/TR/ld-bp/

.. [4] I sei documenti di specifica per la creazione di API sono: Image API
   (https://iiif.io/api/image/3.0/), Presentation API
   (https://iiif.io/api/presentation/3.0/), Content Search API
   (https://iiif.io/api/search/1.0/), Authentication API
   (https://iiif.io/api/auth/1.0/), Change Discovery API
   (https://iiif.io/api/discovery/1.0/), e Content State API
   (https://iiif.io/api/content-state/1.0/).
