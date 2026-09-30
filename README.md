# Coin Apartments & Poshtel

Live site: https://coin.chernivtsi.space

## About
Coin Apartments & Poshtel — хостел і апартаменти у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Викарбувана монета: латунний диск із рифленим гуртом (repeating-conic-gradient), написом по колу APARTMENTS · POSHTEL · ЧЕРНІВЦІ і «COIN» у центрі, на темному тлі.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Безкоштовна парковка
- Спільна кухня
- Лаунж
- Бар
- Кав’ярня
- Цілодобова рецепція
- Сімейні номери
- Трансфер з аеропорту

## Check-in / check-out
Заїзд 14:00–22:00; Виїзд 10:00–12:00

## Reviews
Booking.com 8.3/10 (803), Google 4.3/5 (413). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 50 287 7877
- Booking.com: https://www.booking.com/hotel/ua/c-o-i-n.html
- Google Maps: https://maps.google.com/?cid=14192658132072647056
- Address: не публікується (конфлікт джерел), лише «Чернівці»

## Not published
Вулиця й номер будинку (Google Maps показує Казармений пров., 7, Booking.com — Головна, 119; конфлікт не вирішено), тому немає вбудованої карти й streetAddress у schema; кількість кімнат і ліжок, зірковість, email, сайт, Instagram. Форма — хостельний варіант із типом кімнати та статтю гостей.

## Forms
HotelOS (`ch-coin`): `stay-request` (хостельний варіант зі статтю гостей). Документ `hotels/ch-coin` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Резиденція буковинських митрополитів, нині Чернівецький університет: pexels.com/photo/38163639 (Natalia Sevruk)
- Дворик, оповитий плющем: pexels.com/photo/17268819 (Андрій Копічевський)
- Цегляні склепіння: pexels.com/photo/17280128 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hostel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
