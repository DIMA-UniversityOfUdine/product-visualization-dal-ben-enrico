# ProductVisualization
Autore : Dal Ben Enrico

## Scelta del modello
Inizialmente ho scelto un modello semplice di un freno a disco per imparare a usare gli shader e le equazione viste in classe, oltre che a capire come caricare e manipolare un oggetto caricato da un file esterno.
Ho cercato online un sito in cui venivano offerti modelli gratuiti per uso non commerciale e ho trovato il sito www.turbosquid.com che permette di scegliere tra migliaia di modelli scaricabili creando un account gratuito.
Ho cercato anche una cubemap adatta al modello scelto, in questo caso un minipala gommata, sempre scaricando dal sito  http://www.humus.name/index.php?page=Textures&start=88 che forniva cubemap non a uso commerciale.
Ho deciso di scaricare una texture che rappresenta la pelle nera lavorata per alcuni particolari.

## Attuale stato del lavoro
Caricamento del medello all'interno della scena di threejs e creazione di shader per rendere il colore e i riflessi più realistici.
Per le equazioni degli shader mi sono basato su quelli fatti in classe.
Ho creato diversi materiali che si basano su questi shader così da poter specificare materiali metallici e plastici, con colori diversi.
Attualmente c'è solo una luce puntuale a illuminare l'oggetto e una enviromet map per dargli un aspetto puù realistico, specialmente per i metalli.
Aggiunta una semitrasparenza per i fanali posteriori.
Aggiunta dello specchietto retrovisore tramite una classe fornita da three.js.
Ho aggiunto dei rifinimenti su alcuni pezzi del modello per aggiungere una texture che assomiglia alla pelle lavorata in modo da dargli un aspetto più accattivante.
Si può anche scegliere di colorare il odello in tre diverse tonalità.

## Aggiunte future
Se la base del progetto soddisfa i requisiti minimi pensavo di aggiungere alcuni particolari : 
- una paginazione come un sito di e-commerce
- ombre del modello
- modifica dei colori di base per renderlo più realistico

#### Opzionale
- aggiunta del logo della casa produttrice sulla minipala
