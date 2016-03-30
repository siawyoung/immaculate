---
layout: default
---

<main>

  <section>
      <h1>{{ site.title }}</h1>
      <h3>{{ site.description }}</h3>
  </section>

  <div>
    {% for post in paginator.posts %}
      <article itemscope itemtype="http://schema.org/BlogPosting" role="article">

          <header>
            <h2 itemprop="name"><a href="{{ site.baseurl }}{{ post.url }}" itemprop="url">{{ post.title }}</a></h2>
          </header>

          <div class="post-meta">
            <time datetime="{{ post.date | date_to_long_string }}">{{ post.date | date_to_long_string }}</time>
          </div>

          <section itemprop="description">
            {{ post.content | markdownify }}
          </section>

      </article>
    {% endfor %}
  </div>

  <nav role="navigation">
    {% if paginator.total_pages > 1 %}
    <div class="pagination">
      {% if paginator.previous_page %}
        <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&laquo; Prev</a>
      {% else %}
        <span>&laquo;</span>
      {% endif %}

      {% for page in (1..paginator.total_pages) %}
        {% if page == paginator.page %}
          <em>{{ page }}</em>
        {% elsif page == 1 %}
          <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">{{ page }}</a>
        {% else %}
          <a href="{{ site.paginate_path | prepend: site.baseurl | replace: '//', '/' | replace: ':num', page }}">{{ page }}</a>
        {% endif %}
      {% endfor %}

      {% if paginator.next_page %}
        <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Next &raquo;</a>
      {% else %}
        <span>&raquo;</span>
      {% endif %}
    </div>
    {% endif %}
  </nav>

</main>

{% include footer.html %}
