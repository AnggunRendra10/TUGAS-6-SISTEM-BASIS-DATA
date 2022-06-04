# TUGAS-6-SISTEM-BASIS-DATA

| Nama      | Anggun Rendra |
| ----------- | ----------- |
| NIM     | 312010022     |
| Kelas   | TI.20.D.1    |

### LANGKAH - LANGKAH TUGAS 6 SISTEM BASIS DATA TI.20.D1

### 1. Masuk Ke Database Nama_nim

![image](https://user-images.githubusercontent.com/101658076/172006931-ad15b5e8-5220-452a-8da6-15d91f555b11.png)

### 2. Lakukan proses Backup Dengan Sql Dari Database Tugas Sebelumnya !

![image](https://user-images.githubusercontent.com/101658076/172006947-68064152-944c-4e26-81d2-ef6ad1ecbce6.png)

### 3. Jika Proses Berhasil Maka Akan Muncul File Backup Pada Direktori  C:\xampp\mysql\data\nama database

![image](https://user-images.githubusercontent.com/101658076/172007014-4de3860d-56c3-4160-8175-68ab7f5c4e17.png)

### 4. Recovery

Data Yang Telah Di-Backup Dapat Dikembalikan Kapan Saja Bila Diperlukan. Sintaks SQL Yang Digunakan Adalah LOAD DATA INFILE. Perintah Yang Dijalankan Adalah :
- LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;

![image](https://user-images.githubusercontent.com/101658076/172007716-0fd7641c-bb58-4153-926e-375dfd8bf3f2.png)

### 5. Lakukan Proses Backup dan Recovery Dengan Sqldump Dari Database Tugas Sebelumnya !

![image](https://user-images.githubusercontent.com/101658076/172007827-7424a9b3-a49d-4484-9d48-827d4ab26219.png)

### 6. Tulisakan Script Cron Job Untuk Melakukan Backup Otomatis Setiap Hari Minggu Jam 12 Malam !
Crontab –e

5923***myqldump -u Adminklinik -p klinnik_312010022>backuptugaske6.sql
