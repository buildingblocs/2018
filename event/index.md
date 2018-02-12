---
layout: default
---

# Schedule

{% for day in site.data.schedule %}
<h2>Day {{ day.day }}</h2>
<table>
    {% for activity in day.activities %}
    <tr>
        <td>{{ activity.time }}</td>
        <td width="80%">{{ activity.title }}</td>
    </tr>
    {% endfor %}
</table> 
{% endfor %}

# Details

## Competition

Stay tuned

## Fringe Games

Play games written in Python while getting to know other participants! Battleship, Dots and Boxes, Snake, Space Invaders, Sudoku and card games?

## Lightning Talks

Presenters will be published soon

