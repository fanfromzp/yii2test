Проект на yii2 содержит два главных application - api и backend.
1. запустить этот проект у себя) база в db_dump. vendor Обновляем через composer https://getcomposer.org/ просто composer update. для композера треубется регистрация https://git.pinxterapp.com/ потверждаете email добавляете ключь ssh и тогда оно не будет требовать пароля
также надо настроить коннект к базе. common/config/db_local.php копировать в db.php
2. добавить в админку и в апи новости. добавление/редактирование в админку, в апи просто получение списка новостей. обязательные поля title description img_url.

3. добавить возможность в апи сохранять/удалять в избранное events. в админке добавить возможность просмотра добавленых эвентов в профиле юзера - view в грид юзеров тоже добавить.

приоритет лежит на админке, если не сможете прикрутить в апи - не так страшно.
для работы с апи https://www.getpostman.com/ в папке postman лежит темплейт для все запросов апи + файлик с для настройки окружения, чтобы выполнять запросы - там надо только выставить урл на котором вы ведете разработку.

результат можете комитить частями или полностью в отдельную ветку этого репозитория (требуется регистрация в гитлабе) также можно прислыать просто репозиторий github.
вопросы в скайп или на мыло admin@pinxterapp.com