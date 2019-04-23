# Wechat Auto Admire

(problem setup) reading materials:  https://mp.weixin.qq.com/s/EssVIqNXLDWn_HubHzJ8Mw

### environment：
<br>

```shell
pip install itchat pillow
```

<br/>

### admirebot：
1. in simple_admire.py, set up group name:
```
    group_name = 'your_group_name'; 
```

2. run simple_admire.py
```shell
python3 simple_admire.py
```

3. scan wechat QR code: 

4. input key words like "夸我"、"求夸"， get compliments!

<br/>

### 注意事项：

- 此回复是使用了微信网页端，如果设置了自动回复，电脑端微信自动退出。

- 目前赞美句库就100句多点，你可以自行扩展。

- 用来扫码的那个微信号就自动变成夸夸群机器人，要想体验被夸，需要夸夸群里别的微信号发送关键字信息来触发。

- 如果发现二维码显示不全的情况，请修改simple_admire.py
```
# Windows，enableCmdQR=True
# itchat.auto_login(enableCmdQR=True, hotReload=True)
# Mac、Linux，enableCmdQR=2
itchat.auto_login(enableCmdQR=2, hotReload=True)
```

<br/>

