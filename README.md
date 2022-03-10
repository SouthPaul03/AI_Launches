# AI_Launches
Intelligenza artificiale che, tramite una regressione lineare da singolo input, può prevdere la probabilità di un lancio dall'umidità.


Siamo partiti da un file Excel [Lanci1.xlsx](https://github.com/SouthPaul03/AI_Launches/files/8176505/Lanci1.xlsx) contenente vari dati meteorologici della località selezionata.
Abbiamo dovuto modificare alcuni dati nel file: il lancio è stato eseguito se Lanciato è uguale a 2, altrimenti è uguale a 1. Le condizioni atmosferiche sono state sostituite con dei numeri decimali per avere lo stesso tipo di dati:

Sereno : 0,1

Pioggia/nebbia : 0,2

Parzialmente nuvoloso : 0,3

Cielo coperto: 0,4

Pioggia: 0,5


Successivamente, abbiamo fatto in modo che il file venga letto dal programma e abbiamo creato i set per l'addestramento.
Abbiamo poi normalizzato i dati per aumentare l'efficenza dell'algoritmo.

Il passo successivo è stato quello di creare un modello sequenziale basato sull'umidità, inziando l'addestramento mediante il set creato.
Infine, abbiamo realizzato un grafico sulle predizioni dell'algoritmo.
