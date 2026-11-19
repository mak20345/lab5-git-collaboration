# lab5-git-collaboration

Учебный проект по лабораторной работе №5: ветки, Pull Requests,
code review и разрешение конфликтов слияния в Git/GitHub.

## Структура репозитория
- `README.md` — описание проекта и участники
- `team.txt` — список участников и их вклад
- `maksim.txt`, `ekaterina.txt` — персональные файлы участников

## Участники
| Участник  | GitHub      | Ветка                | Вклад                   |
|-----------|-------------|----------------------|-------------------------|
| Максим    | @mak20345   | feature-maksim-team  | team.txt, README        |
| Екатерина | @ekaterina  | feature-ekaterina    | ekaterina.txt, ревью PR |

## Порядок работы
1. `git checkout main && git pull`
2. `git switch -c feature-<имя>`
3. `git add . && git commit -m "..." && git push -u origin feature-<имя>`
4. Открыть PR в `main`, дождаться review и merge.

## Разрешение конфликтов
`git merge main` → убрать маркеры `<<<<<<<`, `=======`, `>>>>>>>` →
`git add <файл>` → `git commit` → `git push`.
