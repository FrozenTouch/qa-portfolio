
### ID
BUG-006
___
### Тип
Сбой приложения (Crash)
___
### Статус
Open
___
### Серьёзность (Severity)
High
___
### Приоритет (Priority)
High
___


### Окружение

- **Браузер:** Firefox 159.0.1
- **ОС:** CachyOS
- **Сайт:** https://www.realbugz.com/ru/store/
- **Устройство:** ПК

___

### Предусловия

Открыт доступ к странице магазина:
https://www.realbugz.com/ru/store/

___

### Шаги воспроизведения

1. Открыть страницу магазина: https://www.realbugz.com/ru/store/
2. Войти или  зарегистрироваться в аккаунте 
3. Добавить от 4 товаров в избранное


### Ожидаемый результат
Все 4 товара успешно добавляются в избранное, счётчик обновляется, приложение остаётся стабильным и продолжает работу.

### Фактический результат
После добавления 4-го товара приложение падает с ошибкой 
"Application error: a client-side exception has occurred". Пользователь теряет текущую сессию на странице и не может продолжить работу без перезагрузки.

___

### Влияние (Impact)

- Пользователь не может добавить больше 3 товаров в избранное
- Ухудшается пользовательский опыт

___

### Доказательства

- <img width="1920" height="1080" alt="App crashes when adding more than 4 items to favorites image1" src="https://github.com/user-attachments/assets/a51aee79-816f-4740-b3a3-f852e16ff919" />

- <img width="1920" height="1080" alt="App crashes when adding more than 4 items to favorites image2" src="https://github.com/user-attachments/assets/52cd78d1-1634-4606-aa34-6ae7e904a0c7" />




### Рекомендация по исправлению
- Добавить обработку ошибок на стороне клиента
- Проверить логику управления состоянием (State Management)
- Добавить валидацию перед обновлением UI

#### Автор
FrozenTouch (Александр)
