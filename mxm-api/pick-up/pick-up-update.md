# PICK UP UPDATE API



* ### URL =[https://mxmapi.unixus.com.my/api/pickups/update/{mode}](https://mxmapi.unixus.com.my/api/pickups/update/%7bmode%7d)

* ### Method = POST

* ### MODE

| NO | MODE | DESCRIPTION |
| :--- | :--- | :--- |
| 1. | COMPLETED | Update to completed pickup |
| 2. | FAILED | Update to failed pickup |



* ### PARAMETER

##### MODE = COMPLETED

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





* ### File Credentials =

Credential use for file naming as signature, save as file



1. #### USER CREDENTIAL



