# douyu-gift
针对斗鱼直播平台，自动赠送荧光棒续牌子
使用方式：
release下载软件安装，登陆账号，第一次启动可能不会开始赠送，这是一个未知错误，重启软件后就好了。
以后每日在房间领取荧光棒后启动软件等待完成即可

## 已完成
自动获取粉丝牌数据，平均分配荧光棒+赠送

## 待完成
1. 每日自动领取荧光棒，现在需要进入任意一个直播间手动领取，领取荧光棒应该不是XHR完成的，猜测应该是认证服务器做的，以后再测试。
2. 自定义赠送数量
3. 待完善逻辑交互

## 未来
应该会使用TS重构，前提是我得先学TS QAQ···


说明
使用 Vue + ElementUI + TypeScript 驱动，仅用于学习用途。这是第二版，第一版使用了 jQuery + Electron； 第二版从代码上更清晰，但是功能不变，仍然只是自动赠送荧光棒。

当前releases只构建了Windows X86_64版本，如果需要Linux或者Mac版本请在vue.config.js配置，相关配置文档

克隆
https://github.com/Curtion/douyu-gift.git

安装
yarn install

开发
yarn electron:serve

构建
yarn electron:build