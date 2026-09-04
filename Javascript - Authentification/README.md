
# Root-Me — Web Client : Javascript - Authentification

* **Catégorie :** Web Client
* **Challenge :** Javascript - Authentification
* **Difficulté :** Très facile

---

## 🎯 Objectif
S'authentifier sur le formulaire pour récupérer le mot de passe de validation.

## 🔍 Analyse
En inspectant les fichiers de la page via les outils de développement du navigateur (`F12` > onglet **Sources**), on retrouve le fichier d'authentification `login.js` à l'emplacement `/web-client/ch9/ch9/login.js`.
<img width="917" height="297" alt="Capture d&#39;écran 2026-09-04 181825" src="https://github.com/user-attachments/assets/f5cb7d7f-16cf-4623-818d-199243f0571b" />

Le code source contient la fonction de vérification suivante :

```javascript
function Login(){
    var pseudo=document.login.pseudo.value;
    var username=pseudo.toLowerCase();
    var password=document.login.password.value;
    password=password.toLowerCase();
    if (pseudo=="4dm1n" && password=="sh.org") {
        alert("Password accepté, vous pouvez valider le challenge avec ce mot de passe.");
    } else {
        alert("Mauvais mot de passe / wrong password");
    }<img width="717" height="142" alt="Capture d&#39;écran 2026-09-04 181917" src="https://github.com/user-attachments/assets/812c131e-ce73-472f-87f9-b10928432e2a" />

}

<img width="843" height="308" alt="Capture d&#39;écran 2026-09-04 181906" src="https://github.com/user-attachments/assets/46515f77-1215-4b4a-a404-44a756043d67" />
<img width="717" height="142" alt="Capture d&#39;écran 2026-09-04 181917" src="https://github.com/user-attachments/assets/e6958689-7a6f-4026-8170-79568f7761af" />
