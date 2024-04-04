# Configuration du DNS pour le serveur

Afin de se connecter au site internet permettant la réservation du véhicule F-City, il y a besoin de se connecter à l'url suivante : 

- fcity.isen

Cependant, nous rencontrons un problème lors de la tentative de connnexion au site. Pour cela, il faut changer le DNS sur votre machine, avec le protocole suivant.

## Configuration du DNS sur Windows

1 - Ouvrez un bloc note en mode administrateur

2 - Ctrl + O pour ouvrir un fichier

3 - Trouvez le fichier suivant avec le chemin  : 

    C:\Windows\System32\drivers\etc\hosts

4 - Ajoutez la ligne suivante à la fin de votre fichier : 

    10.10.64.13     fcity.isen

5 - Ctrl + s pour sauvegarder

6 - Connectez-vous au site suivant

    monprojm1.isen

7 - Réservez votre projet trajet

## Configuration du DNS sur Mac/ Linux

1 - Ouvrir un terminal

2 - Faire un sudo nano /etc/hosts

3 - Si besoin, entrez le mot de passe administrateur

4 - Ajoutz la ligne suivante : 

    10.10.64.13     fcity.isen

5 - Ctrl + O pour enregistrer puis Ctrl + X pour fermer la page

6 - Réservez votre projet trajet
