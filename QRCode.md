![Logo](./resources/logo.png)
# **Документация по GosuScreen API: QRCode**



## Запрос и его структура

```
  POST /qrcode
```

| Параметр | Тип     | Описание                |
| :-------- | :------- | :------------------------- |
| `token` | `строка` | **Обязательный**. Ваш ключ API |
| `service` | `число` | **Обязательный**. ID сервиса, который будет генерироваться, подробнее о [поддерживаемых сервисах](#поддерживаемые-сервисы) |
| `value` | `строка` | **Обязательный**. Текст для кодирования. Любой текст|

**Возвращает тип:** `image/png`

**При ошибке:** `application/json`
## Поддерживаемые сервисы

| ID  | Название     | 
| :-------- | :------- |
|`0`|`zasilkovna`|
|`1`|`vinted`|
|`2`|`balikovna`|
|`3`|`dpd`|
|`4`|`facebook`|
|`5`|`packeta`|
|`6`|`subito`|
|`7`|`wallapop`|
|`8`|`spedire`|
|`9`|`sbazar`|
|`10`|`bazos`|
|`11`|`ceskaposta`|
|`12`|`ebay`|
|`13`|`olx`|
|`14`|`ebayklz`|
|`15`|`booking`|
|`16`|`dhl`|
|`17`|`jofogas`|
|`18`|`foxpost`|
|`19`|`depop`|
|`20`|`elta`|
|`21`|`acs`|
|`22`|`shpock`|
|`23`|`gumtree`|
|`24`|`gls`|
