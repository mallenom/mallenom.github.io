# Сообщения об ошибках


## Ошибки во время запуска **Ядра распознавания**

Сообщения об ошибках:
&nbsp;<table><tr><td>
Класс не зарегистрирован.</td></tr><tr><td>
Зарегистрировать класс, запустив скрипт _%ProgramFiles(x86)%\Recar2\binaries\register.cmd_ (<a href="ComRegister">Регистрация компонента</a>).


Если регистрация не помогает, то можно удалить из реестра следующие узлы:
&nbsp;<ul><li>
HKEY_CLASSES_ROOT\CLSID\{432CDABA-68B5-4B7C-AE61-F4485EB97A70}


HKEY_CLASSES_ROOT\TypeLib\{3B7476EC-178F-4CA7-BFA7-80FEDA8B9AEA}


HKEY_CLASSES_ROOT\TypeLib\{9ED19E14-72A5-499B-84D8-4E7B89D0D33F}


HKEY_CLASSES_ROOT\WOW6432Node\CLSID\{432CDABA-68B5-4B7C-AE61-F4485EB97A70}</li></ul>&nbsp;
и повторить регистрацию.</td></tr></table>&nbsp;
&nbsp;<table><tr><td>
Исключение System.IO.FileLoadException. Не удалось загрузить файл или сборку "file:///*\recar2.models.dll" либо одну из их зависимостей. Операция не поддерживается. (Исключение из HRESULT: 0x80131515).</td></tr><tr><td>
Добавить в файл _*.exe.config_: 
**XML**<br />
``` XML

```
<a href="http://msdn.microsoft.com/en-us/library/dd409252(v=vs.110).aspx">Подробнее</a>.</td></tr></table>

## Ошибки в файле протоколов

Во время работы Ядро распознавание сохраняет диагностические сообщения в файлы протоколов (лог-файлы) по умолчанию в папку _%ProgramData%\Mallenom\Recar2.Core\logs_. В зависимости от типа сообщения они сохраняются в следующие файлы:
&nbsp;<ul><li>
_recar2.kernel.log_ - информационные сообщения, включая ошибки.</li><li>
_recar2.kernel.dbg.log_ - диагностические сообщения, включая ошибки.</li><li>
_recar2.kernel.err.log_ - подробные сообщения об ошибках.</li></ul>&nbsp;
Сообщения об ошибках:
&nbsp;<table><tr><td>
`[WRN] - Ошибка загрузки файла лицензии. [System.InvalidOperationException:'Не найден файл лицензии.'].`</td></tr><tr><td>
В директории с файлами ядра распознавания отсутствует файл лицензии (*.lic).</td></tr></table>&nbsp;
&nbsp;<table><tr><td>
`[ERR] - ProcessRfmUnit.Initialize() failed. [System.IO.FileNotFoundException:'Не удалось загрузить файл или сборку "mallenom.*.dll" либо одну из их зависимостей. Не найден указанный модуль.'].`</td></tr><tr><td>
Не установлен <a href="https://www.microsoft.com/en-us/download/details.aspx?id=53840">Visual C++ 2015 Redistributable Package (x86/x64)</a>.</td></tr></table>&nbsp;
