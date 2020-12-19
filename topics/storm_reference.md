---
layout: pages
---

# Severe storms in history

## Dust storms table

| Date | Place | Storm name |
| --- | --- | --- |
|April 14, 1935|Texas Panhandle to the Oklahoma Panhandle, United States| Black Sunday|
|December 19-21, 1977||Great Bakersfield Dust Storm|

## Dust storms list

<ul>
{% for storm in site.data.storms %}
   <li>
   {{ storm.name }}: On {{ storm.date }} at {{ storm.place }}
   </li>
{% endfor %}
</ul>

## See also

-  [How to storm a castle](storm_task.md)
-  [What is a storm](storm_concept.md)
