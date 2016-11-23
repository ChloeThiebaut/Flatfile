# boucle ( suite du cours sur Jekyll) #

Les sites en Jekyll sont plus rapides et ne peuvent pas "tomber" car ils sont statiques et n'ont pas de requête sur une base de donnée
Open data -> les institues mettent des données publiques en libre axcés. Les gens peuvent donc crée des application avec.

## boucle pour le menu ##

assign = var 


    <ul>
        {% for page in site.pages %}
            <li> <a href="{{page.url}}">{{page.title}}</a></li>
        {% endfor %}
     </ul>
     
## Liquid ##

## Blog ##

création d'un billet de blog -> Date_titre.md
(2016-11-23_titre.md)
( post.date post.title)

## Info complementaires ##

 _config.yml -> variavle et config
 index.md et contact.md sont converties en .html lorsqu'ils sont transfèrer sur le site
