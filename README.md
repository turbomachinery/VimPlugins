VimConfig
=========

###简介  

VimConfig支持Mac OS、Linux，YCM插件要求Vim最低版本7.4  
  	
- [vim7.4](http://ftp.vim.org/pub/vim/unix/vim-7.4.tar.bz2)  
- [pyclewn](http://pyclewn.sourceforge.net/)

###获取配置文件  

	$git clone https://github.com/chenfjm/VimPlugins.git
	$mv VimPlugins ~/.vim
	$cd .vim
	$git submodule init
	$git submodule update   
	$cp .vimrc ~

###安装插件  

	$vim[:PluginInstall]   
    $cd ~/.vim/bundle/YouCompleteMe
    $./install.sh (--clang-completer)
    $cd ~/.vim/bundle/command-t/ruby/command-t
    $ruby extconf.rb
    $make

###安装依赖软件  

    $brew install ctags(Mac OS)   
    $apt-get install ctags(Linux)

    $easy_install flake8   
    $brew install nodejs(Mac OS)   
    $apt-get install nodejs(Linux)   
    $npm install jshint -g   

    $tar xzf pyclewn-1.11.py3.tar.gz   
    $cd pyclewn-1.11.py3   
    $python setup.py install --force    


- [install command-t](https://app.yinxiang.com/shard/s3/nl/374257207/1d04ad84-d56b-4ca6-93de-13c6af6f28df/)     

###运行效果  

![](https://chenfjm.github.io/VimPlugins/images/vim1.png)
![](https://chenfjm.github.io/VimPlugins/images/vim2.png)
![](https://chenfjm.github.io/VimPlugins/images/vim3.png)
