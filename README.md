# ▶️ TubeDZ TV

**TubeDZ TV** هو تطبيق خاص ومخصص لشاشات سامسونج الذكية (Samsung Tizen TVs) لتشغيل يوتيوب بأعلى جودة، بدون إعلانات وبدون مقاطع الرعاة المزعجة (SponsorBlock).

---

## ✨ المميزات الرئيسية (Features)
- 🛑 **مانع إعلانات مدمج (Ad Blocker)**: مشاهدة مستمرة بدون أي فواصل إعلانية.
- ❗ **دعم SponsorBlock**: تخطي المقاطع الترويجية والافتتاحيات تلقائياً أو يدوياً.
- 📺 **نمط صورة داخل صورة (PiP - Picture-in-Picture)**.
- ⏭️ **التحكم بسرعة الفيديو**: زيادة أو إنقاص سرعة التشغيل بدقة.
- 🔺 **دعم DeArrow**: استبدال العناوين المضللة (Clickbait) بعناوين دقيقة.
- 🔒 **نسخة خاصة ومستقلة (Private & Offline-ready)**: إيقاف التتبع والتحليلات الخارجية والتحديثات التلقائية غير المرغوبة.

---

## 🛠️ البناء والتطوير (Build & Compile)

### 1. بناء حزمة المستخدم (Userscript / Mods):
```bash
cd mods
npm install
npm run build
```
سيتم إنشاء الملف المترجم في `dist/userScript.js`.

### 2. بناء خدمة التطبيق (DIAL Service):
```bash
cd service
npm install
npx rollup -c rollup.config.js
```
سيتم إنشاء الملف في `dist/service.js`.

### 3. بناء خدمة الـ Standalone:
```bash
cd standalone/service
npm install
npm run build
```

---

## 🔒 جعل المستودع خاصاً على GitHub (Make it Private)

للحفاظ على خصوصية هذا المشروع بحيث لا يراه أحد غيرك:
1. توجه إلى صفحة المستودع على GitHub: [https://github.com/rr3050026-pixel/TUBEDZ-TV-/settings](https://github.com/rr3050026-pixel/TUBEDZ-TV-/settings)
2. انزل إلى أسفل الصفحة إلى قسم **Danger Zone**.
3. بجانب **Change repository visibility** اضغط على **Change to private**.
4. أكّد العملية باتباع التعليمات التي تظهر على الشاشة.

---

## 📄 الترخيص (License)
GPL-3.0-only
