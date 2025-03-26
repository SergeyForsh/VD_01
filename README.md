# VD_01 урок Введение в веб-разработку. Основы HTML
---
HTML (Hyper Text Markup Language) — это стандартный язык разметки для создания веб-страниц. Он используется для структурирования содержимого на веб-странице. HTML позволяет задавать заголовки, абзацы, ссылки, изображения и другие элементы, которые составляют веб-страницу.
Чтобы начать работать с HTML в Python необходимо создать отдельный файл. Это можно сделать двумя способами:
1. webPy→New→HTML File (при этом внутри файла автоматически будет создан заготовленный шаблон)
2. webPy→New→File (в этом случае необходимо указать название файла полностью index.html, а для создания шаблона необходимо прописать ! и нажать на Tab)
Теги - это ключевые слова, которые используются для описания и структурирования содержимого веб-страницы (все то, что записано в треугольных скобках).
---
Они являются строительными материалами сайта, аналогичны кирпичикам, из которых состоит его конструкция.

Одинарные теги - это теги, которые не имеют пары. Они записываются самостоятельно внутри треугольных скобок.

Парные теги - это теги, которые имеют начало и конец. В конце закрывающего парного тега всегда присутствует символ "/".
---
HTML очень похож на человека: у него есть тег <head>, аналогичный голове, и тег <body>, аналогичный телу.
Тег <doctype html>(означает "объявление типа документа") сообщает браузеру, какая именно версия HTML используется на странице. Этот тег должен всегда находиться в первой строке каждой страницы. 
Тег <html>является корневым элементом, который заключает в себе все содержимое веб-страницы.
Тег <head> — это раздел документа, который содержит различные методы и кодировки. Например, кодировка UTF-8 позволяет использовать русский язык и другие символы. Внутри этого тега может содержаться заголовок, ключевые слова, описание страницы и другие метаданные. 
Тег <body> — раздел документа, который содержит весь контент, отображаемый на сайте. Для добавления изображения, заголовка, текста, ссылки или другого контента на веб-страницу необходимо разместить их между открывающим и закрывающим тегами <body>. 
Тег <meta> —  предназначен для предоставления структурированных метаданных о сайте. 
Тег <title> определяет заголовок документа, который отображается в заголовке окна браузера или на вкладке страницы.
