# Tayyorlov.uz - Oʻquv Kurslari Platformasi

## 📌 Kirish

Tayyorlov.uz - Oʻzbekistondagi barcha tayyorlov kurslari va oʻquv markazlarini bitta platformada jamlovchi innovatsion yechim. Platforma oʻquvchilar va kurs provayderlari oʻrtasida samarali aloqa kanali yaratadi.

## 🌟 Asosiy Imkoniyatlar

### 🎓 Oʻquvchilar uchun
- Hududingizdagi eng yaxshi kurslarni topish
- Kurslarni narx, joylashuv va baholar boʻyicha solishtirish
- Haqiqiy sharhlar va baholarni koʻrish
- Telegram orqali tezkor bildirishnomalar

### 💼 Kurs Egasi/Koʻrsatuvchilar uchun
- Kurslaringizni platformaga qoʻshish va boshqarish
- Potensial oʻquvchilar bilan bogʻlanish
- Kurs statistikasini koʻrish va tahlil qilish
- Reklama qilish imkoniyati

## 🛠 Texnologik Stack

### Frontend
- **React.js** (asosiy framework)
- **Redux Toolkit** (state management)
- **Tailwind CSS** (styling)
- **Axios** (API calls)

### Backend
- **Node.js** (runtime)
- **Express.js** (web framework)
- **PostgreSQL** (database)
- **Sequelize** (ORM)

### Qoʻshimcha
- **Telegram Bot API** (bildirishnomalar uchun)
- **Docker** (containerization)
- **Nginx** (reverse proxy)

## 🚀 Oʻrnatish

### Dastlabki Talablar
- Node.js (v16+)
- PostgreSQL (v12+)
- Git

### Qoʻllanma

1. Repozitoriyani klon qiling:
```bash
git clone https://github.com/sizning-repo/tayyorlov-uz.git
cd tayyorlov-uz
```

2. Dependensiyalarni oʻrnatish:
```bash
npm install
cd client && npm install
cd ../server && npm install
```

3. Maʼlumotlar bazasini sozlang:
```bash
createdb tayyorlov
```

4. Konfiguratsiya faylini yaratish (.env):
```env
# Umumiy sozlamalar
PORT=5000
NODE_ENV=development

# DB sozlamalari
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=yourpassword
DB_NAME=tayyorlov

# Auth sozlamalari
JWT_SECRET=your_jwt_secret_here
JWT_EXPIRES_IN=30d

# Telegram sozlamalari
TELEGRAM_BOT_TOKEN=your_bot_token
TELEGRAM_CHAT_ID=your_chat_id
```

5. Dasturni ishga tushirish:
```bash
# Backend ishga tushirish
cd server && npm run dev

# Frontend ishga tushirish (yangi terminalda)
cd client && npm start
```

## 📂 Fayl Tuzilmasi

```
tayyorlov-uz/
├── client/               # Frontend qismi
│   ├── public/           # Static fayllar
│   ├── src/              # Asosiy kod
│   │   ├── components/   # UI komponentlari
│   │   ├── pages/        # Sahifalar
│   │   ├── store/        # Redux store
│   │   └── App.js        # Asosiy app
│   └── package.json
│
├── server/              # Backend qismi
│   ├── config/          # Konfiguratsiyalar
│   ├── controllers/     # Kontrollerlar
│   ├── middlewares/     # Middlewarelar
│   ├── models/          # DB modellari
│   ├── routes/          # API yoʻllari
│   ├── utils/           # Yordamchi funksiyalar
│   ├── app.js           # Asosiy app
│   └── package.json
│
├── telegram-bot/        # Telegram bot
├── docker-compose.yml   # Docker konfiguratsiyasi
└── README.md            # Bu fayl
```

## 🌍 Deployment

### Docker orqali

1. Docker va Docker Compose oʻrnating
2. `.env` faylni toʻldiring
3. Quyidagi komandani ishga tushiring:
```bash
docker-compose up --build
```

### Qoʻlda Deployment

1. Serverga SSH orqali ulaning
2. Repozitoriyani klon qiling
3. `.env` faylni sozlang
4. Dependensiyalarni oʻrnatish
5. PM2 yoki similar process manager bilan ishga tushiring

## 📝 Litsenziya

Bu loyiha [MIT litsenziyasi](LICENSE) ostida chiqarilgan.

## 📞 Bogʻlanish

Loyiha haqida qoʻshimcha maʼlumot uchun:
- Email: [info@tayyorlov.uz](mailto:info@tayyorlov.uz)
- Telegram: [@tayyorlovuz_support](https://t.me/tayyorlovuz_support)

---

## DeepSeek
