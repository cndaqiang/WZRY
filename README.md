
http://127.0.0.1:4000/2017/09/27/openwrt-jianshu/

备份
```
tar -czvf /tmp/overlay_backup.tar.gz /overlay
rm -rvf /overlay/* && cd / && tar -xzvf /tmp/overlay_backup.tar.gz
```
