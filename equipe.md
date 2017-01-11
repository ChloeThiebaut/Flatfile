---
title: Equipe
layout: page
---

<main>
    {% for ligue.in.site.data.clubs %}
        {%for club in ligue[1] where:Key,'football-team' %}
        {{club.name}}
        {{% endfor %}}
    {{% endfor %}}
    
</main>
