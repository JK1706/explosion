# explosion
1.打开软件之后填写相应配置
注意：Post数据这里不需要填入整个post数据包
只需要填入这个数据即可：例如：username=123123132121&password=1231212313123&code=1234
填完数据项之后

2.转到配置项
填入网页验证码端的网址（要填写整个验证码地址http://xxx.com/xxxxx，有的可能会后面带time=0.0000120，像这样的参数不用带，只要不带参数的那一段）

3.然后导入想要爆破的用户名或者密码，现不能同时爆破（导入之后可能会不显示，但是会提示导入成功）然后导入完成在打上对勾

4.然后完成这些工作之后转到原始数据页面
点击重发器将会跳到重发器选择页
到了这一步。如果选择的是用户名爆破或者密码爆破
就改成：username=用户名或者password=密码
无论爆破哪个code都要写成code=验证码
“=”后面的都用文字代替

5.然后点击爆破

6.显示结果
爆破完成之后
右侧的框框将会显示类似burp的请求参数
左侧将什么都不会显示
然后爆破完之后，鼠标点击右侧的每一行数据，都将会在左侧显示出来，就是右侧点哪个左侧就显示哪个

7.总之非常方便，奥利给就完事了。

8.有什么问题都可以问我（qq1536803897），本人可能有点菜，不装。
