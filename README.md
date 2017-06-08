# ProductVisualization

Autore : Dal Ben Enrico

## Scelta del modello

Inizialmente ho scelto un modello semplice di un freno a disco per imparare a usare gli shader e le equazione viste in classe, oltre che a capire come caricare e manipolare un oggetto caricato da un file esterno.
Ho cercato online un sito in cui venivano offerti modelli gratuiti per uso non commerciale e ho trovato il sito www.turbosquid.com che permette di scegliere tra migliaia di modelli scaricabili creando un account gratuito.
Ho cercato anche una cubemap adatta al modello scelto, in questo caso un minipala gommata, sempre scaricando dal sito http://www.humus.name/index.php?page=Textures&start=88 che forniva cubemap non a uso commerciale.
Ho deciso di scaricare una texture che rappresenta la pelle nera lavorata per alcuni particolari.

## Shader senza texture

Ho creato uno shader basat sulle equazioni viste in classe, implementa i materiali senza texture come l'acciaio.
Ho creato diversi materiali che si basano su questi shader così da poter specificare materiali metallici e plastici, con colori diversi.
C'è una luce puntuale posto in alto a destra a illuminare l'oggetto, una ambient light leggera per dare più tonalità ai colori e una enviromet map per dargli un aspetto più realistico, specialmente per i metalli.
Ho aggiunto tramite una variabile opacity anche la semitrasparenza per i fanali posteriori, per il pannelo dietro il sedile del guidatore e per i faneli davanti.
Per lo specchietto retrovisore ho usato una classe mirror fornita da three.js.

## Shader con texture

Nel secondo shader ho applicato al modello alcune texture per renderlo un po' più realistico rispetto ad usare solo materiali creati dal primo shader, specialmente er le vernici o la pelle del sedile.
Usando il programma gratuito Crazybump (http://www.crazybump.com/), che permette di caricare una foto e generare una serie di texture, ho ricavato dalle foto di pelle e vernici le Roughness map e specular map da applicare ai modelli.
Anche in questo caso mi sono basato sulle equazioni viste a lezione.

## Sito e-commerce


Se la base del progetto soddisfa i requisiti minimi pensavo di aggiungere alcuni particolari :

una paginazione come un sito di e-commerce

- modifiche tramite il sito e-commerce del colore
- modifica di alcuni particolari tramite l'aggiunta di una texture che assomiglia alla pelle lavorata
