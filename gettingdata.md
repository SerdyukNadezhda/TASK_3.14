[Вернуться к содержанию](readme.md)

## Получение данных о состоянии репозитория

**git status** позволяет отследить состояние репозитория. Позволяет узнать, какие изменения необходимо зарегистрировать *Git* (при необходимости — отменить).

Команда **git status** отображает все файлы, которые различаются между тремя разделами. У файлов есть 4 состояния:

1. ***Неотслеживаемый (untracked)*** — находится в рабочей директории, но нет ни одной версии в *HEAD* или в области подготовленных файлов (Git не знает о файле).
2. ***Изменён (modified)*** — в рабочей директории есть более новая версия по сравнению с хранящейся в *HEAD* или в области подготовленных файлов (изменения не находятся в следующем коммите).
3. ***Подготовлен (staged)*** — в рабочей директории и области подготовленных файлов есть более новая версия по сравнению с хранящейся в *HEAD* (готов к коммиту).
4. ***Без изменений*** — одна версия файла во всех разделах, т. е. в последнем коммите содержится актуальная версия.

**git log** покажет список последних коммитов и их хеши *SHA1*. Команда отображает отправленные снимки состояния и позволяет просматривать и фильтровать историю проекта, а также искать в ней конкретные изменения.

**git show [хэш]** используется для отображения полной информации о любом объекте в *Git*, будь то коммит или ветка. По умолчанию *git show* отображает информацию коммита, на который в данный момент времени указывает *HEAD*.

![](/assets/PHP.5.6.4.png) `Пример использования команд git log и git show`