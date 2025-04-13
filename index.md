---
layout: default
title: Bienvenue sur mon site !
---
![Footix32](Files/Footix.png)

<p align="center">
  <img src="images/ma-photo.jpg" alt="Ma photo" width="400">
</p>

# Salut, moi c'est Footix32 👋

Bienvenue sur ma GitHub Pages ! Je suis un passionné d'IT, de Sécu , et d'IA   
Voici une sélection de mes projets publics hébergés sur GitHub. Une première pierre à l'édifice !

---

## 🌟 À propos de moi

Je suis actuellement étudiant en TSSR et souhaite poursuivre en AIS ! 
Je travaille sur divers projets, et j'apprends à scripter quelques actions pour gagner du temps durant la création de labs
N'hésitez pas à explorer mes dépôts ci-dessous !

---
Un peu d'audio, pour apporter de l'amour dans l'IT.

Généré par SUNO AI

<audio controls>
  <source src="files/premier-ecran.mp3" type="audio/mpeg">
  Votre navigateur ne supporte pas la lecture audio.
</audio>
---

## 💾 Mes Projets Publics 

- [Auto-Deploy](https://github.com/Footix32/auto_deploy) : mes scripts de déploiement semi-auto pour gagner du temps 1- Déploiement d'un ADDS + OU 2- Coming Soon
- [Injection de users dans un AD](https://github.com/Footix32/user_injector_ad) : Script d'injection de users dans un AD, très utiles pour faire rapidement des tests
- [Debian Post Install](https://github.com/Footix32/tssr-linux-debian-post-install) : Fork d'un repo et modification (personalisaton)

---

## Accès rapide vers mes repos ! 🐥

{% for repo in site.github.public_repositories %}
- [{{ repo.name }}]({{ repo.html_url }})  
  *{{ repo.description | default: "Pas de description disponible." }}*
{% endfor %}

---

Merci de visiter ma page ! Pour plus d'informations, consultez mon [profil GitHub](https://github.com/{{ site.github.owner_name }}).
