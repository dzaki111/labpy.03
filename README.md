# labpy.03
#### Nama   = DZAKI ARIF RAHMAN  
#### Kelas  = TI.24.A4  
#### NIM    = 312410312  
#### Matkul = BAHASA PEMOGRAMAN

# LATIHAN 1:latihan1.py
# Program Angka Acak dengan Nilai Kurang dari 0.5

## Deskripsi
Program ini menghasilkan sejumlah `N` angka acak yang nilainya selalu kurang dari 0.5. Setiap angka acak ditampilkan secara berurutan dengan nomor urutannya. Program ini menggunakan kombinasi perulangan `for` dan `while` untuk memastikan bahwa setiap angka yang dihasilkan memenuhi kriteria yang ditentukan.

## Fitur Program
1. **Input Dinamis**: Pengguna dapat memasukkan nilai `N` (jumlah angka acak yang ingin dihasilkan) saat runtime.
2. **Pengulangan dan Seleksi**:
   - Menggunakan perulangan `for` untuk menghasilkan angka acak sebanyak `N` kali.
   - Menggunakan `while` untuk memastikan setiap angka yang dihasilkan selalu kurang dari 0.5.
3. **Fungsi Random**: Menggunakan fungsi `random()` dari modul `random` di Python untuk menghasilkan angka acak.

## Penjelasan Kode

1. Import Library Random
```python
from random import random
```
Kode ini mengimpor fungsi random() dari library random bawaan Python. Fungsi random() menghasilkan angka acak dalam rentang 0 hingga 1.

2. Input Nilai N
```python
n = int(input("Masukkan nilai N: "))
```
Program meminta pengguna memasukkan nilai integer N, yang menunjukkan berapa kali loop akan dijalankan. Nilai ini menentukan jumlah angka acak yang ingin dihasilkan.

3. Looping dan Generasi Angka Acak
```python
for i in range(1, n + 1):
```
Loop for ini berjalan dari 1 hingga N (inklusif). Pada setiap iterasi, variabel i akan menyimpan indeks iterasi saat ini.

4. Membuat Angka Acak
```python
angka_acak = random()
```
Pada setiap iterasi, sebuah angka acak dihasilkan menggunakan fungsi random() dan disimpan dalam variabel angka_acak.

5. Kondisi Pemilihan
```python
Salin kode
if angka_acak < 0.5:
    print(f"data ke: {i} => {angka_acak}")
else:
    while angka_acak >= 0.5:
        angka_acak = random()
   print(f"data ke: {i} => {angka_acak}")
```
Jika angka_acak kurang dari `0.5`, maka angka langsung dicetak dengan `format data ke: {i} => {angka_acak}`.
Jika angka_acak lebih besar atau sama dengan `0.5`, program akan masuk ke dalam loop while untuk terus menghasilkan angka acak baru hingga mendapatkan angka yang kurang dari `0.5`, lalu mencetak angka tersebut.

6. Akhir Program
```python
print("Selesai")
```
Setelah semua angka yang diinginkan berhasil dihasilkan dan ditampilkan, program mencetak "Selesai" sebagai tanda bahwa proses telah berakhir.

## Cara Menjalankan Program
1. Pastikan Python telah terinstal di komputer Anda.
2. Simpan program ini sebagai `latihan1.py`.
3. Buka terminal atau command prompt di lokasi penyimpanan file tersebut.
4. Jalankan perintah berikut:
   ```bash
   python3 latihan1.py
5. Masukkan nilai `N` sesuai jumlah angka acak yang ingin dihasilkan.

## Contoh Output
Jika pengguna memasukkan nilai `N = 5`, maka output yang dihasilkan mungkin terlihat seperti ini:

```python
Masukkan nilai N: 5
data ke: 1 => 0.3729648189127943
data ke: 2 => 0.12069084128885188
data ke: 3 => 0.12486530658774031
data ke: 4 => 0.4755389441515395
data ke: 5 => 0.4919317309126129
Selesai
```

## Berikut adalah hasin screenshot vsc

![Screenshot 2024-10-29 104430](https://github.com/user-attachments/assets/5ec24955-d8d6-4ac8-8984-1e8348906105)

## Penjelasan Kode
Import Modul Random: from random import random untuk mengimpor fungsi random() yang akan digunakan untuk menghasilkan angka acak.
Input Pengguna: `n = int(input("Masukkan nilai N: "))` meminta pengguna memasukkan jumlah angka yang akan dihasilkan.
Loop for: Menghasilkan angka acak sebanyak N kali.
Loop while: Memastikan setiap angka yang dihasilkan `kurang dari 0.5. Jika angka lebih besar atau sama dengan 0.5`, angka akan diacak kembali.
Output: Setiap angka acak ditampilkan dengan `format data ke: {nomor} => {angka}`.

# LATIHAN 2.latihan2.py
# 


