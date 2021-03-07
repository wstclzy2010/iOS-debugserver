# iOS-debugserver
including iOS10/iOS12/iOS13 debugserver
---
already resigned with correct entitlements by ldid

just rename it to debugserver and put it into 
```
/usr/bin/
```
and 
```
chmod +x debugserver
```
Enjoy~~
---
已经通过正确的entitlements用ldid签名过了，只要重命名成debugserver放到目录
```
/usr/bin/
```
可以通过scp放到/usr/bin/，无需提权或修改权限
```
scp -P端口号 debugserver root@127.0.0.1:/usr/bin/
```
~~然后提权即可使用。也可以直接在filza里面设置权限0755~~
~~```
chmod +x debugserver
```
~~
