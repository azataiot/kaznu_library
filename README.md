# This is for using computer in KazNU university library:

## Some useful softwares to start with:

1. Git (Safed Locally) `Git-2.17.0-64-bit`
2. Visual Studio Code (Also saved locally) `VSCodeSetup-x64-1.23.1`
3. Sougou Pinyin input for Chinese lang `sogou_pinyin_90a`
4. PyCharm Professional 


## Some important staff to figure:

### figure Github:
```bash
git config --global user.name "Yaakov Azat"
``` 
``` bash
git config --global user.email "yaakovazat@gmail.com" 
``` 
``` bash
git config --global http.proxy http://10.5.0.83:8080
``` 
``` bash
git config --global https.proxy https://10.5.0.83:8080
``` 
### Configure Visual Studio Code    
Press `Ctrl+Shift+P` to bring up the Command Palette then start typing "config" to filter and display the Configure Language command.
![](img/configure-language-command.png)  

### configure Pycharm   
username:`yaakovazat`   

### config SSH key

create a new ssh key: `ssh-keygen -t rsa -b 4096 -C "yaakovazat@gmail.com"`

add SSH key to ssh agent: `ssh-add ~/.ssh/id_rsa`

clip the SSH key to the clipboard: `clip < ~/.ssh/id_rsa.pub`


