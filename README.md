# Вёрстка видеоплеера

Прототип видеоплеера для российской киностудии «ГОСТФильм». Видеоплеер был сделан на основе [этого проекта](https://github.com/devmanorg/video-player-jslib). Посмотреть на плеер в действии можно [здесь](https://maratdzhukaev09.github.io/player_devman/).

## Установка кода
(Пример на Windows; на Mac и Linux используйте `/`, вместо `\`)

Установите код консольной командой:
```bash
$ git clone https://github.com/maratdzhukaev09/player_devman.git
```
Или скачайте [архив с кодом.](https://github.com/maratdzhukaev09/player_devman/archive/master.zip)


## Подготовка к запуску

Для запуска кода у вас уже должен быть установлен Python 3.

Перейдите в репозиторий командой:
```bash
$ cd путь\к\репозиторию
```

### Использование [virtualenv/venv](https://docs.python.org/3/library/venv.html)

Создайте virtualenv/venv консольной командой:
```bash
$ virtualenv название_virtualenv_venv
```
Активируйте virtualenv/venv командой:
```bash
$ название_virtualenv_venv\Scripts\activate
```

### Установка зависимостей

Установите зависимости с помощью `pip` (или `pip3`, если есть конфликт с Python2) командой:
```bash
$ pip install -r requirements.txt
```

### Запуск кода
Запустите код командой:
```bash
$ python render_website.py
# Используйте python3, если есть конфликт с Python2
```

Сайт с видеоплеером будет доступен по ссылке: [http://127.0.0.1:5500](http://127.0.0.1:5500)
Откройте файл index.html в браузере, чтобы открыть сайт с видеоплеером.

## Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).