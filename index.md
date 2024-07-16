# 这是什么？
这是一个测试仓库，用来测试 Github 的在线笔记功能。

你也可以在github上新建一个**存储库**用来保存你自己的 markdown 笔记，并通过 [github.dev](https://github.dev/) 在任何浏览器访问你的**存储库**

## 步骤如下
### 先决条件
* 在电脑上下载安装 [**Git**](https://git-scm.com/) ，学习 [Git 的使用](https://www.runoob.com/git/git-tutorial.html)。 

* [**新建**](https://www.runoob.com/git/git-create-repository.html)存储库并推送到自己的 Github 。 

* 在自己的手机和平板上安装并登录 **Github APP** [[iOS](https://apps.apple.com/us/app/github/id1477376905?l=zh)] [[Android](https://www.bing.com/search?q=github+android+apk&qs=UT&pq=github+android+&sk=MQT1UT3CT1&sc=10-15&cvid=AE6F19B44ED441659115477A915A871C&FORM=QBRE&sp=6&ghc=1&lq=0)]。 * **（注意 Github APP 只能查看不能编辑）**

* 在自己的手机和平板上使用 Edge 登录 [github.dev](https://github.dev/)（使用自己的 Github 账号即可）这是一个基于 VSCode 开发的完全在浏览器中运行的代码编辑器。这允许你直接在浏览器查看和编辑 Github 存储库。* *（通常来说在移动设备上这样的编辑体验会更好，但这需要可靠的互联网连接，在没有上传进度前离开浏览器很可能让你丢失所有进度。）*

* 在自己的手机上安装 [**MGit**](https://f-droid.org/packages/com.manichord.mgit/) ，作为 Android 平台上的 **Git** 替代品，可以方便的查看和编辑存储库。 

* 在自己的手机上安装 [**MarkdownX**](https://github.com/Ryeeeeee/MarkdownX) 作为 Android 平台上的 Markdown 编辑器。

* 在自己的 iPad 上安装 [**Code APP**](https://thebaselab.com/code/) 作为 iPad 平台上 VSCode 和 Git 的替代品。

### 如何使用笔记

#### 自己的电脑

* 首先通过VSCode打开存储库文件夹

* 使用`git pull`确保本地笔记是最新的，然后即可使用 **VSCode** 编辑笔记内容。可以自由新建和删除文件夹和 markdown 文件。

* 使用`git add .`添加所有修改到暂存区，然后使用`git commit -m "注释内容"`提交修改到本地存储库，确认无误后使用`git push`推送到 Github 。

#### 自己的手机

* 如果是第一次使用，需要从 Github **克隆远程存储库**到本地。

* 使用 **MGit** 拉取远程更新，确保本地笔记是最新的，然后可以自由新建和删除文件夹和 markdown 文件，使用 **MarkdownX** 编辑笔记内容。

* 使用 **MGit** 将修改推送到 Github 。


* *如果有互联网连接，只需要查看不需要编辑，可以直接使用 **Github APP** 查看笔记内容。不需要单独拉取更新，更为方便。*

* *如果有互联网连接，也可以使用 [github.dev](https://github.dev/) 查看和编辑笔记内容。不需要单独拉取更新，更为方便。但不像 MarkdownX 一样有方便的样式选择器，如果没有带键盘编辑起来不是很方便。*

#### 自己的 iPad

* **Code APP** 由 [thebaselab](https://thebaselab.com/) 开发，界面与操作逻辑与 VSCode 十分相似，是其在 iPad 平台上的替代品，可以方便的查看和编辑存储库。

* 如果是第一次使用，需要从 Github **克隆远程存储库**到本地。

* 使用 **Code APP** 拉取远程更新，确保本地笔记是最新的，然后可以自由新建和删除文件夹和 markdown 文件。直接编辑笔记内容。

* 使用 **Code APP** 将修改推送到 Github 。

* *如果有互联网连接，只需要查看不需要编辑，可以直接使用 **Github APP** 查看笔记内容。不需要单独拉取更新，更为方便。*

* *如果有互联网连接，也可以使用 [github.dev](https://github.dev/) 查看和编辑笔记内容。不需要单独拉取更新，更为方便。与 Code APP 相比各有千秋，请实际使用后作出判断。*
## 注意事项
* 请尽量保持本地和远程存储库的一致性，在一端推送提交前不要在其他终端编辑笔记，避免出现冲突。

* 如果在编辑过程中出现意外情况导致笔记丢失，请在电脑上使用`git reset --hard`恢复到最新版本，然后使用`git push -f`强制推送，覆盖远程存储库。

* 虽然 MarkdownX 专门对触屏设备进行了设计优化，但 Code App 和 [github.dev](https://github.dev/) 的设计初衷是在有物理键盘的设备上使用。通过屏幕键盘进行编辑的体验可能不尽人意。如果你打算在移动设备上使用，请记得带上你的键盘。

* 存储库不仅可以用来保存笔记，也可以用来保存其他任何文件，这意味着你可以直接将图片甚至源代码文件保存到存储库中，并在笔记中引用它们。也可以不用导出直接在 VSCode，Code APP，[github.dev](https://github.dev/) 中近乎完美的编辑和运行。

* 如果你已经熟练了 Git 的使用，也可以尝试直接使用 VSCode 的 Github 插件代替 Git，这样你就可以直接在 VSCode 中拉取和提交，而无需使用命令行。

* 如果你在使用过程中遇到任何问题，请随时联系我。

## 联系方式
* 邮箱：[StevenArai@outlook.com](mailto:StevenArai@outlook.com)
* Github：[@StevenArai](https://github.com/StevenArai)

你看我还能输入KaTex！
```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```