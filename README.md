Wilcoxon-W-Test
===============

Версия 1.2

Критерий Вилкоксона W для проверки однородности выборок.

[https://github.com/Harrix/Wilcoxon-W-Test](Wilcoxon-W-Test)

Файл распространяется по лицензии [Apache License, Version 2.0](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/LICENSE.txt).

Непосредственно главный файл: [**_Wilcoxon-W-Test.pdf**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/_Wilcoxon-W-Test.pdf).

Прямая ссылка на скачивание: [**_Wilcoxon-W-Test.pdf**](https://raw.github.com/Harrix/Wilcoxon-W-Test/master/_Wilcoxon-W-Test.pdf).

В данном документе дано описание критерия Вилкосона W по справочнику «Таблицы математической статистики» (Большев Л. Н., Смирнов Н. В.) и методика его применения.

Установка
---------

Прочитать подробно об установке можно тут [http://blog.harrix.org/?p=1216](http://blog.harrix.org/?p=1216).

Скриншоты документа
-------------------

![alt text](https://raw.github.com/Harrix/Wilcoxon-W-Test/master/images/title.png "Первая страница _Wilcoxon-W-Test.pdf")

![alt text](https://raw.github.com/Harrix/Wilcoxon-W-Test/master/images/table.png "Пример части таблицы из _Wilcoxon-W-Test.pdf")

Про структуру проекта
---------------------

Файл [**_Wilcoxon-W-Test.pdf**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/_Wilcoxon-W-Test.pdf) - это непосредственно сам документ "Критерий Вилкоксона W для проверки однородности выборок".

В корневой папке находятся две папки. 

В папке [**Source**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/Source) располагаются файлы непосредственно документа, где находится файл [**_Wilcoxon-W-Test.tex**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/Source/_Wilcoxon-W-Test.tex) (это исходник pdf документа) и файлы, которые являются вызываемыми или вспомогательными для [**_Wilcoxon-W-Test.tex**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/Source/_Wilcoxon-W-Test.tex).

В папке [**images**](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/images) находятся служебные рисунки для отображения в этом файле.

Сведения для редактирования файлов
----------------------------------

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции \*.tex документов в \*.pdf. Автор использует для этого связку [MiKTex](http://www.miktex.org/) и [TeXstudio](http://texstudio.sourceforge.net/). 

В варианте, который использует автор, в \*.tex файлах справок для отображения русских букв используется модуль **pscyr**. Об его установке можно прочитать (и скачать) в статье [http://blog.harrix.org/?p=444](http://blog.harrix.org/?p=444).

Подробное описание установки и настройки связки MiKTeX + TeXstudio + pscyr можно прочитать в статье [http://blog.harrix.org/?p=849](http://blog.harrix.org/?p=849).

Использованные технологии
-------------------------

- [LaTeX](http://ru.wikipedia.org/wiki/LaTeX), [MiKTeX](http://miktex.org/), [BiBTex](http://ru.wikipedia.org/wiki/BibTeX), [TeXstudio](http://texstudio.sourceforge.net/), [PSCyr]([http://blog.harrix.org/?p=444](http://blog.harrix.org/?p=444)).
- [HarrixLaTeXDocumentTemplate](https://github.com/Harrix/HarrixLaTeXDocumentTemplate).

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](https://github.com/Harrix/Wilcoxon-W-Test/blob/master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу [sergienkoanton@mail.ru](mailto:sergienkoanton@mail.ru) или  [http://vk.com/harrix](http://vk.com/harrix).

Сайт автора, где публикуются последние новости: [http://blog.harrix.org](http://blog.harrix.org), а проекты располагаются по адресу: [http://harrix.org](http://harrix.org).

Markdown File
==============

Title
-----

- Code form math.h

```cpp
/* END FLOAT.H COPY */

#if !defined(NO_OLDNAMES)

_CRTIMP double __cdecl j0 (double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;
_CRTIMP double __cdecl j1 (double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;
_CRTIMP double __cdecl jn (int, double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;
_CRTIMP double __cdecl y0 (double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;
_CRTIMP double __cdecl y1 (double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;
_CRTIMP double __cdecl yn (int, double) __MINGW_ATTRIB_DEPRECATED_MSVC2005;

_CRTIMP double __cdecl chgsign (double);
/*
 * scalb() is a GCC built-in.
 * Exclude this _scalb() stub; the semantics are incompatible
 * with the built-in implementation.
 *
_CRTIMP double __cdecl scalb (double, long);
 *
 */
  _CRTIMP int __cdecl finite (double);
  _CRTIMP int __cdecl fpclass (double);
```

Text