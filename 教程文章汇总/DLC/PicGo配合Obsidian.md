#教程 
### GitHub 图床构建过程
（PS：本文基于 PicGo 官方教程做了一些更新）

1. 拥有一个 GitHub 账号，先登录好

2. 新建一个仓库 ![](https://pic.molunerfinn.com/picgo/docs/create_new_repo.png)
- 记下你取的仓库名。

3. 生成一个token用于PicGo操作你的仓库：
	- 访问： [GithubTokens]( https://github.com/settings/tokens )
	- 然后点击 `Generate new token` , 选择**classic**的那个 ![](https://pic.molunerfinn.com/picgo/docs/generate_new_token.png)
	- 把 repo 的勾打上即可。然后翻到页面最底部，点击 `Generate token` 的绿色按钮生成 token![](https://pic.molunerfinn.com/picgo/docs/generate_new_token.png)
**注意：** 这个 token 生成后只会显示一次！你要把这个 token 复制一下存到其他地方以备以后要用。 ![](https://pic.molunerfinn.com/picgo/docs/copy_token.png)

4. 配置PicGo
- **注意：** 仓库名的格式是 `用户名/仓库`，比如我创建了一个叫做 `test` 的仓库，在 PicGo 里我要设定的仓库名就是 `Molunerfinn/test`。一般我们选择 `main` 分支即可。然后记得点击确定以生效，然后可以点击 `设为默认图床` 来确保上传的图床是 GitHub

![](https://pic.molunerfinn.com/picgo/docs/setup_github.png)

至此配置完毕，已经可以使用了。当你上传的时候，你会发现你的仓库里也会增加新的图片了：![](https://pic.molunerfinn.com/picgo/docs/success.png)

