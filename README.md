# Парсинг изображений из интернет-каталога и сохранение их в pdf-файл
(Самостоятельное практическое занятие (материал взят с Youtube-канала PythonToday))

1. Устанавливаем и импортируем библиотеку request,
2. Создаём функцию get_data(), где в цикле проходим по всем изображениям, расположенным по url-ссылке на сайте,
3. Сохраняем каждое пройденное изображение к себе в директорию /media,
4. Установим библиотеку img2pdf для перекодирования картинки в pdf-формат,
5. Выполним сохранение pdf-файла с помощью метода img2pdf.convert()
