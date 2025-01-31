# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

## Проверка статуса репозитория
Просмотреть статус нужного репозитория можно по ключевому слову *status*: его действие распространяется на подготовленные, неподготовленные и неотслеживаемые файлы.

## Просмотр истории коммитов с изменениями
Просматривать изменения, внесённые в репозиторий, можно с помощью параметра *git log*. Он отображает список последних коммитов в порядке выполнения. Кроме того, добавив флаг -p, вы можете подробно изучить изменения, внесённые в каждый файл.

## Просмотр изменений до коммита
Можно просматривать список изменений, внесённых в репозиторий, используя параметр * git diff*. По умолчанию отображаются только изменения, не подготовленные для фиксации.
Также можно указать имя файла как параметр и просмотреть изменения, внесённые только в этот файл *git diff <имя файла>*

 ## Создание новой ветки и переход в неё
 Создать новую ветку можно с помощью параметра *branch*, указав имя ветки.
git branch <новое имя ветки>

Но Git не переключится на неё автоматически. Для автоматического перехода нужно добавить флаг -b и параметр *checkout*.

git checkout -b <новое имя ветки>
