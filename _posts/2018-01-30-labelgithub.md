---
date: 2018/01/30
title: "Labels GitHub"
excerpt: "How to copy labels from/to repository?"
header:
  image: "/assets/images/post/labelgit.png"
  teaser: "/assets/images/post/labelgit-th.jpg"
  # og_image: "https://static1.squarespace.com/static/56023101e4b072a1b1866505/t/56be1e4b37013b18611e028b/1455300256034/before-after.jpg"
categories:
  - Post
tags:
  - Openfab
  - github
---

*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/22), feel at ease to contribute.*

### Contexte
Après maintenant 1 an d'exploration dans Github en lien avec Openfab et la gestion de projet.   
J'ai plusieurs repository à la fois perso et organisation, je commence a trouver mon chemin dans une liste de label qui fait sens MAIS    
c'est punaise pénible de m'imaginer réencoder 15 labels à chaque fois que je crée un nouveau repository.


## Comment dupliquer une liste de Labels?

Ha ben j'ai trouvé un tuto qui va bien.   
[**How to Copy GitHub Labels from One Project to Another**](https://medium.com/@dtinth/how-to-copy-github-labels-from-one-project-to-another-1857adc73e0f)  
>My GitHub project consists of several sub-projects. To make the labels consistent, we can use some tool to copy the label from one project to another

*Merci à [Thai Pangsakulyanont](https://medium.com/@dtinth)*

Du coup, j'ai suivis ce qu'il propose et pour le coup, je propose moi aussi quelques astuces/détails, parce que ça n'a pas marché directement pour moi.

1. le lien pour le token, c'est https://github.com/settings/tokens
2. il faut bien activer les droits d'accès sur le repo lors de la creation du token.
![image.png](https://images.zenhubusercontent.com/599be89f8f62dc7798c39c2f/f84bbe58-f1f7-4dd9-adab-824a1eda8d86)

C'est tout en fait, une fois que le token a les bonnes autorisations, ça marche nickel.   
C'est aussi super pratique pour éditer tout les labels à la volée.

*note: this post is linked to [this issue](https://github.com/nicolasdb/nicolasdb.github.io/issues/22), feel at ease to contribute.*
