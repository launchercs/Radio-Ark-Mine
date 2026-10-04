<!-- ==================== فارسی ==================== -->

<div dir="rtl">

<p align="center">
  <a href="README.md">🇬🇧 English</a> |
  <a href="README_FA.md">🇮🇷 فارسی</a>
</p>


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

---

<!-- ==================== English ==================== -->

<div dir="ltr">

# 📻 Radio Ark Mine

A single-file, fully responsive online radio web app built with **pure HTML, CSS, and JavaScript** — no frameworks, no build tools. Works beautifully on mobile, tablet, and desktop with a native-app-like experience.

### 🔗 Live Demo
👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)

![Preview](screenshot.png)

---

## ✨ Key Features

- 🎧 **9 Music Genres:** Phonk, Phonk 2, Persian, Lofi, Soul, Rock, Pop, Hip-Hop, Country
- 📊 **Live Visualizer:** Circular spectrum + waveform powered by **Web Audio API**
- 🖼️ **Auto-Rotating Covers:** Changes every 12 seconds with smooth fade
- 🔊 **Full Volume Control:** Slider, mute, percentage display, keyboard support
- 📱 **Mobile-First:** iPhone notch support, 44px touch targets, uses `dvh`
- 🎨 **Dark Neon Theme:** Accent color `#2dd4bf` with glow animations
- ♿ **Accessibility:** `prefers-reduced-motion`, focus rings, ARIA labels
- ⚡ **Battery Optimized:** Visualizer throttled to 45fps, paused when tab hidden

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure and `<audio>`
- **CSS3** — Flexbox, Grid, `aspect-ratio`, `clamp()`, CSS variables
- **JavaScript ES6+** — Async/Await, Canvas API, Web Audio API

---

## 📂 Project Structure

```
Radio-Ark-Mine/
├── .github/workflows/static.yml   # GitHub Actions for deployment
├── index.html                      # Everything in one file
├── LICENSE                         # MIT License
├── screenshot.png                  # Preview image
└── README.md
```

---

## 🚀 Getting Started

1. Clone the project:
   ```bash
   git clone https://github.com/launchercs/Radio-Ark-Mine.git
   cd Radio-Ark-Mine
   ```
2. Open `index.html` in a browser — **or** visit the live version:
   👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)
3. Hit the ▶️ button and enjoy live radio.

> ⚠️ Due to browser **autoplay policies**, playback only starts after a user click.

---

## 🌐 Deploy on GitHub Pages

This project uses **GitHub Actions** for automatic deployment. Every push to the `main` branch updates the live site.

**Live URL:**
👉 [https://launchercs.github.io/Radio-Ark-Mine/](https://launchercs.github.io/Radio-Ark-Mine/)

---

## ⚠️ Disclaimer

Built for **educational purposes** only. Streamed content comes from public streaming servers.

---

## 📄 License

Released under the **MIT License** — free to use, modify, and distribute.

</div>
