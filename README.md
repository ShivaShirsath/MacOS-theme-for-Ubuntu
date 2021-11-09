# MacOS theme for Ubuntu
```bash
sudo apt install git -y
```

GTK 
```bash
PWDx=$PWD
cd ~
git clone https://github.com/vinceliuice/WhiteSur-gtk-theme.git
cd WhiteSur-gtk-theme
chmod +x *
./install.sh -c dark -a all -t orange -s 180 -HD --round --dialog
cd $PWDx
```
Icon
```bash
PWDx=$PWD
cd ~
git clone https://github.com/vinceliuice/WhiteSur-icon-theme.git
cd WhiteSur-icon-theme
chmod +x *
./install.sh -t orange -b --black
cd $PWDx
```
Cursor
```bash
PWDx=$PWD
cd ~
git clone https://github.com/vinceliuice/WhiteSur-cursors.git
cd WhiteSur-cursors
chmod +x *
bash install.sh
cd $PWDx
```
Wallpaper
```bash
PWDx=$PWD
mkdir /usr/share/backgrounds
cd /usr/share/backgrounds
wget https://raw.githubusercontent.com/ShivaShirsath/MacOS-theme-for-Ubuntu/main/WhiteSur.svg
cd $PWDx
```
[@vinceliuice](https://github.com/vinceliuice)
