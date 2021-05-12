# UEditor编辑器批量GetShell

## Code By:Tas9er @乐橙信安

#### 0x00 风险概述

本工具仅限授权安全测试使用,禁止未授权非法攻击站点

#### 0x01 工具使用

在ueditor.properties配置自定义漏洞利用页面字典

![1](image\1.jpg)



将需要测试的目标站点保存在当前文件夹下的url.txt里，需要携带HTTP或者HTTPS协议标识

![2](image\2.png)

启动脚本命令行，java -jar UEditorGetShell.jar，将图片马(ASPX)保存在VPS上，然后将RPC远程webshell路径填写在脚本里

![3](image\3.png)

回车，开始挂机批量吧！

![4](image\4.png)



#### 0x02 Bug问题

有空再说，先这样。