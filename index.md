a collection of random thoughts

## whoami

I make computers work, sometimes. You can check out what I do on my GitHub
profile: [link](https://github.com/mkopec)

## Posts

{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
  <p>{{ content }}</p>
{% endfor %}

