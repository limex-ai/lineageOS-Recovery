<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/🇺🇸_EN-grey"></a>
  <a href="./README_RU.md"><img src="https://img.shields.io/badge/🇷🇺_RU-blue"></a>
</div>

<div align="center">
  <img src="./banner.jpg" width="170" alt="LRP Logo">
  <h1>LRP</h1>
  <p><b>Lineage Recovery Platform</b></p>
</div>

[![Release](https://img.shields.io/github/v/release/UralRedux/LRP?label=Release&color=blue&logo=github)]([https://github.com/UralRedux/LRP/releases/latest](https://github.com/limex-ai/lineageOS-Recovery/releases/tag/1.1.0))
![Platform](https://img.shields.io/badge/Platform-Web-success)
![Node.js](https://img.shields.io/badge/Node.js-20+-green?logo=node.js)
![License](https://img.shields.io/badge/License-MIT-orange)

LRP — это веб-эмулятор, воспроизводящий интерфейс AOSP-прошивки **LineageOS** и фирменной среды восстановления **Lineage Recovery**.

Проект представляет собой единую виртуальную экосистему смартфона, позволяющую запускать виртуальное устройство прямо в браузере.

## Совместимость

| | Требования |
|-----------------|----------------|
| `Node.js` | `20+` |
| `npm` | `10+` |
| `Browser` | `Chrome / Edge / Firefox` |

---

## Установка

### 1. Установите Node.js

Скачайте последнюю LTS-версию:

https://nodejs.org

### 2. Клонируйте репозиторий

```bash
git clone https://github.com/UralRedux/LRP.git
```

### 3. Перейдите в папку проекта

```bash
cd LRP
```

### 4. Установите зависимости

```bash
npm install
```

### 5. Запустите проект

```bash
npm run dev
```

После запуска откройте ссылку, которую покажет терминал (обычно `http://localhost:5173`).

---

## Возможности

- Полная эмуляция интерфейса LineageOS
- Эмуляция Lineage Recovery
- Виртуальная файловая система
- Настройки устройства
- Анимации загрузки
- Имитация OTA-обновлений
- Работа полностью в браузере
- Современный интерфейс

---

## Скриншоты

<p align="center">
  <img src="./home.png" width="31%">
  <img src="./recovery.png" width="31%">
  <img src="./setting.png" width="31%">
</p>

<p align="center">
  <img src="./install.png" width="31%">
  <img src="./files.png" width="31%">
  <img src="./about.png" width="31%">
</p>

<p align="center">
  <img src="./rec.png" width="31%">
</p>

---

## Контакты

[![Telegram](https://img.shields.io/badge/Telegram-@lineageOS__recovery-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/lineageOS_recovery)

Новости проекта, обновления, поддержка и обсуждение LRP.

---

## Лицензия

MIT License

> [!NOTE]
> LRP не является настоящей прошивкой Android. Это веб-эмулятор интерфейса LineageOS и Lineage Recovery, предназначенный для демонстрации, тестирования и разработки.
