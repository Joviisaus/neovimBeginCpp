# BeginNeovim
neovim ~/.config/nvim    -----%100lua

转载自https://github.com/nshen/learn-neovim-lua
小改动基本没动准备配C/C++

version 0.0.1

--------------------------------------------------------------------------



github上的经典主题

非常有名的配色 [gruvbox community]的 Lua 移植版本，支持 [treesitter]

(https://github.com/ellisonleao/gruvbox.nvim)

gruvbox.nvim 改动none全透明




替换插件内的文件-- ~/.local/share/nvim/site/pack/packer/
插件内的下的同名文件


version 0.0.2

------------------------------------------------------------------------------------------------



快捷键小改动


c/c++准备


version0.0.3

---------------------------------------------------------------------------------------------



``apt install tree``权限``studo apt install tree``

在``~/.bashrc``中`vim ~/.bashrc`在最后添加`alisa tree='lt'`

可以用`lt`查看替代`ls`

​                           0.0.4




-----------------------------------------------------------------------------------------------

消除所有小毛病

增加插件并未配置更改快捷键备份

0.0.5



-------------

修改c/cpp可以用gd，gh，gr等ctrl+n对齐



0.0.6

-------------------------------------------------
在powershell中直接打开vim

节省vmmen占用资源内存百兆左右，打开速度在1m可以接受

powershell + scoop + oh-my-posh 最新版本

仅用于打开neovim，wsl虚拟机占用资源大除第一次启动较慢体验感更好

powershell实现类比于linux的alias效果不是很好用function

0.0.7

-------------------------------------------
nvim在windows下用户的appdate/local/nvim配置文件入口

添加c++调试dap用Vimspector实现安装lldb或gdb

用lldb调试，体验不好

0.0.8

----------------------------------------
powershell 的软连接function不是很好用

在插件toggleterm中加入`shell = 'pwsh.exe'`

在neovim中使用powershell作为终端

或`:terminal pwsh`

0.0.9

-----

在nvim中用`echo stdpath ("data")`查看插件安装目录

0.1.0

---
在gruvbox中bg3是v模式的背景bg4是当前行高亮的背景

0.1.1

-----------

tokyonight主题透明化

windows terminal 背景透明调节即可

tokyonight的插件的lua目录下的config.lua文件中

在styles{}加入背景模式即可一共有三种模式，

也可参照官网调整

```lua
-- Background styles. Can be "dark", "transparent" or "normal"
    background ="transparent",
    sidebars = "transparent", -- style for sidebars, see below
    floats = "transparent", -- style for floating windows
```

0.1.2

-----------------

.config是linux下的配置文件

nvim是windows下的文件在用户一般/Appdata/local中

也可以在vim中调用`help config`来查看

0.1.3

------

![效果图](E:\github\neovimBeginCpp\效果图.png)

效果图

0.1.4

----------

添加windows terminal的配置文件

0.1.5

----------

在windows terminal中使用oh my push

`$profile`在wt中用命令查看配置文件位置文件

如果没有自己创建命名为

Microsoft.PowerShell_profile.ps1

可以上下键进行历史命令选择，右键进行历史命令补全

tab进行菜单补全、

0.1.6
