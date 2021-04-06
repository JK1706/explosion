# explosion
<strong>一.使用方法</strong>

打开软件之后会有URL和post填入依照下面方式填入即可

如图显示：
![image](https://user-images.githubusercontent.com/72113877/113388137-3ceb7580-93c0-11eb-9be1-11fe10abfe5d.png)

只需要填入Host+POST请求路径即可

写法如:http://www.xxx.xxx/Login/checkLogin.html

post数据那一栏填入：

![image](https://user-images.githubusercontent.com/72113877/113388688-46c1a880-93c1-11eb-9531-99648e3a5c11.png)

这一行数据即可

协议头可以为空

为空的时候post数据类型为(&)符号的时候：name=xxx&passwd=xxx&code=xxx

post数据为json数据的时候
![image](https://user-images.githubusercontent.com/72113877/113653575-b2a95700-96c8-11eb-9389-7953bdb55008.png)

协议头填：Content-Type: application/json

post数据为url部分编码的时候

![image](https://user-images.githubusercontent.com/72113877/113653818-20558300-96c9-11eb-90b9-dfd787eacbfe.png)

协议头填：Content-Type: application/x-www-form-urlencoded

post数据为下面的时候

上传文件的时候的格式

协议头填：Content-Type: multipart/form-data

相应的下面配置验证码，填入验证码对应的web地址（如果碰到对应的时间戳地址，则不取时间戳，只取能刷新出来验证码页面的web地址）

配置完之后，点击发送重发器

如果爆破用户名（username=123456789改成username=用户名）

如果爆破密码（password=123456789改成passowrd=密码）

无论爆破哪一个验证码都需要改成：code=1234改成code=验证码

如果同时爆破用户名和密码，则三个都需要改。

QQ1536803897 有事咨询。还有bug提交。

