
# *Auteur*
| Operation | Verbe |      URL      | Description                                                         |
|-----------|-------|:-------------:|---------------------------------------------------------------------|
|Read (all) | GET   |/author        | Affiche la liste de tous les auteurs                                |
|Create     | POST  |/author        | Ajouter un auteur dans la liste des auteurs                         |
| Read      | GET   |/author/id     | Affiche les infos de cet auteur par rapport a l'id entre            |
|Update     | PUT   |/author/id     | Met a jour les infos de cet auteur                                  |
| Destroy   | DELETE|/author/id     | Supprime cet auteur de la liste des auteurs                         |

# *Article*
| Operation | Verbe |      URL      | Description                                                         |
|-----------|-------|:-------------:|---------------------------------------------------------------------|
|Read (all) | GET   |/author/id/article        | Affiche la liste de tous les articles de cet auteur                                |
|Create     | POST  |/author/id/article        | Ajouter un article a la liste de cet auteur                         |
| Read      | GET   |/author/id/article/id     | Affiche cet article de cet auteur par rapport a l'id entre            |
|Update     | PUT   |/author/id/article/id     | Met a jour cet article de la liste des articles de cet auteur                                  |
| Destroy   | DELETE|/author/id/article/id     | Supprime cet article de la liste des articles de l'auteur                         |

# *Commentaire*
| Operation | Verbe |      URL      | Description                                                         |
|-----------|-------|:-------------:|---------------------------------------------------------------------|
|Read (all) | GET   |/author/id/article/id/comment        | Affiche la liste de tous les commentaires de cet article de cet auteur                                |
|Create     | POST  |/author/id/article/id/comment        | Ajouter un commentaire sur cet article de cet auteur                         |
| Read      | GET   |/author/id/article/id/comment/id     | Affiche ce commentaire de cet article de cet auteur par rapport a l'id entre            |
|Update     | PUT   |/author/id/article/id/comment/id     | Met a jour ce commentaire de cet article de cet auteur                                  |
| Destroy   | DELETE|/author/id/article/id/comment/id     | Supprime ce commentaire de cet article de l'auteur    |

