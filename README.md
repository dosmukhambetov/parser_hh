# Простой парсер вакансий сайта HeadHunter

Парсер вакансий с функцией фильтрации по странам/городам, а также по вакансиям.

## Как запустить?
1. Клонируйте репозиторий с GitHub: `git clone https://github.com/dosmukhambetov/parser_hh.git`
2. Создайте виртуальное окружение: `python -m venv venv`
3. Запустите виртуальное окружение: `source venv/bin/activate`
4. Установите зависимости: `pip install -r requirements.txt`
5. Готово! Запустите файл командой: `python main.py`

## Использование
<img src="https://i.ibb.co/cvFqb8p/Screenshot-from-2023-06-20-21-53-37.png" width="726">
После запуска вас попросят ввести название вакансии, а также страну/город, в котором вы хотите выполнить парсинг (поиск).
После завершения работы программы все данные, такие как: название вакансии, заработная плата, опыт, ссылка на вакансию
и теги, будут сохранены в файле - <b>data.json</b>.
