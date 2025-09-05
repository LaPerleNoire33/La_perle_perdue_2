
<html lang="fr">

<head>

<meta charset="UTF-8">

<title>Indice Secret – Bunker</title>

<style>

body {

    font-family: 'Georgia', serif; /* Police type “lettre” */

    background-color: #f3e4d0; /* Fond beige clair / marron clair */

    color: #3e2f1c; /* Couleur texte foncée */

    padding: 40px;

}

#secret {

    display: none;

    font-style: italic; /* Texte en italique pour effet lettre */

    line-height: 1.8;

    max-width: 600px;

    margin: auto;

    border: 1px solid #cbb79b;

    padding: 20px;

    background-color: #fff3e0; /* Fond légèrement plus clair pour la lettre */

}

#login {

    text-align: center;

    max-width: 400px;

    margin: auto;

}

input {

    padding: 10px;

    font-size: 16px;

    margin-top: 10px;

}

button {

    padding: 10px 15px;

    font-size: 16px;

    margin-top: 10px;

    cursor: pointer;

}

</style>

<script>

function checkPassword() {

    var pass = document.getElementById("password").value;

    if(pass === "laperlenoire") { // Remplace MONCODE par ton mot de passe

        document.getElementById("secret").style.display = "block";

        document.getElementById("login").style.display = "none";

    } else {

        alert("Mot de passe incorrect !");

    }

}

</script>

</head>

<body>



<div id="login">

<h2>Entrez le code pour accéder à l'indice</h2>

<input type="password" id="password" placeholder="Votre code">

<br>

<button onclick="checkPassword()">Valider</button>

</div>



<div id="secret">

<h2>23 décembre 2018</h2>

<p>Me voilà assis sur ce banc, après quarante ans de recherches. Je n’ai jamais réussi à remettre la main sur cette perle. Mon amour… j’aimerais te délivrer de ce mauvais sort, mais ma tête me fait défaut.

Je me rappelle avoir caché des indices près de la cabane, au bord du Bassin, là où nous avions l’habitude de nous retrouver dans notre jeunesse. J’ai cherché, cherché et cherché encore, mais les indices me manquent, je n’arrive plus à les retrouver.


Je sais qu’ils peuvent m’indiquer le chemin de la perle, mais impossible d’y mettre la main dessus. Aujourd’hui, sur ce banc, tu me manques plus que jamais.


Après ces quarante années de recherches, malheureusement, mes forces me manquent. Je ne suis plus capable de continuer cette quête. Je viens te rejoindre, en espérant secrètement qu’une personne prendra le relais et réussira à nous libérer.
</p>
