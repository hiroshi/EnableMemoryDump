Are you tired of sudden death of software on Windows?
----
[![https://gyazo.com/5a420d41a38fc92997926efe0409bd63](https://i.gyazo.com/5a420d41a38fc92997926efe0409bd63.png)](https://gyazo.com/5a420d41a38fc92997926efe0409bd63)

Do this “xxx has stopped working” dialog or silent death of software irritate you?
Just dump memory of the software and send it to fxxkin developer!

A memory dump can be very useful for developers to detect the cause and may help them to fix it.

This tool enables Local Memory Dump of Windows Error Reporter from Microsoft.

## How to
### 1. Download this tool
[![https://gyazo.com/033a123239e1a95a594b7f679d9154df](https://i.gyazo.com/033a123239e1a95a594b7f679d9154df.png)](https://gyazo.com/033a123239e1a95a594b7f679d9154df)

You can download the tool from this button of the page.

### 2. Extract
Right click the downloaded zip file and extract contents of it.

### 3. Enable Local Memory Dump
[![https://gyazo.com/35f743c22614de19510f29ab85cdb66e](https://i.gyazo.com/35f743c22614de19510f29ab85cdb66e.png)](https://gyazo.com/35f743c22614de19510f29ab85cdb66e)

Double click `enable.bat`.

### 3.a If there was errors, exec `enable.bat` as Administrator
To enable Local Memory Dump function, you need to exec `enable.bat` as Administrator.

[![https://gyazo.com/776ebb0b789bc64d5231746a91ec9b77](https://i.gyazo.com/776ebb0b789bc64d5231746a91ec9b77.png)](https://gyazo.com/776ebb0b789bc64d5231746a91ec9b77)

Right click it and execute as Administrator.

### 4. Let the software crash
You can use the software as usual. If the software crash, Windows will automatically dump the memory of the crushed software.

[![https://gyazo.com/5a420d41a38fc92997926efe0409bd63](https://i.gyazo.com/5a420d41a38fc92997926efe0409bd63.png)](https://gyazo.com/5a420d41a38fc92997926efe0409bd63)

### 5. Let’s see the memory dumps
[![https://gyazo.com/c53546972792f702a35dd4befa7d2be2](https://i.gyazo.com/c53546972792f702a35dd4befa7d2be2.png)](https://gyazo.com/c53546972792f702a35dd4befa7d2be2)

Execute `seeDumps.bat`, and you can get the list of memory dumps.

[![https://gyazo.com/9c4feca057b744957e5c030ec1cbda16](https://i.gyazo.com/9c4feca057b744957e5c030ec1cbda16.png)](https://gyazo.com/9c4feca057b744957e5c030ec1cbda16)

### 6. Send dumps to the developer!
Please send the memory dumps to the developers.
These dumps encourage them to find their bugs. Thanks!

## Technical Appendix
### Including files
* Execting `enable.bat` enables your Windows to get memory dumps when some softwares crush.
* Execting `disable.bat` disables your Windows to get memory dumps.
* Execring `showDumps.bat` lead you to the directory where memory dumps are saved. You can get the files.

### more
For more information, see this.
https://msdn.microsoft.com/en-us/library/windows/desktop/bb787181%28v=vs.85%29.aspx

@hidesys

info@hidesys.net
