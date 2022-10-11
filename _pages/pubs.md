---
layout: page
title: Publications
permalink: /pubs/
---
{% if site.data.pubs.preprint != null %}
## Preprints
{% for pub in site.data.pubs.preprint %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[PDF]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[website]</a>
    {% endif %}

    {% if pub.git-link != null %}
    <a href="{{ pub.git-link }}">[code]</a>
    {% endif %}

    {% if pub.data-link != null %}
    <a href="{{ pub.data-link }}">[data]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[video]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}

{% if site.data.pubs.conference != null %}
## Conference Papers
{% for pub in site.data.pubs.conference %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[PDF]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[website]</a>
    {% endif %}

    {% if pub.git-link != null %}
    <a href="{{ pub.git-link }}">[code]</a>
    {% endif %}

    {% if pub.data-link != null %}
    <a href="{{ pub.data-link }}">[data]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[video]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}

{% if site.data.pubs.thesis != null %}
## Thesis Work
{% for pub in site.data.pubs.thesis %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[PDF]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[website]</a>
    {% endif %}

    {% if pub.git-link != null %}
    <a href="{{ pub.git-link }}">[code]</a>
    {% endif %}

    {% if pub.data-link != null %}
    <a href="{{ pub.data-link }}">[data]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[video]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}