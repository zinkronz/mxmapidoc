# PICK UP COUNT API

* ### URL = [https://mxmapi.unixus.com.my/api/pickups/count/{mode}](https://mxmapi.unixus.com.my/api/pickups/count/{mode})
* ### Method = POST
* ### PARAMETER

| No | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | MOBILE USER ID | String | YES | 20 | Mobile User |

* ### MODE

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1. | COMPLETED | Count only completed pickups |
| 2. | FAILED | Count only failed pickups |
| 3. | PENDING | Count only pending pickups |

* ### EXAMPLE

### ![](/assets/countjson.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



