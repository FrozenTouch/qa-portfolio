# 🐞 Баг-репорты (Bug Reports)

Коллекция баг-репортов, составленных в рамках практического тестирования учебных платформ **AcademyBugs** и **Realbugz**. 

Данное портфолио демонстрирует навыки поиска, анализа и профессионального документирования дефектов различных типов: **Crash, Functional, Business Logic, Security, UI/UX**.

---

## 📊 Статистика

| Платформа | Кол-во отчётов | Основные типы дефектов |
|-----------|----------------|------------------------|
| **AcademyBugs** | 2 | Functional, Security |
| **Realbugz (Статья)** | 3 | Functional, UI |
| **Realbugz (Магазин)** | 5 | Crash, Business Logic, Security, Functional, i18n |
| **Итого** | **10** | — |

---

## 📂 Каталог отчётов

### 🎓 AcademyBugs
| ID | Файл | Тип | Severity | Краткое описание |
|----|------|-----|----------|------------------|
| BUG-001 | `academybugs-freeze-quantity.md` | Functional | Medium | Страница зависает при выборе количества товара 5 или 50 |
| BUG-002 | `academybugs-twitter-share-404.md` | Security | Medium | Кнопка Twitter Share ведёт на несуществующий домен (риск фишинга) |

### 📰 Realbugz — Статья
| ID | Файл | Тип | Severity | Краткое описание |
|----|------|-----|----------|------------------|
| BUG-003 | `Broken Link/Broken internal link leads to 404 page.md` | Functional | Low | Битая внутренняя ссылка ведёт на страницу 404 |
| BUG-004 | `heading not centered/Article title is not centered.md` | UI | Low | Заголовок статьи выровнен не по центру |
| BUG-005 | `Non-functional "Share" button/non-working share buttons.md` | Functional | Low | Кнопки «Поделиться» не реагируют на нажатие |

### 🛒 Realbugz — Интернет-магазин *(Новые)*
| ID | Файл | Тип | Severity | Краткое описание |
|----|------|-----|----------|------------------|
| **BUG-006** | `App crashes when adding more than 4 items to favorites.md` | **Crash** | **High** | Приложение падает с client-side exception при добавлении 4-го товара в избранное |
| **BUG-007** | `Incorrect error message when entering an expired promo code "SUMMER24".md` | Functional | Low | Неверный текст ошибки для истёкшего промокода (нарушение ТЗ) |
| **BUG-008** | `Bypassing the quantity limit.md` | Business Logic | Medium | Обход лимита «не более 10 шт. одного товара» при быстром клике |
| **BUG-009** | `Enumeration of users during login.md` | **Security** | Medium | Уязвимость User Enumeration: разные сообщения для несуществующего и существующего email |
| **BUG-010** | `Untranslated message regarding product quantity limits when Russian is selected as the language.md` | UI / i18n | Low | Непереведённое сообщение об ограничении количества при выбранном русском языке |

---

## 📋 Стандартный формат отчёта

Каждый документ в этой папке структурирован по индустриальному стандарту и содержит:
1. **Метаданные**: ID, Тип, Статус, Severity, Priority.
2. **Окружение**: Браузер, ОС, URL, устройство.
3. **Предусловия**: Что необходимо сделать перед началом теста.
4. **Шаги воспроизведения**: Чёткая, нумерованная инструкция.
5. **Ожидаемый и Фактический результат**: Сравнение поведения системы с ТЗ.
6. **Влияние (Impact)**: Оценка влияния на пользователя, бизнес и безопасность.
7. **Доказательства**: Скриншоты, подтверждающие дефект.
8. **Рекомендация по исправлению**: Конкретные технические предложения для разработчиков (Frontend/Backend).

---

## 🛠️ Использованные инструменты
- **ОС**: CachyOS
- **Браузер**: Firefox 159.0.1 (с DevTools)
- **Платформы**: Realbugz, AcademyBugs
- **Методологии**: Проверка граничных значений, анализ соответствия ТЗ, базовый security-чек (User Enumeration).

---

## 📫 Контакты
- **GitHub**: [github.com/FrozenTouch](https://github.com/FrozenTouch)
- **Автор**: Александр (FrozenTouch)
