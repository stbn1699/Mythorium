
# présentation du bot
le robot, Tupperbox, permet lorsqu'on envoie un message, de mettre un nom et une photo de profil différente de la notre afin de pouvoir jouer plusieurs personnages. 

le fonctionnement est simple, le robot va analyser tout les messages, et si par exemple j'ai créé un personnage du nom de thomas et que j'ai dit au robot que si le message commence par `tho:` (qui s'appelle un "Bracket") cela signifie que c'est thomas qui parle, et bien le robot va supprimer mon message, pour le réécrire avec le nom et la photo de profil de thomas !

# comment s'en servir
## créer un personnage :

pour créer un personnage, il faut écrire un message que le robot va comprendre, prenons l'exemple d'un personnage s'apellant thomas il faudra alors dire au robot le nom du personnage, ainsi que ce par quoi doit commencer le message pour que le robot comprenne donc, pour l'exemple de thomas que j'ai donné dans le 4.1, il suffira d'écrire : `tul!register '[nomDuPerso]' [Bracket]:text` en remplaçant bien sur `[nomDuPerso]` et `[Bracket]` par ceux désirés (dans notre cas, le message sera donc : `tul!register 'thomas' tho:text`) et surtout ne pas oublier de mettre l'image de la photo de profil du personnage directement en même temps que le message (pas dans deux messages différents) et voila ! votre personnage est créé ! vous pouvez l'essayer en tapant `[Bracket]: hello world` dans la conversation ! bien sur, le nom du perso ainsi que le texte a mettre avant sont personnalisable.

## 4.3 automatiser le robot

mettre `[Bracket]:` avant chaque message quand on rp c'est chiant, donc on a une solution : automatiser le robot ! en effet, on peut dire au robot qu'il réécrive tout nos messages, tous sauf ceux ou on précise le personnage avant (exemple, si je l'automatise avec thomas et que j'écris `bonjour tout le monde`, le robot va le réécrire avec le personnage de thomas, mais si je dis par exemple `eli: bonjour tout le monde` et que j'ai un personnage du nom de eliot dont le bracket est `eli:`, le robot va écrire avec eliot et non thomas) pour ce faire, il suffira de taper `tul!auto [nomDuPerso] #[nomDuSalon]` en remplaçant bien sur `[nomDuPerso]` et `[nomDuSalon]` par ceux désirés

## 4.4 modifier et supprimer un message

**pour modifier un message :** 
il suffit de mettre l'emoji 📝 en réaction au message, @Tupperbox va vous écrire en privé, vous allez alors devoir réécrire le message 

**pour supprimer un message :** 
il suffit de mettre l'emoji ❌ en réaction