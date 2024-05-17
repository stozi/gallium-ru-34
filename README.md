# gallium-ru-34
A writing-focused 34-key ZMK/Linux layout for gallium and йцукен with mouse keys.

In Linux, set compose to pause, switch lang to rctrl.
Instructions on what to do with the [gallium](https://github.com/stozi/galliumv2-ru-34/blob/main/gallium), [evdev_section](https://github.com/stozi/gallium-ru-34/blob/main/evdev_section.xml), and optionally (for CLI) [gallium.map](https://github.com/stozi/gallium-ru-34/blob/main/gallium.map) files are in those files. Copy the contents of [my ZMK keymap](https://github.com/stozi/zmk-config/blob/master/config/a_dux.keymap) file to yours in Github. ZMK mouse keys require additional setup. If ZMK mouse keys are still in beta and you haven't got it working yet, you can copy the contents of my [west.yml](https://github.com/stozi/zmk-config/blob/master/config/west.yml) file.


Prefix 'C' means ctrl+, 'S' means shift+.

Illustration:

Base layer, mouse keys on the left.

```
Cpu sal pst cpy cut   mut vo- tab esc vo+ 

msl msu msd msr br+   Cbk arl ard aru arr

Cpd rmb mmb lmb br-   Cdl the end hom .,

layer2 layer1/enter  shift/space alt/bkspc   
```               

Hybrid ctrl/fn layer for base layer (skC is sticky ctrl, Cer is ctrl-enter)

```
pgu F10 F1  F2  F3  F4  F5  F6  F7  F8

F9  wlu wld Cer C=  SCb Cal Cad Cau Car

pdn rdo udo skC C-  SCd F11 Ced Chm F12

null layer0/enter  shift/space alt/del   
```

```
b   l   d   c   v     j   y   o   u   /?
й   ц   у   к   е     н   г   ш   щ   з

n   r   t   s   g     p   h   a   e   i
ф   ы   в   а   п     р   о   л   д   ж

x   q   m   w   z     k   f   '"  -_  .,
я   ч   с   м   и     т   ь   б   ю   .,

layer0 layer3/enter  shift/space alt/bkspc
```

Fn layer for alpha layer. 'cmp' is compose, 'lng' switch lang. Accessed by holding down the left-left thumb key or tapping both left-hand thumb keys at once.

```
n/a ~`  :;  lng n/a  n/a com [{  ]}  n/a
    ё   э                    х   ъ

9(  0)  1!  2@  3#   4$  5%  6^  7&  8*

<>  \|  =+  skC cmp  n/a the ()  –—  sen       

null layer2/enter  shift/space alt/del
```
