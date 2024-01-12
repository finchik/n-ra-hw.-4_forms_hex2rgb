[![Build status](https://ci.appveyor.com/api/projects/status/gtlpfyrxhpavjjuw?svg=true)](https://ci.appveyor.com/project/a-naraikin/n-ra-hw-4-forms-hex2rgb)

### [Ссылка на Github Pages](https://finchik.github.io/n-ra-hw.-4_forms_hex2rgb/)

## Домашняя работа «Конвертер цветов из HEX в RGB»

---

Вам необходимо разработать конвертер цветов из HEX в RGB.

![Конвертер цветов](./assets/preview.png)

## Интерфейс конвертера

При правильном вводе цвета он показывает его представление в формате RGB и меняет цвет фона на заданный цвет:
![Цвет](./assets/color.png)

Конвертер при вводе неправильного цвета в формате HEX должен сообщать об ошибке:
![Ошибка](./assets/error.png)

Необходимо дожидаться ввода всех 7-ми символов (включая решётку), чтобы принимать решение о том, показывать ошибку или менять цвет фона.

---

## Команды
Установка зависимостей
```
npm install
```
Запуск проекта
```
npm start
```
Запуск тестов и линтер
```
npm run lint
npm run test
```
