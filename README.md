# Green API

Этот проект демонстрирует использование методов GREEN-API с помощью простой [HTML-страницы](https://EricFeynman.github.io/green-api/). 

## Описание

Проект предоставляет интерфейс для выполнения следующих методов API:
- `getSettings`
- `getStateInstance`
- `sendMessage`
- `sendFileByUrl`

## Установка

1. Склонируйте репозиторий:
    ```bash
    git clone https://github.com/EricFeynman/green-api.git
    ```
2. Перейдите в директорию проекта:
    ```bash
    cd green-api
    ```

## Использование

1. Откройте файл `index.html` в вашем браузере.
2. Введите `idInstance` и `apiTokenInstance` в соответствующие поля.
3. Для каждого метода нажмите соответствующую кнопку:
    - `getSettings`: Получить настройки инстанса.
    - `getStateInstance`: Получить состояние инстанса.
    - `sendMessage`: Отправить сообщение на указанный номер.
    - `sendFileByUrl`: Отправить файл по URL на указанный номер.
4. Результаты запросов будут отображены в текстовом поле "Response".