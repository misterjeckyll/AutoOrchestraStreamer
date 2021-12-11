**Fichier de description**

Fonctionnement :

Ce fichier décrit les indice visuels à générer automatiquement sur la vidéo pour faciliter la
synchronisation avec le conducteur d'un morceau d'orchestre.

Format à respecter :

Sections principales

    Une section principale commence par un # suivi du timecode corespondant dans la vidéo. 
    le timecode doit s'écrire au format MM:ss:m (M minute, s seconde, m milisecondes) et doit être unique
    Le texte qui suit sera affiché jusqu'a la prochaine section. 
    Exemple : # 01:25:3 La fete
    
Sections secondaires

    Une section secondaire permet d'afficher une sous periode, comme une durée avec un chiffrage de mesure.
    La section commence avec un ## suivi du timecode
    Exemple : ## 02:56:0 4/4
    
Indices visuels

    Un indice visuel permet de placer un evenement ponctuel pour se synchroniser. Un indice génère une barre de 
    progression 2 secondes avant, puis au timecode indiqué un point clignote. L'indice commence par un tiret - suivi
    du timecode. Un texte facultatif peut être ajouté à coté.
    Exemple : - 03:18:4 Solo de flute
    
Couleurs
    
    Des couleurs pour les éléments peuvent être spécifiés après un /. La liste des couleurs disponible :
    https://matplotlib.org/stable/_images/sphx_glr_named_colors_003.png
    Exemple : - 12:03:00 Allegro /blue

-------------------------------------------------------------------------------

# 00:00:0   0) Andante semplice 

## 00:00:1 4/4

- 00:09:0 /orange

# 00:09:0   1) The snowman

- 00:48:0 /yellow

# 00:48:0   2) Reveil

- 00:55:0 /red

## 00:55:0 3/4

- 00:55:1 Solo flute /blue
- 00:12:0 /purple

# 01:12:0   3) Allegro energico

- 00:29:0

# 01:29:0   4) Habillage

## 01:55:0 4/4

# 01:58:0   5) Alla marcia, pesante

## 02:10:0 3/4

## 02:11:0 4/4

# 20:05:0   6) Con melancolia
