# ImageCore.ProcessImageByVariants - метод
 

Возвращает варианты распознавания на указанном изображении.

**Пространство имён:**&nbsp;<a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2</a><br />**Сборка:**&nbsp;recar2 (в recar2.dll) Версия: 2.36.0.544-dev[11230eb]

## Синтаксис

**C#**<br />
``` C#
public IReadOnlyCollection<PlateVariant> ProcessImageByVariants(
	IImageMatrix matrix,
	int channelNum = 0,
	CancellationToken cancellationToken = null
)
```

**VB**<br />
``` VB
Public Function ProcessImageByVariants ( 
	matrix As IImageMatrix,
	Optional channelNum As Integer = 0,
	Optional cancellationToken As CancellationToken = Nothing
) As IReadOnlyCollection(Of PlateVariant)
```

**C++**<br />
``` C++
public:
IReadOnlyCollection<PlateVariant^>^ ProcessImageByVariants(
	IImageMatrix^ matrix, 
	int channelNum = 0, 
	CancellationToken cancellationToken = nullptr
)
```

**F#**<br />
``` F#
member ProcessImageByVariants : 
        matrix : IImageMatrix * 
        ?channelNum : int * 
        ?cancellationToken : CancellationToken 
(* Defaults:
        let _channelNum = defaultArg channelNum 0
        let _cancellationToken = defaultArg cancellationToken null
*)
-> IReadOnlyCollection<PlateVariant> 

```


#### Параметры
&nbsp;<dl><dt>matrix</dt><dd>Тип:&nbsp;IImageMatrix<br />Распознаваемое изображение.</dd><dt>channelNum (Optional)</dt><dd>Тип:&nbsp;<a href="http://msdn2.microsoft.com/ru-ru/library/td2s409d" target="_blank">System.Int32</a><br />Номер канала (начиная с 0).</dd><dt>cancellationToken (Optional)</dt><dd>Тип:&nbsp;<a href="http://msdn2.microsoft.com/ru-ru/library/dd384802" target="_blank">System.Threading.CancellationToken</a><br />Токен отмены операции.</dd></dl>

#### Возвращаемое значение
Тип:&nbsp;<a href="http://msdn2.microsoft.com/ru-ru/library/hh881542" target="_blank">IReadOnlyCollection</a>(PlateVariant)<br />Список вариантов распознавания.

## Исключения
&nbsp;<table><tr><th>Исключение</th><th>Условие</th></tr><tr><td><a href="http://msdn2.microsoft.com/ru-ru/library/3w1b3114" target="_blank">ArgumentException</a></td><td>Канал *channelNum* занят обработкой изображения.</td></tr><tr><td><a href="http://msdn2.microsoft.com/ru-ru/library/2asft85a" target="_blank">InvalidOperationException</a></td><td>Превышен лимит количества распознаваемых изображений.</td></tr><tr><td><a href="http://msdn2.microsoft.com/ru-ru/library/hb4a25ka" target="_blank">OperationCanceledException</a></td><td>*cancellationToken* был отменен.</td></tr></table>

## См. также


#### Ссылки
<a href="0ecd30a3-2420-dbc0-b961-311b9ee08659">ImageCore - Класс</a><br /><a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2 - пространство имён</a><br />