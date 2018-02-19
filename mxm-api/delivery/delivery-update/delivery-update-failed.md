# DELIVERY UPDATE FAILED API

* ### URL = [https://mxmapi.unixus.com.my/api/pickups/update/failed](https://mxmapi.unixus.com.my/api/deliveries/update/failed)
* ### Method = POST
* ### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | HAWBNO | String | YES | 50 | Hawb number |
| 3. | MOBILE USER ID | String | Yes | 20 | Mobile user name |
| 4. | LATITUDE | Decimal | No | 10, 6 | Latitude coordinate |
| 5. | LONGITUDE | Decimal | No | 10, 6 | Longitude coordinate |
| 6. | DISPOSE CODE | String | Yes | 10 | Dispose Code number |
| 7. | REMARKS | Text | No |  | Remarks |
| 8. | TIMEZONE ID | String | Yes | 3 | Time zone |
| 9. | IMAGE SHOT | Text | No |  | Image file |
| 10. | ATTEMPT NO | String | No | 255 | Number of Attempt |

##### \* for image shot handled by file management list and file credential because formatted as file

### File Credentials

Credential use for file naming as image shot, save as file

#### USER CREDENTIAL

![](/assets/usrcred.JPG)

#### FILE MANAGEMENT LIST

![](/assets/fileinfor.JPG)

#### INPUT DATA PARAMETER

![](/assets/delfail.JPG)



