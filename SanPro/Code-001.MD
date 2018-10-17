# Get Content from File on Server
---
### Specs:
#### Language: C#
#### ⚠️ Required .NET Framework
---
### Code:
```sh
string YourURL = "https://www.example.com/YourFile";
WebRequest WR = WebRequest.Create(new Uri(YourURL));
WebResponse WS = WR.GetResponse();
StreamReader SR = new StreamReader(WS.GetResponseStream());
string YourString = SR.ReadToEnd();
```
### Additional/Required Code
```sh
using System;
using System.Net;
using System.IO;
```
###### Last check of the code: 17.10.2018 with Microsoft Visual Studio 2017 (.NET Version 4.7)
