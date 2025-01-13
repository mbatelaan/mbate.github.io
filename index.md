---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: main
---

# About me

I am Mischa Batelaan, a postdoctoral researcher at the College of William and Mary. My research is focused on hadron spectroscopy in lattice QCD.
Outside of research I like to spend my time cycling around the Adelaide area and competing in local amateur cycling races. I also enjoy playing around with computers and technology.

<button name="button test" onclick="http://www.google.com">Click me</button>

## Introduction
- I have been a PhD candidate at the University of Adelaide since 2019 working under the supervision of Associate professor James Zanotti and Associate professor Ross Young.
- I received my honours degree in Bachelors of Science in High Performance Computational Physics from the University of Adelaide in 2018. My thesis title was _"Nucleon Form Factor Calculations using the Feynman-Hellmann method"_


## Publications
1. _"Feynman-Hellmann approach to transition matrix elements and quasidegenerate energy states"_ [https://doi.org/10.1103/PhysRevD.108.034507](https://doi.org/10.1103/PhysRevD.108.034507)
2. _"Constraining beyond the standard model nucleon isovector charges"_ [Constraining beyond the standard model nucleon isovector charges](Constraining beyond the standard model nucleon isovector charges)
3. _"Moments and power corrections of longitudinal and transverse proton structure functions from lattice QCD"_ [https://doi.org/10.1103/PhysRevD.107.054503](https://doi.org/10.1103/PhysRevD.107.054503)

## Proceedings
1. M. Batelaan et al.: _"Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD"_ [https://arxiv.org/abs/2202.01366](https://arxiv.org/abs/2202.01366)
2. R. Horsley, M. Batelaan et al.: _"Quasi-degenerate baryon energy states, the Feynman-Hellmann theorem and transition matrix elements"_  [https://arxiv.org/abs/2302.04911](https://arxiv.org/abs/2302.04911)

## Conference presentations
- Lattice22 parallel session: _"Calculation of hyperon transition form factors from two-point functions using the Feynman-hellmann method"_ [Calculation of hyperon transition form factors from two-point functions using the Feynman-hellmann method](https://indico.hiskp.uni-bonn.de/event/40/contributions/531/)
- Lattice21 parallel session: _"Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD"_ [Nucleon Form Factors from the Feynman-Hellmann Method in Lattice QCD](https://indico.cern.ch/event/1006302/contributions/4381736/)
- APLAT2020 parallel session: _"Nucleon electromagnetic form factors at high momenta using the Feynman-Hellmann method"_ [Nucleon electromagnetic form factors at large momenta using the Feynman-Hellmann theorem](https://conference-indico.kek.jp/event/113/contributions/2066/)

## Contact Me
- email: mischa.batelaan [at] adelaide.edu.au
- email: mischa.batelaan [at] gmail.com

# Recent posts

<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a> <b>{{ post.date | date: "%d %B %Y" }}</b> 
    </li>
  {% endfor %}
</ul>

