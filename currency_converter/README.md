# Currency Converter

Currency Converter est une application web simple qui permet aux utilisateurs de convertir des montants d'une devise à une autre en utilisant les taux de change actuels.

## Pour les développeurs

### Prérequis

- Un navigateur web moderne (Chrome, Firefox, Safari, Edge, etc.)
- Un éditeur de texte (VS Code, Sublime Text, Notepad++, etc.)

### Configuration et exécution locale

1. Clonez le dépôt ou téléchargez les fichiers du projet (index.html, style.css et sketch.js) sur votre ordinateur local.

2. Ouvrez le fichier `index.html` dans votre navigateur web. L'application devrait se charger et être prête à être utilisée.

3. Pour modifier le code, ouvrez les fichiers HTML, CSS et JavaScript dans votre éditeur de texte préféré. Les modifications seront visibles en actualisant la page dans votre navigateur.

## Pour les utilisateurs

### Comment utiliser l'application

1. Ouvrez l'application dans votre navigateur web.

2. Sélectionnez la devise d'origine dans le premier menu déroulant.

3. Entrez le montant que vous souhaitez convertir dans le champ de saisie associé à la devise d'origine.

4. Sélectionnez la devise cible dans le second menu déroulant.

5. Cliquez sur le bouton "Result" pour effectuer la conversion. Le montant converti s'affichera dans le champ de saisie associé à la devise cible.

6. Pour inverser les devises, cliquez sur l'icône de swap située entre les deux champs de saisie. Les devises et les montants seront échangés, et les taux de change affichés seront mis à jour.

### Remarque

Cette application utilise l'API `https://api.exchangerate.host` pour récupérer les taux de change actuels. Les taux de change sont basés sur la devise USD par défaut. Si vous souhaitez changer la devise de base, modifiez la variable `requestURL` dans le fichier `sketch.js`.
