# LIFEHUB — Aqlli Hayot Boshqaruvi Platformasi (Smart Life Management Platform)

**LIFEHUB** — kundalik hayotning barcha muhim jabhalarini yagona, qulay va zamonaviy interfeysdan turib boshqarish imkonini beruvchi premium veb-platforma. 

Platforma to‘liq o‘zbek tilida ishlab chiqilgan, zamonaviy SaaS ilovalar dizayn standartlariga (Midnight Navy, Electric Blue, Soft Violet) asoslangan hamda ma’lumotlarni brauzerning `localStorage` xotirasida avtomatik saqlaydi.

---

## 🚀 Texnologiyalar (Tech Stack)

- **Frontend kutubxonasi**: React 18 (TypeScript)
- **Kompilyator va vosita**: Vite
- **Stillar va dizayn**: Tailwind CSS (maxsus ranglar palitrasi, yorug‘ va tungi rejim)
- **Ikonkalar**: Lucide React
- **Animatsiyalar**: Framer Motion
- **Ma’lumotlarni saqlash**: HTML5 `localStorage` (sahifa yangilanganda ma’lumotlar saqlanib qoladi)
- **Grafiklar va statistika**: Interaktiv SVG tahliliy diagrammalar

---

## 🌟 Asosiy Modullar va Imkoniyatlar

### 1. Boshqaruv Paneli (Dashboard)
- Shaxsiylashtirilgan tabrik (`Xush kelibsiz, Alisher!`) va sana ko‘rsatkichi.
- Tezkor harakat tugmalari (*Yangi vazifa*, *Xarid qo‘shish*, *Xarajat kiritish*, *Eslatma o‘rnatish*, *Oilaviy tadbir*).
- 4 ta asosiy metrika kartasi (vazifalar bajarilishi, jami xarajatlar, xaridlar savati, eslatmalar).
- Haftalik faollik dinamikasi grafigi (SVG bar chart, interaktiv tooltip bilan).
- Xarajatlar toifalari taqsimoti (progress bar va foizlar).
- Bugungi vazifalar, eng yaqin xaridlar va kelgusi eslatmalar vidjetlari.

### 2. Aqlli Vazifalar Menejeri (Smart Task Manager)
- Yangi vazifa qo‘shish, tahrirlash va o‘chirish (tasdiqlash bilan).
- Bajarilgan deb belgilash (chizilgan shrift va animatsiyalar).
- Vazifa muddatlari va ustuvorlik darajalari: **Past**, **O‘rta**, **Yuqori**.
- Filtrlash: *Barchasi*, *Bugun*, *Kelgusi*, *Bajarildi*.
- Kalit so‘z bo‘yicha tezkor qidiruv va muddat/ustuvorlik bo‘yicha saralash.
- Vazifalar bajarilish foizi ko‘rsatkichi (progress bar).

### 3. Xaridlar Ro‘yxati (Smart Shopping List)
- Bir nechta xaridlar ro‘yxatini yaratish (*Haftalik bozorlik*, *Uy-ro‘zg‘or*, *Maktab*, h.k.).
- Mahsulot nomi, miqdori va o‘lchov birligi (*kg*, *dona*, *litr*, *pachka*, *quti*, *metr*).
- Taxminiy narxlarni so‘mda (UZS) ko‘rsatish va umumiy smetani hisoblash.
- Olingan va qolgan mahsulotlar hisob-kitobi.
- Namunaviy mahsulotlar (go‘sht, non, sut, tuxum, guruch, meva, sabzavotlar).
- *Eslatma*: Shaxsiy rejalashtirish vositasi bo‘lib, to‘g‘ridan-to‘g‘ri yetkazib berish xizmati emas.

### 4. Oilaviy Rejalashtiruvchi (Family Organizer)
- Oila a’zolari tarkibi (Ota, Ona, O‘g‘il, Qiz) va ularning rangli avatarlari.
- Oilaviy tadbirlar, tug‘ilgan kunlar 🎂 va muhim sanalar taqvimi.
- Umumiy uy-ro‘zg‘or vazifalarini oila a’zolariga biriktirish.
- Ko‘chma qurilmalar o‘rtasidagi sinxronizatsiya va lokal xotira haqida tushuntirish.

### 5. Xarajatlar Nazorati (Expense Tracker)
- Xarajat miqdori (UZS), toifasi, sanasi va izohini kiritish.
- Toifalar: *Oziq-ovqat*, *Transport*, *Ta'lim*, *Uy-ro‘zg‘or*, *Sog‘liq*, *Ko‘ngilochar*, *Boshqa*.
- Jami sarflangan mablag‘ va o‘rtacha chek ko‘rsatkichi.
- Toifalar bo‘yicha ulushlarni diagrammada aks ettirish.
- Tranzaksiyalar tarixi va qidiruv.
- *Eslatma*: Bank hisoblariga ulanmagan mustaqil rejalashtirish tizimi.

### 6. Aqlli Eslatmalar (Reminders)
- Sarlavha, sana, vaqt va toifa bo‘yicha eslatmalar.
- Bajarilgan deb belgilash va vaqt bo‘yicha saralash.
- Nisbiy vaqt ko‘rsatkichlari (*Bugun*, *Ertaga*, *Kechikkan*, *X kundan so‘ng*).
- Brauzer bildirishnomalari (Web Notification API) ruxsatini boshqarish.

### 7. Global Qidiruv (Smart Search)
- `Ctrl + K` yoki bosh sarlavhadagi qidiruv orqali faollashadi.
- Barcha bo‘limlar bo‘yicha guruhlangan tezkor natijalar (vazifalar, xaridlar, xarajatlar, eslatmalar, oilaviy rejalar).
- To‘g‘ridan-to‘g‘ri kerakli bo‘limga o‘tish.

### 8. Sozlamalar va Tashqi Ko‘rinish
- Yorug‘ (Light) va Midnight Navy (Dark) mavzulari.
- Tizim tili va valyuta sozlamalari.
- Foydalanuvchi profilini tahrirlash (ism, elektron pochta).
- Namunaviy ma’lumotlarni bir tugma bilan qayta tiklash (Reset to demo).
- Barcha ma’lumotlarni tozalash (Clear all data).

---

## 💻 Ilovani Ishga Tushirish (How to Run Locally)

Ushbu ilovani ishga tushirish uchun kompyuteringizda **Node.js** (v18 yoki undan yuqori) o‘rnatilgan bo‘lishi lozim.

Loyiha papkasiga o‘ting va quyidagi buyruqlarni bajaring:

```bash
# 1. Kerakli kutubxonalarni o'rnatish
npm install

# 2. Dasturchi serverini ishga tushirish
npm run dev
```

Server ishga tushgach, brauzeringizda quyidagi manzilni oching:
👉 **`http://localhost:3000`**

---

## 📁 Loyiha Tuzilmasi

```
123/
├── package.json
├── vite.config.ts
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
├── index.html
├── src/
│   ├── main.tsx
│   ├── App.tsx
│   ├── index.css
│   ├── types/
│   │   └── index.ts                 # To'liq TypeScript interfeyslari
│   ├── context/
│   │   ├── AppContext.tsx           # Asosiy holat va CRUD amallari
│   │   └── ThemeContext.tsx         # Yorug' va tungi rejim boshqaruvi
│   ├── data/
│   │   └── sampleData.ts            # O'zbekcha namunaviy ma'lumotlar
│   ├── utils/
│   │   ├── formatters.ts            # So'm, o'zbekcha sana va nisbiy vaqt
│   │   └── storage.ts               # LocalStorage xavfsiz o'qish/yozish
│   └── components/
│       ├── common/                  # Modal, Toast, ConfirmDialog, Badge, StatCard
│       ├── layout/                  # Sidebar, Header, MobileNav, GlobalSearchModal
│       ├── dashboard/               # Bosh sahifa vidjetlari va grafiki
│       ├── tasks/                   # Vazifalar boshqaruvi va filtrlash
│       ├── shopping/                # Xaridlar savati, toifalar va narxlar
│       ├── family/                  # Oilaviy tadbirlar va vazifalar
│       ├── expenses/                # Xarajatlar monitoringi va tahlil
│       ├── reminders/               # Eslatmalar va bildirishnomalar
│       └── settings/                # Sozlamalar va ma'lumotlar boshqaruvi
```
# LIFEHUB
