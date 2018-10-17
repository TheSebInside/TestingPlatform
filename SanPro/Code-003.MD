# Download File from Server
---
### Specs:
#### Language: C#
#### ⚠️ Required .NET Framework
---
### Code:
```sh
string YourURL = "https://www.example.com/YourFile";
string YourEndPath = @"C:\ExampleFolder";
WebClient WC = new WebClient();
WC.DownloadFile(YourURL,YourEndPath);
```
### Additional/Required Code
```sh
using System;
using System.Net;
```
###### Last check of the code: 17.10.2018 with Microsoft Visual Studio 2017 (.NET Version 4.7)
