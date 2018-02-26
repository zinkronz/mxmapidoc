# LOGIN AUTHENTICATION SERVICE

#### Service URL =  [http://api.unixus.com.my/Administration/UBaseServices/Security/Authentication.svc](http://api.unixus.com.my/Administration/UBaseServices/Security/Authentication.svc)

The table below showing the credentials that needs to pass into the API. The system need to authenticate the valid user before it can proceed to the next step.

| No | Parameter | Data Type | Length | Mandatory |
| :--- | :--- | :--- | :--- | :--- |
| 1 | LoginName | String | 255 | Yes |
| 2 | Password | String | 255 | Yes |
| 3 | CultureType | Enum |  | Yes |
| 4 | AppCode | String | 255 | Yes |

Example :

![](/assets/credlogin].JPG)

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



