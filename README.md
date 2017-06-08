# Secondo compitino Interactive 3D Grafics

Autore : Dal Ben Enrico

## Scelta del modello

Ho cercato online un sito in cui venivano offerti modelli gratuiti per uso non commerciale e ho trovato il sito www.turbosquid.com che permette di scegliere tra migliaia di modelli scaricabili creando un account gratuito.
Ho cercato anche una cubemap adatta al modello scelto, in questo caso un minipala gommata, sempre scaricando dal sito http://www.humus.name/index.php?page=Textures&start=88 che forniva cubemap non a uso commerciale.

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
Ovviamente Le immagini per le texture sono prese da siti che ne permettono l'uso gratuito a scopo non commerciale.

## Sito e-commerce

Ho trovato online un template che si chiama _Amaranto_ che mi piaceva per come strutturava la pagina.
Non essendo esperto di html ho preferito cercare un template già pronto e non crearlo da me.
Ho modificato la pagina affinche permetta di scegliere il colore e ho aggiunto un link che manda al modello 3D del prodotto.
Ho optato per questa scelta perchè non è detto che tutti gli utenti possiedano hardware o software per visuallizzare il modello.
