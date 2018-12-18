# VideoChannelSettings.BlockDirectionUp - свойство
 

Устанавливает и возвращает флаг, показывающий, необходимо ли учитывать распознанные номера при перемещении ТС по кадру "снизу-вверх".

**Пространство имён:**&nbsp;<a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2</a><br />**Сборка:**&nbsp;recar2 (в recar2.dll) Версия: 2.36.0.544-dev[11230eb]

## Синтаксис

**C#**<br />
``` C#
public IRestrictedSetting<bool> BlockDirectionUp { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property BlockDirectionUp As IRestrictedSetting(Of Boolean)
	Get
```

**C++**<br />
``` C++
public:
property IRestrictedSetting<bool>^ BlockDirectionUp {
	IRestrictedSetting<bool>^ get ();
}
```

**F#**<br />
``` F#
member BlockDirectionUp : IRestrictedSetting<bool> with get

```


#### Значение свойства
Тип:&nbsp;IRestrictedSetting(<a href="http://msdn2.microsoft.com/ru-ru/library/a28wyd50" target="_blank">Boolean</a>)<br />Если `false`, то учитывать, иначе `true`

## См. также


#### Ссылки
<a href="e9c16317-8a46-c70d-6253-3004e99076b2">VideoChannelSettings - Класс</a><br /><a href="0dd0c505-07fc-c3e8-128c-d1a0701f2a29">Recar2 - пространство имён</a><br />