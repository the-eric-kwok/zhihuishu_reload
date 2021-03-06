主要功能：

1. 智慧树共享课自动跳过题目
2. 智慧树共享课自动播放下一个视频
3. 智慧树共享课自动播放未完成的视频
4. 智慧树共享课自动1.5x倍率、自动静音、自动标清
5. 智慧树答题页面解除复制封印
6. 考试、答题时点击题目可一键复制到剪贴板
6. 提供了友好的配置界面

本脚本更适合刷课用，因为它只用于自动播放那些没有打对号（没播放成100%）的视频

预览截图：

![3D10B60C-88EC-4639-A50B-118327363C8F.jpeg](https://i.loli.net/2021/07/05/DZlFtGw43aVA8sq.jpg)

![DE7B30E4-5374-4A2C-BCB9-3A7ADC439E4B.png](https://i.loli.net/2021/07/05/evQy9ZYo4Ft5zKh.png)

GitHub 链接为 [https://github.com/the-eric-kwok/zhihuishu_reload](https://github.com/the-eric-kwok/zhihuishu_reload)，欢迎来 Star 或者提 issue 😁

感谢原作者 C选项_沉默，本脚本是对他的作品的改进和增强。由于原作者已删除脚本，原作品链接因此被移除。

本项目依赖一个外部库：[GM_config](https://codechina.csdn.net/-/snippets/198/raw/master/GM_config.js)，因 GreasyFork 访问速度太慢，故复制了一份托管与国内网站 codechina.csdn.net
觉得官方库导致设置面板打开速度太慢的童鞋们可以自行修改代码
```
- // @require      https://greasyfork.org/scripts/28536-gm-config/code/GM_config.js
+ // @require      https://codechina.csdn.net/-/snippets/198/raw/master/GM_config.js
```

**此外项目中亦提供了不依赖于 GM_config 的版本，即 [No\_GM\_config.js](https://raw.githubusercontent.com/the-eric-kwok/zhihuishu_reload/main/No\_GM\_config.js) ，经测试可以用于：**
- 安卓 Via 浏览器脚本中。如图所示配置即可![](https://i.loli.net/2021/07/05/4lyFNrkdQxKUc9P.jpg)
- iOS Alook 浏览器。配置为被动脚本，匹配域名为 `studyh5.zhihuishu.com@@onlineexamh5new.zhihuishu.com`，并且应禁用视频悬窗功能并允许「设置-通用设置」中的自动弹出式窗口。如：![](https://i.loli.net/2021/07/05/nGWuJimqzKLTDsF.jpg)
