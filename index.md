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
            Online Pre-events begins March
        </p>
        <p><a class="btn" href="{{ site.baseurl }}/register">Register now!</a></p>
    </div>
</section>

> &lsquo;A&rsquo; level / Integrated Programme and &lsquo;O&lsquo; level Computing students come together to build an infocomm-empowered future! 

## Theme: OYEA Python!

Experience and share the Python-powered web with the world!

## Format

Continuing the success of the inaugural BuildingBloCS '17, 2018 sees the expansion of BuildingBloCS in various sectors! This year, BuildingBloCS expands its target audience to both **O-level and A-level Computing students**. Pre-events leading up to the official conference will also enhance students' engagement, building them up for the finale where all will convene at NUS School of Computing for a day of fun, interaction, learning and prizes!

## Pre-events

**Workshop materials, programming puzzles, pop quizzes, fun facts** will be here. The pre-events will boost your Computing and Python prowess and are definitely not to be missed! [More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/pre-event)

## Event

The home. Where the heart of the event is; A line up of **fringe games, lightning talks and a final competition** will be conducted on the **1 June at the NUS School of Computing**! The event will close with a **Lucky Draw** and an **Award Ceremony**. BuildingBloCS '18 is also held in conjuction with **"Python APAC 2018"**, connecting participants to the wider Pythonista community!  [More&nbsp;details&nbsp;&raquo;]({{ site.baseurl }}/event)


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
