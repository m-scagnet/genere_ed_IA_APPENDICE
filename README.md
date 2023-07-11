# genere_ed_IA_APPENDICE
Appendice digitale della tesi di laurea triennale "Sviluppo e validazione di un dataset in italiano per l’analisi di stereotipi di genere nei documenti testuali" (2023) di Martino Scagnet. Università di Padova.

Il file Codice_Survey.zip contiene tutti i codici utilizzati per: estrarre le sezioni di testo e comporre il questionario PsyToolkit.
  I principali moduli Python sono:
    - "survey_compose.py": in cui vengono definite tutte le variabili utili all'estrazione delle domande dal dataset ed alla composizione del survey. Questo modulo richiama "data_extract.py" nel caso vengano modificate le variabili per l'estrazione.
    - "data_extract.py" estrae i testi dalle cartelle di file .txt che compongono il dataset e salva nel file dirs_data.npy le domande basandosi sulle variabili di estrazione e utilizzando le strutture dati definite negli altri moduli python.
    I risultati dell'estrazione ed il file di testo contenente il questionario di output scritto in pseudocodice PsyToolkit si possono trovare nella directory "outputs". 

Il file "Dataset_BiasModelliLinguistici_Scagnet.zip" contiene il dataset vero e proprio di file di testo ed un indice con fonti ed autori di ogni testo.

Il file "score_sezioni_questionario.csv" contiene i risultati dell'analisi del questionario, come discusso nell'elaborato della tesi.
