## vim 编辑器 snipMate 插件的 snippets 补充
  $ cd $HOME/.vim
  $ git clone https:/github.com/zhumengu/snippets.git

## 添加下面行到 ~/.vimrc 中去
    PluginInstall "snippets"
    autocmd BufNewFile,BufRead *.blade.php setlocal filetype=html.blade
    autocmd BufNewFile,BufRead *.html.erb setlocal filetype=html.eruby
