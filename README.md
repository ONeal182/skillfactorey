# Инструкция для работы с GIT

LICENSE: [MIT](./license.md)

---

<img src="./assets/git-logo.png" alt="">

---

## Содержание

1. [Шпаргалка по основным командам](./basicСommands.md)
2. [Шпаргалка по ветвлению и слиянию](./branchCommands.md)
3. [Шпаргалка по совместной работе и обновлению проектов](./changeCommands.md)
4. [Шпаргалка по осмотру и сравнению](./featchCommands.md)
5. [Шпаргалка по отладке](./debugCommands.md)

---



# Шпаргалка по ветвлению и слиянию

### git branch

Команда git branch — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.

### git checkout

Команда git checkout используется для переключения веток и выгрузки их содержимого в рабочую директорию.

### git merge

Команда git merge используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.

### git log

Команда git log используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.

# Шпаргалка по совместной работе и обновлению проектов

### git fetch

Команда git fetch связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.

### git pull

Команда git pull работает как комбинация команд git fetch и git merge, т.е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

### git push

Команда git push используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.

### git remote

Команда git remote служит для управления списком удалённых репозиториев. Она позволяет сохранять длинные URL репозиториев в виде понятных коротких строк, например "origin", так что вам не придётся забивать голову всякой ерундой и набирать её каждый раз для связи с сервером. Вы можете использовать несколько удалённых репозиториев для работы и git remote поможет добавлять, изменять и удалять их.




---

GIT logo by Jason Long - http://git-scm.com/downloads/logos,
license: [CC: BY 3.0](https://creativecommons.org/licenses/by/3.0/)


