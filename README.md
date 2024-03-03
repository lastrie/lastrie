
#Masukkan nama hari dari Senin - Jumat
nama_hari <- c("Senin","Selasa","Rabu","Kamis","Jumat")

#Masukkan jam kerja berurutan dari jam kerja di hari senin
jam_kerja <- c(8, 7.5, 10, 7, 7.5)

#Memberikan nama pada vector jam_kerja
names(jam_kerja) <- nama_hari

#Tampilkan isi jam_kerja sekarang
jam_kerja

#Jam kerja Andra di hari Senin menggunakan nama
jam_kerja[1]

#Jam kerja Andra di hari Senin, Rabu, dan Jumat menggunakan nama
jam_kerja[c(1, 3, 5)]

#Selisih jam kerja Andra di hari Senin dengan hari Rabu
jam_kerja[1] - jam_kerja[3]
