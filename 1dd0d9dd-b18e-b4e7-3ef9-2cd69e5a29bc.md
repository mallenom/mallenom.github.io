# VideoChannelSettings.Roi - поле
 

Устанавливает и возвращает параметр, определяющий зону распознавания.

**Пространство имён:**&nbsp;<a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2</a><br />**Сборка:**&nbsp;recar2 (в recar2.dll) Версия: 2.36.0.544-dev[11230eb]

## Синтаксис

**C#**<br />
``` C#
public ISetting<PointF[][]> Roi
```

**VB**<br />
``` VB
Public Roi As ISetting(Of PointF()())
```

**C++**<br />
``` C++
public:
ISetting<array<array<PointF>^>^>^ Roi
```

**F#**<br />
``` F#
val mutable Roi: ISetting<PointF[][]>
```


#### Значение поля
Тип:&nbsp;ISetting(PointF[][])<br />Значения отступов от краев изображения, в которых номер не будет распознаваться, в долях изображения.

## См. также


#### Ссылки
<a href="e9c16317-8a46-c70d-6253-3004e99076b2">VideoChannelSettings - Класс</a><br /><a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2 - пространство имён</a><br />