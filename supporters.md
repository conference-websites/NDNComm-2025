---
layout: default
title: Supporters
---

## Industrial Supporters

<p>
You want to support ACM ICN 2023? Check our <a href="cf-supporters.html">Call for Supporters</a>.
</p>

### Platinum

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "platinum"
%}<a href="{{ supporter[2] }}"><img src='{% link assets/images/sponsors/{{ supporter[1] }} %}' alt="{{ supporter[3] }}" style="height: 80px; margin: 10px"/></a>
{% endif
%}{% endfor %}
</div>
</p>

### Gold

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "gold"
%}<a href="{{ supporter[2] }}"><img src='{% link assets/images/sponsors/{{ supporter[1] }} %}' alt="{{ supporter[3] }}" style="height: 100px; margin: 25px" /></a>
{% endif
%}{% endfor %}
</div>
</p>


### Silver


<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "silver"
%}<a href="{{ supporter[2] }}"><img src='{% link assets/images/sponsors/{{ supporter[1] }} %}' alt="{{ supporter[3] }}" style="height: 100px; margin: 25px" /></a>
{% endif
%}{% endfor %}
</div>
</p>

### Bronze

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "bronze"
%}<a href="{{ supporter[2] }}"><img src='{% link assets/images/sponsors/{{ supporter[1] }} %}' alt="{{ supporter[3] }}" style="height: 100px; margin: 25px" /></a>
{% endif
%}{% endfor %}
</div>
</p>

### Core Sponsors

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "other"
%}<a href="{{ supporter[2] }}"><img src='{% link assets/images/sponsors/{{ supporter[1] }} %}' alt="{{ supporter[3] }}" style="height: 120px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>
