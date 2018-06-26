---
layout: single
permalink: /contact/
author_profile: true
classes:
  - wide
developers:
  - name: "Leon Thurner"
    nickname: Leon
    email: leon.thurner@uni-kassel.de
    image: "/images/contact/leon.jpg"
    text: "only owns one suit, which he is wearing in this picture."
  - name: "Alexander Scheidler"
    nickname: Alex
    email: alexander.scheidler@iee.fraunhofer.de
    image: "/images/contact/images/alex.jpg"
    text: "thinks the only honest people wearing suits are grave diggers. Prefers red t-shirts."
  - name: "Florian Schäfer"
    nickname: Florian
    email: florian.schaefer@uni-kassel.de
    image: "/images/contact/images/flo.jpg"
    text: "likes to wear suits to any occasion because it makes him feel fancy."
---
<p></p>

# Mailing List <a name="list"></a>
If you want to receive updates about new versions and other news about pandapower, you can subscribe to the pandapower mailing list:

[Subscribe](mailto:sympa@fraunhofer.de?subject=subscribe%20pandapower){: .btn .btn--success .btn--large}

<small>If you no longer want to receive updates, <a href="mailto:sympa@fraunhofer.de?subject=unsubscribe%20pandapower">unsubscribe here</a>.</small>

# About us

pandapower is a joint development of the research group Energy Management and Power System Operation, University of Kassel and the Department for Distribution System Operation at the Fraunhofer Institute for Energy Economics and Energy System Technology (IEE), Kassel.

[<img src="https://www.uni-kassel.de/eecs/fileadmin/datas/fb16/Fachgebiete/energiemanagement/e2n.png">](https://www.uni-kassel.de/eecs/en/fachgebiete/e2n/home.html)
[<img src="https://www.uni-kassel.de/eecs/fileadmin/datas/fb16/Fachgebiete/energiemanagement/iee.png">](https://www.iee.fraunhofer.de/en.html)
 

# Who we are

And these are some of the people behind pandapower:

<div class="authors">
  {% for developer in page.developers %}
    <p>
    <img style="padding:2px 2px 2px 2px; border:2px solid black; margin-right: 15px" src="{{ developer.image | relative_url }}" width="120" align="left"/> 
    <span style="margin-top: -5px; display:inline-block; max-width:500px;">
        <b>{{ developer.name }}</b> {{ developer.text }} <br>
        <a href="mailto:{{developer.email}}">Contact {{developer.nickname}}</a> 
    </span>
    <BR CLEAR="left"/> 
    </p>
  {% endfor %}
</div>

[See Full List of authors and contributors](http://pandapower.readthedocs.io/en/stable/about/authors.html){: .btn .btn--success .btn--large}


