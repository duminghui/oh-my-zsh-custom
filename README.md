oh-my-zsh-custom
================
oh-my-zsh
------------
[oh-my-zsh]:https://github.com/robbyrussell/oh-my-zsh "oh-my-zsh"
>使用[oh-my-zsh][oh-my-zsh]作为原始的配置
>
>在这个的基础上进行自定义的使用

自定义的pod补全
------------
pod插件是使用以下命令获取的
```
mkdir~/.oh-my-zsh-custom/plugins/pod

pod--completion-script > ~/.oh-my-zsh-custom/plugins/pod/_pod
```
使用方法
==============
在.zshrc中添加以下内容
```
source ~/.oh-my-zsh-custom/_zshrc
```
