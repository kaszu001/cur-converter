# Cur converter - Конвертер валют
## Установка
### Активировать Env проекта
```bash
.\env\Scripts\activate
```
### Requirements
```bash
pip install -r requirements.txt
```
### QT5
Создание py скрипта на основе ui
```
.\env\Scripts\pyuic5.exe form.ui -o from.py -x
```
## Директории / файлы
| Название          | Описание                    |
|-------------------|-----------------------------|
| src               | основная директория проекта |
| designer.cmd      | запускает qt designer       |

## API
### Документация currency converter api
[Docs in currencyconverterapi.com](https://www.currencyconverterapi.com/docs)
### Api key
```
apiKey=0b636deb6bc43794e0c9
```
### URL Example
- from - из какой валюты 
- to - в кокую валюту xd
```
https://free.currconv.com/api/v7/convert?q={from}_{to}&compact=ultra&apiKey=0b636deb6bc43794e0c9
```
## Other
### UI/UX
[Figma project](https://www.figma.com/file/9AEOwdIIXmJCNoiHQn1mHF/Cur-converter?node-id=2%3A89)
