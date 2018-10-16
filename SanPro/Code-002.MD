# Get Productversion from other Application
---
### Specs:
#### Language: C#
#### ⚠️ Required .NET Framework
---
### Code:
```sh
FileVersionInfo FVI = FileVersionInfo.GetVersionInfo(@"Path of your Application");
string V = FVI.ProductVersion;
```
### Additional/Required Code
```sh
using System.Diagnostics;
```
###### Last check of the code: 16.10.2018 with Microsoft Visual Studio 2017 (.NET Version 4.7)
