# QRcode3in1（收款码三合一）
测试地址：https://qr.juhua.fun

# 使用方法
1、准备QQ、微信、支付宝的收款码

2、在草料二维码（https://cli.im/deqr） 或其他相似网站，分别上传收款码，获取并保存二维码的内部信息

3、修改添加qq收款码信息到index.html文件中qqUrl的链接

4、修改添加微信收款码信息到index.html文件index.html文件中wechatUrl的链接

5、修改添加支付宝收款码信息到index.html文件中aliUrl的链接

6、将修改后的工程保存并上传至服务器

7、没有服务器的童鞋，可以想我一样挂在 github 或者 码云 上

# github搭建
1、按照如上步骤1-5修改index.html文件

2、新建github项目，并上传index.html文件及img/money.png图片文件
(如果是小白建议你直接包含img目录，全部上传，懂html的可以自己修改index文件中的图片地址）

3、点击项目的Settings，找到GitHub Pages下的Source，将其选项改为master branch

4、自主添加GitHub Pages下的Custom domain的域名（前提是域名已经配置完成）

5、访问域名即可查看三合一二维码

6、无域名的可以访问http://**你的github账号名**.github.io/**收款码项目的名称**


