
# :ru: Абрамов Виталий Артурович
_Текст курсивом_
__Форматирование текста(жирное начертание)__
~~Зачеркивание~~

## Моя работа(fork)
[megasupersite](https://github.com/Abramov-Vitaliy/megasupersite)

### Пример кода
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
