# san-Lang
Tugas Akhir Teknik Kompilasi<br />
Membuat bahasa pemrograman menggunakan python dan library SLY

## Nama Kelompok:
1. Anindya Heranika
2. Muhammad Ikhsan Hadi
3. Rafi el Falih

---

# Dokumentasi
## Perintah di bahasa ini

| San-Lang     |  Arti  |
| --------     |  ----  |
| jika         |  IF    |
| cetak        |  PRINT |
| maka         |  THEN  |
| jktidak      |  ELSE  |
| untuk        |  FOR   |
| fungsi       |  FUN   |
| sampai       |  TO    |
| ->           |  ARROW |

## Cara Menggunakan
- Pastikan perangkat telah terinstall python dan juga library SLY.
- Buka command prompt (cmd) atau terminal dan bukalah folder penyimpanan san-Lang ini `../san-Lang/`
- Jalankan file main.py atau main2.py dengan perintah sebagai berikut:
```
python main.py helloworld.san
```
atau
```
python main2.py
```

## Contoh san-Lang

### Hello World

**kode:**
```
cetak "Hello World!"
```

**hasil:**
```
Hello World!
```


### If-Else

> jika _expr_ maka _stmt1_ jika_tidak _stmt2_

**kode:**
```
a=1
b=2
jika a==b maka cetak "a sama dengan b" jika_tidak cetak "a tidak sama dengan b"
```

**hasil:**
```
a tidak sama dengan b
```

### Operasi Matematika

**kode:**
```
a=4
b=2
cetak a+b
cetak a*b
cetak a-b
cetak a/b
```

**hasil:**
```
6
8
2
2
```

### For Loop

> untuk _index1_ sampai _index2_ maka _stmt_

**kode:**
```
untuk i=0 sampai 5 maka cetak i
```

**hasil:**
```
0
1
2
3
4
```

### Fungsi

> fungsi _namaFungsi_() -> _kode_

**kode:**
```
fungsi dicoba() -> cetak "ini hasil dari fungsi"

dicoba()
```

**hasil:**
```
ini hasil dari fungsi
```
