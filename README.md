# YOLOE

YOLOE è un'implementazione efficiente del modello YOLO (You Only Look Once) per il rilevamento di oggetti. È progettato per offrire un rilevamento veloce e preciso in immagini e video, ottimizzando l'architettura YOLO originale per garantire migliori prestazioni, specialmente nelle applicazioni in tempo reale. Questo modello è in grado di rilevare più oggetti nelle immagini con una singola passata, rendendolo estremamente efficiente per le applicazioni del mondo reale.

## Tutorial

Segui i passaggi sotto per utilizzare il modello YOLOE per il rilevamento di oggetti.

### 1. Importa il notebook su Google Colab
Per iniziare, importa il notebook nel tuo ambiente Google Colab aprendo il file notebook (`.ipynb`) nel tuo Google Drive.

### 2. Configura le classi da rilevare nelle immagini
Nella sezione di configurazione del notebook, specifica le classi che desideri rilevare.

### 3. Carica le immagini nella cartella `dataset`
Crea una cartella chiamata `dataset` nell'ambiente Colab e carica tutte le immagini che vuoi analizzare in questa cartella.

#### 3.1 Opzionale: Calcolare la media dell'IoU (Intersection over Union) su tutto il dataset
Se desideri calcolare la media dell'IoU per il tuo dataset, crea una sottocartella dentro la cartella `dataset` chiamata `annotations`. In questa sottocartella, carica i bounding box (bbox) per ogni immagine nel formato YOLO (xywhn).

### 4. Esegui il codice
Esegui le celle di codice nel notebook per avviare il processo di rilevamento oggetti. Il modello elaborerà le immagini e rileverà gli oggetti in base alle classi specificate.

### 5. Visualizza i risultati
Una volta completato il processo, puoi visualizzare i risultati, che includeranno gli oggetti rilevati insieme ai rispettivi bounding box sulle immagini.

---

## Elaborazione Video

Se desideri eseguire il rilevamento degli oggetti su un video segui questi passaggi.

### 1. Configurazione del Video

Imposta il percorso del video sorgente e il percorso per il video finale. Puoi anche definire l'altezza della timeline e una soglia di confidenza per il rilevamento degli oggetti.

### 2. Esegui il codice

Esegui la cella di codice nel notebook per rilevamento ggetti da uno stream video.
