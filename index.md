---
layout: page
title: El semestre faltante en tu educación de CS
---

Las clases te enseñan de todo sobre temas avanzados de CS, desde
sistemas operativos hasta *machine learning*, sin embargo hay un tema crítico
que rara vez es tratado, y a su vez se deja a los estudiantes 
indagar por su cuenta: el cómo ser productivos con sus
herramientas. Te enseñaremos a como dominar la interfaz de línea de comandos,
a usar un poderoso editor de texto, a usar elaboradas características de
sistemas de control de versión, y mucho más!

Los estudiantes pasan cientos de horas usando estas herramientras en el transcurso
de su vida académica (y miles en su carrera), por lo que hace 
sentido invertir tiempo en hacer la experiencia lo más fluido y suave posible. 
Dominar estas herramientas no solo disminuirá el tiempo utilizado en averiguar 
como usarlas a tú favor, si no además te permitirá resolver problemas que antes 
parecían ser inmensamente complejos. 



Lee acerca de la [motivación detrás de esta clase](/about/).

{% comment %}
# Registro

Sign up for the IAP 2020 class by filling out this [registration form](https://forms.gle/TD1KnwCSV52qexVt9).
{% endcomment %}

# Calendario

{% comment %}
**Lecture**: 35-225, 2pm--3pm<br>
**Office hours**: 32-G9 lounge, 3pm--4pm (every day, right after lecture)
{% endcomment %}

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Videos grabados de la clases disponibles [en
YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J).

# Acerca de esta clase

**Equipo**: Esta clase es co-impartida por [Anish](https://www.anishathalye.com/), [Jon](https://thesquareplanet.com/), y [Jose](http://josejg.com/).
**Preguntas**: Envíanos un correo a [missing-semester@mit.edu](mailto:missing-semester@mit.edu).

# Más allá del MIT

Hemos compartido esta clase más allá del MIT con la esperanza de que otros
puedan beneficiarse del material. Puedes encontrar publicaciones y discusiones
en

 - [Hacker News](https://news.ycombinator.com/item?id=22226380)
 - [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
 - [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
 - [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
 - [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
 - [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

# Traducciones 

- [Chinese (Simplified)](https://missing-semester-cn.github.io/)
- [Chinese (Traditional)](https://missing-semester-zh-hant.github.io/)
- [Korean](https://missing-semester-kr.github.io/)
- [Turkish](https://missing-semester-tr.github.io/)

Nota: estos son link externos a traducciones comunitarias. No los hemos revisado.

Tienes alguna mejora en la traducción? Envía un 
[pull request](https://github.com/missing-semester/missing-semester/pulls) 
para incorporarla!

## Agradecimientos 

Agradecemos a Elaine Mello, Jim Cain, y [MIT Open
Learning](https://openlearning.mit.edu/) por hacer posible la grabación de
las clases; Anthony Zolnik y [MIT
AeroAstro](https://aeroastro.mit.edu/) por el equipo A/V; y Brandi Adams y 
[MIT EECS](https://www.eecs.mit.edu/) por apoyar esta clase. 

---

<div class="small center">
<p><a href="https://github.com/missing-semester/missing-semester">Source code</a>.</p>
<p>Licensed under CC BY-NC-SA.</p>
<p>See <a href="/license/">here</a> for contribution &amp; translation guidelines.</p>
</div>