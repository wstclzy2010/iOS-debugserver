# iOS-debugserver
including iOS10/iOS12/iOS13/iOS14 debugserver
---
Already resigned with correct entitlements by 
```
codesign --force --sign "XXXXXXXXXXXXXXXXXX" --entitlements debuger.entitlements -f debugserver
```
Just rename it to "debugserver" and put it into 
```
/usr/bin/
```
Like:
```
scp -P<port number> debugserver root@127.0.0.1:/usr/bin/
```
Enjoy~~
---
已经通过正确的entitlements签名过了
```
codesign --force --sign "XXXXXXXXXXXXXXXXXX" --entitlements debuger.entitlements -f debugserver
```
只要重命名成debugserver放到目录
```
/usr/bin/
```
可以通过scp放到/usr/bin/，这样无需提权或修改权限
```
scp -P<端口号> debugserver root@127.0.0.1:/usr/bin/
```

