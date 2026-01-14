MOVE FILE NETHUNTER-TERMUX
TERMUX :
- # cp -rf scripts_nethunter /data/local/nhsystem
- $ cp loginshell $PREFIX/bin

NETHUNTER :
- $ cp kalivnc $HOME/.local/bin
- # cp confservice /root

MOVE FILE NETHUNTER-SHELL-ANDROID
SHELL-ANDROID :
- # cp -rf scripts_nethunter /data/local/nhsystem
- $ cp loginshell $PREFIX/bin

NETHUNTER :
- # cp {kalivnc,audiofix} /usr/local/bin
- # cp confservice /usr/local/sbin

COMMAND ON TERMUX :
- $ loginshell <[user_name]>
  |__ login cli nethunter dengan user tertentu.
  
- $ loginshell <[user_name]> startvnc
  |__ login gui vnc nethunter dengan user tertentu.
  
- $ loginshell <[user_name]> wifivnc
  |__ login gui vnc menggunakan wifi ke vncviewer perangkat lain.

- $ loginshell <[user_name]> stopvnc
  |__ logout atau mematikan gui vnc nethunter dengan user tertentu.
