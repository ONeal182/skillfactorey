# Шпаргалка по ветвлению и слиянию

**git branch**

Команда git branch — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.

```
git branch [наименование] — команда, которая создает новую ветку в репозитории.
```

**git checkout**

Команда git checkout используется для переключения веток и выгрузки их содержимого в рабочую директорию.

```
git checkout [наименование] — команда, которая переключает вас на определенную ветку.

Можно совместить выполнение этих команд:

git checkout -b [наименование] — создаёт новую ветку и переключает вас на неё.

```

**git merge**

Команда git merge используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.

```
git merge [наименование]
```

### git log

Команда git log используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.