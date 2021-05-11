# YOLOv4_Train
Dossier pour entrainer le modèle Yolo sur notre base d'apprentissage

Le fichier config .cfg à utiliser est dans le dossier cfg et est yolov4_test.cfg. L'autre est celui obtenu à partir du github du créateur de Darknet pour Yolo.
Dans le code entrainement, on peut changer des paramètres du .cfg (subdivision, width, ...) et l'adaptation au nombre de classes est automatique.

Le fichier de poids .weights est à trouver sur le drive dans weights, c'est yolov4_most_best.weights. Le fichier étant trop gros pour Github.
Les poids actuellement dans le dossier sont les poids du modèle à 2 classes.

Les images sont à trouver dans le dossier images. Les images tests d'Internet (pas de la base Google) sont à trouver dans image_test.
Les dossier obj et test sont utilisés mais leurs contenus sont vidés avant l'entrainement puis rempli des imges obj et test qu'il faut.

train.txt et test.txt sont des exemples de fichiers train.txt et test.txt, ils sont reécrit dans le code d'entrainement.

Le fichier obj.names est le bon, il donne les labels aux classes.

Le fichier obj.data est un exemple de obj.data pour les serveurs Hupi. Le code d'entrainement gère son écriture et le nombre de classe automatiquement.
Il y a la possibilité de changer le dossier de backup pour récupérer les fichiers poids.
