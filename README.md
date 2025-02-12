# Nodego bot 1.1
## 项目介绍
nodego.ai 融资800w的项目，hash capital领投

注册账户：https://app.nodego.ai/r/NODEB2A4DECE0443

插件下载：https://chromewebstore.google.com/detail/nodegoai-depin-hub/jbmdcnidiaknboflpljihfnbonjgegah

## Nodego bot 1.1 配置说明
### config目录说明
``accounts.txt``注册配置，格式：
```txt
dandan01||||dandan@gmail.com||||1111@DANdan||||NODEB2A4DECE0443||||http://192.168.2.7:50003
```

``solver_key.txt``绕开cf验证的key存放

``token.txt`` token一个一个，注册时候会生成，或者手动抓取
抓取教程

![token抓取](https://github.com/user-attachments/assets/bbd0a1c4-3443-451d-aef5-1d95f19e6a9a)


### proxy说明 这里重要更新。这里重要更新
删除proxy目录！！删除proxy目录！！删除proxy目录！！直接使用config/proxy.txt的文件
必须注意，仔细理解这个说明，proxy.txt改成抽取的方式。由用户设置抽取ip的数量跑

### log目录错误运行日志


## Nodego bot 1.1 怎么运行？
注意linux和mac必须先打开终端cd到当前目录
#### mac
```bash
chmod +x Nodego_Mac
./Nodego_Mac
```

#### linux
```bash
chmod +x Nodego_Linux
./Nodego_Linux
```

#### windows
```txt
#方法1:双击Nodego.exe
#方法2:日志方式运行 cmd到当前目录 然后.\Nodego.exe
```
