# VsCode-Keyboard-shortcuts

Keyboard shortcuts for Windows (Windows的键盘快捷键)  
其他系统快捷键可在**aka.ms/vscodekeybindings**(aka.ms/vscodekeybindings)中找到

## General

* `Ctrl+Shift+P,F1`  **显示命令面板** Show Command Palette
* `Ctrl+P` **快速打开** Quick Open, Go to File...
* `Ctrl+Shift+N` **新窗口 打开新的vs** New window/instance  
* `Ctrl+Shift+W` **关闭当前 vs** Close window/instance  
* `Ctrl+,` **打开用户设置** User Settings  测试没作用
* `Ctrl+K Ctrl+S` **打开快捷键列表**Keyboard Shortcuts  

## Basicediting

* `Ctrl+X` **剪切** Cut line (empty selection)  
* `Ctrl+C` **复制** Copy line (empty selection)  
* `Alt+↑ / ↓` **向上/向下移动行** Move line up/down  
* `Shift+Alt+↓/↑` **向上/向下复制行** Copy line up/down  
* `Ctrl+Shift+K` **删除行** Delete line  
* `Ctrl+Enter` **在下面插入行** Insert line below  
* `Ctrl+Shift+Enter` **在上面插入行** Insert line above  
* `Ctrl+Shift+\` **跳到匹配的括号** Jump to matching bracket  
* `Ctrl+ ] / [` **缩进/缩进行** Indent/outdent line  
* `Home / End` **转到行首/行尾** Go to beginning/end of line  
* `Ctrl+Home` **转到文件开头** Go to beginning of file  
* `Ctrl+End` **转到文件末尾** Go to end of file  
* `Ctrl+↑ / ↓` **向上/向下滚动行** Scroll line up/down  
* `Alt+PgUp / PgDn` **向上/向下滚动页面** Scroll page up/down  
* `Ctrl+Shift+**` **折叠区域** Fold (collapse) region  
* `Ctrl+Shift+**` **展开区域** Unfold (uncollapse) region  
* `Ctrl+K Ctrl+**` **折叠所有子区域** Fold (collapse) all subregions  
* `Ctrl+K Ctrl+**` **展开所有子区域** Unfold (uncollapse) all subregions  
* `Ctrl+K Ctrl+0` **折叠所有区域** Fold (collapse) all regions  
* `Ctrl+K Ctrl+J` **展开所有区域** Unfold (uncollapse) all regions  
* `Ctrl+K Ctrl+C` **添加行注释** Add line comment  
* `Ctrl+K Ctrl+U` **删除行注释** Remove line comment  
* `Ctrl+/` **切换行注释** Toggle line comment  
* `Shift+Alt+A` **切换块注释** Toggle block comment  
* `Alt+Z` **切换自动换行** Toggle word wrap  

## Navigation

* `Ctrl+T` **显示所有符号** Show all Symbols  
* `Ctrl+G` **转到行...** Go to Line...  
* `Ctrl+P` **转到文件** Go to File...  
* `Ctrl+Shift+O` **转到符号** Go to Symbol...  
* `Ctrl+Shift+M` **显示问题面板** Show Problems panel  
* `F8` **转到下一个错误或警告** Go to next error or warning  
* `Shift+F8` **转到上一个错误或警告** Go to previous error or warning  
* `Ctrl+Shift+Tab` **导航编辑器组历史记录 在打开的文件之间切换** Navigate editor grouphistory  
* `Alt+← / →` **在打开的文件之间前后切换** Go back/ forward  
* `Ctrl+M` **和 Ctrl+Shift+Tab 功能类似 在打开的文件之间切换** Toggle Tab moves focus

## Search and replace

* `Ctrl+F` **查找** Find  
* `Ctrl+H` **替换** Replace  
* `F3 / Shift+F3` **查找下一个/上一个** Find next/previous  
* `Alt+Enter` **选择查找匹配的所有出现 所有匹配项一起选中** Select all occurences of Find match  
* `Ctrl+D` **将选择添加到下一个查找匹配,相当于 Alt+Enter 的单个选中** Add selection to next Find match  
* `Ctrl+K Ctrl+D` **将最后一个选择移至下一个查找匹配项,类似 F3 / Shift+F3** Move last selection to next Find match  
* `Alt+C/ R / W` **切换区分大小写/正则表达式/整个词 查找时的匹配规则** Toggle case-sensitive/ regex / whole word

## Multi-cursor and selection

* `Alt+Click` **在需要的地方 插入光标,统一操作** Insert cursor  
* `Ctrl+Alt+↑/ ↓` **在上/下插入光标** Insert cursor above/ below  
* `Ctrl+U` **撤消上一个光标操作** Undo last cursor operation  
* `Shift+Alt+I` **在选定的每一行的末尾插入光标** Insert cursor at end of each line selected  
* `Ctrl+L` **选择当前行** Select current line  测试无效
* `Ctrl+Shift+L` **选择当前选择的所有出现 在所有匹配项后面插入光标** Select all occurrences of current selection  
* `Ctrl+F2` **选择当前字的所有出现 相当于 Ctrl+Shift+L** Select all occurrences of current word  
* `Shift+Alt+→` **展开选择 左右分屏** Expand selection  
* `Shift+Alt+←` **缩小选择 左右分屏** Shrink selection  
* `Shift+Alt+(拖动鼠标)` **列（框）选择** Column (box) selection  
* `Ctrl+Shift+Alt+(箭头键)` **列（框）选择 Ctrl+Alt+↑/ ↓** Column (box) selection  
* `Ctrl+Shift+Alt+PgUp/PgDn` **列（框）选择页上/下** Column(box)selection page up/down

## Rich languages editing

* `Ctrl+Space` Trigger suggestion  
* `Ctrl+Shift+Space` Trigger parameter hints  
* `Shift+Alt+F` Format document  
* `Ctrl+K Ctrl+F` Format selection  
* `F12` Go to Definition  
* `Alt+F12` Peek Definition  
* `Ctrl+K F12` Open Definition to the side  
* `Ctrl+.` Quick Fix  
* `Shift+F12` Show References  
* `F2` Rename Symbol  
* `Ctrl+K Ctrl+X` Trim trailing whitespace  
* `Ctrl+K M` Change file language

## Editor management

* `Ctrl+F4,Ctrl+W` **关闭编辑器** Close editor  
* `Ctrl+K F` **关闭文件夹** Close folder  
* `Ctrl+\` **拆分编辑器 当前文件左右分区** Split editor  
* `Ctrl+ 1 / 2 / 3` **聚焦到第1，第2或第3编辑器组** Focus into 1st, 2ndor 3rdeditor group  
* `Ctrl+K Ctrl+←/→` **聚焦到上一个/下一个编辑器组** Focus into previous/nexteditor group  
* `Ctrl+Shift+PgUp/ PgDn` **向左/向右移动编辑器** Move editor left/right  
* `Ctrl+K ←/ →` **移动活动编辑器组** Move active editor group

## File management

* `Ctrl+N` **新文件** New File  
* `Ctrl+O` **资源管理器 打开文件** Open File...  
* `Ctrl+S` **保存** Save  
* `Ctrl+Shift+S` **另存为** Save As...  
* `Ctrl+K S` **全部保存** Save All  
* `Ctrl+F4` **关闭** Close  
* `Ctrl+K Ctrl+W` **关闭所有** Close All  
* `Ctrl+Shift+T` **重新打开关闭的编辑器** Reopen closed editor  
* `Ctrl+K Enter` **保持预览模式编辑器打开** Keep preview mode editor open  
* `Ctrl+Tab` **切换到打开的下一个文件** Open next  
* `Ctrl+Shift+Tab` **导航编辑器组历史记录 在打开的文件之间切换** Open previous  
* `Ctrl+K P` **复制活动文件的路径** Copy path of active file  
* `Ctrl+K R` **显示资源管理器中的活动文件 Ctrl+O选中当前文件** Reveal active file in Explorer  
* `Ctrl+K O` **显示新窗口/实例中的活动文件** Show active file in new window/instance

## Display

* `F11` **切换全屏** Toggle full screen  
* `Shift+Alt+0` **切换编辑器布局 左右分区还是垂直分区** Toggle editor layout(horizontal/vertical)  
* `Ctrl+ =/-` **放大/缩小** Zoom in/out  
* `Ctrl+B` **切换侧栏可见性** Toggle Sidebar visibility  
* `Ctrl+Shift+E` **显示浏览器/切换焦点** Show Explorer / Toggle focus  
* `Ctrl+Shift+F` **显示搜索** Show Search  
* `Ctrl+Shift+G` **显示Git** Show Source Control  
* `Ctrl+Shift+D` **显示调试** Show Debug  
* `Ctrl+Shift+X` **显示扩展** Show Extensions  
* `Ctrl+Shift+H` **替换文件** Replace in files  
* `Ctrl+Shift+J` **切换搜索详细信息** Toggle Search details  
* `Ctrl+Shift+U` **显示输出面板** Show Output panel  
* `Ctrl+Shift+V` **切换Markdown预览** OpenMarkdownpreview  
* `Ctrl+K V` **从旁边打开Markdown预览** Open Markdownpreview to the side  
* `Ctrl+K Z` **当前文件全屏 双Esc退出** Zen Mode(Esc Esc to exit)

## Debug

* `F9` **切换断点** Toggle breakpoint  
* `F5` **开始/继续** Start/Continue  
* `Shift+F5` **停止** Stop  
* `F11 / Shift+F11` **下一步/上一步** Step into/out  
* `F10` **跳过** Step over  
* `Ctrl+K Ctrl+I` **显示悬停** Show hover

## Integrated terminal

* Ctrl + \`  **显示集成终端** Show integrated terminal  
* Ctrl+Shift+\` **创建新终端** Create new terminal  
* `Ctrl+C` **复制选定** Copy selection  
* `Ctrl+V` **粘贴**Paste into active terminal  
* `Ctrl+↑/↓` **向上/向下滚动** Scroll up/down  
* `Shift+PgUp/ PgDn` **向上/向下滚动页面** Scroll page up/down  
* `Ctrl+Home/ End` **滚动到顶部/底部** Scroll to top/bottom  