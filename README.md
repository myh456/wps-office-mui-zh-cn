# WPS 11.1.0.11273版本mui
## 使用方法
``` bash
git clone https://github.com/myh456/wps-office-mui-zh-cn.git
cd ./wps-office-mui-zh-cn
sudo rm -rf /usr/lib/office6/mui
sudo mv ./mui /usr/lib/office6
```
重启wps即可完成汉化。如果将来想恢复wps的英文显示，在第三步可以不选择删除原mui,而是保存至其他位置，如 ` sudo mv /usr/lib/office6/mui ~/Documents `。 
