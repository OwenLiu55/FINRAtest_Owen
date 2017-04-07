# FINRAtest_Owen

See the comments in "/src/main/java/com/finra/upload/utility/Scheduler" to configure the email sending funtionality.

**Upload File**
```
/uploadFile/{id}
@RequestParam multipartFile
```
**Download File**
```
/downloadFile/{id}
```
**Get File Info By Id**
```
/getFileById/{id}
```
**Get File Info By Name**
```
/getFileByName/{name}
```
**Get File Info List**
```
/getFileList
```
**Get File Info Uploaded during Last Hour**
```
/getRecentFile
```
