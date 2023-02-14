# Access-chatGPT-in-Siri
Siri接入ChatGPT指南。目前仅限iPhone端及其他支持快捷指令的Apple产品，后续会更新Android版本。

# 创建账号/登录账号

​第一次使用chatGPT时，先到chatGPT的官网新建账号：
![image-20230210003127112](images/image-20230210003127112.png)
点击“Sign up”进行账号的注册，如果有账号的话则点击“Log in”登录。

![image-20230210003249233](images/image-20230210003249233.png)

可以用大多数的邮箱进行账号的注册，包括但不限于QQ邮箱、163邮箱、google邮箱、教育邮箱等；
![image-20230210003423746](images/image-20230210003423746.png)
如果遇到这种情况，那就代表着chatGPT用户过多，多刷新几次就好了。



登录之后进入这个网站进行API的申领：https://platform.openai.com/account/api-keys

![image-20230210003548551](images/image-20230210003548551.png)

登录账号，点击“Create New Security Key”，进行API key的创建![image-20230210003635094](images/image-20230210003635094.png)



key只会显示一次，只有一次！！！记得妥善保管！如果key没来得及保存的话，只能重新生成！！key的格式：sk-xxxxxx。最好记录上，以后方便随时调用。

# 下载捷径

下面放有快捷指令链接：

1.0 单次问答：
https://www.icloud.com/shortcuts/ddb23c1a0d29406ab82c26cef8621974

1.1 单次问答带QA：
https://www.icloud.com/shortcuts/b7843588bb11435f90e04a992c24e256

2.0 多次连续回答：
https://www.icloud.com/shortcuts/18d3f2621abb424c9bc85a46ede39142

2.1 修复弹窗bug：
https://www.icloud.com/shortcuts/809977bb030f4c9f9ce57a357e3ddf0c

2.2 新增无需手动点击继续对话功能；新增“再见”互动结束语；更新了连续对话显示QA；优化了文本弹窗的问题；优化了格式缩进问题
https://www.icloud.com/shortcuts/cebc3ec416a24a91a60405dd6cdf7708

没魔法没Key可以参考这个：
https://aichatgpt.me/Siri.html

网页版免费无需接口地址：
https://aichatgpt.me/

## 由于版本过多，拷贝下来之后要重命名，例如：smart Siri 1.0 ==> smart Siri

把你的key粘贴到如上图所示的位置，注意！是全选替换！

![image-20230210004316760](images/image-20230210004316760.png)



这样就完成啦！

# [开发不易，请杯瑞幸吧](https://afdian.net/a/Daiyimo/plan)
https://afdian.net/a/Daiyimo/plan

# 使用说明

两种输入方法：

一、“嘿 Siri，smart Siri”，即可打开快捷指令（第一次打开会有权限提醒，一路点是就好）

二、在快捷指令里点开，并在yes！下面的框中输入你的问题即可！

# 补充

发现如下bug：
Siri弹窗超出字符报错；
继续分支可以设为关键词结束；
bug会在下个版本进行修复！！！

部分手机会遇到文本弹窗的情况，请先用Siri语音运行一次Smart Siri，进行第一次问答，一路点允许，直到报错。再次从快捷指令中打开SmartT Siri即可正常使用！！！

目前只支持iPhone的快捷指令，还不知道Android的实现方法，在做了在做了，如有更好的点子欢迎联系我！
## 体验交流群
# 一群已满加二群
# 二群已满加三群
# 三群已满请稍等
