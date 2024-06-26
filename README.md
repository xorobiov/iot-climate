# Курсова робота з дисципліни "Архітектура комп'ютерів-3"

## Функціонал програми

- зчитування даних з датчику DHT-11;
- виведення даних на екран рідкрокристалічного дисплею (драйвер _lcd1602.c_);
- комунікація із ПК за допомогою UART порту та збереження значень датчиків у базі даних;
- вивід значень датчиків у вигляді графіку у веб-застосунку.

Переглянути роботу програми можна за [посиланням](https://iot-climate.onrender.com/).

![image](https://github.com/xorobiov/iot-climate/assets/169550430/bd247c79-5eef-4a4c-b906-ecf1a3f27628)

## Інструкція

1. Встановіть усі залежності

```
npm install
```

2. Додайте змінні середовища (схема описана у _.env.example_)

3. Згенеруйте клієнт Prisma (використовується для роботи із базою даних)

```
npx prisma generate
```

4. Запустіть прослуховування із COM-порту (за необхідності).

```
npm run start:serial
```

5. Запустіть сервер (сторінка із графіком буде запущена на [localhost](http://localhost:80)).

```
npm run start:view
```
