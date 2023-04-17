Qualità dei dati e documentazione
=================================

Questa sezione descrive gli approcci per assicurare la qualità dei dati
(convenzioni di denominazione dei file, revisione, vocabolari
controllati, regole di validazione/verifica dei dati). Il controllo
qualità sarà previsto dopo l’inserimento dei dati per convalidare e
revisionare l'inserimento dei dati e dei loro metadati.

Di seguito sono indicati gli aspetti relativi alla qualità dei dati che
è opportuno descrivere nel DMP, e per ognuno è indicata la
responsabilità nella compilazione.

Analisi della qualità dei dati ⓘ ⓓ
----------------------------------

Secondo la norma ISO 9000:2015, la qualità è la totalità degli elementi
e delle caratteristiche di un prodotto o servizio che concorrono alla
capacità dello stesso di soddisfare esigenze espresse o implicite. Le
misure per quantificare la qualità dei dati sono individuate dallo
standard ISO/IEC 25012:2008, divenuto norma italiana UNI ISO/IEC
25012:2014, che definisce un insieme di 15 caratteristiche specifiche
per la caratterizzazione della qualità dei dati: accuratezza, attualità,
coerenza, completezza, credibilità, accessibilità, comprensibilità,
conformità, efficienza, precisione, riservatezza, tracciabilità,
disponibilità, portabilità e ripristinabilità. L’ISO/IEC 25024 estende
l’ISO/IEC 25012 definendo 63 misure di qualità applicabili alle
caratteristiche di qualità dei dati.

Le caratteristiche più rilevanti ai fini della redazione del DMP sono
quattro: accuratezza, coerenza, completezza e attualità. La
Determinazione Commissariale dell’Agenzia per l’Italia Digitale n.
68/2013 riporta una tabella con un insieme esemplificativo di misure,
con riferimento allo standard ISO, a supporto delle attività di
valutazione della qualità dei dati delle amministrazioni [9]_. Nel DMP è
opportuno descrivere le modalità di analisi della qualità dei dati
adottate nel progetto, e, in particolare, quale standard è stato
adottato per valutare la qualità dei dati; quali misure di qualità dei
dati sono in uso e per ogni misura, in che modo viene eseguita la
misurazione. In caso di tipologie di dati multiple, queste informazioni
devono essere riportate per ogni specifica tipologia.

Bonifica dei dati ⓘ
-------------------

Generalmente l’analisi della qualità del dato può richiedere una fase di
bonifica: i dati all’interno dei sistemi informativi o degli archivi di
un’amministrazione possono talvolta essere “sporchi” e non rispondenti
ai requisiti di qualità previsti dagli standard adottati nel progetto.
La bonifica può essere basata sui dati oppure basata sui processi. Nel
primo caso, il dataset viene corretto tramite un confronto con il mondo
reale (anche con attività economicamente onerose come contattare
direttamente i soggetti preposti alla gestione della base dati) e/o
tramite un confronto incrociato (*matching*) con altri dataset.

La bonifica basata sui processi invece analizza le cause che hanno
portato alla scarsa qualità del dato e rivede i processi di produzione
del dato per garantirne la qualità nel tempo. Per esempio, se si
riscontra che la scarsa accuratezza di una base di dati deriva da un
processo di inserimento dati manuale, si può intervenire sulla fase di
acquisizione introducendo metodi per minimizzare la possibilità di
errori. La bonifica basata sui processi ha dunque il consistente
vantaggio di essere una strategia risolutiva. Nel DMP è opportuno
descrivere le attività di bonifica dei dati previste nel progetto, e in
particolare:

-  quali sono le attività oggetto di bonifica (es. inserimento dati)

-  se la bonifica è basata sui dati oppure sui processi

-  in caso di bonifica basata sui dati, quali sono le modalità di
   bonifica e quali sono i dataset di riferimento per la bonifica

-  in caso di bonifica basata sui processi, quali interventi sono
   previsti per minimizzare gli errori

-  quali software sono utilizzati per la bonifica

In caso di tipologie di dati multiple, queste informazioni devono essere
riportate per ogni specifica tipologia.

Nomenclatura degli oggetti digitali ⓘ ⓒ
---------------------------------------
.. _Nomenclatura degli oggetti digitali: https://docs.italia.it/italia/icdp/icdp-pnd-digitalizzazione-docs/it/v1.0-giugno-2022/nomenclatura-degli-oggetti-digitali.html

.. _Linee guida per la digitalizzazione del patrimonio culturale: https://docs.italia.it/italia/icdp/icdp-pnd-digitalizzazione-docs

Le convenzioni per nominare i file sono importanti per descrivere ciò
che contengono e come si relazionano ad altri file. Lo sviluppo di una
struttura è fatto attraverso l'identificazione degli elementi chiave del
progetto, le differenze importanti e i punti in comune tra i file che
l’istituto produce o gestisce. Questi elementi potrebbero includere
aspetti come la data di creazione, il nome dell'autore, il nome del
progetto, il nome di una sezione o una sottosezione del progetto, la
versione del file, ecc. Un vantaggio nell'usare nomi di file unici e
standardizzati è la capacità di seguire i nomi dei percorsi e collegarsi
ad altri sistemi che richiedono nomi di file unici. Le indicazioni per
la nomenclatura degli oggetti digitali sono riportate nel Capitolo `Nomenclatura degli oggetti digitali`_ delle `Linee guida per la digitalizzazione del patrimonio culturale`_.

Nel DMP è opportuno descrivere la metodologia utilizzata per assegnare i
nomi dei file, spiegando in che modo è implementata e quali software
sono utilizzati per assegnare i nomi dei file. Inoltre, è importante
indicare la modalità di costruzione del codice oggetto (che costituisce
la parte variabile del nome) e la provenienza degli identificativi
presenti nel codice oggetto (es. SBN). In caso di metodologie di
nomenclatura multiple, sarà opportuno riportare queste informazioni per
ogni specifica metodologia adottata.

.. [9] Cfr. https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/aspettiorg.html#qualita-dei-dati
