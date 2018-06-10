# Descrizione Generale
Il nostro progetto prevede il rendering di un robot da guerra. L'utente ha la possibilità di visualizzare il robot in una versione "appena uscito da fabbrica" e una con i metalli arruginiti. Tuttavia abbiamo pensato che alcune parti costruite idealmente con metalli cromati non debbano arrguginire e rimangano pertanto invariati nelle due visualizzazioni. Il robot presenta inoltre una base in roccia per attenuare il rinculo degli spari e dare maggior stabilità. Anch'esso infatti viene visualizzato in una versione "pulita" e una versione invecchiata, sporca e con del muschio.
![Intro](images/intro.png)
Abbiamo implementato il gioco dello snake in modo che quando il serpente mangia la "mela", il suo corpo si allunga di un cubo. Quando il serpente mangia se stesso, il gioco automaticamente si resetta (e di conseguenza la lunghezza del corpo dello snake). Mentre quando va a sbattere lungo la parete dell'arena il serpente devia automaticamente la sua traiettoria lungo il perimetro dell'arena stessa in modo che se l'utente vuole spostarsi attraverso la scena può riprendere a giocare senza perdere i progressi fatti.
![Snake](images/snake.png)
![Sunrise](images/sunrise.png)

# Struttura del progetto
- da ```index.html``` si accede al risultato finale del progetto
- ```config.js``` contiene alcuni nostri parametri di configurazione
- ```favicon.ico``` è l'immagine visualizzata nella tab del broser
- ```journal.md``` una raccolta di tutti gli step fatti per la realizzazione del progetto
- ```./images``` contiene la Heightmap e immagini usate nel readme e nel jorunal
- ```./lib``` contiene le librerie di threejs usate
- ```./obj``` contiene mesh di oggetti importati nella scena principale
- ```./StartingCode``` i codici di partenza dati alla consegna del progetto
- ```./StartingCode``` i codici di partenza dati alla consegna del progetto

# Fasi di implementazione
- implementazione logiche di gioco dello snake su un'arena custom
- esportazione dal sito __________ la heightmap di machu-pichu e modifica della scala di grigi con photoshop
- Generazione terreno a partire dalla heightmap
- modellazione e inserimento dell'arena di gioco nella scena
- inserimento dello snake sull'arena
- Colorazione terreni in base all'altezza
- Implementazione comandi da tastiera (enter e freccette direzionali)
- Creazione del sole e implementazione della sua orbita
- Inserimento ombre sulla scena


# Future features da implementare
- Aggiungere altri materiali
- implementare un particle system per simulare i proiettili che escono dalle canne della mitragliatrice
