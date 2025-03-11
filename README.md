# Xibo Windows Player

## 📺 Définition
Le Xibo Windows Player est une application client qui permet d'afficher du contenu multimédia sur des écrans de diffusion. Il fait partie de la solution de signalisation numérique Xibo.

## 🎯 Rôle
Le rôle principal du Xibo Windows Player est de télécharger, stocker et afficher le contenu programmé par le CMS sur les écrans de diffusion. Il assure une lecture fluide et continue des médias, même en cas de perte de connexion avec le CMS.
## 🔄 Communication avec le CMS
Le Xibo Windows Player communique avec le CMS via des requêtes HTTP/HTTPS. Il télécharge les mises à jour de contenu, les plannings et les configurations depuis le CMS. Le Player envoie également des rapports d'état et des journaux d'activité au CMS pour le suivi et la gestion à distance.

## 🛠️ Outils et technologies utilisés
- **Langage de programmation** : C#
- **Framework** : .NET Framework
- **Communication réseau** : HTTP/HTTPS
- **Gestion des médias** : DirectShow, WPF (Windows Presentation Foundation)
- **Base de données locale** : SQLite
- **Système d'exploitation** : Windows
- **Front-end** : WPF (Windows Presentation Foundation)

## 🌐 Connexion au serveur
Le Xibo Windows Player se connecte au serveur CMS en utilisant des requêtes HTTP/HTTPS. Le client envoie des requêtes pour télécharger le contenu, les plannings et les configurations nécessaires. En retour, le serveur CMS répond avec les données demandées, permettant ainsi au Player de mettre à jour et d'afficher le contenu multimédia de manière fluide et continue. En cas d'erreur de connexion, le Player est conçu pour gérer les exceptions et assurer une lecture ininterrompue des médias déjà téléchargés.
