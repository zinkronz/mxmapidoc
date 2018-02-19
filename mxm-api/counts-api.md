# COUNTS API

### URL = [https://mxmapi.unixus.com.my/api/counts/{mode}](https://mxmapi.unixus.com.my/api/counts/{mode})

#### {mode}  is string that need to fill with parameter



### Method = POST



### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | MOBILE USER ID | String | YES | 20 | Mobile User |

### MODE

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1 | ALL | Count all jobs |
| 2. | COMPLETED | Count only completed jobs |
| 3. | FAILED | Count only failed jobs |
| 4. | PENDING | Count only pending jobs |



