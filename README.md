to export 
code --list-extensions > extensions.list

to install
cat extensions.list | xargs -L 1 code --install-extension

