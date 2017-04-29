#Creer un nouveau modele de page

HHH
###Cahier des charges

On doit trouver les elements suivants

- Résumé
- Image du résumé
- Article
- Image
HHH
- Création d'un repertoire Francisco 
- Création d'une page francisco_1.md => on va donc appeller un modele francisco_1.html.twig

VVV
Dans cette page je n'oublier pas d'ajouter le

```html
---
title: mon titre
---
```
VVV
Ajouter la page francisco_1.html.twig dans votre repertoire template
```html
{% extends 'partials/base.html.twig' %}

{% block content %}

    {{ content }}


{% endblock %}
```

HHH
The End :)
