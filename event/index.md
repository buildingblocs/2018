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

Follow [@buildingblocs18](https://instagram.com/buildingblocs18) for quick notifications on event updates :) 

## Competition

Stay tuned for more details! 

## Fringe Games

Play games written in Python while getting to know other participants! Battleship, Dots and Boxes, Snake, Space Invaders, Sudoku, Card games, the possibilities are boundless! More details on Fringe Games will be uploaded. 

## Lightning Talks

Presenters will be published soon.

