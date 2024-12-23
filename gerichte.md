---
layout: page
title: "Gerichte"
permalink: /gerichte/
---

Hier finden Sie alle getesteten Kaiserschmarrn-Gerichte, geordnet nach meinen persönlichen Bewertungen.

{% for post in site.categories.gerichte %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><strong>Gesamtbewertung:</strong> {{ post.rating }} / 10</p>
  <p>{{ post.excerpt }}</p>
{% endfor %}

---

# Beispiel-Erfahrungsberichte

---
layout: post
title: "Kaiserschmarrn im Gasthaus Alpenblick"
date: 2024-12-01
categories: gerichte
rating: 9
---

**Genereller Geschmack:** Der Kaiserschmarrn war luftig und perfekt karamellisiert.

**Besonderheiten:** Die hausgemachte Zwetschgenröster-Beilage war ein Traum.

**Service:** Sehr freundliches Personal und schneller Service.

**Gesamtbewertung:** 9 / 10

---
layout: post
title: "Kaiserschmarrn in der Berghütte Edelweiß"
date: 2024-12-02
categories: gerichte
rating: 7
---

**Genereller Geschmack:** Solider Geschmack, aber etwas zu trocken.

**Besonderheiten:** Große Portion, die für zwei Personen reicht.

**Service:** Gemütliche Atmosphäre, aber etwas langsam.

**Gesamtbewertung:** 7 / 10

---
layout: post
title: "Kaiserschmarrn im Café Sonnenschein"
date: 2024-12-03
categories: gerichte
rating: 8
---

**Genereller Geschmack:** Sehr lecker, mit feinem Vanillearoma.

**Besonderheiten:** Mit Mandelsplittern und Rosinen verfeinert.

**Service:** Aufmerksam und zuvorkommend.

**Gesamtbewertung:** 8 / 10

---
layout: post
title: "Kaiserschmarrn bei Oma Maria"
date: 2024-12-04
categories: gerichte
rating: 10
---

**Genereller Geschmack:** Perfekt gebacken, wie man es sich wünscht.

**Besonderheiten:** Geheimrezept mit einem Hauch Zimt.

**Service:** Familiär und herzlich.

**Gesamtbewertung:** 10 / 10