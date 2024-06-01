<a name="br1"></a> 

**République Algérienne Démocratique et Populaire**

**Ministère de l’Enseignement Supérieur et de la Recherche Scientifique**

**Université des Sciences et de la Technologie Houari Boumediene**

**Faculté d’Informatique Département SQI**

***MASTER 1 SSI***

**PAPPORT PROJET SYSTEME D’EXPLOITATION**

***realisation d’un environnement de communication***

**réalisé par:**

● Aloui ikram 2020310 G2

● Djehaiche Maroua Fella 202031087068 G2

● Bentaleb ikram 191931080290 G1

● Abdeddaim Rania Farah 202031081335 G1

**1**



<a name="br2"></a> 

Introduction :

Un environnement de communication est une plateforme conçue pour faciliter l'interaction

entre les utilisateurs à travers diverses fonctionnalités. Cela va au-delà de l'échange de

messages, englobant la gestion des comptes utilisateurs, la publication de contenu, la

création et la gestion de groupes, ainsi que des options de communication tant publiques

que privées. Dans le cadre de ce projet, nous avons développé un site web d'environnement

de communication pour une communauté d'une entreprise en utilisant Django comme

framework principal, accompagné des langages de base du web tels que HTML, CSS, et

Bootstrap en tant que framework, ainsi que JavaScript.

● Django :

Est un framework web haut niveau, basé sur le langage de programmation

Python, qui facilite le développement rapide et propre de sites web. Il offre

une architecture MVT (Model-View-Template) qui organise le code de manière modulaire, il

intègre également des fonctionnalités de sécurité avancées.

● HTML, CSS, et JavaScript :

HTML est le langage de balisage standard utilisé pour structurer le contenu d'une

page web. CSS est utilisé pour styliser et mettre en forme ce contenu, tandis que

JavaScript ajoute des fonctionnalités dynamiques et interactives à nos pages web.

● Bootstrap :

Est un framework front-end open source qui simplifie le processus de conception en

fournissant une collection de composants pré-stylisés et réactifs.

**1. Gestion des comptes utilisateurs :**

1\.1 Compte administrateur:

L'administrateur, en tant qu'utilisateur privilégié au sein de notre environnement de

communication, assure une expérience sécurisée en gérant activement les comptes

utilisateurs. Ses responsabilités incluent la création de nouveaux comptes, la

modification des informations associées à chaque profil et la possibilité de supprimer

des comptes.

2\.2 Compte utilisateur:

L'utilisateur est un employé dans l'entreprise il peut ouvrir une session avec son

compte donner , modifier ces information telle que le nom et prénom, réinitialiser le

mot de passe , et de fermer la session de manière responsable une fois leurs activités

terminées.

**2. Gestion des groupes d’utilisateur:**

les utilisateurs ont la possibilité de créer des groupes personnalisés et de les nommer

selon leurs besoins spécifiques. Lorsqu'un utilisateur crée un groupe, il devient

automatiquement l'administrateur du groupe, doté de privilèges étendus. En tant

**2**



<a name="br3"></a> 

qu'administrateur du groupe, l'utilisateur a la capacité d'ajouter ou de supprimer des

participants ,modifiant le groupe ,et en cas de nécessité, l'administrateur peut

également supprimer le groupe.

3\. **Gestion des chats :**

**3.1 définition de websocket :**

WebSocket est un protocole de communication bidirectionnelle, en temps réel, qui

fonctionne au-dessus du protocole TCP. Il permet une communication instantanée

entre un client (généralement un navigateur web) et un serveur. Contrairement à

HTTP, qui suit un modèle de demande-réponse, WebSocket offre une connexion

persistante qui permet au serveur d'initier la communication vers le client ou vice

versa.

**3.2 Gestion des chats entre plusieurs utilisateurs (salle générale) :**

La fonctionnalité de salle générale dans la gestion des discussions entre

plusieurs utilisateurs est essentielle au sein d'une application de chat.

Cette salle, également appelée "genral room", constitue un espace de

communication partagé où tous les utilisateurs peuvent interagir

simultanément. Contrairement aux conversations privées, la salle générale

favorise une communication collective, encourageant ainsi l'interaction

commune et la formation d'une communauté virtuelle.

La salle générale agit comme un lieu de rencontre virtuel, permettant à

chaque utilisateur de participer aux conversations en cours. En

rassemblant l'ensemble des utilisateurs au sein de cet espace, elle favorise

la convivialité, la cohésion et la diffusion d'informations à grande échelle.

Cette approche crée un environnement dynamique et ouvert, propice à

des conversations fluides, contribuant ainsi à une expérience de chat

collaborative et enrichissante pour tous les participants.

La figure ci-dessous illustre notre general room :

**4. Gestion des publications :**

**3**



<a name="br4"></a> 

La gestion des publications offre aux utilisateurs une flexibilité accrue dans la

création et la gestion de leurs contenus. Chaque utilisateur a la possibilité de créer

des publications privées, qui seront visibles uniquement dans leur liste personnelle

de publications. Ceci permet aux utilisateurs de partager des contenus de manière

plus restreinte, idéale pour des informations spécifiques.

D'autre part, les utilisateurs peuvent également créer des publications publiques,

accessibles à l'ensemble de la communauté d'utilisateurs. Ces publications ont une

portée plus large, favorisant le partage d'informations et les interactions entre les

membres de la plateforme

Les fonctionnalités d'édition et de suppression sont également intégrées. Les

utilisateurs et le super-utilisateur ont le pouvoir de commenter dans les publications

des autres utilisateurs. Cependant, chaque utilisateur peut supprimer ses propres

commentaires. Pour assurer la qualité du contenu, l'administrateur peut créer des

publications de la même manière que les utilisateurs standards. Cependant, il

bénéficie d'une capacité exclusive de suppression, limitée aux publications des

utilisateurs. L’administrateur a également le pouvoir de supprimer les

commentaires, assurant ainsi un environnement respectueux et conforme aux

normes de la plateforme.

**4**



<a name="br5"></a> 

**Captures d’ecran de l’application:**

L’interface pour se

connecter

**5**



<a name="br6"></a> 

le Dashboard

contenant la liste des

users et en clickant

sur le SL on peut

modifier chaque user

ici on peut modifier le user

la liste des groupes ainsi que leurs gestion(creation, modification et suppression) on peut

aussi acceder au chats en clickant sur le bouton

**6**



<a name="br7"></a> 

pour ajouter un groupe:

ici on affiche la listes des chates public, en clickant sur le bouton chat, on acced au chat pour

discuter

le chates des groupes s’affichent dans la fenetre qui suit : en clickant sur le bouton chat, on

acced au chat pour discuter

**7**



<a name="br8"></a> 

la file des publications, on peut creer un nouveau post choisir son contenue et son privacy,

ainsi nous pouvons supprimer les posts, modifier les posts, commenter les posts et

supprimer cet commentaire

**8**



<a name="br9"></a> 

l’ajout d’un user (creation)

la navigation bar qu’on utiliser pour naviguer les pages présenté:

**9**



<a name="br10"></a> 

**pour executer le code :**

en executant dans le terminal:

● naviguer le fichier contenant le projet

● creer un environnement virtual : python -m venv nom-env

● activer l’environnement : nom-env\Script\activate

● installer ce qui est necessaire :

○ pip install django

○ pip install daphne

○ pip install pillow

○ pip install channels

● naviguer le fichier contenant le projet

● executer dans le terminal : python manage.py makemigrations

● executer dans le terminal : python manage.py migrate

● executer dans le terminal : python manage.py runserver

● acceder a l’address qui s’affiche dans le terminal et connecter vous en utilisant

le superuser .

superuser email : <admin@se.com>

mdp : admin

**10**


