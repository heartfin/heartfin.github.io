---
title: "Heartfin"
description: "Jellyfin clients using Qt"
layout: default
---
Heartfin is a group of—currently 1—clients for [Jellyfin](https://jellyfin.org/), a free media server for your own media.
With these clients, you can stream images, music and videos from your server and play them back on your own devices!

## Sailfin
![An stylished fish](/assets/sailfin/icon.svg){: width="10%" style="float:left;margin:0.25em;"} Sailfin is the Jellyfin client for [Sailfish OS](https://www.sailfishos.org/).
You can download it from [OpenRepos](https://openrepos.net/content/ahappyhuman/sailfin). 
There is [a Jellyfin thread on the Sailfish OS forum](https://forum.sailfishos.org/t/sailfin-a-jellyfin-client-for-sailfish-os-thread/2260?u=ahappyhuman) for any feedback and suggestions.
Bugs and pull request can be submitted on [GitHub](https://github.com/heartfin/harbour-sailfin).

## libjellyfinqt
is the library that powers Sailfin and in the future other clients under the heartfin umbrella.
Written in C++ and makes use of the [Qt](https://www.qt.io) framework.
If you're interested in contributing to the library or any Heartfin project, please [look at its documentation](https://heartfin.github.io/harbour-sailfin).

## Updates
{% for post in site.posts %}
<article>
    <header>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        {{ post.date | date_to_long_string: "ordinal" }}
    </header>
    {{ post.excerpt }}
</article>
{% endfor %}
