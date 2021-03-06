## Инструкция по работе с GIT:

1. При первом запуске **Git** необходимо пройти авторизация. Для этого мы должны ввести имя пользователя и адрес элеткронной почты. Это делается с помощью двух команд - 
 
>* git config --global user.name "Ваше имя английскими буквами"

>* git config --global user.email почта@example.com

2. Следующий шаг - выбор рабочего каталога. Это делается с помощью команды **cd** "путь к папке вашего каталога"

>* cd c:\git_test

3. После выбора каталога следует инициализация этого каталога. Это делается с помощью команды 
>**git init**

 *После выполнения данной команды в рабочем каталоге создается папка с расширением **.git**. С этого момента git начинает отслеживать все изменения, происходящие в этом каталоге*.

4. Для добавления новых файлов используется команда 
>**git add "имя файла"**

5. Созданный файл необходимо зафиксировать, чтобы в дальнейшем иметь изначальную весрию файла. Это делается с помощью команды 
>**git commit -m "сообщение"**

6. Чтобы посмотреть состояние файла в рабочей директории на текущий момент используем команду 
>**git status**

7. Если необходимо просмотреть истрию комитов в хронологическом порядке следует воспользоваться командой 
>**git log**

8. Для перехода от одного коммита к другому используется команда 
>**git checkout**

9. Чтобы увидеть разницу между текущим состоянием файла и предудущей закоммиченной версией используется команда 
>**git diff**

10. Для того чтобы работать с удаленными репозиториями надо:
-  открыть GITHUB, пройти авторизацию 
- сделать fork интересующего нас репозитория
- потом сделать git clone интересующего нас репозитория
- создать новую ветку с предлагаемыми изменениями
- произвести все изменения только в этой ветке
- отправить эти изменения на свой аккаунт (push)
- в окне GITHUB появляется возможность отправить pull request





