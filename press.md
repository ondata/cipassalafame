---
layout: default
title: Press
permalink: /press/
---

{: .table .table-striped #press}
Data            |Descrizione             |Fonte        |Denominazione
:---------------|:-----------------------|:------------|:-------------------
{% for member in site.data.press %} {{member.data | date: '%d/%m/%Y'}} | {{member.dove}} | {{member.titolo}} | [Fonte]({{member.link}})
{% endfor %}