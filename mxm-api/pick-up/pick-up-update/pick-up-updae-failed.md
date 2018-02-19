# PICK UP UPDATE FAILED API

* ### URL = [https://mxmapi.unixus.com.my/api/pickups/update/failed](https://mxmapi.unixus.com.my/api/pickups/update/failed)
* ### Method = POST
* ### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | PICKUPNO | String | YES | 50 | Pickup number |
| 3. | MOBILE USER ID | String | Yes | 20 | Mobile user name |
| 4. | LATITUDE | Decimal | No | 10, 6 | Latitude coordinate |
| 5. | LONGITUDE | Decimal | No | 10, 6 | Longitude coordinate |
| 6. | DISPOSE CODE | String | Yes | 10 | Dispose Code number |
| 7. | REMARKS | Text | No |  | Remarks |
| 8. | TIMEZONE ID | String | Yes | 3 | Time zone |
| 9. | IMAGE SHOT | Text | No |  | Image file |
| 10. | ATTEMPT NO | String | No | 255 | Number of Attempt |

##### \*for the Image shot will use file management info to handle because the Image shot is formatted as file

* ### File Credentials =

Credential use for file naming as Image shot, save as file

#### USER CREDENTIAL

![](/assets/usrcred.JPG)

#### FILE MANAGEMENT LIST

![](/assets/fileinfor.JPG)

#### INPUT DATA PARAMETER

![](/assets/pickupdaco.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



