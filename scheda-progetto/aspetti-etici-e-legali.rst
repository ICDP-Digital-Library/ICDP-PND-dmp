7.6. Aspetti etici e legali 
============================

Nella gestione di un progetto di digitalizzazione, vanno necessariamente
affrontate alcune questioni etiche e di *policy* dei dati, che in taluni
casi possono avere anche risvolti legali. Questa sezione descrive le
modalità con cui vengono questi affrontati nella gestione dei dati.

7.6.1. Dati personali e consenso informato ⓘ
---------------------------------------------

Il diritto alla protezione dei dati è sancito dalla Carta dei diritti
fondamentali dell'UE e dal Trattato sul funzionamento dell'Unione
europea, che rendono effettivo il diritto alla *privacy* delle persone
fornendo loro il controllo sul modo in cui le informazioni che li
riguardano vengono raccolte e utilizzate.

Le categorie di dati personali che meritano speciale protezione sotto il
profilo della riservatezza sono definite dal Regolamento UE 2016/679
relativo alla protezione dei dati personali (GDPR). In particolare, i
dataset pubblicati non devono contenere “dati personali che rivelino
l'origine razziale o etnica, le opinioni politiche, le convinzioni
religiose o filosofiche, o l'appartenenza sindacale, nonché trattare
dati genetici, dati biometrici intesi a identificare in modo univoco una
persona fisica, dati relativi alla salute o alla vita sessuale o
all'orientamento sessuale della persona” (art. 9 del GDPR) e i “dati
personali relativi alle condanne penali e ai reati o a connesse misure
di sicurezza” (art. 10 del GDPR).

In questo paragrafo occorre dunque indicare:

-  Se nel progetto verranno trattati dati personali, e se sì quali

-  Chi è responsabile del trattamento dei dati personali

-  Quali soggetti sono proprietari dei dati personali

-  Se sono previste modalità di raccolta consenso informato, e se sì
   quali sono.

7.6.2. Diritto d’autore ⓘ
-------------------------

Il diritto d’autore in Italia è protetto dalla legge 22 aprile 1941 n.
633 (*Protezione del diritto d'autore e di altri diritti connessi al suo
esercizio),* che descrive i diritti riconosciuti agli autori di
un’opera, e quali sono le modalità di fruizione di tali diritti. La
legge distingue il diritto morale, che è inalienabile e indipendente
dall’utilizzazione economica dell’opera, dai diritti patrimoniali
(pubblicazione, riproduzione, trascrizione, esecuzione e
rappresentazione, comunicazione, distribuzione, modificazione,
traduzione, noleggio e prestito), che sono invece rinunciabili e
soggetti a un limite temporale. In Italia, la durata prevista per i
diritti patrimoniali è nella maggior parte dei casi di 70 anni.

I diritti relativi alle banche dati, e i doveri a cui sono soggetti gli
utenti delle stesse, son normati dagli articoli 102-bis e 102-ter della
legge sul diritto d’autore, che prevedono una serie di vincoli e un
diritto esclusivo sulla banca dati da parte del costitutore, che ha una
durata di 15 anni.

In un progetto di digitalizzazione, è fondamentale tenere in
considerazione tutti gli aspetti del diritto d’autore (o *copyright*) e
assicurarsi di rispettare la legge, in particolare nel momento in cui
viene adottata una specifica licenza, che deve pertanto essere
compatibile con i diritti che l’istituto detiene.

In questo campo vanno descritti gli aspetti relativi al diritto d’autore
che vanno affrontati nel progetto, e in particolare:

-  Indicare se i beni oggetto di digitalizzazione sono attualmente
   protetti dal diritto d’autore o da altri diritti di natura
   patrimoniale

-  Se sì, indicare le tipologie di beni e la durata dei relativi diritti

-  Se sì, indicare come si prevede di garantire il rispetto di tali
   diritti

-  Indicare se i dati prodotti o raccolti nel progetto sono protetti dal
   diritto d’autore o da altri diritti di natura patrimoniale

-  Se sì, indicare come si prevede di garantire il rispetto di tali
   diritti

-  Indicare se gli eventuali dataset riutilizzati nel progetto (di cui
   al `paragrafo 7.5.6 <bookmark://_5.6_Integrazione_con>`__) sono
   protetti dal diritto d’autore o da altri diritti di natura
   patrimoniale

-  Se sì, indicare come si prevede di garantire il rispetto di tali
   diritti.

7.6.3. Possibili fonti di *bias* ⓘ
-----------------------------------

Nella produzione, modellazione ed elaborazione dei dati è possibile che
vengano introdotti *bias*, ovvero distorsioni che rendono i dati non
rappresentativi della realtà, in particolare per quanto riguarda la
rappresentazione delle minoranze e delle comunità marginalizzate. È
opportuno che nella gestione di un progetto siano individuate tutte le
possibili fonti di *bias*, e che si prevedano meccanismi per correggerli
(oppure, ove non fosse possibile, contestualizzarli).

La pubblicazione di dataset contenenti *bias* corre infatti il rischio
di perpetuare le diseguaglianze sociali, ad esempio quelle di
genere [13]_, etnia, lingua, religione, orientamento sessuale. Nella
rappresentazione di dati storici, è inoltre particolarmente frequente
che esistano *bias* “per omissione”, ovvero che nel dataset siano state
privilegiate talune categorie sociali rispetto ad altre al punto di
rendere queste ultime invisibili [14]_.

Qualora i dati fossero stati elaborati tramite metodi di intelligenza
artificiale (es. apprendimento automatico di conoscenza da testi o
immagini), occorre considerare i limiti degli attuali sistemi di
*machine learning* e valutare attentamente i possibili *bias* che ne
derivano [15]_.

In questo paragrafo vanno descritti:

-  I possibili *bias* derivanti dalla produzione e raccolta dei dati

-  I possibili *bias* derivanti dal riuso di dati esistenti

-  I possibili *bias* derivanti dai modelli utilizzati per rappresentare
   i dati

-  I possibili *bias* derivanti dall’uso di sistemi di intelligenza
   artificiale

-  Eventuali ulteriori tipologie di *bias* individuabili nel progetto

-  Per ogni tipologia di cui sopra, le modalità con cui si prevede di
   farvi fronte

.. _section-7:

.. [13] D’Ignazio, C. and Klein, L. F. (2020). Data Feminism. <Strong> Ideas
   Series. MIT Press.

.. [14] Ortolja-Baird, A. & Nyhan, J. (2021). "Encoding the haunting of an
   object catalogue: on the potential of digital technologies to
   perpetuate or subvert the silence and bias of the early-modern
   archive." \ *Digital Scholarship in the Humanities*.

.. [15] Bender, Emily M., et al. "On the Dangers of Stochastic Parrots: Can
   Language Models Be Too Big?" \ \ *Proceedings of the 2021 ACM
   Conference on Fairness, Accountability, and Transparency*. 2021.
