# Projet-Final_IA-Classification-d-images
classification d’images pour détecter le cancer de la peau

Pour réaliser un projet de classification d'images de détection de cancer de la peau en utilisant l'Arduino Nano 33 Sense BLE et le module caméra fourni, nous allons suivre les étapes ci dessous:

 - Tout d’abord, nous allons installer et configurer l'environnement de développement c'est -à -dire installer le logiciel Arduino et configurer l'environnement pour travailler avec la carte Nano 33 Sense BLE.
 
 - Ensuite, nous allons collecter des données pour les mettre sur Edge impluse en prenant des photos de la peau ”normale” avec  le module de la caméra de la carte, et puis utiliser la banque de donnees suivante:  “https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic “ pour inclure des images de peau cancéreuse (la lésion vasculaire).
 
 - Ensuite, sélectionner la méthode de classification c'est-à-dire  décider de quelles méthodes de classification nous allons utiliser. Nous utilisons ici :  le Processing Block “Image” et le Learning Block “Transfer Learning” pour entrainer le modèle. 
 
 - Ensuite, évaluer le modèle: Dans cette partie, nous allons évaluer les performances du modèle en utilisant des données de validation du code Arduino pour voir si notre modèle arrive à détecter sur une image les peaux saines et cancéreuses
 
 - Enfin, déploiement du modèle : Dans cette partie, nous allons déployer le modèle sur la carte Nano 33 Sense BLE pour une utilisation finale. 

NB: Il est important de noter que la classification d'images en médecine, comme la détection de cancer de la peau, nécessite une précision élevée pour éviter les diagnostics erronés qui peuvent avoir des conséquences graves. Il est donc important de s'assurer que le modèle est soigneusement testé et évalué.




# ------------------------------------------------------------

 - consulter le fichier zippé "Resultats" pour voir ce que j'ai pu realiser pour ce projet (par défaut de la caméra de la carte Sense BLE, le resultat n'est pas tres satisfaisant)

