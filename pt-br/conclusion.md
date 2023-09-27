---
layout: default
title: Parabéns!
number: 8
locale: pt-br
---

Você completou todos os exercícios!

Acredite ou não, apenas _acabamos de começar_ a explorar o que pode ser feito
com Markdown. Há muitas implementações "extendidas" do Markdown que suportam
formatos como tabelas, listas de definição, notas de rodapé, e mais. Como
elas não são padronizadas, não são essenciais para aprender o básico, como já
introduzimos aqui.

Se você quiser saber mais sobre essas implementações do Markdown, sinta-se convidado(a)
para explorar vários outros aplicativos e tutoriais sobre Markdown. Aqui estão alguns:

{% for link in site.data.resources.links %}
* <{{ link }}>
{% endfor %}
