---
layout: default

Bienvenue sur mon site !
---
![Footix32](Files/Footix.png)

# Salut, moi c'est Footix32 👋

Bienvenue sur ma GitHub Pages ! Je suis un passionné d'IT, de cybersécurité , et d'IA   


---

## 🌟 À propos de moi

💻 En reconversion, j’ai plongé à fond dans les systèmes, réseaux & la cybersécurité.
🔒 Analyste SOC en alternance, je surveille, analyse et réagis aux menaces en continu.
🚒 Sapeur-pompier volontaire, j’interviens aussi bien sur le terrain que sur les incidents réseau.
🧠 Curieux & proactif, j’apprends en créant, testant et explorant sans cesse.

📂 Ici, je partage mes projets IT, scripts, tests et autres explorations techniques 👨‍💻

Je travaille sur divers projets, et j'apprends à scripter quelques actions pour gagner du temps sur mes futurs projets
N'hésitez pas à explorer mes dépôts ci-dessous !

---

## Accès rapide vers mes repos ! 🐥

{% for repo in site.github.public_repositories %}
- [{{ repo.name }}]({{ repo.html_url }})  
  *{{ repo.description | default: "Pas de description disponible." }}*
{% endfor %}

---

Merci de visiter ma page ! Pour plus d'informations, consultez mon [profil GitHub](https://github.com/{{ site.github.owner_name }}).
