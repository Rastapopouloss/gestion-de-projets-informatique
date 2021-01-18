Déployer une application:

4 `vercel -v`

5 `vercel init angular`

6 `vercel`

7 `vercel ls`

8 `vercel logs gestion-de-projets-informatique-p8l0hqimg.vercel.app`

10 Les variables d'environnement permettent d'injecter des valeurs que l'on ne souhaite pas placer directement dans le code source et de modifier son comportement en fonction de l'environnement dans lequel il s'exécute.

11 `vercel env plain variable`

13 `vercel env ls`

14 Les variables secrètes sont cryptées et fournissent un moyen sûr de stocker et de partager des informations sensibles entre les déploiements.

13 `vercel secrets add secret_variable 1`

16.1 Production, Preview, Development

16.2 Chaque environnement ne se déploit pas au même moment.

     On peut choisir Development pour n'avoir les variable qu'en local, Production pour avoir les variables lors du déploiements en production, Preview pour les avoirs lors de déploiements de démonstrations.
     
18 https://gestion-projet-voisin.vercel.app/

19 Une pull request permet proposer des changements au responsable du dépôt. Le responsable du dépôt a la possibilité d'examiner les modifications et de les accepter, de les rejeter ou de demander que d'autres modifications soient apportées.

<img width="450" alt="Push Branch" src="https://user-images.githubusercontent.com/74765462/104932622-1fedfb80-59a8-11eb-899d-05a332191c99.PNG">

Vercel détecte automatiquement une pull request et créé un déploiment de type Preview

20 Vercel a créé un nouveau déploiment de type production
