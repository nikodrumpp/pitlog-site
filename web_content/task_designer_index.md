# Задача для дизайнера — index.html (Landing Page)

## Контекст продукта

**Продукт:** PitLog — цифровая сервисная книжка с AI-распознаванием чеков  
**Сайт:** pitlog.botneversleeps.com  
**Репозиторий сайта:** github.com/nikodrumpp/pitlog-site  
**Репозиторий приложения:** github.com/nikodrumpp/pitlog  

---

## Техническое задание

**Файл:** `index.html`  
**Технология:** чистый HTML + CSS — один файл, без фреймворков, без внешних зависимостей  
**Все стили:** в теге `<style>` внутри HTML файла  
**Требование:** mobile-first, корректная работа на мобильных устройствах  

---

## Контент

Полный контент всех секций — тексты, заголовки, CTA, body copy:  
`web_content/landing_page.md`  
https://github.com/nikodrumpp/pitlog-site/blob/main/web_content/landing_page.md

Текст использовать точно как написан, без изменений.

---

## Структура страницы

7 секций в строгом порядке:

1. **Hero** — headline, subheadline, CTA кнопка App Store, визуал
2. **Problem** — 3 карточки с иконками
3. **Solution** — 3 шага с flow-визуалом
4. **Features Overview** — сетка 6 фич с иллюстрациями
5. **Why PitLog** — 3 карточки с иллюстрациями
6. **Pricing** — 2 плана (Free / Pro)
7. **Final CTA** — headline, subheadline, CTA кнопка

---

## Визуальный стиль

- **Тема:** Dark-first (тёмный фон, светлый текст)
- **Стиль:** минималистичный, нативный iOS feel, premium качество
- **Визуальный референс:** страница About внутри приложения — там уже установлен стиль с SVG иллюстрациями, карточками с акцентными рамками, тёмным фоном и системными цветами
- **Скриншоты приложения** для референса UI: `nikodrumpp/pitlog/screenshots/`

---

## Графика — что уже готово, что нужно создать

### Готовые SVG иллюстрации (использовать напрямую)

Эти иллюстрации уже существуют в репозитории приложения.  
Путь: `nikodrumpp/pitlog/assets/icons/`  
Каждая иллюстрация доступна в двух версиях: `_dark.svg` и `_light.svg`.  
Для лендинга использовать **dark-версии**.

| Иллюстрация | Файл | Использовать в секции |
|---|---|---|
| AI сканирование чека | `ai_scan_dark.svg` | Features Overview, Why PitLog |
| Неограниченные записи | `unlimited_records_dark.svg` | Features Overview |
| PDF экспорт | `pdf_export_dark.svg` | Features Overview |
| Напоминания | `smart_reminders_dark.svg` | Features Overview, Why PitLog |

### Плейсхолдеры — нужны от иллюстратора

Для этих элементов иллюстрации будут нарисованы отдельно.  
Дизайнер оставляет блоки-плейсхолдеры с подписями:

| Секция | Плейсхолдер |
|---|---|
| Hero | `[VISUAL: Phone — AI scan screen]` |
| Problem, карточка 1 | `[ICON: Crumpled receipt]` |
| Problem, карточка 2 | `[ICON: Calendar with cross]` |
| Problem, карточка 3 | `[ICON: Question mark above car]` |
| Solution | `[VISUAL: 3-step flow — phone with camera on receipt]` |
| Features — Full Service History | `[ICON: Service history list]` |
| Features — Multiple Cars | `[ICON: Multiple cars]` |
| Features — History Transfer | `[ICON: Two figures + transfer arrow]` |
| Why PitLog — карточка 2 | `[ICON: Two figures + transfer arrow]` |
| Why PitLog — карточка 3 | `[ICON: Shield + lock]` |
| Final CTA | `[VISUAL: Car silhouette or phone with app]` |

---

## Pricing секция — важные детали

- Два блока рядом (desktop) / стопкой (mobile): **Free** и **Pro**
- Pro блок визуально выделен: акцентная рамка, badge **"Most Popular"**
- Free блок намеренно скромнее — направляет взгляд на Pro
- Под Pro CTA кнопкой строка: *"Cancel anytime. No questions asked."*

---

## App Store CTA кнопка

Использовать официальный Apple badge:  
https://developer.apple.com/app-store/marketing/guidelines/

Кнопка появляется дважды: в **Hero** и в **Final CTA**.  
Ссылка на App Store: будет добавлена после публикации. Пока использовать `href="#"`.

---

## Результат

Готовый файл `index.html` закоммитить в репозиторий:  
`github.com/nikodrumpp/pitlog-site`
