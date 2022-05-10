# Some important commands to execute the project 
## PowerShell
convert words into base64 so as to be accepted in mongdb credentials
```
[System.Convert]::ToBase64String([System.Text.Encoding]::UTF8.GetBytes('Word')) 
```
## bash/sh
```
echo -n 'Word' | base64
```


