1/	Aller sur le site facebook developper :
https://developers.facebook.com/apps/237859304275743/fb-login/quickstart/

2/	Atteindre le point 4 du tutoriel et effectuer la commande si dessous :
Télécharger openssl :https://code.google.com/archive/p/openssl-for-windows/downloads
Lien additionnel tuto YT: https://www.youtube.com/watch?v=LUv8NDgu2Xk

Ligne de commande complétée et exécutée dans le dossier du JRE java :
keytool -exportcert -alias androiddebugkey -keystore "C:\Users\brice\.android\debug.keystore" | "E:\Travail\OpenClassRoom\Autres\Ressources\FBKEY\bin\openssl" sha1 -binary |
"E:\Travail\OpenClassRoom\Autres\Ressources\FBKEY\bin\openssl" base64

3/	Ajouter un mot de passe

4/	Enregistrer la clef de hachage de développement


Autre méthode qui fonctionne :

1/	Prendre la clef sha1 de l'app

2/	http://tomeko.net/online_tools/hex_to_base64.php --> transformer la clef en base64