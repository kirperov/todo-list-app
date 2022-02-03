
## Sommaire


1.  **[Utilisation](/todo-list-app/no_tech_use)** \
1.1 *Introduction* \
1.2 *Ajout d'un todo* \
1.3 *Édition d'un todo* \
1.4 *Suppression d'un todo* \
1.5 *Marquer comme complété*
2.  **[Fonctionnement technique de l'application](/todo-list-app/tech_use_controller)** \
1.1 *[app.js et controlleur.js](/todo-list-app/tech_use_controller)* \
1.2 *[model.js](/todo-list-app/tech_use_model)* \
1.3 *[store.js](/todo-list-app/tech_use_storejs)* \
1.4 *[template.js](/todo-list-app/tech_use_template)* \
1.5 *[view.js](/todo-list-app/tech_use_view)*
3.  **[Audit](/todo-list-app/tech_use_audit)**

---

**Audit de l’application “Todo list app”**

Auteur: Kirill Petrov
Date de modification: 03/02/2022
Version: 0.1


L’application est très réactif au terme de performance. Aucun ralentissement n’est pas observé. L’utilisation de l’application se fait très simplement et intuitif. Le design est très épurée et moderne ce qui donne plus de confort lors d’utilisation.

---

**1. Performance**

La performance est très haute selon l'audit.


![First](https://raw.githubusercontent.com/kirperov/todo-list-app/main/docs/images/todo_list_app_audit/performance/capture.JPG)

---

**2. Resultat de la performance**

![Second](https://raw.githubusercontent.com/kirperov/todo-list-app/main/docs/images/todo_list_app_audit/performance/capture2.JPG)


*Point négatif*

pas de `<meta name="viewport">` tag with `width` ou `initial-scale`

*Points positifs*

 - Minification de java script
 - Minification de CSS
 - Execution de java script rapide

---

**2. Accessibilité**

![accessibility](https://raw.githubusercontent.com/kirperov/todo-list-app/main/docs/images/todo_list_app_audit/accessibility/Capture.JPG)

*Points positifs*

 - Les id's uniques
 - Les éléments du formulaire ont les labels associés

---

**3. Les bonnes pratiques**

![best practices](https://raw.githubusercontent.com/kirperov/todo-list-app/main/docs/images/todo_list_app_audit/best_practices/Capture.JPG)

*Points positifs*

- Une politique de sécurité du contenu (CSP) solide réduit considérablement le risque d'attaques de script intersite (XSS)
- Utilisation de https

*Point négatif*

  - Retour des erreurs dans la console
Source du fichier: /learn.json:1

Erreur: `Failed to load resource: the server responded with a status of 404 ()`

 ---

**4. SEO**

![best practices](https://raw.githubusercontent.com/kirperov/todo-list-app/main/docs/images/todo_list_app_audit/seo/capture2.JPG)


*Point positif*

Le lien hreflang indiquent aux moteurs de recherche quelle version d'une page ils doivent répertorier dans les résultats de recherche pour une langue ou une région donnée.

*Point négatif*

Pas de tags meta description
