# AI_Launches
Intelligenza artificiale che, tramite una regressione lineare da singolo input, può prevdere la probabilità di un lancio dall'umidità.

Siamo partiti da un file Excel [Lanci1.xlsx](https://github.com/SouthPaul03/AI_Launches/files/8176505/Lanci1.xlsx) contenente vari dati meteorologici della località selezionata.
Successivamente, abbiamo fatto in modo che il file venga letto dal programma e abbiamo creato i set per l'addestramento.
Abbiamo poi normalizzato i dati per aumentare l'efficenza dell'algoritmo.

Il passo successivo è stato quello di creare un modello sequenziale basato sull'umidità, inziando l'addestramento mediante il set creato.
Infine, abbiamo realizzato un grafico sulle predizioni dell'algoritmo: si può notare come, secondo il programma, maggiore sia l'umidità minore sia la probabilità di lancio.

![Probabilità](https://user-images.githubusercontent.com/100573794/156545556-fbe102ba-6581-4a66-9f80-63e7596029df.png)
