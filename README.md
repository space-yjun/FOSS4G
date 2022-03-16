# FOSS4G
오픈소스 GIS 심화과정 강의
```
<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h1><a href="{{ site.baseurl }}{{ post.url }}">
      {{ post.title }} </a></h1>
        <div class="entry">
          {{ post.excerpt }}
         </div>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
     </article>
   {% endfor %}
   

</div>
```

# Git Branch