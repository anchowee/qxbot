**这个项目已经很长时间没有更新, 可能无法正常使用,如果你需要类似的功能, 可以参考 [magpie](https://github.com/coldnight/magpie) 项目**
## 介绍
一个桥接XMPP和QQ的机器人,现在仅仅支持桥接XMPP和QQ群消息,桥接后可以实现XMPP和QQ互通

## 环境
* Linux
* Python 2.7

## 配置
编辑settings.py填入相应配置项

## 安装
pip install -r dev_requirements.txt

## 运行
python qxbot.py

## 不足
* 需手动添加两个要桥接的帐号为好友
* QQ验证码没有提供解决方案,现在重试可跳过
