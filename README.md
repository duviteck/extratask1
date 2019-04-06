Написать программу, показывающую список последних загруженных фотографий на сервис Flickr.
 
Программа состоит из двух экранов:
 
1. На первом экране показываются миниатюры первые 20 фотографий в виде таблички. Каждая фотография должна быть обрезана до квадратного размера.В портрете фотографии должны быть расположены в две колонки и иметь высоту и ширину = 35% от ширины экрана (+10% отступ слева, 10% между и 10% справа). В landscape ориентации фотографии должны быть расположены в 4 колонки и иметь ширину и высоту = 20% (+4% отступы слева, справа и между фотографиями).
2. На втором экране должна показываться фотография на весь экран в максимальном разрешении, которое влезает в экран без поворота и обрезания. Второй экран открывается по клику на миниатюру на первом экране.
 
Список фотографий надо забирать через Flickr API:
https://api.flickr.com/services/rest/?method=flickr.photos.getRecent&api_key=da9d38d3dee82ec8dda8bb0763bf5d9c&format=json&nojsoncallback=1

URL фотографии формируется на основе полученного ответа следующим образом:
https://farm{farm-id}.staticflickr.com/{server-id}/{id}_{secret}.jpg
 
Список должен отображать 20 последних фотографий, загруженных на Flickr (метод flickr.photos.getRecent)
 
В программе должны быть кнопка обновления, которая обновляет список.
 
Программа должна локально сохранять все загруженные фотографии в базе данных и работать при отсутствии интернет соединения.
 
Общий бал может быть снижен за нестабильную работу, плохо написанный код или плохо продуманный user interface. Не забывайте про иконку и название приложения и другие важные мелочи, за это тоже могут быть сняты баллы. 
 
Ничего из условия выше не заменит здравого смысла.

Результат:
=======
Исходный код (вся функциональность или сколько успели) надо прислать по email. Собранный APK прикладывать не нужно.

Ограничение по времени:
=======
На все задание дается 4 часа.
