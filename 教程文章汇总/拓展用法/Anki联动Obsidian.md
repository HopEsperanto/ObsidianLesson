---
cards-deck: ObsidianLesson::教程文章汇总
---

#教程 #联动 
## Anki 联动 Obsidian

### Obsidian
安装好插件 [[Flashcards]]
### [[Anki]]
安装好 [[AnkiConnect]] 插件
- 安装步骤
    - Obsidian 端
        - 设置-第三方插件-社区市场插件-点击浏览
        - 搜索 **Flashcards**，安装&启用
    - Anki 端
        - 在菜单栏-工具-插件中**点击获取插件**
        - 在代码中输入 `2055492159`，安装**AnkiConnect**
        - 双击 [[AnkiConnect]] 打开 AnkiConnect 的设置
            - ![](https://raw.githubusercontent.com/HopEsperanto/ob-pic-cloud/main/20230110185056.png)
        - 复制后文字段，点击确定

```
{
	"apiKey": null,
	"apiLogPath": null,
	"ignoreOriginList": [],
	"webBindAddress": "127.0.0.1",
	"webBindPort": 8765,
	"webCorsOrigin": "http://localhost",
	"webCorsOriginList": [
		"http://localhost",
		"app://obsidian.md"
	]
}
```

- 重启 Anki，让 [[AnkiConnect]] 插件生效

