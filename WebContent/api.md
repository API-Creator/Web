# R inc. API-Creator API Docs  
## URL = http://api.rinc.kr  

#### Error code  
```
{  
'status' : 'miss_match_content_type'  //request header Content-type miss match
'status' : 'no_argument'  //sql where argument not found  
'status' : 'data_not_found' // database result not found  
'status' : 'undefined token' // not decoded jwt token  
'status' : 'sql_error' // insert query values error
}  
```
### /getProjects.php
Requests data [POST]  
```
{  
'token' : '~~~'
}
```
Response data  
```
{
'status' : 'complate'  
'idx' : 2//integer  
'owner' : 5051//integer  
'url' : 'http://~~~'  
'title' : 'api cretor hehe' 
'description' : 'heheheheh'
'invited' : '11,22,33'
}  
```
### /addProject.php  
Request data [POST]
```
{
'token' : '~~~~'  
'url' : 'http://~~'  
'title' : 'cocoa~~~~'  
'description' : 'description ooo' 
'invited' : '1,2,3,4'  
}
```
Response data  
```
{
'status' : 'complate'
}
```

### /delProject.php  
Requests data [POST]  
```
{  
'token' : '~~~'  
'idx' : 1  
}
```

Response data
```
{  
'status' : 'complate'  
}  
```

### /modiProject.php  
Request data [POST]  
```  
'token' : '~~~~~'  
'idx' : 2  
'url' : 'http://~`'
'title' : 'qqqqq'
'description' : 'abcdefg'  
'invited' : '1,2,3,6,8'  
```

Response data  
```
{  
'status' : 'complate'  
}  
```





