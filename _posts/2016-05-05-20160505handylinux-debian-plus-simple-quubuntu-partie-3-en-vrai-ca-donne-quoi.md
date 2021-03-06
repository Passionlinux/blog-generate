---
title: Handylinux; Debian plus simple qu'Ubuntu ! En vrai, ça donne quoi ?
date: 2016-05-05 20:09
layout: post
---

<header class="cartouche">
<div class="postmeta">

</div>

</header>
<div class="main">

<div class="chapo surlignable">

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/wiki-handypn458d.png)

<p>
La première fois que j’ai entendu parlé de cette distribution fut sur le
forum de [MLO](http://www.mageialinux-online.org/mlo/){.spip_out}, un
habitué annonçait la sortie de sa version 1.X. J’ai aussi entendu parlé
d’elle sur les forums de debian (surtout
[debian-facile](https://debian-facile.org/){.spip_out}). Puis [Frederic
Bezies](http://frederic.bezies.free.fr/blog/){.spip_out} en a aussi
souvent parlé et enfin sur le blog de [Cyrille
Borne](https://www.cyrille-borne.com/){.spip_out}.  

</div>

<div class="texte surlignable">

<div id="outil_sommaire" class="cs_sommaire cs_sommaire_avec_fond">

<div class="cs_sommaire_inner">

### Introduction {#introduction .cs_sommaire_titre_avec_fond .cs_done}

</div>

</div>

Je vais parler d’un cas concret, en l’occurrence du miens. Pour la
petite histoire, mon oncle avait encore une xubuntu 14.04 sur un vieux
Acer Athlon XP avec 1Go de ram, tout allait plus ou moins bien sauf que
l’ensemble était diablement lourd par rapport a la wheezy Xfce qui était
dessus auparavant. Donc il était prévu de retourner sur debian, la
xubuntu permettait de gagner un peu de temps, car soyons franc, debian
avec xfce est très dépouillé et beaucoup de travail reste a faire pour
rendre l’ensemble totalement opérationnel, comme par exemple les images
qui s’ouvrent avec iceweasel ou « photoprint » au lieu de ristretto, les
pdf avec gimp ou « aperçu avant impression » et bien d’autre
incohérence…

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20menu7c54.png)

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20menu0cc7.png)

Pour tout dire j’étais pas convaincus de la nécessité de cette
distribution mais faut dire que j’ai déjà du bagage sur debian et pour
être totalement franc, je m’attendais un énième truc a la
[lmde](https://www.linuxmint.com/download_lmde.php){.spip_out}, un truc
qui se base sur ses propres dépôts et qui en fin de compte s’éloigne de
sa base. Mais pas du tout, c’est une pure debian avec quelques paquets
plus récent ou non présent dans les dépôts debian, rien de plus.  
<!--more-->

### Debian et ses qualités/défauts {#outil_sommaire_1 .spip}

J’avais donc cette idée de faire repasser mon oncle sur une debian, avec
xfce, pour les raisons que je cite habituellement, mais je vais les
répéter :

-   stabilité de la distribution
-   stabilité des dépôts
-   stabilité des fonctions des logiciels
-   tranquillité sur le long terme en ayant au minimum 2ans de support
-   légèreté qui permet de faire tourner de vieilles machines
-   dépôt complet contenant des milliers de logiciels
-   grosse communauté
-   grosse documentation
-   plusieurs forums
-   …

Le défaut de debian, dans sa version xfce, est la finition, il n’y en a
aucune, pas d’intégration des logiciels kde (manque les paquets
d’integration kde/gtk) ou avec ceux de gnome, fichiers qui s’ouvrent
dans les mauvais programmes (images qui s’ouvrent dans un navigateur
web, les pdf s’ouvrent dans gimp,...) il manque des paquets pour
certaines utilisations, la police(font) qui éclate les yeux et bien
d’autre, …

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20jeu2d0f2.png)

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20look9ec3.png)

On remarque bien sur cette capture ce que je veux dire. Tout est
configurable bien sur mais c’est du taff en plus que d’autres
distributions font a notre place comme [Xubuntu par
exemple](http://xubuntu.org/){.spip_out}.  

### Handylinux entre en jeu, téléchargement et installation {#outil_sommaire_2 .spip}

C’est la que la [Handylinux entre en
jeu](https://handylinux.org/){.spip_out}, c’est une debian (je me répète
ça doit être l’age), avec xfce pour pouvoir tourner aussi bien avec des
machines récentes que anciennes, qui mise sur l’accessibilité pour les
personnes ayant des soucis et surtout la simplicité permettant même a
ceux qui n’ont jamais utilisé de pc, la possibilité d’avoir un système
qui a pensé a eux.

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/handylinux_d5734.png)

J’ai donc [téléchargé la
Handylinux](https://handylinux.org/wiki/doku.php/fr/download){.spip_out}
pour la mettre en condition réelle et la tester par moi même. Avec une
idée en tête, trouver un défaut qui la recalerait par rapport a une
debian pure, un faux pas, le moindre petit truc… Pour ce faire, je l’ai
testé sur plusieurs machines :

-   une très vieille qui a 256mo de ram et une carte graphique savage3,
    c’est un pc portable de marque siemens, un amilo…
-   sur un packard bell easynote (portable) de 512mo de ram avec wi-fi,
-   et enfin un pc portable plus moderne, un petit HP de 3go de ram avec
    wi-fi et Bluetooth.

L’iso fait 1,3go ce qui en fait une iso pour dvd, mais pour les vieux pc
qui ne lisent pas les dvd on peut charger une [version
light](https://handylinux.org/wiki/doku.php/fr/handylinuxlight){.spip_out}
qui doit par contre être connecté au réseau pour avoir la totalité des
paquets, ou sinon il faudra graver un autre cd pour les paquets non
compris dans le 1^er^ cd si on a pas accès au réseau. Après la gravure
on lance l’installation (voir
[l’article](http://passiongnulinux.tuxfamily.org/?p=58){.spip_in} , une
installation qui rappel celle de
[debian](http://passiongnulinux.tuxfamily.org/?p=53){.spip_in}, oui
c’est bien le même installateur…

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/handy_instalf0c4.png)

Alors c’est sur que c’est moins jolie que celle d’une
[ubuntu](https://doc.ubuntu-fr.org/tutoriel/installer_ubuntu_avec_le_live_cd){.spip_out}
ou d’une
[mint](http://lea-linux.org/documentations/Installer_Linux_Mint_12){.spip_out}
voir manjaro, mais a contrario, c’est fiable et fonctionnel !!! Donc
c’est l’installateur debian qui fait le boulot et pour l’occasion il
arbore les couleurs d’Handylinux, il ne change pas, il reste simple et
efficace, il demande pas le mot de passe root et passe directement au
premier utilisateur qui aura les pleins pouvoirs via sudo. Ensuite c’est
le partitionnement, il est automatique par défaut avec un home non
séparé de la racine, mais on peut très bien le séparé en choisissant
« manuel ». Puis une fois accepté, pas de choix des environnements ou
des services a installer, c’est la copie du système qui se lance. Notez
que je parle de copie du système et non de l’installation du système,
ici c’est le système contenu dans le cd qui se copie et non
l’installation des paquets, ce qui rend l’installation bien plus rapide,
faudra compter moins de vingt minutes au lieu du double avec une
installation classique.

<div style="text-align: center;">

<iframe src="https://player.vimeo.com/video/122423367" width="640" height="480" frameborder="0" allowfullscreen="allowfullscreen">
</iframe>

</div>

Le dvd s’éjecte et on nous demande de confirmer le redémarrage…  

### Premier lancement {#outil_sommaire_3 .spip}

C’est la qu’on s’aperçoit du travail de simplification fait par
l’équipe, a commencer par les drivers, que ce soit le wifi, les cartes
graphiques ou le Bluetooth, tout est reconnu et sans rien faire, j’ai
regardé le pourquoi du comment, en faite a l’installation, les pilotes
sont aussi de la partie, ainsi firmware-nonfree et autre pilote wifi
sont installé. Donc j’ai pas eu de soucis ni pour mes imprimantes hp qui
ne posent jamais de problèmes ou par la suite, l’imprimante epson de mon
oncle qui me fait des galères habituellement sur mageia. Sur les trois
portables, le wifi a été reconnue, que ce soit les wifi interne ou en
usb pour le plus vieux. La résolution fut la bonne sur tous. Tout ça
sans rien faire, ce qui m’a fait gagné du temps. Les maîtres mots sont
bien accessibilité et simplicité, xfce est dans une forme a la windows
(1 seule barre qui se trouve en bas), un thème d’icône avec code
couleurs qui a vue d’œil permet de reconnaître les applications
« système » des autres, des icônes qui sont facilement interprétable.

<div style="text-align: center;">

<iframe src="https://player.vimeo.com/video/127889810" width="640" height="400" frameborder="0" allowfullscreen="allowfullscreen">
</iframe>

</div>

Comment parler d’Handylinux sans parler de son menu **Handymenu** qui
fait partie d’une liste d’applications spécialement faite par l’équipe
de devs pour simplifier cette distribution, il est simple, modifiable
mais par défaut comporte les principales fonctionnalités (multimédia,
bureautique, jeux, …).

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/handymenu4-df6dc.png)

<div style="text-align: center;">

<iframe src="https://player.vimeo.com/video/153305094" width="640" height="400" frameborder="0" allowfullscreen="allowfullscreen">
</iframe>

</div>

Comment ne pas parler aussi de ces applications qui ont été fait par
l’équipe pour faciliter la vie, comme **Handytri**, un petit outil de
tri automatique. En effet, il arrive que certains dossiers soient vite
pleins de fichiers divers et variés.

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/autotri_lancbc67.png)

L’interface simple vous propose de choisir le dossier à trier puis de
cocher les layouts de fichier que vous désirez trier :

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/autotri_choidede.png)

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/autotri_choidc82.png)

Les fichiers sont classés selon l’extension (“.png”, “.doc”, “.txt”,
etc) et envoyés dans les dossiers “Images”, “Documents”, “Musique” et
“Vidéos”. Ou **liveUSBcreator** qui sert, comme son nom l’indique, a
transférer facilement une image de layout ISO sur une clé USB, créant
ainsi un liveUSB :

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/appfinder-lif571.png)

Ou bien **Info4forum** qui vous permet de recueillir des informations
sur votre système, de les éditer, et de les copier-coller sur le forum
afin d’obtenir de l’aide :

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/info4forumpnd90a.png)

Ou encore **HandyTheme**, qui change simultanément la police utilisée,
le thème GTK (celui de l’intérieur des fenêtres), les décorations de
fenêtres, la taille du curseur et votre fond d’écran.

<div style="text-align: center;">

<iframe src="https://player.vimeo.com/video/124065070" width="640" height="382" frameborder="0" allowfullscreen="allowfullscreen">
</iframe>

</div>

Comme évoqué plus haut, les icônes ont un code couleur, je n’arrive pas
a retrouver le lien qui parlait de ce code couleur, mais de mémoire
c’était le rouge pour les applications systèmes comme synaptic et mise a
jour, bleu pour le web c’est a dire firefox, thunderbird (icedove)…  
Handylinux c’est aussi le plein de programmes visant l’accessibilité,
comme le Lecteur d’écran ORCA ou la loupe… Bref, tout est fait pour
faciliter la vie du nouveau venu !

![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/access-menup6595.png)

Et comment ne pas parler de ce [forum
réactif](https://handylinux.org/forum/){.spip_out} et dont le maître mot
est simplifier, de cette [documentation abondante et
compréhensible](https://handylinux.org/wiki/doku.php/fr/start){.spip_out}
accessible aussi dans notre dossier personnel et ainsi que de ces
nombreux [tutoriels](https://handylinux.org/tutos/){.spip_out}.  

### Reconnaissance matériel {#outil_sommaire_4 .spip}

Ce qui connaissent debian savent parfaitement que celle ci mise sur la
liberté, du coup ne fournit pas les drivers non-free pendant
l’installation et peut poser des soucis avec certains matériels comme le
wifi, Bluetooth et pareils pour les codecs… Bien sur, tout les drivers
et codecs nécessaires sont disponible dans les dépôts a condition
d’avoir activé les dépôts non-free. Sous handylinux, non seulement les
dépôts non-free sont déjà activé par défaut, mais en plus, les codecs et
les drivers non libres sont déjà installés !  
Aucuns soucis n’a été détecté pendant mes essaies, tout a été reconnue,
que ça soit les carte wifi, les usb wifi, les imprimantes, les webcams,
les scanners, tout de tout.  

### Cas congret : mon oncle {#outil_sommaire_5 .spip}

Alors voila, le pc comme vu plus haut est un vieux coucou, un acer
aspire avec un athlon xp64 de 1go de ram avec carte nvidia (legacy) avec
vista comme système d’origine, c’est pas de première fraîcheur mais je
suis assez radin et je ne suis pas pour le changement systématique d’un
truc qui fonctionne encore. Debian wheezy avec xfce fut très bien en son
temps pour remplacer la ubuntu 10.04 que j’avais mis auparavant. Puis
j’avais remplacé la wheezy par une mageia xfce et par la force des
choses (mageia 5 apporta pas mal de soucis) par xubuntu pour gagner du
temps car comme je le dis, xfce sous debian n’est pas fignoler et ça
peut prendre du temps avant d’avoir l’équivalent de xubuntu. Mais c’est
un fait, la famille ubuntu est lourde et pousse au changement de
matériel un peu comme windows, xubuntu n’est pas en reste et pour une
distribution avec xfce, elle est assez lourde (aussi bien qu’en
sensation qu’en consommation de ram et de processeurs). Du coup la
nécessité de repasser a debian s’est fait sentir, jessie ayant corrigé
ses problèmes de jeunesse, fut la candidate approprié mais je reviens
sur le soucis de finition, donc je me suis tourné sur la distribution
qu’on cite de partout, la handylinux !!! Le téléchargement de l’iso est
rapide, 1.3go de donnée avec la fibre c’est même pas 1 minute, on grave
sur un dvd et on lance. Après avoir vérifié avec le live que tout se
passait bien, je lance l’installation et en 10 ou 15 minutes tout était
fait. On reboote, on installe les applications qui manquent a mon oncle,
principalement les jeux de kde car tout le reste est déjà présent, que
ce soit vlc, firefox, thunderbird(icedove), les codecs, les firmwares,
gimp, … bref tout est déjà la, je rajouterais même que les divers
utilitaires spéciales handy ont eu un succès. L’imprimante 3en1 epson
qui m’a tant causé de soucis sous mageia est reconnue sans rien faire,
la webcam aussi, les téléphones portables sous androides ou les
appareils photo aussi… L’intégration des applications qt (kde) est
opérationnel, la police (ou fonts) est de bonne taille et grasse ce qui
permet de bien lire, le thème d’icône est clair et facile a interpréter
ainsi que le thème de l’environnement. J’ai rien eu a faire si ce n’est
que l’ajout de kdegames.  
Il n’y a pas photo par rapport a debian :

**Debian**![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20look9ec3.png)

**Handylinux**![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/handylinux20f2dd.png)

**Thunar sous
Debian**![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/debian20menu0cc7.png)

**Thunar sous
Handylinux**![](http://download.tuxfamily.org/passionlinux/IMG/distant/png/handylinux20a596.png)

Si a ce moment je devais résumer et comparer avec debian, je dirais que
j’ai déjà gagné 30min sur le temps que prend l’installation de handy par
rapport a debian, que j’ai gagné du temps sur la mise en place des
dépôts nonfree/contrib et sur la mise a jour et l’installation des
paquets manquant, c’est a dire icedove, vlc, les codecs, les firmwares,
l’intégration…, je pense avoir gagner une dizaine de minutes sur ça.
Enfin j’ai gagner beaucoup de temps sur la configuration pour la vue de
mon oncle, c’est a dire adapter le look de xfce pour le mettre a la
windows, un thème de fenêtre simple et visible (rouge pour fermer, vert
pour agrandir…), des icônes reconnaissable d’un coup, une police de
bonne taille, installation et la configuration de redshift (filtre
d’ecran), installation de loupe, tout ça doit bien représenter aussi dix
minutes facilement… J’ai du gagner pas loin d’une heure minimum.  
Mon oncle a trouvé son pc bien plus vivace et rapide qu’avant, il est
content et s’est inscrit au forum de la handy.  

### Mot de la fin {#outil_sommaire_6 .spip}

Vous l’aurez compris, je suis conquis par cette distribution, enfin une
qui mélange la stabilité de debian, car oui c’est une debian pure, avec
la simplicité qu’on peut trouver sur les mageia, ubuntu et autre
manjaro… Enfin une debian utilisable out of the box, une debian avec une
finition irréprochable, avec un choix d’applications couvrant les
principaux besoins. Une distribution qui ne laisse personne sur le bord
de la route, ni ceux qui débutent en informatique, ni les pros de
l’informatique, ni les âgés, ni les plus jeunes, ni ceux ayant des
problèmes de vision. Bref, une distribution adapté a tous et je la
recommande pour tous.

</div>

</div>
