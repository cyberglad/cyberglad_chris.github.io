---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: Home
icon: fa-home
order: 1
---
<!DOCTYPE html>
<html lang="{{ site.lang }}">
<head>
    <meta charset="utf-8">
    <meta name="description" content="{% t site.description %}"/>
    <meta name="keywords" content="{% t site.keywords %}"/>
    <title>{% t site.name %} - {% t site.tagline %}</title>
</head>
<body>
    <section id="{% t main.welcomeSection.anchor%}">
        <div>
            <h2>{% t main.welcomeSection.heading %}</h2>
            <p>{% t main.welcomeSection.p1 %}</p>
        </div>
    </section>
</body>
</html>
