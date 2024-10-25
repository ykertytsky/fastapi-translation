# Зовнішні посилання та статті 

**FastAPI** має чудову спільноту, що постійно зростає.

Існує багато постів, статтей, інструментів і проєктів, що повʼязані з **FastAPI**.

Ось неповний список деяких з них: 

/// tip

Якщо у вас є стаття, проєкт інструмент, або будь-що повʼязане з **FastAPI** що ще не показаний у цьому списку is створіть <a href="https://github.com/fastapi/fastapi/edit/master/docs/en/data/external_links.yml" class="external-link" target="_blank">Pull request додавши його</a>.

///

{% for section_name, section_content in external_links.items() %}

## {{ section_name }}

{% for lang_name, lang_content in section_content.items() %}

### {{ lang_name }}

{% for item in lang_content %}

* <a href="{{ item.link }}" class="external-link" target="_blank">{{ item.title }}</a> by <a href="{{ item.author_link }}" class="external-link" target="_blank">{{ item.author }}</a>.

{% endfor %}
{% endfor %}
{% endfor %}

## Projects

Останні GitHub проєкти повʼязані з темою `fastapi`:

<div class="github-topic-projects">
</div>
