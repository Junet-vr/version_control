# Подсказки по Git
## Основные команды

Создание локального репозитория (Инициализация):
```sh
git init
```
Добавление файла в репозиторий:
```sh
git add <filename>
```

Фиксация изменений в репозитории:
```sh
git commit -m "Сomment"
```

Вывод журнала изменений:
```sh
Расширенный
git log


Краткий
git log --oneline

Графический для ветвей
git log --graph
```

Разница между изменениями:
```sh
git diff
```

Откат до предыдущей версии без сохранения:
```sh
git restore <file>
```

Перемещение между изменениями: 
```sh
Между коммитами
git checkout <commit number>

Между ветками
git checkout <name branch>
```

## Графика

Изображение
```sh
![текст](путь к изображению "Всплывающая подсказка")
```

Ввод кода (выделение апострофами):
```python (название языка)
if x > 0:
	print (x)
else:
	print ('Hello, World!')
```

## Команды по ветвлению

Работа с ветками 
```sh
Вывод списка веток 
git branch

Создание новой ветки
git branch <имя ветки>

Удаление ветки
git branch -d(-D) <имя ветки>
```

Перенос репозитория из Git в GitHub:
```sh
git push
```

Получение изменений и слияние с удалённого репозитория
```sh
git pull
```

Отправка изменений в удалённый репозиторий
```sh
git push origin main
```

Слияние веток
```sh
git merge
```

Клонирование репозитория 
```sh
git clone <ссылка на клонированный репозиторий>
```

Стереть удалённую ветку
```sh
git push origin --delete existing_branch_name
```

Восстанавливает конфликтующие файлы до стабильного состояния
```sh
git reset
```

Cведения об удалённом репозитории
```sh
git remote show <origin>
```

Использование перебазирования
```sh
git rebase branch_name
```