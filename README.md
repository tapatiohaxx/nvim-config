<h1> My VIM Configuration for Windows </h1>

Description: An ever expanding configuration document for my VIM software on Windows. 

<h3> How to use </h3>
<ol>
   <li> make a directory called <code> $HOME\AppData\Local\nvim </code> and place the <code> init.vim </code> inside it. </li>
   <li> install <code> vim-plug </code> using <b> <code> iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force </code> <b> for neovim or <b> <code> iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni $HOME/vimfiles/autoload/plug.vim -Force </code> <b> for vim. </li
	>
   <li> install <code> NodeJS </code> </li>
   <li> restart your client and run the command <code> :PlugInstall </code> </li>
   <li> Navigate to the folder named <code> $env:LOCALAPPDATA\nvim-data\plugged\coc.nvim </code> and then run the command <code> npm install -g yarn </code>. After installing yarn, use <code> yarn install </code> to install the syntax highlighter.   </li>
   <li> Install Python 2.7 or 3.1 to use the terminal. It may not work. If it does not work, crearte and environment variable for the Python DLL. </li>
</ol>

<h3> Problems and Extra Information </h3> 

<ul> 
   <li> As stated above, you need to have a version of nvim or vim with ebmedded Python or an environment variable for proper terminal function. </li>
   <li> For any languages you want syntax highlighting for, you should search for that language and CoC highlighting configs and follow instructions to install. </li>
</ul>

