# 从源站安装workflow后不生效？
请打开debug
我从debug中发现了源代码是基于 python2的，但是我mac上是python3，有语法不兼容，因此改写了源文件：


## 第一步
找到源文件路径：
/Users/xxx/Library/Application Support/Alfred/Alfred.alfredpreferences/workflows/user.workflow.711D21CD-B558-4BDA-B597-3154D4E398E9
下面有三个 .py 文件，替换我仓库中最新的代码
alfred.py        chrome.py        docopt.py
我都已经上传到gitHub上了。
## 第二步
双击 woekFlow 后，修改脚本如下：
<img width="971" alt="image" src="https://github.com/user-attachments/assets/342a822f-4bff-4fc9-9857-b209eb14b214" />
