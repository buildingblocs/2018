---
layout: default
---

<section class="jumbo">
    <div>
        <h1>
            {{ site.title }}<br>
            <span class="huge">2018</span>
        </h1>
        <p>
            <a href="{{ site.baseurl }}/contact">{{ site.date }}, {{ site.location }}</a><br>
            Online pre-event begins March
        </p>
        <p><a class="btn" href="{{ site.baseurl }}/register">Register now!</a></p>
    </div>
</section>

> Eight &lsquo;A&rsquo; level and twenty-six &lsquo;O&lsquo; level school computing students come together to build an infocomm-empowered future! 

## Theme: Dear Mr. Python...

Python powered web-pages! Experience how to set up server-side renders to host the websites of your dreams!

## Format

Continuing the success of previous years, 2018 sees the expansion of BuildingBloCS in various sectors! This year, BuildingBloCS have extended its target audience to both the **A-level and O-level students**, allowing for more diverse interactions. Pre-Events leading up to the official event will also be held to better enhance students' learning, building them up for the final event. (and increase their  chances of winnings ;))

## Pre-Event

Here is where the event lives! **Workshop materials, quizzes, fun facts and the lucky draw criterias** will all be hosted here. The Pre-event is definitely one not to be missed. [More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/pre-event)

## Event

The home. Where the heart of the event is; A line up of **fringe games, lightning talks and a final competition** are to be conducted on the **1-2 June at the NUS School of Computing**! The event will close with a **Lucky Draw Segment** and a **Prize Ceremony** to end the event  with a bang. This year's BuildingBloCS will also be held in conjuction with **"Python APAC 2018"**, making it a rare opportunity not to be missed.  [More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/event)

## Organised by

<section class="organisers">
    {% for organiser in site.data.organisers %}
    <img src="{{ site.baseurl }}/assets/img/{{ organiser.img }}" title="{{ organiser.title }}" />
    {% endfor %}
</section>

## Supported by

<section class="organisers">
    {% for organiser in site.data.sponsors %}
    <img src="{{ site.baseurl }}/assets/img/{{ organiser.img }}" title="{{ organiser.title }}" />
    {% endfor %}
</section>
