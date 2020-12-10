# NPOI Examples

This repository is splitted from [NPOI master repository](https://github.com/nissl-lab/npoi) in order to manage the examples easily.

# To Get Started with NPOI (on Windows 10)
a. Open PowerShell and run the following command:
```
git clone https://github.com/nissl-lab/npoi-examples
```
b. Open npoi-examples/ss/CalendarDemo/CalendarDemo.csproj with Visual Studio 2019 community version and click 'Run program' button

c. You will see a new generated file called Calendar.xls under npoi-examples/ss/CalendarDemo/bin/Debug folder
d. Open the Calendar.xls with Microsoft Excel or Kingsoft WPS 
e. Go back to Powershell window and run the following command
```
cd npoi-examples/ss/CalendarDemo/bin/Debug
./CalendarDemo -xlsx 
```
f. You will see a new generated file called Calendar.xlsx under npoi-examples/ss/CalendarDemo/bin/Debug folder
g. Open the Calendar.xlsx with Microsoft Excel or Kingsoft WPS

The result of Calendar.xls and Calendar.xlsx looks same in Microsoft Excel or Kingsoft WPS but they are totally different file formats generated by NPOI.

# Folders Explained
|Folder Name| Description|
|---|---|
|POIFS|OLE2/ActiveX document examples|
|HSSF |examples for Microsoft Excel BIFF(Excel 97-2003, xls) |
|SS | Excel Common examples for both Excel 2003(xls) and Excel 2007+(xlsx)|
|XSSF |Excel 2007(xlsx) examples|
|XWPF |Word 2007(docx) examples|
|OOXML|OpenXml format low-level examples|
|ScratchPad/HWPF|Word 2003(doc) examples|

