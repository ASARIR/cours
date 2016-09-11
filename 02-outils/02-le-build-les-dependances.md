# Le build et la gestion des d�pendances
## Contenu et utilit�

Le build couvre les diff�rentes �tapes suivantes:
* la mise � jour et le t�l�chargement des d�pendances
* la constitution des binaires utiles pour le d�ploiement
* le lancement des diff�rentes suites de test : ( unitaire, int�gration, acceptation)
 
Il peut par ailleurs dans certains cas inclure des t�ches de d�ploiement du code et/ou des utilitaires utilis�s pour des actions r�p�titives dans les travaux de d�veloppement. 
Comme �voqu� pr�c�dement, l'objectif est d'automatiser ce qui peut l'�tre pour que le temps soit le plus possible pass� sur les activit�s g�n�ratrices de valeur : le d�veloppement proprement dit.

## Choix du syst�me de build

Le choix du syst�me de build est tr�s fortement influenc� par le choix du framework et de la technologie de d�veloppement.
En effet chaque langage/framework est livr� avec son build, le choix est donc assez restreint.

## Quelques logiciels de build/gestion de d�pendance

Selon le langage et le framework, parfois la gestion des d�pendances est externalis�e par rapport au build proprement dit.
Selon les cas, il peut arriver que le m�me fichier/logiciel de build remplisse les deux fonctions

| langage                 | Build                                 |
|-------------------------|---------------------------------------|
| [ruby][0] / [rails][1]  | [rake][2], [bundler][3], [gem][4]     |
| java / [spring][5]      | [maven][6], [gradle][7] , ant         |
| nodejs                  | npm, gruntjs                          |
| groovy / [grails][8]    | [gradle][7]                           |
| scala / [play][9]       | sbt                                   |

## La morale de l'affaire:

![pourquoi faire simple quand c'est si simple de faire compliqu�](http://img3.bibamagazine.fr/var/bibamagazine/storage/images/media/images/culture/20150505-10-citations/les-shadoks-8/292381-1-fre-FR/Les-Shadoks-8_max1024x768.jpg)


Utiliser un syst�me de build li� � son �cosyst�me de d�veloppement **peut au premier abord para�tre inutile** : en effet on pourrait tr�s bien tout faire � la main ?? 

**FAUX : il y a une vie apr�s l'UV de LPA2 !!! si vous devez reprendre le code 6 mois plus tard, vous ne vous rappelerez plus de comment tout installer.** Mieux vaut passer quelques heures de plus sur le sujet aujourd'hui et s'�pargner des jours plus tard.

Suite [L'int�gration continue](03-integration-continue.md)

[0]:https://www.ruby-lang.org/fr/
[1]:http://rubyonrails.org/
[2]:http://rake.rubyforge.org/files/doc/rational_rdoc.html
[3]:http://bundler.io/
[4]:https://rubygems.org/
[5]:https://spring.io/
[6]:https://maven.apache.org/
[7]:https://gradle.org/
[8]:https://grails.org/
[9]:https://www.playframework.com/