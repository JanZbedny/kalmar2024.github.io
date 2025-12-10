---
title: Curriculum Vitae
layout: default
---

# Curriculum Vitae

## 🧑‍💼 Dane osobowe
- **Imię i nazwisko:** {{ site.title }}
- **Email:** example@example.com
- **Telefon:** +48 123 456 789
- **Adres:** Twoje miasto

---

## 🎓 Wykształcenie — Oś czasu

<div class="timeline">

  <div class="entry">
    <div class="icon">🎓</div>
    <div class="content">
      <h3>Szkoła / kierunek</h3>
      <span class="date">2010 — 2015</span>
      <p>Opis szkoły, kierunku, kwalifikacji.</p>
    </div>
  </div>

  <div class="entry">
    <div class="icon">🎓</div>
    <div class="content">
      <h3>Szkoła 2</h3>
      <span class="date">2007 — 2010</span>
      <p>Opis drugiej szkoły.</p>
    </div>
  </div>

</div>

---

## 💼 Doświadczenie zawodowe — Oś czasu

<div class="timeline cv-timeline">
  {% for item in site.data.experience %}
  <div class="timeline-item">
    <div class="timeline-icon"><i class="fa-solid fa-briefcase"></i></div>
    <div class="timeline-line"></div>
    <div class="timeline-content">
      <span class="timeline-year">{{ item.year }}</span>
      <h3>{{ item.company }}</h3>
      <p>{{ item.position }}</p>
    </div>
  </div>
  {% endfor %}
</div>

---

## 🧠 Umiejętności

- Programowanie: Python, Java, C#
- HTML, CSS, Jekyll, GitHub Pages
- Systemy Windows & Linux
- Obsługa sprzętu i diagnostyka IT

---

## 📄 Pobierz pełne CV (PDF)

👉 _Prześlij mi PDF, a przygotuję automatyczne pobieranie tutaj._

---


---

