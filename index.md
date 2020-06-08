---
layout: default
---


<div class="jumbotron bg-darkblue">
  <h1 class="display-5 bg-darkblue">Willkommen bei ready to go out!</h1>
  <p class="lead">{{ site.description }}</p>
  <hr class="my-4">
  <p>
    Du möchtest als Gruppe oder alleine das Geländespiel spielen und Spaß haben?
    Du möchtest in deiner Gruppenstunde oder bei einem anderen Event mit vielen Leuten spielen, und schonmal
    alle anmelden? Dann, worauf wartest du?
  </p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Los gehts!</a>
</div>


<div>
  {% for post in site.posts %}
    <div class="card my-4">
      <h5 class="card-header">{{ post.title }}</h5>
      <div class="card-body">
        {{ post.excerpt }}<a href="{{ post.url }}">mehr lesen...</a>
      </div>
    </div>
  {% endfor %}
</div>
