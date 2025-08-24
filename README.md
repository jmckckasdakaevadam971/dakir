# Мини‑сайт DAKIR

Использование: разместить содержимое папки `site/` на любой статический хостинг (GitHub Pages, Netlify, любой хостинг). Указать корень как «Адрес сайта» в анкете YooKassa, а страницу `requisites.html` как ссылку с реквизитами.

## Страницы
- index.html – описание, тарифы
- requisites.html – реквизиты (ФИО, ИНН, контакты)
- offer.html – публичная оферта
- privacy.html – политика конфиденциальности
- payment-return.html – страница возврата после оплаты (использовать в YOOKASSA_RETURN_URL)

## Настройка переменных окружения для приложения
Создай файл `yookassa.env` рядом с `sales.db`:
```
YOOKASSA_SHOP_ID=XXXXXX
YOOKASSA_SECRET_KEY=live_xxxxxxxxxxxxxxxxxxx
YOOKASSA_RETURN_URL=https://example.com/payment-return.html
```
(или установи переменные окружения в системе).

Обнови реквизиты в файлах (ФИО, ИНН, контакты) перед публикацией.
