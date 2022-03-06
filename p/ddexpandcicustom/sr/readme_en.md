

servarica
-----

这是个大盘鸡，仓库主要是用了xen pv的guest驱动和gpt/efi支持

```
          ## sr
          #sudo sed -i "s/gitee.com\/minlearn\/onekeydevdesk/gitee.com\/minlearn\/onekeydevdesksr/g" ./ci.sh
          #sudo sed -i "s/github.com\/minlearn\/onekeydevdesk/github.com\/minlearn\/onekeydevdesksr/g" ./ci.sh
          #sudo sed -i "s/_build\/onekeydevdesk/_build\/onekeydevdesksr/g" ./ci.sh
          #sudo chmod +x ./ci.sh && sudo ./ci.sh -b 0 -h sr -t onekeydevdesk
```
