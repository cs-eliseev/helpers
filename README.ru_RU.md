[English](https://github.com/cs-eliseev/helpers/blob/master/README.md) | Русский

PHONE CSE HELPERS
=======

[![Travis (.org)](https://img.shields.io/travis/cs-eliseev/helpers.svg?style=flat-square)](https://travis-ci.org/cs-eliseev/helpers)
[![Codecov](https://img.shields.io/codecov/c/github/cs-eliseev/helpers.svg?style=flat-square)](https://codecov.io/gh/cs-eliseev/helpers)
[![Scrutinizer code quality](https://img.shields.io/scrutinizer/g/cs-eliseev/helpers.svg?style=flat-square)](https://scrutinizer-ci.com/g/cs-eliseev/helpers/?branch=master)

[![Packagist](https://img.shields.io/packagist/v/cse/helpers.svg?style=flat-square)](https://packagist.org/packages/cse/helpers)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.1-8892BF.svg?style=flat-square)](https://packagist.org/packages/cse/helpers)
[![Packagist](https://img.shields.io/packagist/l/cse/helpers.svg?style=flat-square)](https://github.com/cs-eliseev/helpers/blob/master/LICENSE.md)
[![GitHub repo size](https://img.shields.io/github/repo-size/cs-eliseev/helpers.svg?style=flat-square)](https://github.com/cs-eliseev/helpers/archive/master.zip)

CSE HELPERS это коллекция из нескольких библиотек предназначенных для быстрой разработки WEB-приложений. 

Репозиторий проекта: https://github.com/cs-eliseev/helpers

***


## Описание проекта

Несмотря на повсеместное использование PHP в качестве основного языка для WEB разработки, его зачастую недостаточно.

CSE HELPERS создан для быстрой разработки веб-приложений и призван расширить возможности PHP.

**Список библиотек CSE Helpers:**
* [Array CSE helpers](https://github.com/cs-eliseev/helpers-arrays)
* [Cookie CSE helpers](https://github.com/cs-eliseev/helpers-cookie)
* [Date CSE helpers](https://github.com/cs-eliseev/helpers-date)
* [Email CSE helpers](https://github.com/cs-eliseev/helpers-email)
* [IP CSE helpers](https://github.com/cs-eliseev/helpers-ip)
* [Json CSE helpers](https://github.com/cs-eliseev/helpers-json)
* [Math Converter CSE helpers](https://github.com/cs-eliseev/helpers-math-converter)
* [Phone CSE helpers](https://github.com/cs-eliseev/helpers-phone)
* [Request CSE helpers](https://github.com/cs-eliseev/helpers-request)
* [Session CSE helpers](https://github.com/cs-eliseev/helpers-session)
* [Word CSE helpers](https://github.com/cs-eliseev/helpers-word)


## Установка

Самая последняя версия проекта доступна [здесь](https://github.com/cs-eliseev/helpers).

### Composer

Чтобы установить последнюю версию проекта, выполните следующую команду в терминале:
```shell
composer require cse/helpers
```

Или добавьте следующее содержимое в файл composer.json:
```json
{
    "require": {
        "cse/helpers": "*"
    }
}
```

### Git

Добавить этот репозиторий локально можно следующим образом:
```shell
git clone https://github.com/cs-eliseev/helpers.git
```

### Скачать

[Скачать последнюю версию проекта можно здесь](https://github.com/cs-eliseev/helpers/archive/master.zip).

## Использование

Все классы использует статические методы, которые удобно использовать в любом проекте.

_Примеры работы с классами можно найти в документации для каждого проекта:_
* [Arrays](https://github.com/cs-eliseev/helpers-arrays) - работа с массивами
* [Cookie](https://github.com/cs-eliseev/helpers-cookie) - работа с куки
* [Date](https://github.com/cs-eliseev/helpers-date) - работа с датами
* [Emai](https://github.com/cs-eliseev/helpers-email) - работа с email адресами
* [IP](https://github.com/cs-eliseev/helpers-ip) - работа с IPv4 и IPv6 адресами
* [Json](https://github.com/cs-eliseev/helpers-json) - работа c JSON данными
* [MathConverter](https://github.com/cs-eliseev/helpers-math-converter) - работа с матиматическими преобразованиями данных
* [Phone](https://github.com/cs-eliseev/helpers-phone) - работа с телефонными адресами
* [Request](https://github.com/cs-eliseev/helpers-request) - работа с запросами
* [Session](https://github.com/cs-eliseev/helpers-session) - работа с сессиями
* [Word](https://github.com/cs-eliseev/helpers-word) - работа с текстовыми данными


## Тестирование и покрытие кода

PHPUnit используется для модульного тестирования. Данные тесты гарантируют, что методы класса выполняют свою задачу.

Подробную документацию по PHPUnit можно найти по адресу: https://phpunit.de/documentation.html.

Чтобы запустить тесты выполните:
```bash
phpunit PATH/TO/PROJECT/tests/
```


## Лицензия

CSE HELPERS это PHP-библиотека с открытым исходным кодом распространяемая по лицензии MIT. Для получения более подробной информации, пожалуйста, ознакомьтесь с [лицензионным файлом](https://github.com/cs-eliseev/helpers/blob/master/LICENSE.md).

***

> GitHub [@cs-eliseev](https://github.com/cs-eliseev)