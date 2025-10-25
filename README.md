# FolderJump v1.03

这是一款帮你解决日常"最近"问题的办公效率工具：

This is an office efficiency tool that helps you solve your daily "recent" problems (Pay/Free):

- 简洁漂亮的用户界面。

  Simple and beautiful program UI.

- 免安装（绿色版）、无联网、免管理员权限、不搜集用户隐私信息。

  No installation required (Portable), no Internet connection, no administrator privileges, no collection of user privacy information.

- 自动记录打开过的文件夹、文件：支持快速打开、合并文件夹、复制路径、快速搜索。

  Auto record the recently visited folders and files: Quickly open,  merge folders, copy paths, and quick search for files/folders.

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



# 软件界面 (GUI)

![Menu](Menu.png)

![About](About.png)

![Contact](Contact.png)

![Settings](Settings.png)

![Menu_EN](Menu_EN.png)

![About_EN](About_EN.png)

![Contact_EN](Contact_EN.png)

![Settings_EN](Settings_EN.png)





# 功能介绍 (Features)

下面的演示中是使用了第三方的鼠标手势去触发FolderJump弹出界面的快捷键。

In the following demonstration, a third-party mouse gesture is used to trigger the shortcut key for the FolderJump pop-up interface

## 1. 近期记录 (Recent History)

- 自动记录打开过的文件夹

  Auto record the opened folder

- 自动记录打开过的文件（默认记录双击打开的文件；如果打开Windows的"最近访问"功能，则可以跟踪更多文件打开行为）

  Auto record the opened file (By default, the file opened by double-clicking is recorded. If you enable the "Recent" feature in Windows, you can track more file opening behaviors.)

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



- 其他快捷键说明：

  Other shortcut key instructions:

  - 切换文件平铺和文件树模式：按下'f'。

    Toggle between Flat or Tree View modes: Press 'f'.

  - 关闭、滚动弹出、右键弹出右侧平铺或文件树窗口：按下'r'.

    Close, wheelup/down-pop or right-button-pop the right Flat or Tree View window: Press 'r'

  - 打开最近3个文件夹：按下'b'。

    Open the last 3 folders: Press 'b'.

  - 切到当前窗口的搜索栏：按下'Tab'。

    Focus on the search bar of the current window: Press 'Tab'.



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

Display the currently open folders and the hierarchical relationships among them.

已经支持的资源管理器如下，可以在"设置"界面配置。

- OFF：关闭跳转树。

- Explorer：Win10、Win11不支持多标签的情况。

- Explorer+Tab：Win11且支持多标签的情况。

  > Win11多标签原生支持有限，暂未找到完整的控制方法，所以功能上仅支持跳转和关闭所有窗口。

- QTTabBar：已安装QTTabBar插件的情况。

- XYplorer：已把 XYplorer 配置成系统默认资源管理器的情况。

- D-Opus：不支持。

![JumpTree](JumpTree.png)

**功能展示：**

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

该功能依赖于Everything的搜索引擎，请先安装Everything并让它在后台运行。

This function relies on the search engine of Everything，please install Everything and make sure it's running.

**语法关键字符(Grammar key character):**

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



# 快捷键 (Shortcut)

**默认快捷键如下：**

- 弹出主面板：Ctrl + Alt + 空格。
- 置顶窗口：Ctrl +  t。
- 同类程序窗口切换：Ctrl + 空格
- 重命名窗口标题：Ctrl +  F2

**快捷键修改方法：**

请到软件的 "设置" 界面里先删除对应快捷键、然后录入想要的快捷键、最后保存。如果"设置"里无法正常录入新的快捷键，一般是快捷键已经被其它软件占用。

  方法1：先取消其它软件对快捷键的暂用。

  方法2：退出软件后修改软件包下的Setttings.ini文件，修改完再启动软件。例如：

  ```ini
  HotkeyPop=^!Space 
  ```

  语法规则: 

  - `^`: 表示Ctrl
  - `+`: 表示Shift
  - `!`: 表示Alt
  - `#`: 表示Win
  - `MButton`：鼠标中键。
  - 其它按键：原本的含义。

  例如：

  - `^+1`: Ctrl + Shift + 1
  - `^!z`: Ctrl + Alt + z
  - `!Space`：Alt + 空格
  - `+c`：Shift + c

- 功能的快捷键也是一样的修改方法，只是Settings.ini里选项名字不同而已。



# 联系方式 (Contact)

- Email: folderjump@gmail.com
- QQ: 297010976
- QQ Group: 758125907