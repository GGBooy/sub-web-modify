# sub-web-modify
[最美订阅转换](https://sub.v1.mk)基于[CareyWang/sub-web](https://github.com/CareyWang/sub-web)，UI小改，增加近百条远程配置！
### 食用方法【以Linux为例】：
1.安装 [node](https://blog.csdn.net/achabuhecha/article/details/111400068) 和 [yarn](https://classic.yarnpkg.com/en/docs/install#debian-stable) 和 [git](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)

2.终端执行 `cd /home && git clone https://github.com/limr95/sub-web-modify.git && chmod -R 755 sub-web-modify && cd sub-web-modify && yarn install && yarn build`

3.build成功后，服务器自行配置ngnix并指定默认目录为/home/sub-web-modify/dist

4.如需进一步修改前端，请在/home/sub-web-modify下执行 `yarn serve` 进行调试即可