# VIM
工欲善其事，必先利其器

## 1、vim 插件包地址
  http://47.104.15.66:8080/resource/vim.tar.gz  
  插件包解压到用户根目录，修改vimrc文件->.vimrc，即可正常使用。

## 2、vim 插件配置
  根据.vimrc中的配置启用或关闭插件，例如：开启自动补全插件 Plugin 'Valloric/YouCompleteMe'

#### vim 插件可能出现的问题  
  YouCompleteMe自动补全插件启动失败，  可以在.vimrc配置中开启ycm的debug日志，查看错误原因:

  let g:ycm_keep_logfiles = 1
  let g:ycm_log_level = 'debug'

  dsadwf
  =======
  sssssss
  ----
