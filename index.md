---
layout: homepage
title:  "DikkeKlok.nl - De Dikste Klokken"
description: "De plek voor iedereen die op zoek is naar advies voor een eerste horloge, een klassieker, een sportief, of een echte Dikke Klok om mee te shinen!"
search: false
---

<div class="row-main">
  <div class="column-info" style="width: 55%; float:left">
    Bovenaan de site is het menu te vinden. Deze linkt naar de <strong><a href="/winkel">winkel</a></strong>, de <strong><a href="/blog">blog</a></strong> met verschillende artikelen (o.a. over de beste horloge <strong><a href="/accessoires/handigste-horloge-accessoires">accessoires</a></strong> en <strong><a href="/categories#alternatief">alternatieve keuzes</a></strong>), en een overzicht van <strong><a href="/best-buy">de beste aankopen</a></strong> van dit moment!    
    <hr>
    <h3>Beschikbaar in de winkel:</h3>

    <div class="entries-grid">
      {%- for entry in site.winkel limit:4 -%}
        {% include home/entry-featured-home.html %}
      {%- endfor -%}
    </div>
  </div>

  <div class="column-articles" style="width: 40%; float:right;">
    <div class="entries-grid">
      {%- for entry in site.posts limit:4 -%}
        {% if forloop.first %}
        {% else %}
          {% include home/entry-featured-home.html %}
        {% endif %}
      {%- endfor -%}
    </div>
  </div>
</div>

<div class="home-ad">
  <center><a href="https://partner.bol.com/click/click?p=1&amp;t=url&amp;s=1321762&amp;url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fm%2Fsieraden%2F&amp;f=BAN&amp;name=Sieraden%20en%20accessoires%20-%20NL&amp;subid=" target="_blank"><img src="https://www.bol.com/nl/upload/partnerprogramma/190605-sieraden-en-accessoires-pp-728x90.jpg" width="728" height="90" alt="Sieraden en accessoires - NL"  /></a><img src="https://partner.bol.com/click/impression?p=1&amp;s=1321762&amp;t=url&amp;f=BAN&amp;name=Sieraden%20en%20accessoires%20-%20NL&amp;subid=" width="1" height="1" alt="Sieraden en accessoires - NL"/></center>
</div>

### Beschikbaar in de winkel:
<div class="entries-grid">
  {%- for entry in site.winkel limit:4 -%}
    {% include home/entry-featured-home.html %}
  {%- endfor -%}
</div>

