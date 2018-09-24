# ДЗ №1: создание тест-кейсоов

## Набор тест-кейсов для проверки формы заполнения анкеты на странице [moscow-job.tinkoff.ru](moscow-job.tinkoff.ru)
* В поле "Имя, фамилия, отчество" не должно быть цифр
* В поле "Имя, фамилия, отчество" не должно быть знаков
* В поле "Имя, фамилия, отчество" как минимум 2 слова написанные через пробел (допускаем отсуствие отчества)
* В поле "Имя, фамилия, отчество" все символы в словах должны быть одного языка (одной раскладки)
* В поле "Имя, фамилия, отчество" в каждом слове заглавная буква только одна и только первая в каждом слове (если разрешаются все заглавные буквы, как в загранпаспорте, то условие можно дополнить)
* В поле "Электронная почта" должны быть буквы только латинского алфавита
* В поле "Электронная почта" обязательно должен быть символ собачки @
* В поле "Электронная почта" обязательно должна быть точка между именем хоста и гланым доменом (вообще говоря всего точек может быть больше чем 1)
* В поле "Электронная почта" в части домена (после символа @) должны присутствовать либо буквы, либо цифры, либо знак дефиса, либо точка (да, этот сложный тест-кейс следует разбить на 4 простых)
* В поле "Номер телефона" должны присутствовать только цифры
* В поле "Номер телефона" должно быть введено 10 цифр
* В поле "Номер телефона" проверка первых трех цифр  на соответствие коду мобильного оператора (если это необходимо)
* В поле "Город" первое слово должно быть с заглавной буквы
* В поле "Город" допустимы только буквы русского алфавита (мы же о российских городах говорим)
* В поле "Выберите вакансию" выбрана вакансия из выпадающего списка
- Рядом с обязаельными полями выводится символ звездочка *
- Кнопка "Отправить" неактивна, пока не активирован чекбокс «Я даю согласие на обработку личных данных»
- Кнопка "Отправить" неактивна, пока не заполнено хотя бы одно поле
- Кнопка "Отправить" неактивна, пока все введенные данные не прошли положительную валидацию
- Ограничение на количество введенных данных в текстовое поле 50 (чтобы при вводе сток суммарной длиной 1000 поле подсвечивалось красным) 

## Набор тест-кейсов для проверки функционала всей страницы [moscow-job.tinkoff.ru](moscow-job.tinkoff.ru) (не только формы)
* Корректность всех гиперссылок (нужно написать n простых тест-кейсов, где n количество всех гиперссылок на странице)
* Файлы cookies зашифрованы перед записью на компьютер пользователя
* Проверить безопасность при удалении файлов cookies
* Ошибки (синтаксические) HTML
* Проверить что сайт индексируется через поиск (через гугл, яндекс)
* Отсутствуют орфографические, грамматические ошибки
* Изображения размещены правильно и имеют соответствующие размеры
* Адекватный, удобный размер шрифта
* Правильная цветовая палитра



One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
