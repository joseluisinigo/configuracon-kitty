## kitty conf
```bash
enable_audio_bell no

include color.ini

font_family      HackNerdFont
font_size 11

disable_ligatures never

url_color #61afef

url_style curly

map ctrl+left neighboring_window left
map ctrl+right neighboring_window right
map ctrl+up neighboring_window up
map ctrl+down neighboring_window down

map f1 copy_to_buffer a 
map f2 paste_from_buffer a
map f3 copy_to_buffer b
map f4 paste_from_buffer b
map f5 copy_to_buffer c
map f6 paste_from_buffer c

cursor_shape beam
cursor_beam_thickness 1.8
 
mouse_hide_wait 3.0
detect_urls  yes

repaint_delay 10
input_delay 3
sync_to_monitor yes

map ctrl+shift+z toogle_layout stack
tab_bar_sytle powerline

inactive_tab_background #e06c75
active_tab_background #98c379
inactive_tab_roreground #000000
tab_bar_margin black

map ctrl+shift+enter new_window_with_cwd
map ctrl+shift+t new_tab_with_cwd

background_opacity 0.95



shell zsh



wget https://github.com/joseluisinigo/configuracion-kitty/color.ini 
in ~.config/kitty

```
control+shift enter Abrir una pantalla dentro de kitty

control+shift w cerrar ventana

ctrl+shift flechas moverte

control+sift r resizear

control + shift + l organizar ventanas

control + shift + t crea ventanas
control + shift + alt +t cambiar nombre
control + shift + izq o derecha te mueves entre ventanas

