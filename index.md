---
title: Accueil
layout: default
---

<main> 
     <h1>presentation</h1>
    <p> test equipe </p>
      
        {% for post in site.posts limit:3 %}
            <h3><a href="{{post.url}}">{{post.title}}</a></h3>

        <p>{{post.excerpt}}</p>

        {% endfor %}

     {% for Cours in site.Cours.cours limit:3 %}
        <ul>
            <li><a href="{{Cours.url}}">{{Cours.title}}</a></li>
        <!--
        <p>{{post.excerpt}}</p>
        -->
            </ul>
        {% endfor %}

 </main>
