# PICK UP UPDATE COMPLETED API

* ### URL = [https://mxmapi.unixus.com.my/api/pickups/update/completed](https://mxmapi.unixus.com.my/api/pickups/update/completed)
* ### Method = POST
* ### PARAMETER

| NO | PARAMETER | DATA TYPE | MANDATORY | LENGTH | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | TOKEN KEY | String | YES | 255 | Token Key for validate |
| 2. | PICKUPNO | String | YES | 50 | Pickup number |
| 3. | MOBILE USER ID | String | Yes | 20 | Mobile user name |
| 4. | LATITUDE | Decimal | No | 10, 6 | Latitude coordinate |
| 5. | LONGITUDE | Decimal | No | 10, 6 | Longitude coordinate |
| 6. | ITEM QUANTITY | INT | Yes |  | Quantity of items |
| 7. | REMARKS | Text | No |  | Remarks |
| 8. | HAWB NO | String | Yes | 50 | Hawb number |
| 9. | SIGNATURE | Text | No |  | File of signature |
| 10. | TIMEZONE ID | String | Yes | 3 | Time zone |
| 11. | ID NO | String | No | 255 | Identity number |
| 12. | CONSIGNEE | String | No | 255 | Consignee Name |

##### \*for the signature will use file management info to handle because the signature is formatted as file

* ### File Credentials =

Credential use for file naming as signature, save as file

#### USER CREDENTIAL

![](/assets/usrcred.JPG)

#### FILE MANAGEMENT LIST

![](/assets/fileinfor.JPG)

#### INPUT DATA PARAMETER

![](/assets/pickupdaco.JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



