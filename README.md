# DATA MODELING MAP
mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
dosen (kd_ds, nama)
matakuliah (kd_mk, nama, sks)
jadwalmengajar (kd_ds, kd_mk, hari, jam, ruang)
krsmahasiswa (nim, kd_mk, kd_ds, semester, nilai)
