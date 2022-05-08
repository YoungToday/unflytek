# 华为平板C5（BZT-W09）科大定制系统破解方法
本教程要求你有一定的动手能力。

**破解平板会清空所有数据！**

## Before Entering

感谢[@xtuiflyzhkt](https://github.com/xtuiflyzhkt)。

你需要准备以下工具：

- 剪刀，或者镊子，实在没有的话回形针也能凑合，反正导电就行
- 一张Micro SD卡，如果你不知道那是什么，按着这幅图去找一张
- ![mirocsd](https://user-images.githubusercontent.com/74454693/166671135-48e70eef-7453-479a-a465-8b2ff6437f30.png)
- 一块华为平板C5，对没错就是你要破解的那台
- 一台电脑，最好是Windows，如果你不知道什么是Windows，建议找别人帮你破解平板

## Step 1: 拆机
在你的平板侧面，屏幕和外壳间，有两条肉眼可见的分隔。

首先轻轻用力弯折你的平板，如下图所示，这两条分隔会稍微变大一些

用指甲、小刀或者别的什么卡进靠外壳的那一条缝隙，注意千万不要用力，否则有可能损坏屏幕。

现在你需要轻轻沿着缝隙划过，你应该听到清脆的塑料卡扣脱离声，如果没有，检查你捅进去的缝隙是不是靠近外壳的那一条。

随着最后一个塑料卡扣脱离，你现在应当能够卸下屏幕，注意不要用力扯，会拉断屏幕和主板间的排线。

是时候进行下一步了。

## Step 2: 安装软件
打开你的电脑，下载一个软件并双击安装：
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/HiSuite_11.0.0.610_OVE.exe>

这个软件我相信不需要教程。

再从下面的两个网址下载两个压缩包并解压到合适的文件夹下，通常解压到桌面即可：
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/Huawei.drivers.testpoint.rar>
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/PotatoNV-next-v2.2.1_2022.03-x86.zip>

打开你解压的`Huawei drivers testpoint`文件夹  
![Huawei drivers testpoint](https://user-images.githubusercontent.com/74454693/166671707-5be5caaf-93d6-4e78-bcac-649f1d19390a.png)

当中应该有下列文件：  
![图片](https://user-images.githubusercontent.com/74454693/166671782-285b502a-6914-4d85-a6ae-4866ba48edd4.png)

你应该双击`DriverSetup.exe`并在接下来的用户账户控制提示中按`是`：  
![图片](https://user-images.githubusercontent.com/74454693/166672249-ab4bb695-1594-41a8-a78e-f8a0c5c7a415.png)

等待一会儿，安装完成后你会看到任务栏上有一个图标，点击它  
![图片](https://user-images.githubusercontent.com/74454693/166672467-9949cd62-ab95-48de-8b1c-c5233f15eeaf.png)

然后按确定  
![图片](https://user-images.githubusercontent.com/74454693/166672538-f9716e95-9541-4936-84db-c6fb059cd221.png)

## Step 3: 短接和解锁Bootloader
打开这个文件夹  
![图片](https://user-images.githubusercontent.com/74454693/166672785-982dac3c-35da-4487-a7bf-c5ae48a6fb14.png)

打开其中的`PotatoNV-next.exe`  
![图片](https://user-images.githubusercontent.com/74454693/166672827-899b7fbb-dbb9-40b6-bb04-0c392496b917.png)  
![图片](https://user-images.githubusercontent.com/74454693/166673284-63c83e32-4bb4-4a55-8d0a-59a615fb746c.png)

先把平板关机，接着掀起你的平板屏幕，你会看着密密麻麻的电路板：  
![图片](https://user-images.githubusercontent.com/74454693/166672927-0197d79b-6bb8-4547-a47c-b2993b0801f5.png)

找到这个金属触点：  
![图片](https://user-images.githubusercontent.com/74454693/166672971-df733251-c457-4b18-a4ec-e988d6e683b0.png)

把它和旁边的金属屏蔽罩用剪刀或者镊子连接，使其形成通路，如图：  
![图片](https://user-images.githubusercontent.com/74454693/166673129-34b696ad-6d9d-4f8c-b638-9671e621c4f7.png)

不要松手，把USB线一头插到平板，另一头插电脑，你应该看到窗口中发生变化：  
![图片](https://user-images.githubusercontent.com/74454693/166673448-2d10f0e1-c17d-4336-9ce9-01ec7eb44e12.png)

这是示例图片，实际显示可能不同。

如果`Bootloader`下面显示
![图片](https://user-images.githubusercontent.com/74454693/167281689-096d7978-1063-4c2a-8d6a-3af2e1948a77.png)
的不是`Kirin 65x(A)`，请手动更改成`Kirin 65x(A)`。  

接着按`Start!`，程序会运行，不超过一分钟，程序界面上的文本框里会显示出一串随机排列的字母数字，复制它。  
![图片](https://user-images.githubusercontent.com/74454693/167281702-ca8e1e3c-363f-471e-8a74-1a1ea1f88680.png)

然后从下面的链接下载一个压缩包，也解压到桌面：
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/bootloader_unlock.rar>

打开解压完成的文件夹，右键单击`unlock.bat`：  
![图片](https://user-images.githubusercontent.com/74454693/166674581-82b6cef7-e5d8-49b8-ad57-34a4c0f4be7d.png)

选择`编辑`，把`UUUUUUUUUUUUU`改成刚刚你复制的一串字母数字，保存文件：  
![图片](https://user-images.githubusercontent.com/74454693/166674750-19ae9ba4-7850-4aa6-bcde-3a818f4350fd.png)

接着双击运行`unlock.bat`，如果平板屏幕上没有显示这样的内容，回到本步骤开头重来一遍，不过你要记住，程序重新生成的一串随机字母数字将会显示到文本框最底部，你要手动滚动到最下面。  
![图片](https://user-images.githubusercontent.com/74454693/166675152-51528e98-ff4e-452f-8308-0ea707341024.png)

你需要用音量键调整，使`Yes`变成红色，然后按下电源键，平板会自动解锁Bootloader，接着会重启并恢复出厂设置，但由于科大定制的系统阉割了部分功能，会提示恢复失败。

然后我们就可以刷入TWRP了。 

## Step 4: 刷入TWRP

拿出你的Micro SD卡，插上电脑，从下面这几个链接下载文件并复制到SD卡里，最好放在根目录上：
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/swcy>

然后把平板的SD卡槽用取卡针取出，把SD卡插入。

接着，把USB线插入平板，从下面的链接下载一个压缩包并解压到电脑桌面上：
- <https://github.com/sora-orz/unflytek/releases/download/v1.0.0/recovery_flash.rar>

按住平板的音量减和电源按键，当平板振动重启时，松开电源键，看到屏幕上出现一个机器人时，松开音量减键。

双击运行文件夹中的`flash.bat`，稍等完成。

接下来就是破解平板了。

## Step 5: 破解

拔下平板上的USB线，按住音量加和电源键，当平板振动重启，松开电源键，看到屏幕上出现`奇兔刷机`LOGO时，松开音量加键。

将SD卡插入卡槽，然后挂载SD卡和system分区。  
![图片](https://user-images.githubusercontent.com/74454693/167282313-e80cb671-433f-4eb7-b299-0e77d7162078.gif)

接着进入`高级`>`终端命令`，输入`cd extern_sdcard`，此处有个小技巧，只输入`cd ex`然后按`tab`就能自动补全命令。  
接着输入`./swcy`，命令会很快执行完成。  
![图片](https://user-images.githubusercontent.com/74454693/167282542-2e7c6768-9c0b-4c81-87eb-33a756f40278.gif)

回到主界面，重启到系统即可。

至此破解完成！
