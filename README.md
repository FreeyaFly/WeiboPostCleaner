# WeiboPostCleaner
[Javascript] Browser-side automation script for managing personal Weibo posts via DevTools Console. (deleting all original, sharing and quick-sharing posts) 

[Javascript] 通过浏览器开发者工具控制台管理微博个人主页帖子的自动化脚本（删除所有原创、转发及快转的帖子）

软件环境：windows系统 Google浏览器（其它的也大差不差）

1. 打开微博网页版，进入个人主页。
2. 键盘ctrl+shift+i，调出开发者模式。
3. 点上方console，在最下方蓝色“>”这里粘贴代码。（有可能需要先输入allow pasting，按照提示操作然后再粘代码就行）
4. 粘贴代码之后回车Enter，开始运行。看到 “#数字 已点击确认” 就是在正常运行。
5. 如果想要停止可以直接粘贴 __WB_DEL_STOP = true ，然后回车Enter即可停止。
