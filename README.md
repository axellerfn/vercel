4) 
vercel -v

5) 
vercel init

6)
vercel

7)
vercel list

8)
vercel logs https://td-gestion-e7babak7w.vercel.app

9)
vercel inspect https://td-gestion-e7babak7w.vercel.app
vercel inspect + url deploiement
La commande "vercel inspect" est utilisée pour récupérer des informations sur un déploiement.

10)
Une variable d'environnement est une valeur dynamique, chargée en mémoire, pouvant être utilisée par plusieurs processus fonctionnant simultanément. 
Sur la plupart des systèmes d'exploitation, les emplacement de certaines librairies, voire des principaux exécutables du système peuvent avoir un emplacement différent selon l'installation.
Ainsi, grâce aux variables d'environnement, il est possible, à partir d'un programme, de faire référence à un emplacement en s'appuyant sur les variables d'environnement définissant ces données. 

11)
vercel env add plain ENV_VAR production

12)
vercel env ls

13)
Les secrets permettent de stocker des informations partagées sur plusieurs projets ou de stocker des informations sensibles 
car elles sont cryptées.

15)
vercel secret add secret2 value 
vercel env add secret ENV_SECRET2 production
et on écrit secret2 à la question

16)
production, preview, development
Ils nous permettent de décomposer le travail sur le projet et de pouvoir modifier un environnement sans changer les autres.
exemple : tester des modifications dans preview en laissant production fonctionnel s'il y a des erreurs.

18)
https://vercel-two-gamma.vercel.app/
reçu par mail :
vercel.axellerfn.vercel.app
vercel-git-master.axellerfn.vercel.app
vercel-two-gamma.vercel.app

19)
Un pull request permet de demander à l'administrateur du projet git s'il autorise 
ou non les modifications et les merge sur la branche cible. 
Souvent des tests sont lancés avant de merge les deux branches.

Vercel créé automatiquement une réponse au pull request en montrant ce que les changements
impliqueraient et deploie l'environnement preview.

20)
Au moment du merge, de l'acceptation de la pull request, l'environnement production
est déployé.
On voit bien la succession des deploiement dans longlet environnement situé à 
droite à l'origine du projet.






