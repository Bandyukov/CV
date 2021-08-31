# Документация по началу работы с проектом

## Клонирование репозитория

Для клонирования проекта необходимо установить [GIT LFS](https://git-lfs.github.com)


После понадобиться создать [access token](https://hq-gitlab.megafon.ru/-/profile/personal_access_tokens). Придумываем любое название, срок на несколько лет и выбираем все пункты. Данный токен необходимо сохранить.


Теперь можно клонировать проект `clone with https`. Рекомендуется сделать это через терминал. Когда попросят авторизироваться, нужно вставить `access token` вместо пароля.

_Запускаем проект!_



## Для дальнейшей работы

Для того чтобы отправлять изменения на удаленный репозиторий, потребуется создать [gpg key](https://hq-gitlab.megafon.ru/help/user/project/repository/gpg_signed_commits/index.md). После на гитлабе в настройка пользователя добавлем созданный ключ.

----

Для прохождения автотестов должен быть доступ к [MLK Autotesting Identifiers](https://hq-gitlab.megafon.ru/megafon/cko/lk/nlk/mlk-autotesting-identifiers) и [QA LK autotests](https://hq-gitlab.megafon.ru/automatic_tests/qa_lk_autotests)

Если доступы отсутсвуют, обратись в канал `sysadmin_task` с просьбой их выдать.
