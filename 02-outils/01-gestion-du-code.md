# La gestion du code: [le CVS](https://en.wikipedia.org/wiki/Version_control)
## L'enjeu :
Pour un d�veloppeur et plus g�n�ralement pour une entreprise r�alisant des d�veloppements, le code et au travers lui les fonctionnalit�s qu'il permet sont sa richesse.
**Pour un d�veloppeur, la seule activit� "rentable" est de produire du code.**

Les autres activit�s d'un d�veloppeur ne rapportent pas d'argent ! 
* g�n�rer des livrables
* installer des environnements
* d�buguer 
* d�ployer des applications 
 
Ces activit�s sont certes obligatoires, mais aucun utilisateur ne va par exemple payer une fonctionnalit� si l'application n'est pas d�ploy�e pour qu'il l'utilise. 
Par contre, l'utilisateur ne paye pas pour une installation, il paye une fonctionnalit�.

La production du code et donc sa gestion sont donc le processus clef. Tout le reste est r�duit au strict minimum, car non source de valeur ajout�e.

## Les outils d'hier et d'aujourd'hui:
Auparavant les gestionnaires de source permettaient une gestion "simple" du code source : exemple CVS, SVN.
Pas d'interaction particuli�re: on versionne et on sauvegarde du code en mode 'en ligne'.

Aujourd'hui les outils ont �volu� vers du mode hors ligne avec la possibilit� de versionner et de g�rer du code m�me lorsque le PC n'est pas au r�seau. 
Tous les gestionnaires de code proposent maintenant une tr�s forte int�gration avec les syst�mes de gestions de bug, ainsi qu'une forte composante sociale. 
Le d�ploiement continu constitue maintenant la colonne vert�brale de ces syst�mes.

### Quelques outils modernes pour la gestion du code :
* http://github.com
* https://bitbucket.org/
* https://about.gitlab.com/
 
[Le build et les d�pendances](./02-le-build-les-dependances.md)