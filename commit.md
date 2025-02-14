[< к содержанию](./readme.md)

## git commit

При выполнении команды **git commit** изменения всех файлов, внесённые в индекс, переносятся в репозиторий. При создании коммита (точки фиксации изменений) требуется указать сообщение.

Параметр **-m** позволяет написать сообщение из командной строки.

Обычно в сообщении пишется задача, которая решается этим обновлением, например «инициализация», «добавление счетов» или «исправление ошибки создания счёта». А правила «что написано в коммите» устанавливаются внутри команды разработчиков.

Однако общепризнанная практика состоит в том, что сообщения коммитов пишутся на английском языке *«init», «add Invoices»* или *«fix bug of create Invoice»* или на родном языке проекта и содержат достаточную информацию о точке фиксации изменений.

Пример:

```bash=
git commit -m «init»
```