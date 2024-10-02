# TUGAS-PRAKTIKUM-SISTEM-OPERASI-6-SK3B
**TUGAS PRAKTIKUM 6 SISTEM OPERASI**

**NAMA : MIKI PURNAWAN**

**KELAS : SK3B**

**NIM : 09011282328122**

Pertama-tama ubah settingan network pada virtual box nya dari NAT ke Bridge Adapter dengan cara buka menu settings - Networrk dan ganti Attached to dari NAT ke Bridge Adapter kemudian sesuaikan dengan wifi adapter kalian dikarenakan saya menggunakan tp-link jadi saya pilih tp-link setelah itu sambungkan perangkat ke jaringan wifi.

![Screenshot 2024-10-02 142618](https://github.com/user-attachments/assets/60dc1024-5c8c-4b41-a088-21e570c1e0df)

Setelah berhasil menyambungkan ke jaringan wifi, kita akan menginstall ssh openserver untuk client dan server nya, caranya ketik command "sudo apt install openssh-client && sudo apt install openssh-server" kemudian masukkan password dari username linux 

![Screenshot 2024-10-02 135823](https://github.com/user-attachments/assets/57133771-01b3-4a46-a2f7-ab986834a20c)

Kemudian cek ip address pada perangkat linux menggunakan command ifconfig dan gunakan ip address "inet" yang atas

![Screenshot 2024-10-02 140849](https://github.com/user-attachments/assets/17d04457-85ec-4b96-8207-c2677c845a18)

Jika ip address diketahui, kita tinggal login ke ssh server sebagai host dengan cara ssh miki-purnawan@192.168.1.16 (miki-purnawan@192.168.1.16 itu contoh, bisa kalian ubah sesuai username linux dan ip address kalian masing masing)

![Screenshot 2024-10-02 141244](https://github.com/user-attachments/assets/a370b5ed-6aa6-4f74-84bd-bf978d858be5)
