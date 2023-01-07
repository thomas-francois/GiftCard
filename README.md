# Guide pour le site GiftCard
Guide d'utilisation et de consultation de l'application Wordrpress

### Prérequis:
Installer docker-compose:
https://docs.docker.com/compose/install/
<br>Verifier que l'application Docker est lancée


### Installation:
- Télecharger et décompresser le dossier ZIP de Github
![SCR-20230107-dx9](https://user-images.githubusercontent.com/103375765/211143320-9227861d-344c-4557-9198-24536dff837a.png)

- Ouvrir le terminal
- Naviguer avec le terminal jusqu'à l'emplacement du dossier et entrer dedans (avec la commande cd emplacement/nomdDuDossier)
- Exécuter dans le terminal la commande: docker-compose up
- Attendre l'initialisation et l'installation complète du système<br>
  (les deux images doivent être en cours d'éxecution sur l'aplication Docker)
- Ouvrir votre naviguiateur et rechercher : http://localhost/wp-admin/
- Se connecter à Wordpress avec les identifiants admin / admin


### Utilisation:
Vous avez maintenant accès au site GiftCard, vous pouvez accèdez aux deux articles customisés.
Vous pouvez aussi modifier et rajouter d'autres articles grâce à l'interface de Wordpress.
<br><br>
Pour quitter l'application, appuyer sur Ctrl+C dans le terminal puis executer la commande: docker-compose down
