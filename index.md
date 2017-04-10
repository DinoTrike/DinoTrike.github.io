## Welcome to Dino Trike

![Dino Trike]({{ site.url }}/images/DinoTrike.png)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
