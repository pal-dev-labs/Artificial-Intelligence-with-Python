# Artificial Intelligence with Python
[IIS via ROMA 298](https://www.liceoguidonia.edu.it/)

Docente: Prof. Giandomenico Palumbo

**Il contenuto di questo corso evolve in linea con l'evoluzione tecnologica**

DATA INIZIO CORSO: 02 FEBBRAIO 2023

* Sessione 1. febbraio/maggio 2023, ogni giovedi' dalle ore 14:30 alle ore 16:45, presso il Laboratorio di Informatica, sede centrale IIS via Roma 298

Il presente corso è valido come alternanza scuola-lavoro (P.C.T.O.)

# Strumenti utilizzati
Per seguire il corso è possibile utilizzare un laptop personale.
In questo caso è necessario installare sul proprio laptop la suite **Anaconda Navigator** (scaricabile dal sito web https://anaconda.org/anaconda/anaconda-navigator). Per l'installazione potete seguire le video-istruzioni pubblicate sul sito classroom del corso (vedi sotto) oppure visionabili sul mio canale YouTube https://www.youtube.com/channel/UCvE1MUP-vbzUQnV_N4nbPfA

Coloro che non dispongono di un laptop personale possono utilizzare i laptop del laboratorio di informatica. L'ambiente utilizzato è **Google Colab** che è fruibile con un browser (Chrome per es.) da un qualsiasi PC, direttamente dall'indirizzo https://colab.research.google.com/ 

Per accedere a Colab è necessario disporre di un **account Google** (chi non lo avesse lo può creare dal sito https://www.google.com/intl/it/account/about/). Una volta creata l'utenza google effettuate il log-in per verificare l'accesso all'ambiente. 

Per poter importare i notebooks in Colab è necessario disporre di un **account GitHub**. Chi non lo avesse lo può creare dal sito web https://github.com/join

**RICORDATE** di portare con voi nel laboratorio di informatica **UID e PWD di accesso a Google e GitHub**.

# Ambiente di lavoro Google Classroom
Per gli studenti del corso, il materiale del corso ed eventuali comunicazioni sono pubblicate in un ambiente Google Classroom dedicato, fruibile dal seguente link
https://classroom.google.com/c/NTgyNDg1NTU4NDA5?cjc=ow5m5ob

# Descrizione del corso

Il corso ha lo scopo di fornire agli studenti abilità per codificare algoritmi di base per implementare al calcolatore semplici modelli di **Machine Learning** (Supervised Learning). Gli studenti hanno l’opportunità di apprendere **Python**, un linguaggio di programmazione molto utilizzato in ambito  scientifico, e di utilizzarlo per implementare alcune tecniche di **Supervised Learning** (prediction e classification). Infine hanno la possibilità di applicare tali tecniche a contesti reali, per “toccare con mano” come un dato possa essere predetto o classificato in automatico da un algoritmo, sulla base di una conoscenza pregressa dei dati.
 
Il fine ultimo è quello di far comprendere allo studente come un calcolatore possa essere istruito in modo da prendere decisioni in autonomia (per es. classificare una mail come spam o no spam) sulla base di un modello matematico che utilizza i tools del calcolo, dell’algebra lineare e della statistica e codificato attraverso un linguaggio di programmazione.

Il corso si pone anche l’obiettivo di creare un corpus di studenti che conoscono il linguaggio di programmazione Python al fine di poter sviluppare nel tempo successive esperienze di **fisica-matematica computazionale**, man mano più complesse (modelli matematico-statistici di regressione lineare, studi di funzioni, interpolazioni, tecniche numeriche di risoluzione di equazioni ordinarie e differenziali, tecniche di minimizzazione di funzioni, simulazioni al calcolatore di modelli fisici, tecniche avanzate di machine learning, networks). 

Alla fine del corso agli studenti (organizzati in gruppo) sarà assegnato un problema reale che può essere risolto con un algoritmo di Machine Learning (per es. classificare delle immagini o dividere le mail in spam o non spam). Gli studenti dovranno quindi sviluppare un programma in grado di leggere una banca dati predefinita, effettuare il training dell’algoritmo di Machine Learning e applicare il modello ai nuovi dati in modo da poterli classificare.  
   
# Materiale didattico e link utili
Nel corso vengono trattati molteplici argomenti afferenti a diverse discpipline scientifiche quali Matematica, Fisica, Data Science, Computer Science e pertanto non esiste un unico libro di testo che racchiude tutti gli argomenti. 
Presentiamo di seguito un elenco del materiale che può essere consultato per gli specifici approfondimenti.

1. Anaconda Navigator
https://docs.anaconda.com/navigator/index.html
2. Jupyter Notebook
https://docs.jupyter.org/en/latest/
3. Nei Notebook Jupyter del presente corso sono inserite diversi commenti che descrivono il codice man mano implementato.
4. Python base:

    4.1 Corso base Python del Prof. Nicola Cassetta (in Italiano): https://ncassetta.altervista.org/Tutorial_Python/index.html

    4.2 Jake VanderPlas - A Whirlwind Tour of Python - O'Reilly: https://github.com/jakevdp/WhirlwindTourOfPython

    4.3 M. Lutz - Learning Python - O'Reilly (molto dettagliato)

    4.4 Per le esercitazioni possono essere utilizzati gli esercizi della W3 Resource.com visionabili al sito https://www.w3resource.com/python-exercises/basic/

5. La libreria Numpy:

    5.1 Jake VanderPlas - Python Data Science Handbook (Cap. 2 Introduction to Numpy) - O'Reilly: https://github.com/jakevdp/PythonDataScienceHandbook

Section in progress...

# Obiettivi del corso
1. Saper utilizzare i comandi base di Python, le strutture cicliche e condizionate e le strutture dati di base (Liste e Dictionary)
2. Saper utilizzare le principali librerie di Python per gestire l’algebra lineare (Numpy), la Data Manipulation (Pandas), e la Data and Information Visualization (MatPlotLib)
3. Saper utilizzare le librerie di Python Scikit-Learn e SciPy limitatamente ai tool statistici di Machine Learning relativi alla regression e classification
4. Acquisire le basi matematico-statistiche minimali per comprendere i modelli utilizzati (rudimenti di statistica, algebra lineare e calcolo)
5. Eseguire programmi-esempio che implementano algoritmi di regression e classification utilizzando le librerie Python Scikit Learn e Scipy in modo da saperli adattare a situazioni simili.

# Syllabus

1. Lezione 1
    - Introduzione ad Anaconda, Jupyter, Google Colab
    - Introduzione alle variabili e al TYPE di una variabile. I type int, float, boolean, str e list
    - Operazioni aritmetiche e di confronto tra variabili. Operatori booleani.
    - Le funzioni in Python: funzioni predefinite e definizione di una nuova funzione
    - Esempio di plotting di una funzione
2. Lezione 2
    - Come richiamare l'help dei comandi Python
    - L'istruzione condizionale IF - ELIF - ELSE
    - L'istruzione che genera i loop: FOR 
    - Come utilizzare le istruzioni condizionali e i LOOPS per risolvere alcuni problemi
    - La relazione tra le variabili e gli oggetti Python. I metodi di un oggetto. La sintassi nomevariabile.metodo
3. Lezione 3: Numpy parte 1
    - Primi esempi di algoritmi e diagrammi di flusso. Estrazione di numeri primi da una lista e ricerca di una parola in un testo
    - Introduzione ai moduli Python: il modulo Math
    - Introduzione alla libreria Numpy e al tipo ndarray
    - Modalità di creazione di array, matrici e tensori in Numpy
    - Gli attributi ndim, shape e size
    - Prime operazioni con gi array: somma, sottrazione e moltiplicazione per scalare. 
    - La Vectorization e il Broadcasting
    - Come applicare una funzione ad un array. La Vectorization delle funzioni
    - Prima applicazione con la libreria Numpy: il plotting di una funzione generica di una variabile
    - Seconda applicazione della libreria Numpy: come modellizzare un'immagine con un array 
4. Lezione 4: Numpy parte 2
    - Le celle MarkDown del notebook Jupyter. Come formattare il testo e inserire formule matematiche 
    - Array indexing e slicing: come estrarre singoli elementi o sottoinsiemi di array e matrici da altri array
    - Rudimenti di algebra delle matrici in Numpy: somma di matrici, prodotto scalare tra vettori, prodotto di matrici, determinante di una matrice
5. Lezione 5: Pandas parte 1
    - Come importare un file csv in Pandas
    - Proprietà elementari degli oggetti Dataframe e Series
    - Come estrarre righe e colonne dai dataframe (il metodo iloc)
    - Come effettuare lo slicing sulle righe e sulle colonne
    - Introduzione ai boolean filter. Primi esempi
    - Primo esempio di plotting di dati estratti dal dataframe
6. Lezione 6: Pandas parte 2
    - Come creare un plot Bar e un plot Pie con un dataframe Pandas
    - Come aggregare i dati: le tabelle Pivot e gli indici multipli
    - Come creare un istogramma
    - Come definire una metrica aggregando colonne del dataframe in una nuova colonna
    - Esercizio di data analysis su un dataset reale (dataset calciatori)
7. Lezione 7: Data Visualisation
    - Introduzione a MatPlotLib
    - Il comando plot e i principali attributi
    - Come creare grafici da un dataframe 
    - Come creare uno scatterplot
    - Three-Dimensional Plotting in MatPlotLib
    - Density and Contour Plots
8. Lezione 8: Introduction to Supervised Learning
    - Overview su Artificial Intelligence, Machine Learning, Supervised Learning e Unsupervised Learning
    - Supervised Learning con valori continui per una sola feature: il problema della regressione
    - Notazione di base: features, target, training set e learning algorithm
    - Introduzione alla hypotesis function: il caso della funzione lineare e parametrica (linear regression)
    - Introduzione al Mean Square Error (MSE) e alla Cost Function
9. Lezione 9: Multiple Features Linear Regression e Polynomial Regression
    - La necessità di considerare una regressione lineare con più predictors
    - Hypotesis function per una regressione lineare con più predictors. Formalismo algebrico
    - Esempio di applicazione di una regressione lineare con più predictors
    - Perchè estendere la regressione lineare ad un modello polinomiale
    - Esempi di applicazione. Introduzione al problema dell'overfitting

10. - Lezione 10: La tecnica dell'embedding nel NLP
    - L'embedding nella rappresentazione dei colori. Esempi di vettorizzazione. Distanze tra i colori. Similitudini
    - L'embedding per la rappresentazione delle parole. Distributional Semantics e ipotesi distributiva
    - Vettori di parole per mezzo del conteggio dei contesti. Il progetto GloVe della Stanford University. 
    - Vettorizzazione delle parole. La libreria spaCy. Introduzione al concetto di token    
    - Cosine similarity e ricerca dei "closest neighbors"
    - Sentence similarity. Cenni a WordToVec
11. - Lezione 11: Progetto per la realizzazione di un classificatore di sms Spam/no spam
    - Codifica del data processing: importazione dei dati e delle librerie, data cleaning
    - Data visualization utilizzando wordcloud (spam/no spam)
    - Predisposizione al machine learning: utilizzo della piattaforma NLTK per la rimozione delle stop words e punctuations e per la conversione del testo in vettori (count vectorizer e TF-IDF)
    - Costruzione del modello di classificazione (slitting dai dati in train e test). Implementazione della logist regression
    - Utilizzo di altri modelli di classificazione (Naive Bays, Tree, KNC)
    - Valutazione dell'accuracy tramite confusion matrix
    - Forecasting
12. - Introduzione alle reti neurali (lezione solo teorica, senza notebook).
    - Il modello a singolo neurone (Perceptron)
    - Il modello a più neuroni. La costruzione di una rete neurale
    - L'importanza degli strati interni di una rete neurale
    - Visione del filmato "But what is a neural network?"  https://www.youtube.com/watch?v=aircAruvnKk
    - Sviluppi e applicazioni dei Neural Networks

# Datasets
    - Dataset sui terremoti nel mondo - file earthquakes.csv 
    - Dataset calciatori - file player_20.csv

Section in progress...
