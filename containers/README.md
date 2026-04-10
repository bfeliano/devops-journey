# Docker

Docker é uma plataforma open source que simplifica a criação, o empacotamento,
a distribuição e o gerenciamento de aplicações utilizando **containers**.  

> ℹ️ **Aviso**  
> Os recursos listados neste documento são baseados na minha experiência
pessoal e nos materiais que utilizei ao longo da minha jornada profissional.  
> Eles não representam recomendações oficiais da Docker Inc.

## Português

<div class="card-grid">
{% for item in site.data.containers.docker.portugues %}
  {% include card.html
    title=item.title
    badge_class=item.badge_class
    badge_text=item.badge_text
    meta=item.meta
    description=item.description
    url=item.url
  %}
{% endfor %}
</div>

## Inglês

<div class="card-grid">
{% for item in site.data.containers.docker.ingles %}
  {% include card.html
    title=item.title
    badge_class=item.badge_class
    badge_text=item.badge_text
    meta=item.meta
    description=item.description
    url=item.url
  %}
{% endfor %}
</div>

⬅️ [Voltar ao início](../)
