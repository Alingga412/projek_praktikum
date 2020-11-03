# Tugas pertemuan ke 6
## Profil
**Nama : Reza Riyaldi Irawan**

**NIM : 312010284**

**Kelas : TI.20.A.2**

## Daftar Isi
| No | ISI | Link |
| -- | --- | ---- |
| 1. | Pertemuan ke 6 - Lab 1 | [lihat](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/README.md#pertemuan-ke-6---lab-1) |
| 2. | Pertemuan ke 6 - Lab 2 | [lihat](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/README.md#pertemuan-ke-6---lab-2)|

### Pertemuan ke 6 - Lab 1
Pada pertemuan kali ini saya di beri tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan bahasa python. Berikut adalah source code yang diberikan dosen kepada saya [source code lab 1](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/tugas6-lab2.py)

![output](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%201.PNG)

#### Penggunaan END
> end `end=''` digunakan untuk memberi karakter diakhir baris dipisah oleh tanda koma (,)

```
# penggunaan end
print('A', end='')
print('B', end=' ')
print('C', end='\n')
print()
print('X')
print('Y')
print('Z')
```

Penjelasan

* Penggunaan `end` digunakan untuk memberi karakter diakhir baris dipisah oleh tanda koma (,)
```
+ tidak ada
print('A', end='')

+ menambah space

print('B', end=' ')

+ membuat baris baru dengan \n
print('C', end='\n')
```

* Penggunaan `print()` digunakan untuk membuat baris baru tanpa pemanggilan variable atau yang bukan variable
```
print()
```

* Jika tanpa `end` maka akan langsung membuat baris baru
```
print('X')
print('Y')
print('Z')
```
Maka hasilnya akan seperti berikut

![output](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%203.PNG)

#### Penggunaaan Separator
> Separator  `sep=''` adalah syntax yang digunakan untuk memberi pemisah pada baris yang dipisah oleh tanda koma (,)

```
# penggunaan separtor
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep='+')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
Penjelasan

* Pendeklarasian variable
```
w, x, y, z = 10, 15, 20, 25
```

* Pemanggilan variable tanpa separator

```
print(w, x, y, z)
```
* Pemanggilan variable dengan separator
```
print(w, x, y, z, sep='+')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
Maka hasilnya akan seperti berikut

![output2](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%204.PNG)

### Pertemuan ke 6 - Lab 1/2
