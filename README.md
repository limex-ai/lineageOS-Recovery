<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/🇺🇸_EN-grey"></a>
  <a href="./README_RU.md"><img src="https://img.shields.io/badge/🇷🇺_RU-blue"></a>
</div>

<div align="center">
  <img src="./banner.jpg" width="170" alt="LRP Logo">
  <h1>LRP</h1>
  <p><b>Lineage Recovery Platform</b></p>
</div>

[![Release](https://img.shields.io/github/v/release/UralRedux/LRP?label=Release&color=blue&logo=github)](https://github.com/UralRedux/LRP/releases/latest)
![Platform](https://img.shields.io/badge/Platform-Web-success)
![Node.js](https://img.shields.io/badge/Node.js-20+-green?logo=node.js)
![License](https://img.shields.io/badge/License-MIT-orange)

LRP — это веб-эмулятор, воспроизводящий интерфейс AOSP-прошивки **LineageOS** и фирменной среды восстановления **Lineage Recovery**.

Проект представляет собой единую виртуальную экосистему смартфона, позволяющую запускать виртуальное устройство прямо в браузере.

## 📋 Совместимость

| | Требования |
|-----------------|----------------|
| `Node.js` | `20+` |
| `npm` | `10+` |
| `Browser` | `Chrome / Edge / Firefox` |

---

## 🚀 Установка

### 1. Установите Node.js

Скачайте и установите последнюю LTS-версию Node.js.

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

## ✨ Возможности

- Полная эмуляция интерфейса LineageOS
- Эмуляция Lineage Recovery
- Виртуальная файловая система
- Настройки устройства
- Анимации загрузки
- Имитация OTA-обновлений
- Работает полностью в браузере
- Современный интерфейс

---

## 📸 Скриншоты

| Главный экран |
|---------------|
| ![](./assets/home.png) |

| Recovery |
|----------|
| ![](./assets/recovery.png) |

---

## 📁 Структура проекта

```text
LRP
├── assets/
├── css/
├── js/
├── system/
├── recovery/
├── package.json
├── vite.config.js
└── README.md
```

---

## 👨‍💻 Разработчик

**UralRedux**

---

## 📄 Лицензия

MIT License

---

> [!NOTE]
> LRP не является настоящей прошивкой Android. Это веб-эмулятор интерфейса LineageOS и Lineage Recovery, предназначенный для демонстрации, тестирования и разработки.
