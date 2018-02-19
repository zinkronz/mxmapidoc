# DELIVERY LIST API

* ### URL = [https://mxmapi.unixus.com.my/api/deliveries/list/{mode}](https://mxmapi.unixus.com.my/api/deliveries/list/%7bmode%7d)
* ### Method = POST
* ### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | MOBILE USER ID | String | YES | 20 | Mobile User |



* ### MODE

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1 | TODO | Shows all deliveries |
| 2. | COMPLETED | Shows only completed deliveries |
| 3. | FAILED | Shows only failed deliveries |
| 4. | CALENDAR | Shows all deliveries by calendar/ date |



### EXAMPLE

![](/assets/delist.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.       







