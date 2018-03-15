# 2.9.4.1B Delivery Update Completed API \(RESTful\)

#### Sample source code for Delivery Update Completed API

**URL = https://mxmapi.unixus.com.my/api/deliveries/update/completed**

Delivery Update Completed
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
          "FileBase64": "file base format number",
          "FileExtension": ".jpg",
          "FileName": "20171026041750-156130010396102Test.jpg",
          "FileType": "image/jpg",
          "FileFolderType": 3,
          "SASUrlExpiryDay": 1
        },
        "FileCategory": 2
      }
    ],
    "Longitude":12.1211212,
    "Latitude":123.23434,
    "Username":"user name",
    "MobileUserId":"mobile user name",
    "JobStatusId":1,
    "HawbNo":"Hawb number",
    "TokenKey":"Token Number",
    "FireBaseToken":"FireBase Number",
    "InsertTimeZoneId":"01",
     "DisposeCode" : "99"
  }
}

```
##### \*This API update the delivery job into completed delivery job (with necessary fields to fill) and token number for validate user.

---

###### Copyright © 2018 Unixus Solutions Sdn. Bhd. All rights reserved.



