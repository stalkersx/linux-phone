SYARAT NETHUNTER PRO :
- perangkat harus prosesor qcom-sdm845
- sudah terunlock bootloader

BAHAN NETHUNTER PRO :
- images nethunter pro terbaru
- kabel data
- otg jika flashing dari hp
- tools adb terinstall di hp/komputer (bugjeger di hp, minimal adb di komputer)
- file images twrp sesuai tipe hp

INSTALL NETHUNTER PRO :
1. DI KOMPUTER/HP
- siap kan tools adb di hp/komputer
- colokkan kabel data ke hp/komputer (usb colok otg jika flash dari hp)
- flash file images recovery dengan perintah "fastboot boot /path/file.recovery"
- ekstak file images nethunter pro
- flashing nethunter pro dengan perintah
  "fastboot flash userdata /path/filerootfsnh"
- jalakan perintah jika tidak memecah partisi
  "fastboot flash boot /path/filebootnh"
- jalankan perintah jika partisi dipecah
  "fastboot flash recovery /path/filebootnh"
  
2. DI HP YANG AKAN DI INSTALL :
- clear data dari mode recovery
- masuk mode fastboot dengan tekan tahan volume atas dan power bersamaan.
- jika sudah masuk recovery twrp
- masuk ke opsi terminal
- jalankan perintah atau gunakan script ./config_partisi_nh.sh
  "chmod 755 parted"
- kembali ke mode fastboot
- restart jika sudah flashing
- jika susah masuk nh tekan pijit beberapa kali di volume bawa ketika logo hp muncul.
