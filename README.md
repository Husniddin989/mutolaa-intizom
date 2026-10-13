# Mutolaa — Intizom kundaligi

React + Vite + Tailwind CSS ilovasi.

## Docker
```bash
docker build -t mutolaa-intizom .
docker run -d --name mutolaa-intizom --restart unless-stopped -p 8080:80 mutolaa-intizom
```
Ochish: http://localhost:8080

## Lokal development
```bash
npm install
npm run dev
```

## Imkoniyatlar
- 30 kunlik taqvim va har kunlik mutolaa/xulosa qaydlari
- Dashboard, bajarilish foizi va ketma-ket kunlar hisoblagichi
- Fokus taymeri, pauza/davom ettirish/qayta boshlash
- Kitoblar kutubxonasi: qidiruv, filtr, yangi kitob, tahrirlash, status va asosiy kitob tanlash
- Sahifa soni va kundalik xulosalar
- Sozlamalar, JSON backup import/export, TXT hisobot eksporti
- localStorage orqali avtomatik saqlash, responsive UI

Ma’lumotlar shu brauzerda saqlanadi. Qurilmalararo sinxronlash uchun backend va autentifikatsiya qo‘shish kerak.
# mutolaa-intizom

