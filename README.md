# ecommerce

### lien vers le ttuto https://www.youtube.com/watch?v=kpSYFMV4eJc&list=PLBq3aRiVuwyzI0MT4LhvwqkVenz5pF_DM&index=1

### Diagramme de la base de données : https://dbdiagram.io/d/61643981940c4c4eec8f40a5

#### Questions 👍
question 1 dans symfony 6 si le webpack n'est pas installé mon browser fonctionne correctement et mes Uri sont atteignables

si webpack est installé alors j'ai un message type :

An exception has been thrown during the rendering of a template ("Could not find the entrypoints file from Webpack: the file "C:\Users\patmo\ecommerce/public/build/entrypoints.json" does not exist.").
 qui met en cause le bloc
         {% block stylesheets %}
            {{ encore_entry_link_tags('app') }}
        {% endblock %}
de base.html.twig. 
 
Je viens d'identifier la source du probleme que je traine depuis 3 semaines et qui m'a bloqué pour construire l'appli.
Quelqu'un peut il m'expliquer les causes de ce problème ?