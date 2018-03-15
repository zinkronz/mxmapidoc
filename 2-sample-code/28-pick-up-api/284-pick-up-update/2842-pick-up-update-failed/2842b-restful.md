# 2.8.4.2B Pick Up Update Failed API \(RESTful\)

#### Sample source code for Pick Up Update Failed API

**URL = [https://mxmapi.unixus.com.my/api/pickups/update/failed](https://mxmapi.unixus.com.my/api/pickups/update/failed)**


Pick Up Update Failed
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
          "FileBase64": "File Base 64 format",
          "FileExtension": ".jpg",
          "FileName": "20171026041750-156130010396102Test.jpg",
          "FileType": "image/jpg",
          "FileFolderType": 3,
          "SASUrlExpiryDay": 1
        },
        "FileCategory": 2
      }
    ],
    "Longitude":311.0859824,
    "Latitude":121.5866858,
    "Username":"User Name",
    "MobileUserId":"Mobile User Id",
    "JobStatusId":1,
    "HawbNo":"hawb number",
    "TokenKey":"Token Number",
    "FireBaseToken":"Firebase",
    "InsertTimeZoneId":"01",
    "DisposeCode" : "99",
    "PickupNo":"pick up number"
  }
```




##### \*This API update the pick up job into failed pick up job (with necessary fields to fill) and token number for validate user.

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



