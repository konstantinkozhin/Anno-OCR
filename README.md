<p align="center">
  <img src="https://github.com/user-attachments/assets/e79d8c96-5347-437d-9ddb-3941d0827871" width="677" />
</p>

<p align="center">
Десктопное приложение для автоматического распознавания и аннотирования текстов в рукописных и архивных документах.
</p>

---

## Оглавление

- [О программе](#о-программе)
- [Установка и запуск](#установка-и-запуск)
- [Инструкция пользователя](#инструкция-пользователя)
- [Используемые библиотеки и лицензии](#используемые-библиотеки-и-лицензии)

---

## О программе

**Anno OCR** — инструмент для работы с рукописными и историческими документами. Программа позволяет:

- **Распознавать текст** в изображениях документов — локально или через API
- **Размечать** области текста вручную или автоматически
- **Организовывать** распознанные слова в строки и блоки с правильным порядком чтения
- **Корректировать** результаты распознавания с помощью языковой модели (включая дореформенную орфографию)
- **Экспортировать** результаты в JSON, COCO-формат или PDF

Программа распространяется в виде одного `.exe` файла — ничего дополнительно устанавливать не нужно.

---

## Установка и запуск

1. Перейдите на страницу [**Releases**](https://github.com/konstantinkozhin/anno-ocr/releases/latest) или [**Яндекс Диск**](https://disk.yandex.ru/d/Hc4lDQJKahEbIg)
2. Скачайте файл `Anno_OCR.exe`
3. Запустите — готово!

> **Системные требования:** Windows 10/11, 64-bit, более 4 ГБ оперативной памяти.  
> При первом использовании локального OCR модели скачиваются автоматически в `~/.manuscript/weights/`.

---

## Инструкция пользователя


https://github.com/user-attachments/assets/d9915a50-54ab-403a-9321-87b21b36e340


1. **Демо-ролик**  
   Посмотрите основные функции Anno OCR

2. **Подробная инструкция**  
   Пошаговое руководство в файле [`user_manual.md`](https://github.com/konstantinkozhin/Anno-OCR/blob/main/user_manual.md).

---

## Используемые библиотеки и лицензии

Anno OCR использует следующие открытые библиотеки. Спасибо их авторам!

| Библиотека | Лицензия | Описание |
|------------|----------|----------|
| [PySide6](https://pypi.org/project/PySide6/) | [LGPL-3.0](https://pypi.org/project/PySide6/) | Фреймворк пользовательского интерфейса (Qt для Python) |
| [manuscript-ocr](https://github.com/konstantinkozhin/manuscript-ocr) | [MIT](https://github.com/konstantinkozhin/manuscript-ocr?tab=MIT-1-ov-file) | Модели OCR для рукописных и архивных документов |
| [ReportLab](https://pypi.org/project/reportlab/) | [BSD](https://pypi.org/project/reportlab/) | Генерация PDF-документов |
| [Shapely](https://shapely.readthedocs.io/) | [BSD-3-Clause](https://github.com/shapely/shapely/blob/main/LICENSE.txt) | Геометрические операции |
| [SQLite](https://www.sqlite.org/) | [Public Domain](https://www.sqlite.org/copyright.html) | Встроенная база данных |

Иконки: [Google Material Symbols](https://fonts.google.com/icons) — [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

<p align="center">
  <sub>Сделано с ❤️ для исследователей рукописей и архивных документов</sub>
</p>
