# Nodego bot 1.0
## 项目介绍
nodego.ai 融资800w的项目，hash capital领投

注册账户：https://app.nodego.ai/r/NODEB2A4DECE0443

插件下载：https://chromewebstore.google.com/detail/nodegoai-depin-hub/jbmdcnidiaknboflpljihfnbonjgegah

## Nodego bot 1.0 配置说明
### config目录说明
``accounts.txt``注册配置，格式：
```txt
dandan01||||dandan@gmail.com||||1111@DANdan||||NODEB2A4DECE0443||||http://192.168.2.7:50003
```

``solver_key.txt``绕开cf验证的key存放

``token.txt`` token一个一个，注册时候会生成，或者手动抓取
抓取教程

![token抓取](https://github.com/user-attachments/assets/bbd0a1c4-3443-451d-aef5-1d95f19e6a9a)


### proxy目录说明
必须注意，仔细理解这个说明，proxy代理_1代表token第一行

proxy_1.txt对应token.txt第一行

proxy_2.txt对应token.txt第二行

proxy_3.txt对应token.txt第三行

### log目录错误运行日志


## Nodego bot 1.0 怎么运行？
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
