# SEAF.1C Example

Пример описания корпоративной архитектуры с использованием специализированного
фреймворка [SEAF.1C](https://github.com/DoublesunRUS/seaf-1c-core) основанного на [SEAF](https://github.com/SEAFTeam/seaf-core).

## Развертывание

1. Установите DocHub используя [инструкцию](https://github.com/RabotaRu/DocHub#быстрый-старт).
   Для ознакомления, рекомендуется использовать вариант развертывания - плагин для IDEA;
2. Установите менеджер архитектурных пакетов [archpkg](https://www.npmjs.com/package/archpkg);
3. Клонируйте данный репозиторий и перейдите в директорию проекта;
4. Установите зависимости командой:
   ```console
   npx archpkg install
   ```
5. Перед тем как приступить к работе с проектом, нужно установить graphviz c помощью команды:
    ```console
        linux: 
                 sudo apt-get install graphviz
        
        windows: 
                 winget install graphviz
    ```
   детальнее по установке можно посмотреть [тут](https://graphviz.org/download/)
6. Откройте проект в IDE.

**ВНИМАНИЕ:**
Рекомендуется использовать плагин IDEA версии 3.12.0 и выше!
Ссылка на [плагин](https://github.com/RabotaRu/DocHub/tree/master/distrib).

## Системные требования:
```
nodejs 20.11.0
Dochub latest
```
