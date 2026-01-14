######### INSTALL NETHUNTER MODULE #########
- root hp dan install magisk
- download nethunter lite di situs resmi
- pasang nethunter lite dari magisk
- ekstark kali-arm64.****.tar.gz di file nethunter lite ke sdcard
- buka nethunter app dan buka menu manager chroot
- pasang file hasil ekstrak tadi
- login shell dari terminal app

######### INSTALL SCRIPTS VNC IN TERMUX #########
- $ cp loginshell $PREFIX/bin
- # cp scripts_nethunter /data/local/nhsystem
- # mkdir /path/chroot_fs/home/user/.local/bin
- # cp kalivnc /path/chroot_fs/home/user/.local/bin
- # chown [user_linux]:[user_linux] /path/chroot_fs/home/user/.local/bin/kalivnc

######### JIKA KALIVNC TIDAK BEKERJA ###########
- # nano /path/chroot_fs/etc/profile

# tambahkan text dibawah ini
export PATH="$HOME/.local/bin:$PATH"
