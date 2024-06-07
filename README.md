# 关于WeTender

WeTender是一个基于[FISCO BCOS](https://fisco-bcos-doc.readthedocs.io/zh-cn/latest/index.html)开源平台打造的政企之间关于项目招标的管理平台，利用区块链、云计算、人工智能等多方面技术，建设一个高效的、统一的信息化系统，实现政企之间招标采购的数据共享和业务协同，保障各工程快速、高效稳步推进。

## 与WeTender-Front的关系

[WeTender-Front](https://github.com/Belowkm/WeTender)是专为WeTender开发的前端项目，采用[Vue3](https://cn.vuejs.org/) + [ElementPlus](https://element-plus.org/zh-CN/)等底层开源平台开发。github源码请见：<https://github.com/Belowkm/WeTender>。

## 原始人，启动！

1. 管理台基于WeBase，环境配置及详情步骤见官方说明文档：<https://webasedoc.readthedocs.io/zh-cn/latest/docs/WeBASE/install.html>。
2. 启动！

- 初次启动

```sh
python3 deploy.py installAll
```

- 日常启动

```sh
python3 deploy.py startAll
```

- 停止

```sh
python3 deploy.py stopAll
```

### 配置合约

1. 打开浏览器，访问：<http://localhost:5000>，进入WeBase管理界面。（初始账号密码为：Admin / Abcd1234）
2. 点击左侧导航栏的“合约管理”，进入“合约IDE”页面。
3. 点击“导入合约”，选择所有合约文件，进行导入和编译。
4. 为Bank、County_Gov、Enterprise、Town_gov四个合约，创建四个私钥用户，其余合约无需准备用户。
5. 选择“Bank”合约，点击“部署”按钮，部署合约。
6. 选择“County_Gov”合约，点击“部署”按钮，部署合约。
7. 选择“Enterprise”合约，点击“部署”按钮，部署合约。
8. 选择“Town_gov”合约，点击“部署”按钮，部署合约。
9. 所有合约部署完成。

### 使用方法

- 方法论暂时不想写了，诶嘿~
