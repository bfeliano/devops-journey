# Dados

Aqui você encontra cursos, dicas e outros conteúdos relacionados a
engenharia de dados, análise de dados e plataformas modernas como
Databricks, com foco em aprendizado prático e aplicabilidade no dia a dia.

> ℹ️ **Aviso**  
> Os recursos listados neste documento são baseados na minha experiência
pessoal e nos materiais que utilizei ao longo da minha jornada profissional.  

## Engenharia de Dados

Conteúdos voltados à engenharia de dados utilizando ferramentas modernas
como Databricks, Apache Spark e arquitetura Lakehouse.

> ⭐ Indicado para quem deseja trabalhar com pipelines de dados,
transformação, análise em larga escala e ambientes cloud.

### Português

<div class="card-grid">
{% for item in site.data.dados.data-engineering.portugues %}
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

### Inglês

<div class="card-grid">
{% for item in site.data.dados.data-engineering.ingles %}
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
