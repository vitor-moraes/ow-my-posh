1) https://brew.sh/
2) https://ohmyposh.dev/docs/installation/linux
3) Find the "themes" folder. I use the windows explorer.
4) Put my theme there, garantee that is a .omp.json file, without .txt
5) With, `nano ./bashrc` put at the end:
``
export PATH="/home/linuxbrew/.linuxbrew/bin:$PATH"
eval "$(oh-my-posh init bash --config $(brew --prefix oh-my-posh)/themes/vitor-craver.omp.json)"
``
7) FiraCode in terminal https://www.youtube.com/watch?v=2LEnBXH8xV0
8) FireCode Font in vsCode terminal https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions
