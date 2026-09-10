+++
title = "Maqui Maqui"
url = "/2013/03/maqui-maqui-2/"
date = "2013-03-25"
draft = false
+++

Perché fare un altro [Makey Makey](http://www.makeymakey.com/ "makey")?ngg\_shortcode\_0\_placeholder

MaquiMaqui, inspired by MaKey MaKey, a version of MaKey MaKey that can be made at home with DIY techniques

“*vista una cosa si può provare a ricrearla, ..”*

Innanzitutto occorre la premessa che il nostro non vuole essere una versione low cost del Makey Makey realizzato dal M.I.T. a cui ci siamo ispirati, sebbene il costo effettivo per la sua costruzione sia intorno ai 2$ contro i 49,95$ dell’originale. E’ piuttosto un tentativo di poter creare qualcosa sfruttando ciò che si ha a disposizione, spesso senza farci caso, come una vecchia tastiera IBM compatibile datata 1997 destinata probabilmente a diventare un ecosistema popolato da acari in cima a qualche armadio polveroso.

Accértati che il controller al suo interno funzioni ancora e con alcuni componenti elettronici saldati su una basetta millefori riesci ad ottenere una consolle collegabile al PC come una comune tastiera, col vantaggio di poter generare 6 caratteri tra quelli normalmente disponibili utilizzando dei tasti “fantasiosi” come frutti, ortaggi, vaschette d’acqua ecc.more

Le applicazioni variano a seconda dei propri gusti, sia che si voglia giocare ad un videogioco con un joypad disegnato su carta con della grafite oppure strimpellare il proprio PC come un pianoforte suonando dei gambi di sedano.

Il concetto è che tu sei un componente del circuito, alla stregua dei transistor e delle resistenze, ci sei dentro e puoi azionare le cose semplicemente sfiorandole grazie all’ impercettibile corrente che ti attraversa.

E quindi cosa fa il tasto melanzana? hehe, niente di più che non possa fare un altro semplice bottone, perché in ogni caso stai chiudendo dei contatti.

La differenza è rassegnarsi al cablaggio prestabilito, che ha disposto chi l’ha costruito oppure provare a cambiarlo?

L’hacker artigiano decide la disposizione delle carte sul tappeto verde del circuito e si da la possibilità di scelta.

ngg\_shortcode\_1\_placeholder

L’aggeggio originale è configurato su 6 tasti, ma ti da la possibilità di allargare le tue possibilità di combinazione (rimappando il firmware del microcontrollore). Il nostro invece di quel chip (atmega32u4) utilizza direttamente il controller di una vecchia tastiera, così che per decidere che tasti vuoi usare non devi andare a scrivere nessun codice, ma piuttosto giocare a battaglia navale tra i contatti.(capito? Mai visto le viscere di una vecchi tastiera ps2.. andate ad aprirne una, che dopo trovate lo schema elettrico di cosa potete farci 🙂

A noi piace anche l’idea di poter dare una seconda giovinezza ad una di quelle vecchie periferiche che vengono dimesse anche se funzionano ancora, solo per il gusto di potersi accaparrare qualcosa di sempre più nuovo con la convinzione che ci sarà utile o renderà più elegante la nostra scrivania. E’ una piccola resistenza alla corsa del consumare

e a volte ci sembra di rifugiarci in queste cataste di rifiuti verdi, scrutandole fino a quando non ci vediamo la forma di un oggetto, o la possibilità di una nuova applicazione.

Da lì lo prendiamo ed empiricamente o applicando volumi di teoria (ormai a portata di mano nel web) vediamo di realizzare materialmente quello che nella nostra testa è già funzionante.

A volte il più lungo del lavoro è trovargli un nome 🙂

Già. Anche con questo oggettino ci siam rimasti su un po..

ma pensa che ti ripensa ci è venuta una splendida fascinazione da parte del nostro compare catalano. Lo chiameremo Maqui Maqui, come i partigiani sul confine spagna/francia. Un omaggio a chi ha a cuore la libertà, anche in un contesto storico dove viene considerata guerriglia o terrorismo e lui/lei/loro chiamati banditi.

Ci sono delle linee guida sulle possibilità di battezzare un dispositivo ispirato al MaKey MaKey™ , che prevengono l’utilizzo del nome Makey anche solo in parte o di assonanze con il marchio registrato. Lo trovate qui: <http://makeymakey.com/derivatives.php>

La Sparkfun, che sono quelli che hanno realizzato il prototipo per il MIT hanno indicato nel loro schema:

    Released under Creative Commons Attribution – Share Alike 3.0
    Licence http://creativecommons.org/licenses/by-sa/3.0/

**Quindi, visto che presenta SA (condividi allo stesso modo) dobbiamo utilizzare la medesima licenza per diffondere questo nuovo progetto derivato:**

**Maquie Maquie**

**Created by ofPCina ([www.ofPCina.net](/)) and licensed under**

**Creative Commons Attribution – Share Alike 3.0**

    Licence http://creativecommons.org/licenses/by-sa/3.0/

ngg\_shortcode\_2\_placeholder

**Vi suggeriamo ora di passare alla pratica:**

LISTA COMPONENTI:

n. 2 Connettori strip maschio 20 poli passo 2,54, altezza 10

n. 1 Connettore strip femmina 20 poli passo 2,54

n.12 Resistenze da 10 MΩ, 1/4 W

n. 6  Resistenze da 10 KΩ, 1/4 W

n. 6 Transistor BC547, TO-92

n. 1 Condensatore ceramico 100 Nf

n. 1 circuito integr. 4049 (tradizionale)

n. 1 zoccolo 16 pin

n. 1 basetta millefori dimensioni almeno 100 x 50

- TEORIA:

L’effetto dei tasti premuti è realizzato da semplici transistor in open collector, azionati singolarmente da un integrato c-mos che commuta quando variano i valori di tensione dei rispettivi ingressi. A questi sono collegati i famosi ortaggi, e quando se ne tocca uno o anche più di uno allo stesso tempo si varia lo stato logico della porta.

In realtà è possibile avere questo effetto con qualunque cosa conduca, non solo verdura!

L’unica limitazione è data dal valore di impedenza ottenuto tra la melanzana e noi che gli siamo “in serie”, che non deve superare quella con cui è mantenuto alto ogni ingresso dell’integrato ( ben 20Mega Ohm! )

[altreinfo](https://n-1.cc/dokuwiki/1284224/doku.php?id=makey_makey)

    Released under Creative Commons  Attribution – Share Alike 3.0
    Licence http://creativecommons.org/licenses/by-sa/3.0/

info@ofPCina.net
