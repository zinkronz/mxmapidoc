# 2.9.4.2B Delivery Update Failed API \(RESTful\)

#### Sample source code for Delivery Update Failed API

**URL = [https://mxmapi.unixus.com.my/api/pickups/update/failed](https://mxmapi.unixus.com.my/api/deliveries/update/failed)**


Delivery Update Failed
```
{
  "request": {
    "FileCredentials": {
      "CultureType": "1",
      "Password": "password",
      "UserName": "user name"
    },
    "FileManagementList": [
      {
        "FileReferenceId": "156130010396102Test",
        "RemoteFileInfo": {
          "FileBase64": "file base 64 format",
          "FileExtension": ".jpg",
          "FileName": "20171026041750-156130010396102Test.jpg",
          "FileType": "image/jpg",
          "FileFolderType": 3,
          "SASUrlExpiryDay": 1
        },
        "FileCategory": 2
      }
    ],
    "Longitude":113.085329824,
    "Latitude":121.22866858,
    "Username":"user name",
    "MobileUserId":"mobile user name",
    "JobStatusId":1,
    "HawbNo":"ccc",
    "TokenKey":"token number",
    "FireBaseToken":"firebasee",
    "InsertTimeZoneId":"01",
    "DisposeCode" : "99"
  }
}
```



##### \*This API update the delivery job into failed delivery job (with necessary fields to fill) and token number for validate user.

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



