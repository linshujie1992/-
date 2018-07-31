# 工程文件操作

## 做好文件备份工作！！！

1、打开自动保存设置，预防突发情况（比如maya突然崩溃、公司突然断电）

![&#x6253;&#x5F00;&#x201C;&#x81EA;&#x52A8;&#x4FDD;&#x5B58;&#x201D;&#x8BBE;&#x7F6E;](.gitbook/assets/zi-dong-bao-cun-she-zhi.png)

2、在CGTeamwork和本地电脑都做好备份

> 在CGteamwork上，一般在工程文件对应的文件夹目录下，新建一个“history”文件夹，在里面放置备份文件即可。

## 不要引用同一个绑定文件

在同一个场景文件下，如果你要同时引用同一个绑定文件A1，那请将A1复制多一份为A2，再分别引用A1和A2。

> 这样可以避免前缀重名的情况，在后面的渲染才不会对应不上相应的文件。

比如你需要在你的场景里引用多个积木，但只有一个积木文件A，那你需要把文件A复制为A1、A2、A3……，然后分别引用A、A1、A2、A3……

![&#x5C06;&#x540C;&#x4E2A;&#x7ED1;&#x5B9A;&#x6587;&#x4EF6;&#x590D;&#x5236;&#x6210;&#x591A;&#x4E2A;&#x6587;&#x4EF6;](.gitbook/assets/yin-yong-tong-ge-bang-ding-wen-jian-1.png)

![&#x5206;&#x522B;&#x5F15;&#x7528;&#x591A;&#x4E2A;&#x6587;&#x4EF6;&#xFF0C;&#x4F7F;&#x524D;&#x7F00;&#x4E0D;&#x540C;](.gitbook/assets/yin-yong-tong-ge-bang-ding-wen-jian-2.png)



## 删除引用文件的多余前缀

二次引用转import后、或一次引用时，文件名前有时会有多余的前缀，可以在namspace edits 窗口里删除掉 。确保最后只留下 root 层级的前缀

> 如果有多余前缀，后期渲染时会出现名称不对应，导致出错~

![&#x5220;&#x9664;&#x5F15;&#x7528;&#x6587;&#x4EF6;&#x7684;&#x591A;&#x4F59;&#x524D;&#x7F00;](.gitbook/assets/shan-chu-duo-yu-qian-zhui.png)



## 引用文件时务必将前缀也引用上



















