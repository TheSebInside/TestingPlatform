# iTextSharp - add Text with position
---
### Specs:
#### Language: C#
#### ⚠️ Required .NET Framework
#### ⚠️ Required iTextSharp Libary
---
### Code:
```shPdfContentByte pdfContentByte = pdfWriter.DirectContent;
ColumnText column = new ColumnText(pdfContentByte);
column.SetSimpleColumn(70, 70, 70, 70);
column.AddElement(new Paragraph("Your Text goes here"));
column.Go();
```
###### Last check of the code: 21.10.2018 with Microsoft Visual Studio 2017 (.NET Version 4.7)
