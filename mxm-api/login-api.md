# Login API

This API is only for credential of Login, to authorized driver for using the application

* ### URL = [https://mxmapi.unixus.com.my/api/login](https://mxmapi.unixus.com.my/api/login)

* ### Method = POST

* ### PARAMETERS

| NO | PARAMETER | DATA TYPE | LENGTH | MANDATORY | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | UserName | String | 255 | Yes | Login name |
| 2 | Password | String | 255 | Yes | Login Password |
| 3 | CultureType | Enum |  | Yes | Login Culture |
| 4 | ApplicationCode | String | 255 | Yes | “DriverApps” |

### EXAMPLE :

![](/assets/userinfo.JPG)

