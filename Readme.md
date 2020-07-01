# DocTalla
---
## Описание
DocTalla - это программа для анализа файлов OLE и OpenXML, таких как документы MS Office (например, Word, Excel), для обнаружения макросов VBA, извлечения их исходного кода в виде открытого текста и обнаружения шаблонов, связанных с безопасностью, таких как автоматически выполняемые макросы, подозрительные ключевые слова.


## Зависимости

В данной разработке использован язык программирования Python, а также сторонние его библиотеки: [Tkinter](https://docs.python.org/3/library/tkinter.html), [Pathlib](https://docs.python.org/3/library/pathlib.html), [Oletools](https://github.com/decalage2/oletools). Неопсредственно для анализа электронных документов был использован инструмент библиотеки Oletools - [Olevba](https://github.com/decalage2/oletools/wiki/olevba).

## Установка
Саму программу нет необходимости устанавливать на компьютер. Однако, необходимо наличие Python (версии 3.6 и выше) и некоторых его сторонних библиотек: Tkinter, Oletools, xlrd, xlutils.<br>
Их можно установить с помощью одной PIP командной в консоли:<br><br>
`pip install -r requirements.txt`<br>
<br>
Для непосредственного запуска программы необходимо запустить visual.py и выбрать нужные действия.

## Лицензия
Эта лицензия применяется к пакету python-oletools, за исключением сторонней папки, которая содержит сторонние файлы, опубликованные с собственной лицензией.

Авторские права на пакет python-oletools (c) 2012-2019 Philippe Lagadec (http://www.decalage.info)

Все права защищены.

Перераспределение и использование в исходной и двоичной формах, с изменениями или без них, разрешается при условии соблюдения следующих условий:

* При повторном распространении исходного кода должно сохраняться указанное выше уведомление об авторских правах, этот список условий и следующий отказ от ответственности.
<br><br>
* При повторном распространении в двоичной форме должно быть воспроизведено указанное выше уведомление об авторских правах, этот список условий и следующий отказ от ответственности в документации и / или других материалах, поставляемых при распространении.