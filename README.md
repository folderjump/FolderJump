# FolderJump v1.02

这是一款帮你解决日常"最近"问题的办公效率工具（付费/免费）：

This is an office efficiency tool that helps you solve your daily "recent" problems (Pay/Free):

- 简洁漂亮的用户界面。

  Simple and beautiful program UI.

- 免安装（绿色版）、无联网、免管理员权限、不搜集用户隐私信息。

  No installation required (Portable), no Internet connection, no administrator privileges, no collection of user privacy information.

- 快速打开最近访问过的文件夹和文件、合并文件夹、复制路径、快速搜索。

  Quickly open recently visited folders and files, merge folders, copy paths, and quick search for files/folders.

- "保存"、"另存为" 等各类对话框的文件夹快速跳转。

  Quick swtich to folders in various dialog boxes such as "Save" and "Save As".

- 窗口增强：置顶、移动、调整大小、最大化、重命名、同类窗口切换。

  Window Enhancements: Pin, Move, Resize, Maximize, Rename, Windows switch between the same program.

- 资源管理器增强：跳转树快捷导航。

  Resource Manager Enhancement: Quick navigation through JumpTree.

- 结合Everything 进行全局搜索。

  Global search in combination with Everything.



# 系统环境 (System)

- Win10、Win11
- Explorer、Explorer+QtTabBar、XYplorer
- Language: 中文、English



# 软件界面 (Program UI)

![Menu](Menu.png)

![About](About.png)

![Contact](Contact.png)

![Settings](Settings.png)

![Menu_EN](Menu_EN.png)

![About_EN](About_EN.png)

![Contact_EN](Contact_EN.png)

![Settings_EN](Settings_EN.png)



# 软件功能 (Program Feature)

下面的演示中我是使用第三方的鼠标手势触发FolderJump弹出界面的快捷键。

In the following demonstration, a third-party mouse gesture is used to trigger the shortcut key for the FolderJump pop-up interface


## 1. 近期记录 (Recent History)

- 自动记录打开过的文件夹

  Auto record the opened folder

- 自动记录打开过的文件（如果打开Windows的"最近访问"功能，则可以跟踪更多文件打开行为）

  Auto record the opened file (If you enable the "Recent" feature in Windows, you can track more file opening behaviors.)

![0-0](0-0.gif)

- 搜索历史记录: 在全路径中进行关键词匹配

  Search folder/file history: match keyword in full path.

![0-1](0-1.gif)

- 滚动时自动显示路径

  Auto show path when wheel up/down

- 鼠标悬停时显示路径

  Auto show path which is under the cursor

- 点击'[+]'翻页

  Click '[+]' to the next page

- 右击'[+]'回到主页

  Right Click '[+]' back to Home page

- 双击打开路径

  Double click to open path

- 复制路径: 按下'c'

  Copy path: press 'c'

- 删除路径：按下'd'

  Delete path：press 'd'

![0-01](0-01.gif)

- 多选模式：按下 'RAlt'，再进行复制、删除、打开...

  Mulitple selection mode: press 'RAlt', then you can: copy, delete, open ...

![0-02](0-02.gif)

- 路径置顶或取消：鼠标中键

  Toggle item always-on-top: MButton

- 主面板置顶或取消：鼠标中键点击logo图标

  Toggle main panel always-on-top: MButton on logo icon

- 主面板和收藏夹切换：单击logo图标

  Toggle main panel and favoriate panel: click logo icon

- 路径加入到收藏夹：按下 'a'

  Add item to favoriate panel: press 'a'

- 收藏夹下的路径删除：按下 'd'

  Delete item from favoriate panel: press 'd'

![0-2](0-2.gif)

- 路径分组：一个分组可包含多个路径。最多可设置3个分组: 按下 'g'

  Folder Group: contains multiple path. Up to 3 groups are supported : press 'g'

![0-3](0-3.gif)

- 展开当前目录：平铺或文件树：右键。

  Expand target folder: Flat or Tree View. Use Right Button

![0-4](0-4.gif)

- 粘贴文件到文件夹内: ctrl+v或拖拽

  Paste file to the folder: ctrl+v or drag

![0-5](0-5.gif)

- 双击条目：打开对应文件

  Double click: open the file

- 右击条目：打开对应文件所有在的文件夹

  Right click: open the folder where this file is

- 搜索历史记录: 在全路径中进行关键词匹配

  Search folder/file history: match keyword in full path

- 从列表中清除不存在的文件: 无效文件图标的显示为红色的'x'

  Remove non-existent files from the list: which icon is displayed as a red 'X'

![1-1](1-1.gif)

- 复制路径: 按下'c'

  Copy path: press 'c'

- 删除路径：按下'd'

  Delete path：press 'd'

- 复制文件: 按下'ctrl+c'

  Copy file: press 'ctrl+c'

- 导入文件到列表中：ctrl+v或拖拽

  Add item to the list: ctrl+v or drag

![1-2](1-2.gif)

- 打开文件或文件夹：双击。

  Open file or folder: Double click

- 复制路径：按下'c'

  Copy path: press 'c'

- 复制文件：按下'ctrl+c'

  Copy file: press 'ctrl+c'

- 粘贴文件到父目录：按下'ctrl+v'

  Paste file to parent folder: press 'ctrl+v'

- 文件树也支持上面这些操作，不做演示。

  The file tree supports the above operations too, I don't show that again..

![1-3](1-3.gif)

- 搜索：在全路径中进行关键词匹配，显示匹配的文件、文件夹（保留目录层次结构、高亮自己）

  Search: match keyword in full path, Display matching files and folders (keep the directory structure and highlight itself

![1-4](1-4.gif)

- 合并文件夹:  按下'm'。提取所有文件到当前目录，删除空文件夹。

  Merge folders: press 'm'. Move all files from sub folders to the current folder, then delete empty sub folders

![2-3](2-3.gif)

- 强制覆盖文件: 按下'o'。任何拖入/粘贴到目录的文件都会被强制替换成目标文件。

  Forced overwrite file: Press 'o'. Any file dragged/paste into the directory will be forcibly replaced with the target file

  > 例如：D:\Program Files\Git\sample\etc\A_ToBeOverride.png。那么任何被拖入或粘贴到 D:\Program Files\Git\sample\etc\目录的文件都会替换掉A_ToBeOverride.png。
  >
  > (For example: D:\Program Files\Git\sample\etc\A_ToBeOverride.png. Then any file dragged/paste into the D:\Program Files\Git\sample\etc\ directory will replace A_ToBeOverride.png)

![2-4](2-4.gif)



## 2. 快速切换 (Quick Switch)

- 自动吸附目标窗口，最近一次访问的文件夹用 '红圈+打勾' 表示。

  Automatically tracking the target window. The folder of the last visit is indicated by a 'red circle + checkmark'

- 快捷键'Alt'：导入最近一次访问的路径

  Shortcut Key 'Alt' : Switch to the path of the last visit

- 支持所有历史条目、支持搜索结果、支持树形结构对话框

  supports all history items, search results and tree structure dialog boxtree.

![1-5](1-5.gif)

- 如果使用了平铺或文件树窗口：选中文件时自动转换为所在目录的路径。

  For flat or tree View: If a file is selected, it will be converted to the path of the directory where it is located

![1-6](1-6.gif)



## 3. 跳转树 (Jump Tree)

显示正打开的文件夹、它们之间的层次关系。

Display the currently open folders and the hierarchical relationships among them

- 使用资源管理器时会自动弹出；不使用时自动隐藏。

  It will pop up automatically when using the Resource Manager.Automatically hide when not in use)

- 高亮图标：当前所在的窗口。

  Highlight: The current window.

- 单击图标：跳转到对应的文件夹。

  Click the icon: Jump to the corresponding folder.

- 图标1：显示或隐藏窗口。

  Icon1: Show or hide the window

![1-7](1-7.gif)

- 图标2：合并所有窗口：(仅支持Qttabbar)

  Icon2: Merge All Windows: (Only supports Qttabbar)

- 右击图标：关闭对应的文件夹。

  Right-click the icon: Close the corresponding folder

- 图标3：关闭其它窗口。

  Icon3: Close other Windows

![1-7-1](1-7-1.gif)

- 图标4：关闭所有窗口。

  Icon4: Close all Windows.

- 主界面显示跳转树

  Main panel shows JumpTree and go to it

![1-8](1-8.gif)



## 4. 窗口增强 (Window Enhance)

- 选中某个文件夹 --> 按下'Tab': 展开选中的文件夹

  Select a folder --> press 'Tab': Expand the selected folder tree

- 未选中任何文件夹 --> 按下Tab: 展开当前整个目录

  Not select any folder --> press 'Tab': Expand current directory tree

![2-0](2-0.gif)

- 单击Esc正下方那个按键: 从前一级开始展开目录

  Press the key under Esc: Expand the parent-parent folder tree

- 双击Esc正下方那个按键 : 从前二级开始展开目录

  Double Press the key under Esc: Expand the parent-parent folder tree

![2-1](2-1.gif)

> Caps 指的是大写锁定键，即字母A左边那个CapsLock按键。
>  ("Caps" refers to the uppercase lock key, which is at the left of the letter "A")

- Caps + 左键拖动：移动目标窗口。

  Caps + Left Button drag: Move the window

- Caps + 右键拖动：调整目标窗口大小。

  Caps + Right Button and drag: Resize the window

- Caps + 左键双击：对窗口进行置顶或取消置顶目。（或快捷Ctrl + T）

  Caps + Double click: Toggle window always-on-top. (Or the shortcut Ctrl + T

- Caps + 中键：对窗口最大化或恢复大小。

  Caps + Middle Button: Maximize or restore the window size
  

![1-9](1-9.gif)

- 窗口切换：在同类程序的多个窗口之间快速切换。快捷键Ctrl+空格。

  Window switching: Quickly switch between multiple Windows of the same type of program.The shortcut key is Ctrl+ Space.


- 窗口重命名：修改窗口标题栏的名字，快捷键Ctrl+F2。

  Window renaming: Modify the name of the window title bar, Shortcut key: Ctrl+F2. 

![1-10](1-10.gif)



## 5. 全局搜索 (Global Search)

该功能依赖于Everything的搜索引擎

This function relies on the search engine of Everything

语法关键字符(Grammar key character):
1. ";" : 切到everything搜索 (Switch to everything to search)
2. "\\" : 匹配路径关键词，否则匹配文件名关键词 (try to match the keyword in search path, otherwise try to match the keyword in the file name)

- 全局搜索文件夹(global search folder): `D:\Program Files\Git\etc\pkcs11`

  > 搜索词(keyword): pkcs11; \prog \etc

- 全局搜索文件(global search file): `D:\Program Files\Git\etc\pkcs11\pkcs11.conf.example.txt`

  > 搜索词(keyword): pkcs11 examp; \prog txt

![0-6](0-6.gif)

- 快速跳转(Quick switch): `D:\Program Files\Git\etc\pkcs11`

  > 搜索词(keyword): pkcs11; \prog \etc

![0-7](0-7.gif)



# 免费 (Free)

免费版的功能有限，支持的最多条目数量和次数具体如下：

The free version has limited functions. The maximum number and frequency of supported entries are as follows:

- 不支持数据保存，软件重启后数据自动清零。

  Data saving is not supported. Data will be automatically reset to zero after the software restarts.

- 最近打开的文件夹数量：12。

  Number of recently opened folders: 12.

- 最近打开的文件夹置顶数量：3。

  The number of recently opened folders pinned to the top: 3.

- 最近打开的文件数量：10。

  Number of recently opened files: 10.

- 对话框快捷跳转数量：8。

  Number of quick switch in the dialog box: 8.

- 跳转树的跳转次数：60。

  The number of jumps in the jump tree: 60.

- 相同程序快捷切换次数：30。

  Quick switch times for the same program: 30.

- 任意窗口置顶次数：15。

  The number of times any window is pinned to the top: 15.

- Everything 全局搜索：仅支持预览结果。

  Everything Global Search: Only supports preview results.

- 文件夹图标样式只有一种。

  There is only one style for folder ICONS.

说明：超出限制范围的操作不会有任何效果，次数用完后您重启软件即可重新获得使用次数。

Note：Operations outside the restricted range will have no effect. After the usage limit is used up, you can restart the software to regain the usage limit.

免费版 (free version)：

- 登录名(login name)：folderjump；
- 登录邮箱(login email)：folderjump@gmail.com。



# 付费 (Pay)

- 买断制：一次购买支持永久升级和使用。一个激活码仅激活一台计算机，任意数量购买。

  Lifetime: One-time purchase for permanent upgrade and use. One License can only activate one computer

- 价格：1个激活码15.6元。(少喝1杯奶茶/咖啡，您就可永久获得这款效率软件)

  Price: 15.6 RMB per one License. If you drink one less cup of milk tea or coffee, you can permanently get this efficiency software.

- 优惠：2个85折、3个或以上75折。(价格四舍五入)

  Offer: 15% off for 2 items and 25% off for 3 or more items.(Prices are rounded off)

- 激活/反激活：由于本软件完全离线的特殊性，所以目前一个激活码终生仅提供1次激活码服务，并且需要购买一年后才可以申请，请通过邮件方式联系我。

  Activation/deactivation: Due to the special nature of this software being completely offline, currently, each License only provides one time service for life, and it can only be applied for one year after purchase. Please contact me via email.

- 请务必充分试用免费版后再购买！非软件自身问题不支持退款。

  Please be sure to fully try the free version before purchasing!Refunds are not supported for issues not related to the software itself.



# 购买流程 (Purchase process)

- 购买流程：

  1. 找到右下角托盘，软件图标右键菜单选择： "购买/激活" 。

     Locate the tray at the lower right corner, right-click the software icon and select "Purchase/Activate" from the menu.

  2. 填写注册信息后生成申请码。

     After filling in the registration information, an request license code will be generated.

  3. 付费、再把激活码和付款截图发送到邮箱：folderjump@gmail.com。

     Pay and then send the License and payment screenshot to email: folderjump@gmail.com.

  4. 我会通过邮件发送激活码+正式版软件。

     I will send the License and the official version of the software by email.

  5. 找到右下角托盘，软件图标右键菜单选择："购买/激活"，再导入激活码。

     Locate the tray at the lower right corner, right-click the software icon and select "Purchase/Activate" from the menu, then import the License.

  6. 启动软件后登录使用。

     Start the software and login to use.

- 不确定软件是否受欢迎，目前没有正式的付费通道，有兴趣额的朋友请通过右键或QQ联系我。

  I'm not sure if the software is popular. Currently, there is no official paid channel. If you are interested, please contact me by right-clicking or via QQ.

- 目前付费版本的软件不提供公开下载（避免网上版本混乱），付费后会和激活码一起发送。

  Currently, the paid version of the software is not available for public download (to avoid confusion of online versions). After payment, it will be sent together with the activation code.



# 联系 (Contact)

- Email: folderjump@gmail.com
- QQ: 297010976
- QQ Group: 758125907
