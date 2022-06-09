<h1 align="center"> Arch Linuxga DE (Desktop Environment) bo'yicha qo'llanma </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/de.jpg"/> </p>
<br>
<p align="center"> <b> Asosiy va eng ko'p ishlatiladigan DE lar haqida yozilgan </b> </p>
<br>
## GNOME DE o'rnatish
<h1 align="center"> GNOME DE o'rnatish</h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/gnome.png"/> </p>
<br>
GNOME DE haqida batafsil
GNOME DE You Tube tavsif
1-Paketlarni yangilaymiz
```bash
$ sudo pacman -Syu
```
2-`GNOME DE` O'rnatamiz
```bash
$ sudo pacman -S xorg gnome-gnome-extra gdm
```
Theme So'raganda default holda o'rnatamiz `enter` bosamiz
`[Y/n]` chiqganda `y` bosamiz
3-`GDM` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo sytemctl enable gdm
```
4-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda `GNOME DE` o'rnatildi
`Eslatma:` GNOME DE O'rnatilganda Eng Oxirgi versiyasi bilan keladi

## XFCE DE o'rnatish
<h1 align="center"> XFCE DE o'rnatish </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/xfce.png"/> </p>
<br>
XFCE DE haqida batafsil
XFCE DE You Tube tavsif
1-Paketlarni yangilaymizz
```bash
$ sudo pacman -Syu
```
2-`XFCE DE` O'rnatamiz lightdm Display Manageri bilan 
```bash
$ sudo pacman -S xorg xfce4 xfce4-goodies lightdm lightdm-gtk-greeter
```
Theme So'raganda default holda o'rnatamiz `enter` bosamiz
`[Y/n]` chiqganda `y` bosamiz
3-`Lightdm` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo systemctl enable lightdm
```
4-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda `XFCE DE` o'rnatildi



## KDE DE o'rnatish
<h1 align="center"> KDE DE o'rnatish </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/kde.jpg"/> </p>
<br>
KDE DE haqida batafsil
KDE DE You Tube tavsif
1-Paketlarni yangilaymizz
```bash
$ sudo pacman -Syu
```
2-`Xorg` o'rnatamiz
```bash
$ sudo pacman -S xorg
```
`[Y/n]` chiqganda `y` bosamiz
3-`KDE DE` O'rnatamiz
$ sudo pacman -S plasma-meta kde-applications
Theme So'raganda default holda o'rnatamiz `enter` bosamiz
`[Y/n]` chiqganda `y` bosamiz
4-`sddm` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo sytemctl enable sddm
```
```bash
$ sudo sytemctl enable NetworkManager
```
5-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda `KDE DE` o'rnatildi






## MATE DE o'rnatish
<h1 align="center"> MATE DE o'rnatish </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/mate.png"/> </p>
<br>
MATE DE haqida batafsil
MATE DE You Tube tavsif
1-Paketlarni yangilaymizz
```bash
$ sudo pacman -Syu
```
2-`Xorg` o'rnatamiz
```bash
$ sudo pacman -S xorg
```
`[Y/n]` chiqganda `y` bosamiz
3-`MATE DE` O'rnatamiz
```bash
$ sudo pacman -S mate mate-extra lightdm lightdm-gtk-greeter
```
Theme So'raganda default holda o'rnatamiz `enter` bosamiz
`[Y/n]` chiqganda `y` bosamiz
4-`Lightdm` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo systemctl enable lightdm.service
```
5-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda MATE DE o'rnatildi





## Deepin Desktop Environment `DDE` o'rnatish
<h1 align="center"> Deepin Desktop Environment `DDE` o'rnatish </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/deepin.jpg"/> </p>
<br>
Deepin Desktop Environment DDE haqida batafsil
Deepin Desktop Environment DDE You Tube tavsif
1-Paketlarni yangilaymiz
```bash
$ sudo pacman -Syu
```
2-`Xorg` o'rnatamiz
```bash
$ sudo pacman -S xorg
```
3-Deepin Desktop Environment `DDE` O'rnatamiz
```bash
$ sudo pacman -S deepin deepin-extra lightdm lightdm-gtk-greeter
```
Theme So'raganda default holda o'rnatamiz `enter` bosamiz
`[Y/n]` chiqganda `y` bosamiz
4-`Lightdm` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo systemctl enable lightdm
```
5-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda Deepin Desktop Environment `DDE` o'rnatildi




## Cinnamon DE o'rnatish
<h1 align="center"> Cinnamon DE o'rnatish </h1>
<p align="center"> <img src="https://github.com/ismoilovdevml/Archlinux-DE/Pictures/cinnamon.jpg"/> </p>
<br>
Cinnamon DE haqida batafsil
Cinnamon DE You Tube tavsif
1-Paketlarni yangilaymiz
```bash
$ sudo pacman -Syu
```
2-`Xorg` o'rnatamiz
```bash
$ sudo pacman -S xorg
```
3-`Lightdm` Display Managerini o'rnatamiz
```bash
$ sudo pacman -S lightdm lightdm-gtk-greeter
```
4-`Cinnamon DE` O'rnatamiz
```bash
$ sudo pacman -S cinnamon gnome-terminal gnome-system-monitor
```
5-`Lightdm` Display Managerini tizim bilan ishga tushadigan qilamiz
```bash
$ sudo systemctl enable lightdm
```
6-Kompyuterni o'chirib yoqamiz
```bash
$ sudo reboot
```
Tabriklayman Sizda Cinnamon DE o'rnatildi
