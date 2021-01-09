disini saya memiliki beberapa user kucing, tikus, marmout dan singa yang akan dikelompokkan :
1. user sebagai guest, dan
2. singa sebagai superadmin

usermod -G nama_group nama_user

ket:
1. usermod : perintah untuk memodifikasi group
2. -G : pilihan yang akan menggunakan grup

perintah memindahkan user ke grup guest yang sudah dibuat :
usermod -G guest kucing && usermod -G guest tikus && usermod -G guest marmout

perintah memindahkan user ke grup guest yang sudah dibuat :
usermod -G superadmin singa

menampilkan group :
cat /etc/group

![alt text}(https://github.com/asepboy/devops-dumbways-btch3-kl2/blob/main/folder-image-jawaban/02.png)

