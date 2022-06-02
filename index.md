---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# Recent posts

<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a> <b>{{ post.date | date: "%d %B %Y" }}</b> 
    </li>
  {% endfor %}
</ul>

# About me

<img class="profile-picture" src="{{site.baseurl}}/{{site.profile-picture}}">

I am Mischa Batelaan, a PhD candidate at the [University of Adelaide](https://www.adelaide.edu.au). My main area of research is in the study of the structure of nucleons through Lattice QCD methods. I have been working on a novel method for calculating nucleon form factors which is based on the Feynman-Hellman method.

Outside of research I like to spend my time cycling around the Adelaide area and competing in local amateur cycling races. I also enjoy playing around with computers and technology.

## Introduction
- I have been a PhD candidate at the University of Adelaide since 2019 working under the supervision of Associate professor James Zanotti and Associate professor Ross Young.
- I received my honours degree in Bachelors of Science in High Performance Computational Physics from the University of Adelaide in 2018. My thesis title was _"Nucleon Form Factor Calculations using the Feynman-Hellmann method"_


## Publications
1. M. Batelaan et al.: _"Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD"_ [https://arxiv.org/abs/2202.01366](https://arxiv.org/abs/2202.01366)

## Conference presentations
- Lattice21 parallel session: _"Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD"_ [Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD](https://indico.cern.ch/event/1006302/contributions/4381736/)
- APLAT2020 parallel session: _"Nucleon electromagnetic form factors at high momenta using the Feynman-Hellmann method"_ [Nucleon electromagnetic form factors at large momenta using the Feynman-Hellmann theorem](https://conference-indico.kek.jp/event/113/contributions/2066/)

## Contact Me
- email: mischa.batelaan [at] adelaide.edu.au
- email: mischa.batelaan [at] gmail.com