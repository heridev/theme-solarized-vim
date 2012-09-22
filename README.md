###How to install theme solarized for Vim (Gvim, Mvim)

###First Clone the repo
If you can use the color or style for theme solarized you will need to 
    
    git clone git@github.com:heridev/theme-solarized-vim.git solarized

After that we need to move inside the directory called solarized with the next command

    $ cd solarized

And now we need to move the file called solarized.vim in the vim colors directory we can do this with the next code

    $ mv solarized.vim ~/.vim/colors/

Now lets continue with the edition of the file vimrc we do this with

    $ mvim .vimrc

and we need to add this lines at the end of the file

    syntax enable
    set background=dark
    olorscheme solarized

After that we need to close and reopen our Editor Vim if we have opened
Vim

If you have problems at the moment to install the theme you can visit my
complete post in the next url
http://heridev.micompu.com.mx/generales/how-to-install-an-incredible-theme-solarized-for-vim-gvim-or-mvim/


