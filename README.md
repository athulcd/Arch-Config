# Configuration
Various configuration files on an Arch Linux) System  

Things I did/to-do after installing:  
1. Optimise sound configuration for better quality
2. Change the default shell and customize the zsh/fish shell
3. Text Editor (Vim/Emacs) config
4. Setting up the terminal app(Konsole/kitty)
5. WM config (like i3wm Community Edition for Manjaro)
6. Aliases, keybindings, gestures etc
7. Scaling display/setting dpi
8. Scrolling


I will keep on updating this with configuration files for various tools I use.

Interesting Links:  
1. https://medium.com/@gamunu/enable-high-quality-audio-on-linux-6f16f3fe7e1f  
2. https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH  
3. https://wiki.archlinux.org/index.php/libinput 
4. https://medium.com/@ivanaugustobd/your-terminal-can-be-much-much-more-productive-5256424658e8

## For implementing gestures
sudo usermod --append --groups=input `whoami`   
xorg-xinput 1.6.3-2   

