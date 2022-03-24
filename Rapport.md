# DoodleStudent

## Accès à l'application
L'application est accessible en suivant ce [lien](http://tufe.diverse-team.fr:8085/)

## Binôme
* Clément BRIAND <clement.briand@etudiant.univ-rennes1.fr>
* Jules DURAND <jules.durand@etudiant.univ-rennes1.fr>

## Tâches
### Tache 0
Nous avons créé une VM à l'ISTIC en demandant le sous domaine _tufe_.
### Tache 1
Deux dockerfiles ont étés créés, ils sont présents à la racine du projet.
Un fichier docker-compose.yml a aussi été créé afin de permettre le déploiement de l'application.
### Tache 2
La configuration de bunkerized-nginx est stockée dans le fichier api.conf. Aussi des configurations ont étés ajoutés dans le docker-compose de l'application pour paramètrer le proxy.
### Tache 3
En raison du blocage des VM à cause des failles Log4j, l'application n'a pas encore été déployé sur notre VM ISTIC.
### Tache 4
![](C:\Users\User\IdeaProjects\doodlestudent\images\tache4.png)
### Tache 5
Le fichier .github/workflows/doodlestudent.yml contient le paramétrage de la chaine d'intégration continue de l'application.
Sous reserve de modification lors de l'avancé du projet, nous l'avons paramétré pour qu'une pipeline s'execute à chaque push sur la branche principale du projet: main. Le lancement d'une pipeline par action manuelle reste possible, par la présence du trigger de lancement `workflow_dispatch:`.
Nous avons également instancié un runner github sur notre poste, le dossier actions-runner contient en local les paramétrages de ce runner.
### Tache 6
Nous avons ajoutés prometheus et grafana aux services lancés par notre docker-compose.
### Tache 7
Nous avons essayé de faire cette partie mais en raison d'un manque de temps et de difficultés à installer microk8s sur nos Windows (L'utilisation des VM ISTIC étant compliquée en raison des blocages) nous ne sommes plus allés plus loin.