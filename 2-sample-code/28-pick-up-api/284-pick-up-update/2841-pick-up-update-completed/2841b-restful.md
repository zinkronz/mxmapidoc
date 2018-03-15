# 2.8.4.1B Pick Up Update Completed API \(RESTful\)

#### Sample source code for Pick Up Update Completed API

**URL = [https://mxmapi.unixus.com.my/api/pickups/update/completed](https://mxmapi.unixus.com.my/api/pickups/update/completed)**


Pick Up Update Completed
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
    "Longitude":312.0859824,
    "Latitude":121.5866858,
    "Username":"user name",
    "MobileUserId":"mobile user name",
    "JobStatusId":1,
    "HawbNo":"hawb number",
    "TokenKey":"token number",
    "FireBaseToken":"fireebaaseee",
    "InsertTimeZoneId":"01",
    "DisposeCode" : "99",
    "PickupNo":"pickup number"
  }

```

##### \*This API update the pick up job into completed pick up job (with necessary fields to fill) and token number for validate user.

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



