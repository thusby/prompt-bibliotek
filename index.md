---
layout: default
title: Heim
---

# 📚 Prompt-bibliotek for AI-arbeid

**Kurerte samlingar av AI-prompt på nynorsk**

## 🎯 Kven er du?

Vel persona for å sjå relevant innhald:

<div class="persona-grid">
  {% for persona in site.personas %}
  <div class="persona-card">
    <div class="persona-icon">{{ persona.ikon }}</div>
    <h3>{{ persona.namn }}</h3>
    <p>{{ persona.beskriving }}</p>
    <a href="{{ persona.url | relative_url }}">Utforsk →</a>
  </div>
  {% endfor %}
</div>

## 📖 Eller utforsk direkte

- [Alle prompt]({{ '/prompt/' | relative_url }})
- [Alle personas]({{ '/personas/' | relative_url }})

## 📊 Biblioteket i tal

- **{{ site.personas | size }}** personas
- **{{ site.prompt | size }}** prompt
- **{{ site.grupper | size }}** grupper
- **Sist oppdatert:** {{ site.time | date: "%Y-%m-%d" }}

## 🚀 Kom i gang på 3 minutt

1. **Vel din persona** → Finn prompt relevante for deg
2. **Kopier persona-instruksjonar** → Lim inn i AI-samtalen
3. **Vel eit prompt** → Tilpass og bruk!

## 🤝 Bidra

Dette er eit open source-prosjekt. [Les korleis du kan bidra](CONTRIBUTING.html).