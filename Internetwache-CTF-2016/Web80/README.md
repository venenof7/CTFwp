![image](https://github.com/Veneno0/CTFwp/blob/master/Internetwache-CTF-2016/Web80/2885962034.jpg)
Clicking on the link
![image](https://github.com/Veneno0/CTFwp/blob/master/Internetwache-CTF-2016/Web80/2563772299.jpg)
We will find the hint is git
![image](https://github.com/Veneno0/CTFwp/blob/master/Internetwache-CTF-2016/Web80/1732830763.jpg)
We get .git , but we cannot find the flag , of courese , on the link , we will find another hint——————years，we also know the git head，so I use this command：
```java  
   
$ git reset --hard HEAD^
   
```
OK，find the flag.
![image](https://github.com/Veneno0/CTFwp/blob/master/Internetwache-CTF-2016/Web80/3775518615.jpg)
