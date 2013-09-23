# Base install packages
base base-devel iw wpa_supplicant grub

# X Server
xorg-server xorg-server-utils xorg-xinit mesa mesa-demos xf86-input-synaptics xf86-video-intel lib32-intel-dri ttf-dejavu

# Audio
alsa-utils pulseaudio pulseaudio-alsa lib32-libpulse lib32-alsa-plugins gst-plugins-good gstreamer0.10-good-plugins

# Other utilites
git wget xdg-user-dirs ttf-droid ntp openssh cower pacaur reflector pkgstats pkgfile tmux kdeutils-ark zip p7zip unzip unrar dosfstools ntfs-3g gpart mtools abs gdb dnsutils nfs-utils pipelight android-sdk android-udev poppler-glib rxvt-unicode gtk2-perl xorg-xev os-prober ttf-mac-fonts ttf-microsoft-tahoma ttf-ms-fonts ttf-anonymous-pro emacs ttf-oxygen-git jdk skype dropbox gparted grsync calibre digikam gimp 

# KDE Install and other KDE apps
kdebase kdemultimedia-kmix kde-gtk-config gtk gtk2 gtk3 oxygen-gtk2 oxygen-gtk3 kdegraphics-okular kdegraphics-gwenview kdegraphics-ksnapshot kipi-plugins kdeutils-kcalc python python2 kdebindings-python kdebindings-python2 bluedevil kdesdk-kioslaves kdesdk-dolphin-plugins kdeplasma-addons-applets-showdesktop ksuperkey kamoso kdeutils-kwallet kdeutils-kgpg kdesdk-thumbnailers kdemultimedia-ffmpegthumbs audiothumbs kio-mtp kdegraphics-strigi-analyzer kdenetwork-strigi-analyzers kdesdk-strigi-analyzers kdeplasma-addons-applets-icontasks kdeadmin-kuser

# Network Manager
networkmanager kdeplasma-applets-networkmanagement networkmanager-dispatcher-ntpd networkmanager-dispatcher-sshd

# Bumblebee
bumblebee bbswitch primus lib32-primus nvidia lib32-nvidia-utils 

# Applications
## Browser
google-chrome google-talkplugin
## Multimedia
vlc banshee easytag transmission-qt gstreamer0.10-plugins google-musicmanager amarok

# Power management tools
tlp tlp-rdw smartmontools tp_smapi acpid htop powertop lm_sensors thinkfan

# Libreoffice
libreoffice-{en-US,kde4,writer,calc,impress} {hunspell,mythes,hyphen}-en libreoffice-extension-languagetool

# Print and Scanner
cups cups-filters ghostscript gsfonts avahi samba hplip hpoj kdeutils-print-manager sane skanlite kdegraphics-ksaneplugin

# Steam
steam libtxc_dxtn lib32-libtxc_dxtn wqy-zenhei lib32-flashplugin
