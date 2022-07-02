# Основные команды Git

## Work on the current change
- add - Add file contents to the index (добавить файл или файлы к следующему коммиту)
- mv - Move or rename a file, a directory, or a symlink (переместить или переименовать файл, каталог или символическую ссылку)
- restore - Restore working tree files (восстановление файлов рабочего дерева)
- rm - Remove files from the working tree and from the index (удаление файлов из рабочего дерева и из индекса)

## Examine the history and state

- bisect - Use binary search to find the commit that introduced a bug (используйте двоичный поиск, чтобы найти коммит, который привел к ошибке)
- diff - Show changes between commits, commit and working tree, etc (показывает изменения между коммит, коммитом и рабочим деревом и т. д.)
- grep - Print lines matching a pattern (печать строк, соответствующих шаблону)
- log - Show commit logs (вывод на экран истории всех коммитов с их хеш-кодами)
- show - Show various types of objects (показывать различные типы объектов)
- status - Show the working tree status (получить информацию от git о его текущем состоянии)

## Grow, mark and tweak your common history
- branch - List, create, or delete branches (посмотреть список веток в репозитории)
- commit - Record changes to the repository (-m “message” – создание коммита)
- merge - Join two or more development histories together (слияние отдельных направлений разработки, созданных с помощью команды git branch, в единую ветку)
- rebase - Reapply commits on top of another base tip (интеграция изменений из одной ветки в другую)
- reset - Reset current HEAD to the specified state (универсальный инструмент для отмены изменений)
- switch - Switch branches (переключение между ветками)
- tag - Create, list, delete or verify a tag object signed with GPG (создание, перечисление, удаление или проверка объекта тега, подписанного с помощью GPG)

## Collaborate
- fetch - Download objects and refs from another repository (загружает коммиты, файлы и ссылки из удаленного репозитория в ваш локальный репозиторий)
- pull - Fetch from and integrate with another repository or a local branch (получение изменений и слияние с локальной версией)
- push - Update remote refs along with associated objects (отправляет локальную версию репозитория на внешний)