# Инструкция работы на сайте GitHub

## Создание  репозитория

Репозиторий — это место, в котором вы систематизируете свой проект. Здесь вы храните файлы, папки, видео, изображения, блокноты Jupyter Notebook, наборы данных и т.д
Лучше сразу добавлять в репозиторий README -файл с информацией о проекте.

* Перейдите на сайт GItHub. Выберите New repository.

* Придумайте имя репозитория и добавьте краткое описание.

* Нажмите Initialize this repositiry with a README для добавления README-файла. 

## Работа в репозитории

## 1. Внесение изменений в проект


Вносить изменения можно двумя способами. Можно изменять файлы на компьютере либо делать это на сайте GitHub.

* Для начала необходимо перейти в репозиториq

* Для выбора файла кликните по его названию (например, кликните по README.md для перехода к файл- описанию).

* Напишите короткое сообщение, предлагающее суть изменений( и подробное описание, если сочтете это нужным).

* Нажмите кнопку Commit changes.

Также можно создать новую ветку этого коммита и добавить pull request.



## 2. Клонирование репозитория

Для дальнейшей работы с репозиторием можно клонировать его на локальный компьютер:

1. 


* нужно нажать на кнопку Clone or download ( можно просто скачать репозиторий и избежать всех заморочек с терминалом)

* Проследите, чтобы появилась надпись Clone with HTTPS.

* Теперь нажмите на иконку буфера обмена для копирования-вставки (либо выделите ссылку и скопируйте ее).

* Откройте терминал и перейдите для копирования репозитория. Например, для перехода на **Рабочий стол** напечатайте это:

cd Desktop

* Затем клонируйте туда репозиторий по следующей команде:

git clone < то, что вы только что скопировали>

2. Вместо клонирования можно сделать форк проекта на GitHub:

* для этого нажмите кнопку Fork в верхнем правом углу сайта.

Совсем не обязательно создавать репозиторий на рабочем столе. Клонировать можно в любое место на компьютере. Команду dit clone можно выполнять и сразу после открытия терминала. 


## 3. Добавление файлов в проект

* Проверить статус проекта:

git status

* Добавляем файлы в репозиторий

git add <имя файла>

Либо все сразу

git add - all

или даже

git add
 
* Создаем коммит с изменениями:

git commit -m "<сообщение о коммите>"

* Для отправки изменений на удаленный репозиторий выполнить команду:

git push
