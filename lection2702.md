# Ресурсы

Ресурсы добавляются как отдельный файл ресурсов в папку res/values необходимого типа. <br>Файл локализации создается посредством следующих действий:
```
values -> New -> values resources file -> locale -> тип локализации и название файла
```
Синтаксис у такого файла будет 
```
xml

<?xml version="1.0" encoding="utf-8"?>
<resources> </resources>
```
## Виды ресурсов
1. Измерений
```
xml

<dimen name="header-width">200.dp</dimen>
```
2. Цветов
```
xml

<color name="white">#FFFFFFFF</color>
```
3. Локализаций
```
xml

<string name="hello_world">Привет, мир!</string>
```
4. Стилей
```
xml

<style name="TextAppearance.Title">
  <item name="android:textSize">20sp</item>
  <item name="android:textStyle">bold</item>
</style>
```
5. Массивов
```
xml

<string-array name="planets_array">
  <item>Меркурий</item>
  <item>Венера</item>
  <item>Земля</item>
</string-array>
```
