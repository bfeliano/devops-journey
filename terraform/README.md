# Terraform

Terraform é uma ferramenta de **Infrastructure as Code (IaC)** que permite
criar, modificar e versionar recursos de infraestrutura em ambientes de cloud
e on‑premises de forma segura e eficiente.

> ℹ️ **Aviso**  
> Os recursos listados neste documento são baseados na minha experiência
pessoal e nos materiais que utilizei ao longo da minha jornada profissional.  
> Eles não representam recomendações oficiais da HashiCorp.

## HashiCorp Certified: Terraform Associate

Recursos de estudo úteis para ajudar na preparação para o exame
**HashiCorp Certified: Terraform Associate**.

> ⭐ Certificação recomendada para quem está começando com
Infrastructure as Code e Terraform  

## Português

<div class="card-grid">
{% for item in site.data.terraform.portugues %}
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
{% for item in site.data.terraform.ingles %}
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
