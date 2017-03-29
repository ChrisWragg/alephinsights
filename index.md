## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.summary }}
    </li>
  {% endfor %}
</ul>
