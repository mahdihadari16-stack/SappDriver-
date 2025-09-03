## 📝 توضیح Pull Request

<!-- توضیح بده که این Pull Request چه کاری انجام می‌ده. چه مشکلی رو حل کرده یا چه قابلیتی اضافه شده؟ -->

## ✅ نوع تغییرات

لطفاً نوع تغییرات این Pull Request را مشخص کنید:

- [ ] رفع باگ 🐞
- [ ] افزودن ویژگی جدید ✨
- [ ] بهبود مستندسازی 📚
- [ ] بهبود عملکرد یا طراحی 💡
- [ ] سایر موارد:

## 📌 ارتباط با Issue

<!-- اگر این Pull Request مربوط به یک Issue خاص هست، شماره آن را بنویسید. مثلا: Closes #12 -->

## 📷 اسکرین‌شات‌ها (در صورت نیاز)

<!-- اگر تغییرات ظاهری داشتید، لطفاً اسکرین‌شات اضافه کنید تا بررسی راحت‌تر انجام شود -->

## 🔍 چک‌لیست قبل از Merge

لطفاً مطمئن شوید که موارد زیر رعایت شده‌اند:

- [ ] کد تست شده و بدون خطاست
- [ ] مستندات به‌روز شده
- [ ] تغییرات در محیط توسعه بررسی شده
- [ ] وابستگی جدیدی اضافه نشده یا توضیح داده شده

## 👤 اطلاعات توسعه‌دهنده

نام: <!-- نام خودتان -->
نقش: <!-- مثلا توسعه‌دهنده اصلی، مشارکت‌کننده، طراح رابط کاربری -->

## 📅 اطلاعات زمان‌بندی (اختیاری)

- تاریخ شروع: <!-- YYYY-MM-DD -->
- تاریخ پایان: <!-- YYYY-MM-DD -->
- نقطه عطف مرتبط: <!-- اگر مربوط به milestone خاصی هست -->
{
  "name": "azure-webapp-project",
  "version": "1.0.0",
  "description": "پروژه وب اپلیکیشن Azure",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "build": "npm run build:client",
    "build:client": "webpack --mode=production",
    "test": "jest",
    "test:watch": "jest --watch",
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  },
  "keywords": [
    "azure",
    "webapp",
    "nodejs"
  ],
  "author": "mahdihada",
  "license": "MIT",
  "dependencies": {
    "express": "^4.18.2",
    "cors": "^2.8.5",
    "helmet": "^7.0.0",
    "morgan": "^1.10.0",
    "dotenv": "^16.3.1",
    "compression": "^1.7.4"
  },
  "devDependencies": {
    "nodemon": "^3.0.1",
    "jest": "^29.7.0",
    "eslint": "^8.45.0",
    "webpack": "^5.88.2",
    "webpack-cli": "^5.1.4"
  },
  "engines": {
    "node": ">=18.0.0",
    "npm": ">=9.0.0"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/mahdihada/your-repo.git"
  },
  "bugs": {
    "url": "https://github.com/mahdihada/your-repo/issues"
  },
  "homepage": "https://github.com/mahdihada/your-repo#readme"
}
