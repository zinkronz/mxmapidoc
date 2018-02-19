# DISPOSE CODE API

### URL = [https://mxmapi.unixus.com.my/api/disposecode/{mode}](https://mxmapi.unixus.com.my/api/disposecode/%7bmode%7d)

#### {mode}  is string that need to fill with parameter



### Method = POST



### PARAMETER

| NO | PARAMETER | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | YES | 255 | Token Key for validate |



### MODE :

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1. | PICKUP | Shows the pickup dispose codes |
| 2. | DELIVERY | Shows the delivery dispose codes |



### EXAMPLE :

---

var discod = new DisposeCode\(mode\);

discod.TokenKey = “TokenNumber”;

---



