---
sort: 3
---

# Posts

Browse in this archive by month and year

{% assign postsByYearMonth = site.posts | group_by_exp: "post", "post.date | date: '%B %Y'" %}
{% for yearMonth in postsByYearMonth %}

<h3 id="{{ yearMonth.name }}">{{ yearMonth.name }}</h3>
<ul>
  {% for post in yearMonth.items %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>

        &nbsp;

        {%- for tag in post.tags -%}
            <small>
                <a class="post-tag" href="/tag_index#{{tag}}">
                    {{ tag }}
                </a>
            </small>
        {%- endfor -%}
    </li>

{% endfor %}

</ul>
{% endfor %}

<!--- ```
Hey @saowang, what do you think of this?
``` 

Hey @saowang, what do you think of this?

```tip
Set config `plugins: [jekyll-mentions]`

For documentation, see: [https://github.com/jekyll/jekyll-mentions](https://github.com/jekyll/jekyll-mentions)
```
-->
