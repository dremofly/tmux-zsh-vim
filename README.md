# tmux-zsh-vim
Here is the tmux, zsh and vim setting I use. 

Reference: https://andela.com/insights/configuring-vim-and-tmux-to-boost-your-productivity/

## Installation
复制`tmux.conf`，`vimrc`,`zshrc`到根目录，分别命名为`.tmux.conf`，`.vimrc`,`.zshrc`.
其中在`.vimrc`中需要安装插件。[安装页面](https://github.com/junegunn/vim-plug#unix).
安装完插件以后进入vim，运行命令`PlugInstall`。

## Tmux Usage
纵向分割页面: `ctrl+a`然后`|`
横向分割页面: `ctrl+a`然后`-`
选择下一个面板： `ctral+a`然后`o`
## vim usage
打开vim以后，快捷键如下：
使用ctrl+hjkl移动窗口。
在NerdTree中，使用`o`打开文件，使用`i`打开上下分割的窗口，使用`s`打开左右分割窗口。

## 添加拓展
[Markdown](./markdown.preview)