# DigitalCar

> Ayol haydovchilar uchun mashina xizmati kalkulyatori: oddiy va tushunarli tilda.

DigitalCar — Chevrolet avtomobillari (Onix, Cobalt, Damas, Spark, Nexia 3, Tracker) egalari, ayniqsa professional va aniq qo'llanma istagan ayol haydovchilar uchun keyingi texnik xizmat nima, qachon va qancha turishini ortiqcha texnik jargonsiz 30 soniyada bashorat qilib beruvchi mobil-birinchi veb-ilova.

---

## Jonli havola va foydalanish

* **Onlayn veb-ilova (GitHub Pages):** [https://atabaev.github.io/DigitalCar/](https://atabaev.github.io/DigitalCar/)
* **Offlayn rejimda:** `index.html` faylini istalgan brauzerda ikki marta bosib ochish kifoya (hech qanday server yoki o'rnatish talab qilinmaydi).

---

## Qo'llab-quvvatlanadigan modellar (6 ta model)

1. **Chevrolet Onix** (1.2 MT, 1.2 Turbo AT) — to'liq zavod oraliqlari va narxlar smetasi bilan.
2. **Chevrolet Cobalt** (1.5 MT, 1.5 AT) — zavod oraliqlari va qismlar holati.
3. **Chevrolet Damas** (0.8 MT) — zavod oraliqlari va qismlar holati.
4. **Chevrolet Spark** (1.2 MT, 1.2 AT) — zavod oraliqlari va qismlar holati.
5. **Chevrolet Nexia 3** (1.5 MT, 1.5 AT) — zavod oraliqlari va qismlar holati.
6. **Chevrolet Tracker** (1.2 Turbo AT) — zavod oraliqlari va qismlar holati.

### Yangi model yoki trim qo'shish
Barcha modellar `data/cars.js` faylida markazlashtirilgan. Yangi model qo'shish uchun:
1. `images/` papkasiga avtomobil rasmini joylang (masalan, `model.png` yoki `model.jpg`).
2. `data/cars.js` ichida `CAR_NOM` obyektini qo'shing: `id`, `name`, `image`, `years`, `years_verified: false`, `trims: [ { name, parts: [ ... ] } ]`.
3. Har bir qism uchun oddiy tildagi tushuntirish (`why`) maydonini to'ldiring.

---

## Asosiy qulayliklar

1. **Ayol haydovchilar uchun qulay ohang:** Murakkab mexanik atamalar o'rniga har bir detal uchun *"Nima uchun kerak?"* degan sodda izoh berilgan.
2. **"Shu probegga qadar odatda nima bo'lishi kerak edi":** Probeg va avtomobil yoshi bo'yicha qaysi xizmatlar taxminan necha marta o'tkazilishi kerak bo'lganligi ko'rsatiladi.
3. **Servisda nima so'rash kerak (Checklist):** Ustaxonaga borganda ustadan nimalarni so'rash va hisob-fakturaga nimalarni yozdirish bo'yicha aniq nazorat ro'yxati.
4. **Priborlar panelidagi 6 ta asosiy belgi:** Moy bosimi, harorat, akkumulyator, tormoz, check engine va shina bosimi haqida oddiy tushuncha va amaliy harakatlar.
5. **A4 Servis kitobchasi:** Bir bosishda chop etishga tayyor servis hisoboti.

---

## Ogohlantirish

> Ayol haydovchilar uchun sodda va tushunarli qo'llanma. Taxminiy hisob. Narxlar 2026-noyabr o'rtacha bozor narxi. Rasmiy servis xulosasi o'rnini bosmaydi.

---

## Mualliflar va Litsenziya

* **Muallif:** [LOYIHA EGASI ISMI], [KAFEDRA NOMI], Andijon davlat texnika instituti
* **Litsenziya:** Barcha huquqlar himoyalangan. Ilmiy-ta'lim prototipi.
