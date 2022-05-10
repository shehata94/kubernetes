# Some important commands to execute the project 
### PowerShell - bash/sh
convert words into base64 so as to be accepted in mongdb credentials
```
[System.Convert]::ToBase64String([System.Text.Encoding]::UTF8.GetBytes('Word')) 
echo -n 'Word' | base64
```


