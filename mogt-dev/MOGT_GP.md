# Отчет о работе Панкова

## 07.06.2021-11.06.2021

- JSON схема
        - Изучение синтаксиса, состаление схем
        - Изучение типов данных string, number, integer, object, array, boolean, null
        - Изучение доп. параметров для выше описанных типов данных
        - Изучение доп.парметров для схемы
        - Пример:

   ``` json
                {
        "$schema":"http://json-schema.org/draft-07/schema",
        "title" : "Document A-1",
        "type": "object",
        "description": "an options of document A-1",
        "properties": 
         {
         "format1":
                {
            
                "type" : "string",
                "pattern": "^[0-9]{2}:$"
                },
        "format2":
                {
            
                 "type" : "string"
                },
        "number":
                {
                "description": "nomer",
                "type": "integer",
                "minimum": 1,
                "maximum": 99999999
                }
         },
        "required": ["format1", "format2","number"]
        }

   ```

## 01.06.2021-05.06.2021

- Изучение JSON
        - Изучение понятия JSON
        - Изучение базового синтаксиса JSON
        - Пример:

    ``` json
            {
            "Имя": "Гоша",
            "Фамилия": "Панков",
            "Пол": "Мужской",
            "Увлечения": ["1", "2", "3"]
            }
    ```

- Изучение JSON схем
        - изучение понятий о JSON схемах
