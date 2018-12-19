# GCP_VSCode_sftp
Edit remote files on localhost with VS Code.

## Usage
Config

``` 
{
    "host": "xx.xx.xx.xx",
    "port": 22,
    "username": "amyfanpti",
    "password": "xxxx",
    "remotePath": "/home/amyfanpti/project/python/",
    "privateKeyPath": "D:\\project\\GCP\\xxxx.ppk",
    "passphrase": null,

    "ignore": [

        ".vscode",

        ".git",

        ".DS_Store",

        ".svn"

      ],
    "profiles": {
        "google_sheets_update": {
            "remotePath": "/home/amyfanpti/project/python/google_sheets_update/",
            "uploadOnSave": true
        },        
        "moneyhunter": {
            "remotePath": "/home/amyfanpti/project/python/moneyhunter/",
            "uploadOnSave": true
        }
    },
    "defaultProfile": "google_sheets_update" 
}
``` 

Demo

![alt tag](https://i.imgur.com/3ZOSZrM.jpg)
![alt tag](https://i.imgur.com/64htIAB.jpg)
![alt tag](https://i.imgur.com/R0ZReTD.jpg)

## Reference 
* [遠端編輯VSC 但是!!!這種方法不是我想要的那種，這一次只能開一個檔案，我希望他跟平常一樣在旁邊的explorer列出所有的文件阿~~~](http://kestanley.blogspot.com/2018/03/vsc.html)
* [Super fast sftp/ftp extension for VS Code](https://github.com/liximomo/vscode-sftp)
* [Visual Studio Code - SFTP Extension Using SSH Authentication](https://stackoverflow.com/questions/46852476/visual-studio-code-sftp-extension-using-ssh-authentication)