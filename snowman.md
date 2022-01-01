**Fichier de description**

Fonctionnement :

Ce fichier décrit les indice visuels à générer automatiquement sur la vidéo pour faciliter la
synchronisation avec le conducteur d'un morceau d'orchestre.

Format à respecter :

Sections principales

    Une section principale commence par un # suivi du timecode corespondant dans la vidéo. 
    le timecode doit s'écrire au format MM:ss:m (M minute, s seconde, m dixieme de secondes) et doit être unique
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

# 00:00:0       0) Andante semplice 


## 00:00:1 4/4

- 00:09:0 /lime

# 00:09:0       1) The snowman

- 00:46:8 /lime

# 00:46:8       2) Reveil

## 00:54:5 3/4

- 00:54:5 Solo flute /blue
- 01:02:3 Dainty /purple
- 01:11:6 /lime

# 01:11:6       3) Allegro energico

- 01:29:1 /lime

# 01:29:1       4) Chaussettes

## 01:55:0 4/4

- 01:57:3 /lime

# 01:57:3       5) Alla marcia, pesante

## 02:10:0 3/4

## 02:11:0 4/4
- 02:11:9 Solo clarinet
- 02:19:7 crash
- 02:24:0 /lime
# 02:24:0       6) Con melancolia


- 02:41:1 /lime
# 02:41:1       7) Construction snowman

- 02:48:8 Solo flute
- 03:12:4 Solo flute
- 03:24:8 /lime

# 03:24:8       8) Accessoires snowman

- 03:28:4 Solo Flute
- 03:36:0 Solo Flute
- 03:47:7 F Dolce pt orgue
- 03:58:2 mp Triolet noire
- 04:07:7 regard 1
- 04:09:7 regard 2
- 04:11:2 regard 3

- 04:14:5 /lime
# 04:14:5 9) 
- 04:29:9 Horloge
- 04:30:4 hautbois
## 04:30:4 3/4

- 04:48:2 Cantabile
- 04:52:4 
- 05:01:4 /lime
# 05:01:4       10) Minuit
- 05:15:3 cloche

# 05:34:0 11)

- 06:20:1 /lime
# 06:20:1       12) Chat

- 06:20:1 /lime
# 06:38:4       13) Sapin

- 07:08:3 /lime
# 07:08:3       14) Television
- 07:21:6 Montée

- 07:28:9 /lime
# 07:28:9 15)

- 07:41:1 switch
- 07:47:7 switch
- 07:48:2 switch
- 07:49:2 switch
- 08:08:0 savon

- 08:22:9 /lime
# 08:22:9 16)

- 08:55:1 /lime
# 08:55:1 17) Alla calypso
# 09:31:1 18)
# 19)
# 20)
# 21)
# 22)
# 23)
# 24)
# 25)
# 26)
# 27)
# 28)
# 29)
# 30)
# 31)
# 32)
# 33)
# 34)
# 35)
# 36)
# 37)
# 38)
# 39)
# 40)
# 41)
# 42)
# 43)
# 44)
# 45)
# 46)
# 47)
# 48)
# 49)
# 50)
# 51)