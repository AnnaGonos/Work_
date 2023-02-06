# Лабораторная работа 7

Парсер метаинформации в формате ID3v2.4 из mp3 - файлов.

## Задача

Реализовать консольное приложение для отображения метаинформации в формате ID3v2.4 из mp3-файлов.
Способ отображения - не специфицируется и остается на усмотрение автора.
Аргументы командной строки  - так же не специфицируются

## ID3v2.4

Детальную спецификацию о структуре ID3v2.4 можно найти в [документации](https://github.com/AnnaGonos/Work_/blob/main/id3v2.4.0-structure.rst)
Различная по смыслу информации (название, артист, жанр и тд) хранятся в различных фреймах. Список возможных фреймов можно также найти в [документации](https://github.com/AnnaGonos/Work_/blob/main/id3v2.4.0-frames.rst)

[Оригинальная докуменатция](https://mutagen-specs.readthedocs.io/en/latest/id3/index.html)

## Реализация

Все фреймы можно поделить на разные категории (например как сделано в документации). Поэтому предполагается, что Вами будет реализована иерархия классов для описания всех фреймов. Именно это является основным заданием лабораторной работы.

Возможно Вам помогут [пораждаюдие шаблоны проектирования](https://en.wikipedia.org/wiki/Creational_pattern)


### Фреймы не обязательные для реализации

* AENC
* APIC
* ASPI
* GEOB
* MCDI
* MLLT
* MLLT
* RVRB
* SIGN
* SYTC
* TFLT
* TMED

## NB

Выполнение работы подразумевает только базовые знания о классах. Однако, вам не запрещается пользоваться другими механизмами языка.

## Тестовые данные

Для проверки работоспособности вашей программы, можно воспользоваться свободно-распространяемыми в интернете mp3 - файлами. Например на сайте [Free Music Archive](https://freemusicarchive.org/home)

Так же, большинство стандартных  программ для проигрывания mp3 позволяют редактировать метаинформацию.


## Deadline

1. 19.02.23 24:00 - 0.8
2. 26.02.23 24:00 - 0.65
3. 05.03.22 24:00 - 0.5

