<!DOCTYPE html>
<html>
  <head>
    <title>La Divina Commedia di Dante Alighieri</title>
    <meta http-equiv="Content-Type" content="text/html; charset="UTF-8">
    <style type="text/css" media="all">
    
    p

    {
        font-size:px;
        font-family: Gill, Helvetica, sans-serif;
    }
    
    pre

    {
        font-style: italic;
        font-weight: bold;
    }
    
    figure { display: inline; }
    
    /* selettori combinatori */
    article h1 { color: red; }
    hgroup > h4 { color: blue;}
    h1 + h4 { border-top: 1px solid red;}
    header ~ footer { background-color: lime;}
    
    /* selettori di attributo */
    a[hreaf] { font-size: 16px; }
    a[href = "http://www.wikimedia.org/"] { color: red; }
    img[alt ] ~ = "Immagine"] { border: 4px dotted red; }
    section[lang |= "it"] { background-color: alice-blue; }
    p[id  ^= "letre"] { font-weight: bold; }
    a[href $= ".org/"] { text-transform: uppercase; }
    section[title *= "simboleggiano"] { border: 3px ridge blue; }

    /* pseudo-classi dinamiche e per gli stati degli elementi di una UI */
    a[href $= "Pagina Principale"]:link { text-decoration: none; }
    a:visited { color: yellow }
    p:hover { font-size : 26; }
    
    a: active
    {
        background-color: black;
        color: lime;
    }

    input[type="text"]:focus { background-color: lightcyan; }
    input[type="button"]:enabled { border: 2px double green; }
    input[type="button"]:disabled { border: 2px double red; }
    input[type="radio"]:checked { border: 2px dotted green; }

    /* pseudo classi strutturali */
    section[lang="it"] > p:nth-child(2n + 1)
    {
        font-style: italic;
        color: red
    }
    section[lang="it"] > p:nth-lastchild(1) { font-weight: bold; }
    form > label:nth-of-type(3) { font-weight: bold; }
    form > label:nth-last-of-type(2) { font-weight: bold; }
    form > label:first-child { font-weight: bold; }
    form > input:first-of-type { border: 2px solid green; }
    footer > pre:only-child { border: 1px solid black; }
    section > h1:only { text-align: center; }

    /* pseudo elementi */
    section > p:nth-child(odd)::first-line { font-weight: bold; }
    section > p::first-letter { font-size: 1.5em; }
    section > h1::before
    {
        content: "{ ";
        color: black;
    }
    </style>
    </head>
    <body>
        <article>
            <header>
                <hgroup>
                <h1>La Divina Commedia</h1>
                <h4>Da Wikipedia, l'enciclopedia libera</h4>
                </hgroup>
                <form>
                    <label for="importo">Fai una piccola donazione: </label>
                    <input id="importo" type="text" /><input type="button" 
    value="Dona..." /><br/>
                    <input id="ammontare_5" type="radio" name="euro" /><label
    for="ammontare_5">5 €</label>
                    <input id="ammontare_10" type="radio" name="euro" /><label
    for="ammontare_10">10 €</label>
                    </form>
                    </header>
                    <hr/>
                    <section lang="it">
                        <p> Commedia o Divina Commedia (originariamente Comedìa; l'aggettivo
    Divina,_</p>
                        <p id="letreparti">Il poema è diviso in tre parti, chiamate cantiche
    (Inferno, Purgatorio e Paradiso),_</p>
                        <p>L'opera ebbe subito uno straordinario successo, e contribuì in
    maniera_</p>
                        <p>Oggi si dispone di un'edizione di riferimento realizzata da Giorgio
    Petrocchi...</p>
                        <p>La Commedia, pur proseguendo molti dei modi caratteristici della_</p>
                        <p>Curioso notare come tutte le tre cantiche termino con la parola
    "stelle"_</p>
                        </section>
                        <hr />
                        <section title="Alcune immagini che simboleggiano Dante e la Divina Commedia">
                            <h1>Alcune immagini:</h1>
                            <figure id="immagine_1">
                                <img src="bronzino.jpg" alt="Immagine di Angelo Bronzino"/>
                            <figure id="immagine_2">
                                <img src="dimichelino.pg" alt="Immagine di Domenico Di Michelino"/>    
                            </figure>
                        </section>
                        <hr />
                        <footer>
                            <pre>
    Ultima modifica per la pagina: 16:30, 12 dic 2011. Il testo è disponibile secondo la
    licenza Creative Commons Attribuzione-Condividi allo stesso modo; possono applicarsi
    condizioni ulteriori.
    Vedi le condizioni d'uso per i dettagli. <a href="http://it.wikipedia.org/wiki/Pagina_
    principale">Wikipedia®</a> è un marchio registrato della <a href="http://www.wikipedia.
    org/">Wikimedia Foundation, Inc</a>
                            </pre>
                        </footer>
                    </article>
                </body>
            </html>
 
