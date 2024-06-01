/* ---------- Copy button ----------*/

function myFunction() {
    // Sélectionne l'élément h1 contenant l'adresse e-mail
    var emailElement = document.querySelector('.monmail');

    // Crée une zone de texte temporaire pour copier le contenu de l'e-mail
    var tempInput = document.createElement('textarea');
    tempInput.value = emailElement.textContent;

    // Ajoute la zone de texte temporaire à la DOM pour pouvoir copier son contenu
    document.body.appendChild(tempInput);

    // Sélectionne le contenu de la zone de texte temporaire
    tempInput.select();

    // Copie le contenu sélectionné dans le presse-papiers
    document.execCommand('copy');

    // Supprime la zone de texte temporaire de la DOM
    document.body.removeChild(tempInput);

    // Vous pouvez également ajouter une notification ou effectuer d'autres actions après la copie
    alert('Adresse e-mail copiée : ' + tempInput.value);
}
