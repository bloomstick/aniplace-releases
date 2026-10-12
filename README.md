<div align="center">

# 🌸 Aniplace — Аниплейс

**Твоё уютное место для аниме.** Каталог, списки просмотра, рекомендации и дружное сообщество — бесплатно, без подписок.

🌐 Сайт: **https://ani.place** · 📱 Android APK · 🖥️ Windows · 🏪 RuStore (скоро)

[![Releases](https://img.shields.io/github/v/release/bloomstick/aniplace-releases?color=ff4d6d&label=latest%20release)](https://github.com/bloomstick/aniplace-releases/releases)
[![Downloads](https://img.shields.io/github/downloads/bloomstick/aniplace-releases/total?color=ff8fa3)](https://github.com/bloomstick/aniplace-releases/releases)

</div>

---

## 📥 Скачать

| Платформа | Файл | Где взять |
|---|---|---|
| 🤖 **Android** | `aniplace-<версия>-android.apk` | [Последний релиз →](https://github.com/bloomstick/aniplace-releases/releases/latest) |
| 🖥️ **Windows** | `aniplace-<версия>-windows.zip` | [Последний релиз →](https://github.com/bloomstick/aniplace-releases/releases/latest) |
| 🏪 **RuStore** | — | *скоро, ссылка появится здесь* |

> 🆕 Впервые устанавливаешь APK или запускаешь на Windows? Загляни в
> **[пошаговую инструкцию на ani.place/install](https://ani.place/install)** —
> там с картинками explained как разрешить установку из неизвестных источников
> на Android и как запустить приложение на Windows.

---

## ✨ Что умеет Aniplace

- 🎬 **Большой каталог** — тысячи аниме и дунхуа с постерами, описаниями и рейтингами
- 💖 **Персональные рекомендации** — подборки под твой вкус
- 📝 **Списки просмотра** — смотрю / просмотрено / запланировано / отложено
- 🔔 **Уведомления о новинках** — новые серии любимых озвучек не пройдут мимо
- 🎙️ **Выбор озвучки** — смотри с любимой студией дубляжа
- 💬 **Обсуждения и блоги** — комментарии, мемы, арты и новости сообщества
- 📊 **Статистика и достижения** — прогресс просмотра и значки в профиль
- 🌙 **Ночной режим** — бережёт глаза перед сном

---

## 🗂️ Как устроены релизы

Каждый релиз — это один GitHub Release с тегом вида `v1.2.3`:

- `aniplace-1.2.3-android.apk` — установка на Android 8.0+
- `aniplace-1.2.3-windows.zip` — portable-сборка для Windows 10/11
- `SHA256SUMS.txt` — контрольные суммы, сверь после скачивания
- Ниже на странице релиза — **changelog** на русском: что нового и что починили

Полная история версий дублируется в [`CHANGELOG.md`](CHANGELOG.md).

### 🔒 Проверка подлинности

```powershell
# Windows (PowerShell)
Get-FileHash aniplace-1.2.3-android.apk -Algorithm SHA256
# Android / Linux
sha256sum aniplace-1.2.3-android.apk
```

Сравни вывод с `SHA256SUMS.txt` из того же релиза. Совпало — файл настоящий и не побился при скачивании.

---

## 🆘 Не устанавливается?

1. Android: разреши «Установку из неизвестных источников» для браузера — [инструкция](https://ani.place/install#android).
2. Windows: распакуй ZIP и запусти `Aniplace.exe` — [инструкция](https://ani.place/install#windows).
3. Всё ещё не получается? [Создай issue](https://github.com/bloomstick/aniplace-releases/issues) — укажи модель устройства и версию ОС.

---

## 📜 Лицензия и права

Приложение распространяется бесплатно. Каталог носит информационный характер,
права на произведения принадлежат их правообладателям. Контакты для
правообладателей: см. сайт [ani.place](https://ani.place).
