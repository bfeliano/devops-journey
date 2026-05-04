# Linguagens de Programação

Aqui você encontra cursos, dicas e outros conteúdos relacionados a
linguagens de programação, com foco em aprendizado prático e
aplicabilidade no dia a dia.  

> ℹ️ **Aviso**  
> Os recursos listados neste documento são baseados na minha experiência
pessoal e nos materiais que utilizei ao longo da minha jornada profissional.  

## Fundamentos de Programação

Cursos introdutórios focados em lógica de programação,
pensamento computacional e conceitos base, independentes de linguagem.  

### Português

<div class="card-grid">
{% for item in site.data.programming.fundamentos.portugues %}
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

## Python

Conteúdos voltados ao aprendizado e uso prático da linguagem Python.

<div class="card-grid">
{% for item in site.data.programming.python.portugues %}
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

## JavaScript

### Inglês

<div class="card-grid">
{% for item in site.data.programming.javascript.ingles %}
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
