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
            {{ site.date }}, {{ site.location }}<br>
            Online pre-event begins March
        </p>
        <p><a class="btn" href="{{ site.baseurl }}/register">Register now!</a></p>
    </div>
</section>

> Eight &lsquo;A&rsquo; level and twenty-six &lsquo;O&lsquo; level school computing students come together to build an infocomm-empowered future! 

## Theme: Dear Mr. Python...

Python powered web-pages! Experience how to set up server-side renders to host the websites of your dreams!

## Format

Continuing the success of previous years, 2018 sees the expansion of Buildingblocs in various sectors! This year, Buildingblocs have extended its target audience to both A-level and O-level students, allowing for more diverse interactions. Pre-Events leading up to the official event will also be held to enhance students' learning (and increase chance of winnings ;)). 

## Pre-Event

Here is where the event lives! Workshop materials and potentially competition and lucky draw criteria is all here, so don’t miss out! Accompanying will be some fun facts and quizzes! [More details &raquo;]({{ site.baseurl }}/pre-event)

## Event

The home. Where the heart of the event is; The fringe games, competition and prizes ceremony happens here, at NUS School of Computing! This year's Buildingblocs is also held in conjuction with "Python APAC 2018", making it a rare opportunity not to be missed.  [More details &raquo;]({{ site.baseurl }}/event)

## Sponsored by

<section class="organisers">
    {% for organiser in site.data.sponsors %}
    <img src="{{ site.baseurl }}/assets/img/{{ organiser.img }}" title="{{ organiser.title }}" />
    {% endfor %}
</section>

## Organised by

<section class="organisers">
    {% for organiser in site.data.organisers %}
    <img src="{{ site.baseurl }}/assets/img/{{ organiser.img }}" title="{{ organiser.title }}" />
    {% endfor %}
</section>
