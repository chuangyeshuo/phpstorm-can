

PhpStorm中的快捷键共分为9大类：
1.编辑相关

    Ctrl + Space  最基本的自动完成提醒功能，提醒内容包括类名，方法名以及变量名。一般情况下输入一个字母后会自动出现含该字母的自动提醒内容。 按上下箭选择，然后回车确认即可。输入的越多，匹配的越完整。该组合键一般被输入法占用，我的更改为Alt + z 组合。使用的情况不多，当上述自动提醒弹出框消失时可以使用该组合调出自动提醒框。
    Ctrl + Shift + Enter 智能完善代码， 如 foreach，你可以输入for，然后上下键选择foreach，不过不是用回车确认，而是使用Ctrl + Shift + Enter确认，此时会自动完善括号等内容。可以尝试其他函数。
    Ctrl + P 函数参数提醒。一般情况输入函数名会自动弹出参数提醒内容，如date()；当提醒消失时可使用该组合键调出提醒。不常用。
    Ctrl + Q 把光标点位到函数上，按该组合键显示该函数的注释内容。注释应采用标准的注释格式：/**这是注释*/。常用。
    Ctrl + mouse over code  按住Ctrl，光标放到某函数上面，可查看到简短的函数介绍。当然，按住Ctrl点击该函数即可定位到该函数的位置，最常用。
    Ctrl + F1 显示错误或警告信息的描述（需要把光标放到错误或警告位置）。不常用，有错误的时候，会有红色波浪提醒。
    Alt + Insert 生成代码段，包括函数或类注释，版权信息，构造方法，抽象方法等，其中函数注释最常用。为函数添加注释的方法：按组合键Alt + Insert—>选择PHPDoc Blocks—>选择需要添加注释的函数—>回车确定—>输入注释内容即可。生成的注释内容可以定制，会在另一篇中介绍。常用。
    Ctrl + O 插入覆盖父类的方法，与组合键Alt + Insert—>选择Overide Motheds功能相同。
    Ctrl + I 实现抽象方法，与组合键Alt + Insert—>选择Implement Motheds功能相同。
    Ctrl + Alt + T 把选中的代码放在if..else..、for、foreach里,或者函数里，或者为选中的代码块添加区域解释（可以折叠该段代码，折叠后只显示解释，便于代码管理）。
    Ctrl + / 以添加“//”的方式添加注释，会添加到光标所在行的最前端。常用。
    Ctrl + Shift + / 以添加“/**/”的方式添加注释，会添加到选中代码段的两端。常用。
    Ctrl + W 增量式的选中当前块，会从光标所在处开始，每按一次，选中代码块增大一个区域。尤其在html中常用。
    Ctrl + Shift + W 与Ctrl +  W对应，减小选中范围。
    Alt + Q 显示包含光标所在位置的标签头。在html中，标签中的内容会很多，导致一个页面不能显示标签头和尾，例如<div class="class1"><form id="form1" action="" method="post">代码</form></div>，按下该组合是会显示出<form id="form1" action="" method="post">，再次点击会显示上层标签头<div class="class1">。用于查看class，id等信息。
    Alt + Enter 显示意图行动。  Show Intention Action。参考：https://www.jetbrains.com/help/phpstorm/2016.2/intention-actions.html
    Ctrl + Alt + L 格式化代码。面对写成一行的代码怎么办，例如if($moon){}else{}，选中，按下该组合键就可以了。格式化后便于阅读。php一般没人会这么写，主要用于js等。
    Ctrl + Alt + I 自动缩进。标准缩进采用四个空格或者按一下Tab键，如果是三个空格，按该组合键后会自动缩进为四个空格。
    Tab / Shift + Tab 手动缩进/反向缩进。常用。
    Ctrl?+?X or Shift?+?Delete 剪切。将当前行或者选择的内容剪切到粘贴板。常用。
    Ctrl?+?C or Ctrl?+?Insert 复制。将当前行或者选择的内容复制到粘贴板。常用。
    Ctrl?+?V?or?Shift?+?Insert 粘贴。从粘贴板粘贴内容到光标处。常用。
    Ctrl?+?Shift?+?V 从粘贴板中选择内容进行粘贴。常用。
    Ctrl?+ D 复制。将当前行或者选择的内容复制到下一行或光标处。常用。
    Ctrl?+ Y 删除光标所在的行。
    Ctrl?+ Shift + J 合成选中代码到一行。格式化代码的反向动作。主要用于js等。
    Shift + Enter 另起一新行。无论光标在行的那个位置。
    Ctrl?+?Shift + U 字符大小写切换。常用。
    Ctrl?+?Shift + ] / [  以区块为单位，从光标处 向后/向前 选择，再次点击增加选择范围。常用。
    Ctrl?+?Delete 删除光标之后的部分单词。
    Ctrl?+?Backspace 删除光标之前的部分单词。
    Ctrl?+?NumPad+/- 折叠/打开代码块，再次点击扩大折叠/打开范围
    Ctrl?+?Shift?+?NumPad+ 打开全部
    Ctrl?+?Shift?+?NumPad- 折叠全部
    Ctrl?+?F4 关闭当前页面

2.搜索/替换

    Ctrl + F 查找。常用。
    F3 查找下一个，结合查找使用
    Shift + F3 查找前一个，结合查找使用
    Ctrl + R 替换。常用。
    Ctrl + Shift + F 在文件中查找。常用。
    Ctrl + Shift + R 在文件中替换。常用。

3.被使用搜索

    Alt + F7 / Ctrl + F7 全项目被使用查找/当前文件声明变量处。光标定位到某变量或函数上，查找该变量或函数在项目中的何处被使用到。
    Ctrl + Shift + F7 在文件中变量或函数被使用处高亮
    Ctrl + Alt + F7 显示详细被使用的位置列表

4.项目运行

    Alt + Shift + F10 选择配置并运行。
    Alt + Shift + F9 选择配置并debug。
    Shift + F10 运行。常用。
    Shift + F9 debug。常用。
    Ctrl + Shift + F10 运行上次运行的配置。
    Ctrl + Shift + X 运行命令行。

5.debug相关（在debug的时候使用）

    F8 步过。继续执行断点后程序，按行执行，按一次执行一行。
    F7 步进。进入到断点执行的内容程序。
    F9 执行程序。常用。继续执行断点以后的程序，停到下一个断点处。
    Ctrl + F8 为光标所在行打上断点。
    Ctrl+Shift+F8 浏览断点。常用。相当于断点搜索功能。

6.导航相关

    Ctrl + N 搜索类。全项目范围。
    Ctrl + Shift + N 根据文件名搜索文件。全项目范围。
    Ctrl + Alt + Shift + N 搜索函数。全项目范围。
    Alt + Right/Left 左右切换打开的文件。
    F12 放回上次打开的工具窗口。
    Esc 返回编辑器界面。
    Ctrl + G 按行号快速定位。
    Ctrl + E 打开最近打开过的文件列表。常用。
    Ctrl + Alt + Left/Right 返回/前进到上次导航操作。
    Ctrl + Shift?+?Backspace 返回到上次编辑的位置。常用。
    Alt + F1 调出目标窗口。例如调出文件列表窗口，文件结构窗口等。
    Ctrl + B or Ctrl + Click 跳转到函数的声明处。最常用。
    Alt + Up/Down 上下切换函数。常用。
    Ctrl + ] / [  定位到右/左侧最近的大括号处。连续点击扩大范围。
    Ctrl + F12 打开文件结构的弹出窗。
    Ctrl + H 浏览选定类的层次结构。
    F2 / Shift + F2 下一个错误提示位置，或上一个错误提示位置。

7.重构相关

    F5 复制文件。
    F6 移动文件。
    Alt + Delete 安全删除。会自动检查被删除的内容是否应用到其他地方。
    Shift + F6 为所选文件重命名。需要光标定位到文件名上。

8.版本控制/本地历史记录

    Alt + BackQuote (`) 打开版本操作控制台。BackQuote (`) 为ESC下面的那个键。
    Ctrl + K 提交代码到svn。
    Ctrl + T 更新代码到本地。
    Alt + Shift + C 浏览最近更改记录。

9.普通操作

    Ctrl + Shift + A 查找操作。必须系统的keymap设置不知道在哪，点击组合后属于keymap即可搜索到。常用。
    Alt + #[0-9] 打开对应的工具窗口。例如Alt + 6打开TODO工具窗口。
    Ctrl + Shift + F12 编辑区窗口最大化。
    Alt + Shift + F 添加到搜藏。
    Alt + Shift + I 检查当前文件。会显示出错误提示，警告等信息。
    Ctrl + BackQuote (`) 快速切换主题。
    Ctrl + Alt + S 打开设置窗口。
    Ctrl + Tab  切换活动文件。普通操作，其他软件通用，例如浏览器可以切换多个页面。

10.live template（快速模板）

    输入fore，按下Tab，会直接输出foreach ( as $item) {}。
    输入forek，按下Tab，会直接输出foreach ( as $index => $item) { }。
    输入pubf，按下Tab，会直接输出public function 。
    以上只是系统自带的示例，重要的是可以自定义自己的模板，例如输入sj，按下Tab直接显示当前时间，会在专门的文章中讲到。

