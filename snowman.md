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

- 00:01:6 depart piano /lime
# 00:01:6       1) The snowman

- 00:24:0 Depart cordes /darkorange

- 00:46:6 /lime

# 00:46:6       2) Reveil

- 00:54:5 Solo flute /darkorange
- 01:02:2 Dainty /darkorange
- 01:11:7 /lime

# 01:11:7       3) Allegro energico

- 01:28:7 /lime

# 01:28:7       4) Chaussettes
 - 01:49:4 /lime

- 01:57:3 /lime

# 01:57:3       5) Alla marcia, pesante

- 02:11:8 Solo clarinet /darkorange
- 02:19:5 crash /darkorange
- 02:23:9 /lime
# 02:23:9       6) Con melancolia

- 02:41:0 /lime
# 02:41:0       7) Construction snowman

- 02:48:7 Solo flute /darkorange
- 03:12:5 Solo flute /darkorange
- 03:24:9 /lime

# 03:24:9       8) Accessoires snowman

- 03:28:5 Solo Flute /darkorange
- 03:36:4 Solo Flute /darkorange
- 03:47:5 F Dolce pt orgue /darkorange
- 03:58:3 mp Triolet noire /darkorange

- 04:14:4 /lime
# 04:14:4       9) 
- 04:29:0 Horloge /darkorange
- 04:30:8 hautbois /darkorange

- 04:47:9 Cantabile /darkorange

- 05:01:6 /lime
# 05:01:6       10) Minuit


- 05:34:0 /lime
# 05:34:0       11)

- 05:57:0 picolo - après vous /darkorange
- 05:58:6 basson - merci /darkorange

- 06:19:9 /lime
# 06:19:9       12) Chat

- 06:38:4 /lime
# 06:38:4       13) Sapin

- 07:08:3 /lime
# 07:08:3       14) Television

- 07:21:5 Montée /darkorange

- 07:29:0 /darkorange

- 07:39:1 /lime
# 07:39:1 15)

- 07:41:1 switch /darkorange
- 07:57:4 solo starwars /darkorange

- 08:08:0 savon /darkorange
- 08:13:4 /darkorange
- 08:24:0 /lime
# 08:24:0 16)

- 08:55:0 /lime
# 08:55:0 17) Alla calypso

- 09:21:4 changement tempo pizzicato /darkorange
- 09:25:3 Lumière /darkorange

- 09:31:1 /lime
# 09:31:1 18) 

- 09:54:5 /lime
# 09:54:5 19) 

- 10:10:0 percussion chapeau /darkorange
- 10:30:8 depart corde /darkorange

- 10:43:0 /lime
# 10:43:0 20) Slower

- 11:03:8 Atchoum /darkorange

- 11:11:9 /lime
# 11:11:9 21) Tempo di valse

- 11:23:8 glissade /darkorange

- 11:37:8 /lime
# 11:37:8 22) 

- 11:53:9 /lime
# 11:53:9 23)
- 12:13:8 /darkorange
- 12:17:3 /lime 
# 12:17:3 24)

- 12:44:0 /lime
# 12:44:0 25) Moto

- 13:07:7 /darkorange

- 13:19:0 /lime
# 13:19:0 26)

- 13:39:0 /lime
# 13:39:0 27)

- 13:57:0 /lime
# 13:57:0 28)

- 14:16:0 /lime
# 14:16:0 29)

- 14:37:0 /lime
# 14:37:0 30)
- 14:48:6 moderato /darkorange

- 14:55:5 /lime
# 14:55:5 31)
- 15:12:4 /lime

- 15:25:4 /lime
# 15:25:4 32)
- 15:32:8 soprane /darkorange

- 16:17:9 /lime
# 16:17:9 33)

- 16:32:8 Chant /darkorange

- 16:55:2 /lime
# 16:55:2 34)

- 17:14:0 /lime
# 17:14:0 35)

- 17:36:9 35a)
# 17:36:9 35a)

- 17:56:8 /lime
# 17:56:8 36)
- 18:03:7 baleine /darkorange

- 18:17:8 /lime
# 18:17:8 37)

- 18:58:2 /lime
# 18:58:2 38)

- 19:27:2 /lime
# 19:27:2 39)
- 19:41:0 /lime
# 19:41:0 40)

- 19:57:2 /lime
# 19:57:2 41)

- 20:13:2 /lime
# 20:13:2 42)

- 20:21:2 /lime
# 20:21:2 43)

- 20:37:4 /lime
# 20:37:4 44)

- 20:53:2 /lime
# 20:53:2 45)

- 21:09:2 /lime
# 21:09:2 46)

- 21:25:3 /lime
# 21:25:3 47)

- 21:38:7 /lime
# 21:38:7 48)
- 21:49:9 altos /darkorange

- 22:15:5 /lime
# 22:15:5 49)

- 22:59:5 /lime
# 22:59:5 50)
- 23:21:0 /darkorange
- 23:34:7 /darkorange

- 23:50:4 /lime
# 23:50:4 51)
- 24:27:9 depart piano /darkorange
- 24:33:3 /lime
# 24:33:3 52)

- 24:55:8 /lime
# 24:55:8 53)
- 25:18:8 /darkorange

