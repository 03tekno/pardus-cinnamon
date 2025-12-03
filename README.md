Pardus 25 Cinnamon Masaüstü ISO (Resmi değil) 
Trixie Backport depo eklenmiştir. Kernel Backports depodaki kerneldir. 
Web tarayıcı eklemedim. Pardus mağazadan kendi istediğiniz browser uygulamasını kurabilirsiniz.


Kurulum sonrası:
```
sudo apt update && sudo apt upgrade && sudo update-grub
```

Backports depodan firmareleri güncellemek isterseniz: 
```
sudo apt install -t trixie-backports '?upgradable ?source-package("firmware")'
```

Backports depodan mesa güncelemek isterseniz
```
sudo apt install -t trixie-backports '?upgradable ?source-package("mesa|libdrm")'
```
