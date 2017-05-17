# ProductVisualization
Autore : Dal Ben Enrico

## Scelta del modello
Inizialmente ho scelto un modello semplice di un freno a disco per imparare a usare gli shader e le equazione viste in classe, oltre che a capire come caricare e manipolare un oggetto caricato da un file esterno.
Ho cercato online un sito in cui venivano offerti modelli gratuiti per uso non commerciale e ho trovato il sito www.turbosquid.com che permette di scegliere tra migliaia di modelli scaricabili creando un account gratuito.
Ho cercato anche una cubemap adatta al modello scelto, in questo caso un bobcat, sempre scaricando dal sito  http://www.humus.name/index.php?page=Textures&start=88 che forniva cubemap non a uso commerciale.
Ho deciso di scaricare una texture che rappresenta la pelle nera lavorata per alcuni particolari.

## Attuale stato del lavoro
Caricamento del medello all'interno della scena di threejs e creazione di shader per rendere il colore e i riflessi più realistici.
Per le equazioni degli shader mi sono basato su quelli fatti in classe.
Ho creato diversi materiali che si basano su questi shader così da poter specificare materiali metallici e plastici, con colori diversi.
Attualmente c'è solo una luce puntuale a illuminare l'oggetto e una enviromet map per dargli n aspetto puù realistico, specialmente per i metalli.

## Aggiunte future
Se la base del progetto soddisfa i requisiti minimi pensavo di aggiungere alcuni particolari : 
- una paginazione come un sito di e-commerce
- alcune spot ligth e relative ombre
- aggiunta di uno specchietto retrovisore con equazioni per mostrare parte del bobcat
- modifiche tramite il sito e-commerce del colore
- modifica di luci posteriori per le frecce
