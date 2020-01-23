# qutebrowser-config
Configuration files for qutebrowser
qutebrowser 配置_colemak配置
## Usage:
Backup existing qutebrowser config:

mv ~/.config/qutebrowser ~/qutebrowser-config-backup

Clone repo:

git clone https://github.com/adlawren/qutebrowser-config.git ~/.config/qutebrowser

## Notes:
- On MacOS, the config folder location is ~/.qutebrowser, not ~/.config/qutebrowser


## Overview of Configuration

* Remapped some of the default keybindings to increase compatibility with the Colemak keyboard layout, and some additional rearranging
  * I -> S (switch to insert mode)
  * H -> N (scroll left)
  * J -> E (scroll down)
  * K -> U (scroll up)
  * L -> I (scroll right)
  * N -> K (iterate through search results)使用/ 查找时用k遍历符合的对象S-k反向遍历
  * S -> J (misc. settings operations)
  * U -> H (undo tab closure)
  
