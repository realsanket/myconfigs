to export 
code --list-extensions > extensions.list

to install
 cat extensions.list |% { code --install-extension $_}
