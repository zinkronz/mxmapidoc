# USER INFO API

This API is for credential about user info, and show the information of the user \(in this case is Driver\)

* ### URL = [https://mxmapi.unixus.com.my/api/userinfo](https://mxmapi.unixus.com.my/api/userinfo)
* ### Method = POST
* ### PARAMETERS

| NO | PARAMETER | DATA TYPE | LENGTH | MANDATORY | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | UserName | String | 255 | Yes | Login name |
| 2 | Password | String | 255 | Yes | Login Password |
| 3 | CultureType | Enum |  | Yes | Login Culture |
| 4 | ApplicationCode | String | 255 | Yes | “DriverApps” |

* ### EXAMPLE :

![](/assets/userinfojson.JPG)

#####*after getting the information, it will automatically generate token number for user to validate in the rest of API

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



