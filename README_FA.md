# 📻 رادیو ارک ماین

یک وب‌اپلیکیشن تک‌صفحه‌ای و کاملاً واکنش‌گرا برای پخش آنلاین رادیو که با **HTML، CSS و JavaScript خالص** ساخته شده — بدون هیچ فریم‌ورک یا ابزار build. روی موبایل، تبلت و دسکتاپ تجربه‌ای شبیه به اپ‌های نیتیو ارائه می‌دهد.

### 🔗 مشاهده آنلاین
👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)

![پیش‌نمایش](screenshot.png)

---

## ✨ ویژگی‌های کلیدی

- 🎧 **۹ ژانر موسیقی:** فونک، فونک۲، فارسی، لوفای، سول، راک، پاپ، هیپ‌هاپ، کانتری
- 📊 **Visualizer زنده:** نمایش موج دایره‌ای و طیف فرکانس با **Web Audio API**
- 🖼️ **کاورهای چرخشی:** هر ۱۲ ثانیه کاور آهنگ با انیمیشن نرم عوض می‌شود
- 🔊 **کنترل کامل صدا:** اسلایدر، دکمه بی‌صدا، نمایش درصد، پشتیبانی از کیبورد
- 📱 **طراحی موبایل‌فرست:** پشتیبانی از iPhone notch، حداقل تاچ ۴۴px، استفاده از `dvh`
- 🎨 **تم تیره نئون:** رنگ اصلی فیروزه‌ای (`#2dd4bf`) با افکت‌های glow
- ♿ **دسترس‌پذیری:** پشتیبانی از `prefers-reduced-motion`، focus ring، ARIA
- ⚡ **بهینه برای باتری:** Visualizer روی ۴۵fps throttle شده و هنگام مخفی شدن تب متوقف می‌شود

---

## 🛠️ تکنولوژی‌ها

- **HTML5** — ساختار معنایی و `<audio>`
- **CSS3** — Flexbox، Grid، `aspect-ratio`، `clamp()`، CSS variables
- **JavaScript ES6+** — Async/Await، Canvas API، Web Audio API

---

## 📂 ساختار پروژه

```
Radio-Ark-Mine/
├── .github/workflows/static.yml   # GitHub Actions برای دیپلوی
├── index.html                      # کل پروژه در یک فایل
├── LICENSE                         # لایسنس MIT
├── screenshot.png                  # تصویر پیش‌نمایش
└── README.md
```

---

## 🚀 نحوه استفاده

1. پروژه را کلون کن:
   ```bash
   git clone https://github.com/launchercs/Radio-Ark-Mine.git
   cd Radio-Ark-Mine
   ```
2. فایل `index.html` را در مرورگر باز کن — **یا** نسخه آنلاین را ببین:
   👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)
3. دکمه ▶️ را بزن و از پخش زنده لذت ببر.

> ⚠️ به‌دلیل سیاست **Autoplay** مرورگرها، پخش فقط با کلیک کاربر شروع می‌شود.

---

## 🌐 دیپلوی روی GitHub Pages

این پروژه از **GitHub Actions** برای دیپلوی خودکار استفاده می‌کند. هر بار که تغییری به برنچ `main` پوش کنی، سایت به‌طور خودکار به‌روزرسانی می‌شود.

**آدرس سایت:**
👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)

---

## ⚠️ سلب مسئولیت

این پروژه صرفاً برای **اهداف آموزشی** ساخته شده و محتوای پخش‌شده از سرورهای عمومی استریم خوانده می‌شود.

---

## 📄 لایسنس

تحت لایسنس **MIT** منتشر می‌شود — استفاده، تغییر و توزیع آزاد است.

</div>
