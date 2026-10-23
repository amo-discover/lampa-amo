<div align="center">
  <a href="https://app.amo.watch">
    <img src="https://raw.githubusercontent.com/amo-discover/lampa-amo/main/banner.svg" width="100%" alt="Amo Server Switcher for Lampa (install_amo.js)" />
  </a>
  <br />
  <p>
    <a href="https://app.amo.watch/install_amo.js"><img src="https://img.shields.io/badge/Plugin-install__amo.js-FF385D?style=flat-square" alt="install_amo.js" /></a>
    <a href="https://amo-discover.github.io/lampa-amo/"><img src="https://img.shields.io/badge/Landing_Page-GitHub_Pages-141418?style=flat-square" alt="GitHub Pages" /></a>
    <a href="https://github.com/amo-discover/lampa-amo/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-222228?style=flat-square" alt="MIT License" /></a>
  </p>
</div>

## RU — Быстрая установка Amo в Lampa (`install_amo.js`)

Плагин **Amo Server (`install_amo.js`)** от **Amo Helper** позволяет в один шаг переключить любой клиент **Lampa** (Smart TV Samsung Tizen, LG webOS, Android TV, ТВ-приставки, ПК Lampa Desktop и браузер) на сервер **`https://app.amo.watch`** (фильмы и сериалы в 4K, прямой эфир ТВ, 14 языков интерфейса).

### Ссылки для добавления в Lampa

**Основная ссылка (рекомендуется):**
```text
https://app.amo.watch/install_amo.js
```

**Зеркало GitHub Pages:**
```text
https://amo-discover.github.io/lampa-amo/install_amo.js
```

### Как установить в Lampa

1. Откройте **Lampa** на телевизоре, приставке или ПК.
2. Перейдите в **Настройки (Settings) → Расширения (Extensions) → Добавить плагин (Add Plugin)**.
3. Введите адрес `https://app.amo.watch/install_amo.js` и подтвердите.
4. Приложение автоматически переключится на **`https://app.amo.watch`**.
   - Чтобы при запуске остаться на прежнем сервере Lampa, удерживайте кнопку **ВНИЗ (DOWN)** на пульте или клавиатуре.
   - Также плагин добавляет кнопку **Amo** в верхнюю панель и пункт **Сервер Amo** в настройки Lampa.

---

## EN — Easy Install Amo Server Plugin for Lampa

**`install_amo.js`** (maintained by **Amo Helper**) rewrites and switches your **Lampa** client server to **`https://app.amo.watch`** with a single plugin URL.

### Plugin URLs

**Primary URL:**
```text
https://app.amo.watch/install_amo.js
```

**GitHub Pages Mirror:**
```text
https://amo-discover.github.io/lampa-amo/install_amo.js
```

### Features & Compatibility

| Feature | Details |
| :--- | :--- |
| **Native Server Rewrite** | Updates `lampaUrl` in Lampa Desktop (Electron), `WidgetLoader` in Samsung Orsay, and `Lampa.Storage` across Android TV, Tizen, and webOS |
| **Top-Bar Quick Action** | Adds an **Amo** button in the Lampa header bar and an **Amo Server** section in Settings |
| **Safe Startup Override** | Hold the `DOWN` key on your remote or keyboard during launch to stay on your current Lampa server |
| **Legacy WebView Safe** | Pure ES5 JavaScript compatible with older Tizen, webOS, Orsay, and Android 5+ WebViews |
| **14 UI Languages** | English, Russian, Ukrainian, Belarusian, Romanian, Portuguese, Spanish, French, German, Polish, Turkish, Arabic, Hindi, Chinese |
