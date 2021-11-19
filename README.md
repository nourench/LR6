# LR6
Лабораторная работа №6
Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

Был создан аккаунт на  и скачано приложение.

Форкнут (создана копия в личное хранилище) репозиторий.
Далее использованы команды git config --global user.name <username> и git config --global user.email <email> для настройки клиента Git и введены свои данные от GitHub.

![ввод данных](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/1.png?raw=true)

Клонирован удаленный репозиторий с использованием команды git clone <url>.

![клонирование репозитория](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/2_clone.png?raw=true)

Добавлен файл через интерфейс GitHub. Далее осуществлен переход в директорию LR6 командой cd LR6/ для дальнейшей работы с файлами.

![переход в директорию](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/3_cd.png?raw=true)

Подтянуты изменения из веб-интерфейса GitHub для клиента Git. Для этого использована команда git pull.

![подтянуты изменения](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/4.png?raw=true)

Используя git log, можно посмотреть все коммиты ветки.

Просмотрены существующие ветки в текщем репозитории командой git branch. Осуществлен переход в ветку branch1 командой git checkout branch1.

![переход в ветку branch1](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/5_gotobranch1.png?raw=true)

Просмотрены коммиты ветки branch1 с помощью команды git log.

![git log](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/6_log.png?raw=true)

Рассмотрены подробно коммиты командой git log -p.

![git log -p](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/6_logp.png?raw=true)

Переход в ветку master и выполнение слияния ветки branch1 с веткой master. Слияние производится командой git merge branch1.

![слияние](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/7_merge.png?raw=true)

Произошел конфликт. Команда git status, чтобы проверить состояние ветки. Команда git add mergefile.txt. Проверим еще раз, отслеживается ли файл. Осталось оставить коммит git commit -m "change1".

![конфликт](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/8_fixconflict.png?raw=true)

![коммит1](https://github.com/nourench/LR6/blob/master/скрины%20фор%20гит/9_commit.png?raw=true)

Удалена побочная ветка git branch1.

![удаление побочной ветки](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/10_delbranch.png?raw=true)

Созданы изменения и комментарии для них. Для создания текстовика использована команда echo hello > <имя файла>, фиксация изменений git add <имя файла>. Комментарий git commit -m "change2".

![коммиты](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/11_change2.png?raw=true)

Осуществлен "хард" откат коммита - git reset --hard HEAD~1 

![](https://github.com/nourench/LR6/blob/reportRenata/скрины%20фор%20гит/12_hardreset.png?raw=true)

Создана ветка для отчета и осуществлен переход в нее git branch report.

![](https://github.com/nourench/LR6/blob/master/скрины%20фор%20гит/13_report.png?raw=true)

После редактирования отчета, его нужно будет сохранить и произвести команды git add и git commit.
Папку со скриншотами просто переместить в директорию проекта.
В конце работы необходимо будет отправить все локальные изменения в сетевое хранилище GitHub командой git push
