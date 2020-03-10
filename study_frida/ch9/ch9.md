#  第九课
* 第九课 frida android中的一些实例 socket_trace、java常用算法trace、ssl_trace式   
    export PATH=$PATH:/Users/haidragon/Library/Android/sdk/platform-tools
    
```
import ssl
ssl._create_default_https_context = ssl._create_unverified_context
```


