# PICK UP LIST API

* ### URL = [https://mxmapi.unixus.com.my/api/pickups/list/{mode}](https://mxmapi.unixus.com.my/api/pickups/list/{mode})

#### {mode}  is string that need to fill with parameter

* ### Method = POST
* ### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | MOBILE USER ID | String | YES | 20 | Mobile User |

* ### MODE

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1 | TODO | Shows all pickups |
| 2. | COMPLETED | Shows only completed pickup |
| 3. | FAILED | Shows only failed pickup |

* ### EXAMPLE

![](/assets/countjson.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



