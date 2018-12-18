# VideoCoreCom.MakeImageSnapshot - метод
 

Сохраняет снимок с видеоканала в указанный файл.

**Пространство имён:**&nbsp;<a href="68726a4f-5108-9c67-8918-cc6a6e73f216">Recar2.Com</a><br />**Сборка:**&nbsp;recar2.com (в recar2.com.dll) Версия: 2.36.0.544-dev[11230eb]

## Синтаксис

**C#**<br />
``` C#
public void MakeImageSnapshot(
	int channel,
	string filename
)
```

**VB**<br />
``` VB
Public Sub MakeImageSnapshot ( 
	channel As Integer,
	filename As String
)
```

**C++**<br />
``` C++
public:
virtual void MakeImageSnapshot(
	int channel, 
	String^ filename
) sealed
```

**F#**<br />
``` F#
abstract MakeImageSnapshot : 
        channel : int * 
        filename : string -> unit 
override MakeImageSnapshot : 
        channel : int * 
        filename : string -> unit 
```


#### Параметры
&nbsp;<dl><dt>channel</dt><dd>Тип:&nbsp;<a href="http://msdn2.microsoft.com/ru-ru/library/td2s409d" target="_blank">System.Int32</a><br />Канал.</dd><dt>filename</dt><dd>Тип:&nbsp;<a href="http://msdn2.microsoft.com/ru-ru/library/s1wwdcbf" target="_blank">System.String</a><br />Файл для сохранения изображения.</dd></dl>

#### Реализации
<a href="2f111fcd-402f-57e8-2e89-a5d1c0dea46f">IVideoCore.MakeImageSnapshot(Int32, String)</a><br />

## См. также


#### Ссылки
<a href="ccf26244-bb52-2173-a366-1022cb598c45">VideoCoreCom - Класс</a><br /><a href="68726a4f-5108-9c67-8918-cc6a6e73f216">Recar2.Com - пространство имён</a><br />