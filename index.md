## Test 123

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[test post link]({{ site.baseurl }}{% post_url 2017-02-22-test %})