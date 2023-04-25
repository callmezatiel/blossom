# Blossom
SDDM Waifu

Prerequisites
KDE Plasma Desktop

Dependencies

* "SDDM"


# Install
Módulos Qt5 para evitar posibles errores al momento de aplicar la configuración sddm

Debian based distros using the APT package manager:
(Ubuntu/Kubuntu/Kali/Neon/antiX etc.)
```
sudo apt install --no-install-recommends sddm qml-module-qtquick-layouts qml-module-qtgraphicaleffects qml-module-qtquick-controls2 libqt5svg5
Arch based distros using the pacman package manger:
```
(Obarun/Artix/Manjaro/KaOS/Chakra etc.)
```
sudo pacman -S --needed sddm qt5-graphicaleffects qt5-quickcontrols2 qt5-svg
```
openSUSE using the zypper package manager:
```
sudo zypper install sddm libqt5-qtgraphicaleffects libqt5-qtquickcontrols2 libQt5Svg5 libQt5Svg5
```
Red Hat based distros using the dnf package manager:
(Fedora/Mageia/RHEL/CentOS)
```
sudo dnf install sddm qt5-qtgraphicaleffects qt5-qtquickcontrols2 qt5-qtsvg
```
creditos a Marian Arlt

* copy the blossom folder to the following directory:

```
   /usr/share/sddm/themes/
```

And add "blossom" to you 
/etc/sddm.conf



```
[Theme]
# Current theme name
Current=blossom
```

![Preview](https://i.postimg.cc/j5rqjL0m/preview.png)
