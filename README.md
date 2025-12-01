# Практика по Github

## ИСПп-1.23, Седельникова И.А.
Из прошлой работы я узнал следующие git команды:
* git init - инициализация нового локального репозитория.
* git config --global user.name и git config --global user.email - установка имени пользователя и email для коммитов.
* git status - просмотр текущего состояния репозитория.
* git add - добавление файла в область индекса.
* git commit -m "сообщение" - фиксация изменений в репозитории с сообщением.
* git log - просмотр истории всех коммитов.
* git diff - просмотр различий между текущим состоянием и указанным коммитом.
* git reset - откат к указанному коммиту.

---
### Пример кода на Python

```python
git_commands = [
    "git init",
    "git add",
    "git commit",
    "git push",
    "git status",
]

print("Изученные команды:")
for cmd in git_commands:
    print(f"- {cmd}")

