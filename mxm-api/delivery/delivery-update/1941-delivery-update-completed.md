# DELIVERY UPDATE COMPLETED

* ### URL = [https://mxmapi.unixus.com.my/api/deliveries/update/completed](https://mxmapi.unixus.com.my/api/deliveries/update/completed)
* ### Method = POST
* ### PARAMETERS

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | MOBILE USER ID | String | Yes | 20 | Mobile user name |
| 3. | LATITUDE | Decimal | No | 10, 6 | Latitude coordinate |
| 4. | LONGITUDE | Decimal | No | 10, 6 | Longitude coordinate |
| 5. | REMARKS | Text | No |  | Remarks |
| 6. | HAWB NO | String | Yes | 50 | Hawb number |
| 7. | SIGNATURE | Text | No |  | File of signature |
| 8. | TIMEZONE ID | String | Yes | 3 | Time zone |
| 9. | ID NO | String | No | 255 | Identity number |
| 10. | CONSIGNEE | String | No | 255 | Consignee Name |

##### \* for signature handled by file management list and file credential because formatted as file

### File Credentials

Credential use for file naming as SIGNATURE , save as file

#### USER CREDENTIAL

![](/assets/usrcred.JPG)

#### FILE MANAGEMENT LIST

![](/assets/fileinfor.JPG)

#### INPUT DATA PARAMETER

![](/assets/decom.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



