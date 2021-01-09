key pair menurut saya mengakses server melalui remote host dengan calara login passwordless (tanpa password), selain itu dapat membuat SSH server aman dengan hanya menerima request login menggunakan key pair. key pair dengan SSH menggunakan teknik kriptografi untuk memastikan semua komunikasi yang masuk keluar dari server remote secara terenkripsi.

Command SSH key Pair
    ssh{user}@{host}
    
Cara kerjanya adalah melalui SSH key menginstruksikan sistem membuka koneksi secure shell yang dienkripsi merujuk pada akun {user} sebagai root dan administrator dapat memodifikasi apapun pada sistem. {host} disini merujuk pada komputer yang ingin diakses.

pada saat masuk, akan diminta key number pada request. ketika request yang diminta sudah benar maka akan muncul jendela terminal remote.
