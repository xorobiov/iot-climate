# Курсова робота з дисципліни "Архітектура комп'ютерів-3"

## Функціонал програми

- зчитування даних з датчику DHT-11;
- виведення даних на екран рідкрокристалічного дисплею (драйвер _lcd1602.c_);
- комунікація із ПК за допомогою UART порту та збереження значень датчиків у базі даних;
- вивід значень датчиків у вигляді графіку у веб-застосунку.

Переглянути роботу програми можна за [посиланням](https://iot-climate.onrender.com/).

![image](https://github.com/xorobiov/iot-climate/assets/169550430/bd247c79-5eef-4a4c-b906-ecf1a3f27628)

## Інструкція

Запуск прослуховування із порту.

```
npm run start:serial
```

Запуск сервера (сторінка із графіком).

```
npm run start:view
```
