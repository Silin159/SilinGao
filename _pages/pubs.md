---
layout: page
title: Publications
permalink: /pubs/
---
{% if site.data.pubs.preprint != null %}
<!-- ## Preprints -->
{% for pub in site.data.pubs.preprint %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[Paper]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[Website]</a>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.data-link }}">[Dataset]</a>
    {% endif %}

    {% if pub.code-link != null %}
    <a href="{{ pub.code-link }}">[Code]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[Video]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.poster-link }}">[Poster]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}

{% if site.data.pubs.conference != null %}
<!-- ## Conference Papers -->
{% for pub in site.data.pubs.conference %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.award != null %}
    <b>{{ pub.award }}</b><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[Paper]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[Website]</a>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.data-link }}">[Dataset]</a>
    {% endif %}

    {% if pub.code-link != null %}
    <a href="{{ pub.code-link }}">[Code]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[Video]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.poster-link }}">[Poster]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}

{% if site.data.pubs.thesis != null %}
<!-- ## Thesis Work -->
{% for pub in site.data.pubs.thesis %}
<p class="message">
    <b>{{ pub.title }}</b><br>
    {{ pub.author }}<br>

    {% if pub.venue != null %}
    <i>{{ pub.venue }}</i><br>
    {% endif %}

    {% if pub.award != null %}
    <b>{{ pub.award }}</b><br>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.pdf-link }}">[Paper]</a>
    {% endif %}

    {% if pub.website != null %}
    <a href="{{ pub.website }}">[Website]</a>
    {% endif %}

    {% if pub.pdf-link != null %}
    <a href="{{ pub.data-link }}">[Dataset]</a>
    {% endif %}

    {% if pub.code-link != null %}
    <a href="{{ pub.code-link }}">[Code]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.video-link }}">[Video]</a>
    {% endif %}

    {% if pub.video-link != null %}
    <a href="{{ pub.poster-link }}">[Poster]</a>
    {% endif %}
</p>
{% endfor %}
{% endif %}
