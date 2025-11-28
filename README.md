
# :ru: Абрамов Виталий Артурович
> [!NOTE]
> форматирование текста(жирное начертание, курсив и зачеркивание)

_Текст курсивом_

__Форматирование текста(жирное начертание)__

~~Зачеркивание~~

## Пример ссылки
[megasupersite](https://github.com/Abramov-Vitaliy/megasupersite)

### Пример кода 
> [!TIP]
 main.yml
```
name: MyAction
on: 
  push:
      branches: master
jobs:
  MyBuild:
    runs-on: windows-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Build and run
        run: dotnet run --project VitaliyAbramov/VitaliyAbramov.csproj
```

### Эмоджи
:muscle:   :metal:   :punch:
