# 从源站安装workflow后不生效？
请打开debug
我从debug中发现了源代码是基于 python2的，但是我mac上是python3，有语法不兼容，因此改写了源文件：

源文件路径：
```/Users/xxx/Library/Application Support/Alfred/Alfred.alfredpreferences/workflows/user.workflow.711D21CD-B558-4BDA-B597-3154D4E398E9

## 第一步
需要改写三个文件
alfred.py        chrome.py        docopt.py
我都已经上传到gitHub上了。
## 第二步
双击 woekFlow 后，修改脚本如下：
<img width="962" alt="image" src="https://github.com/user-attachments/assets/fb320fbb-4275-445b-b8bc-83b7737c525d" />
