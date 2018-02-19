# Login API

### URL = [https://mxmapi.unixus.com.my/api/login](https://mxmapi.unixus.com.my/api/login)

### 

### Method = POST

### 

### PARAMETERS

| NO | PARAMETER | DATA TYPE | LENGTH | MANDATORY | DESCRIPTION |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | UserName | String | 255 | Yes | Login name |
| 2 | Password | String | 255 | Yes | Login Password |
| 3 | CultureType | Enum |  | Yes | Login Culture |
| 4 | ApplicationCode | String | 255 | Yes | “DriverApps” |



### EXAMPLE :

---

var \_AuthCredentials = new auth\_ixm.AuthCredentials\(\);

\_AuthCredentials.UserName = "loginname";

\_AuthCredentials.Password = "password";

\_AuthCredentials.ApplicationCode = "DriverApps";

\_AuthCredentials.CultureType = auth\_ixm.CultureType.English;

---



