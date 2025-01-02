TUGAS AKHIR BASIS DATA (G)

# Step by Step
### Step 1: Membuat database db_Bidang1Imatika (`db_Bidang1Imatika`)
```sql
CREATE DATABASE db_Bidang1Imatika
```
![Create-Database](/Gambar/1.png)

### Step 2: Membuat table Anggota (`Anggota`)
```sql
CREATE TABLE Anggota(
	ID_Anggota INT PRIMARY KEY AUTO_INCREMENT,
	NPM BIGINT,
	Nama VARCHAR(225),
	Tanggal_Lahir Date,
	Email VARCHAR(225),
	Nomer_Telepon BIGINT
);
```
![Create-Table-Anggota](/Gambar/2.png)
![Show-Table-Anggota](/Gambar/3.png)

### Step 3: Memasukkan data ke dalam table Anggota
```sql
INSERT INTO Anggota (ID_Anggota, NPM, Nama, Tanggal_Lahir, Email, Nomer_Telepon) VALUES
('','4522210001','Gino Putra Widana','2000-04-10','gino.widana@email.com','081234567800'),
('','4523210128','Rizky Nuril Ikhsan','1999-08-22','rizky.nuril@email.com','081234567801'),
('','4522210002','Emyely Nemy Agustine','2001-12-15','emyely.agustine@email.com','081234567802'),
('','4523210127','Siti Nurhaliza Fahmi','2000-02-17','siti.nurhaliza@email.com','081234567803'),
('','4522210003','Haryo Bintang Alfareza','1999-07-28','haryo.bintang@email.com','081234567804'),
('','4523210113','Daffa Muhammad Pratama','2001-03-05','daffa.pratama@email.com','081234567805'),
('','4522210004','Rizka Adelia Wijaya','2002-06-18','rizka.wijaya@email.com','081234567806'),
('','4523210098','Aulia Rahayu Kartika','2000-11-25','aulia.rahayu@email.com','081234567807'),
('','4522210005','Adi Nugroho Saputra','1999-09-10','adi.nugroho@email.com','081234567808'),
('','4523210077','Farah Indira Putri','2001-01-08','farah.indira@email.com','081234567809'),
('','4522210006','Naufal Yudha Setiawan','2000-05-12','naufal.yudha@email.com','081234567810'),
('','4523210069','Nadya Maulida Ayu','2002-02-27','nadya.maulida@email.com','081234567811'),
('','4522210007','Bayu Alif Ramadhan','2000-08-14','bayu.ramadhan@email.com','081234567812'),
('','4523210130','Andini Cahya Permata','2001-10-30','andini.permata@email.com','081234567813'),
('','4522210008','Bimo Arya Saputra','1999-06-21','bimo.saputra@email.com','081234567814'),
('','4523210126','Zahra Anindita Ramadhani','2000-04-09','zahra.ramadhani@email.com','081234567815'),
('','4522210009','Fikri Ahmad Ramzi','2002-03-19','fikri.ramzi@email.com','081234567816'),
('','4523210049','Putri Maharani Dewi','1999-01-11','putri.dewi@email.com','081234567817'),
('','4522210010','Rendi Maulana Setyo','2001-07-04','rendi.setyo@email.com','081234567818'),
('','4523210072','Sabrina Hanifa Lestari','2002-09-23','sabrina.lestari@email.com','081234567819'),
('','4522210011','Aditiya Pratama','2001-02-15','aditya.pratama@email.com','081234567890'),
('','4523210039','Fauzan Alfarizi','2000-11-25','fauzan.alfarizi@email.com','081234567891'),
('','4522210012','Nabila Maharani','2002-03-10','nabila.maharani@email.com','081234567892'),
('','4523210023','Rahma Widyaningrum','2001-07-05','rahma.widyaningrum@email.com','081234567893'),
('','4522210013','Dimas Kurniawan','2000-05-20','dimas.kurniawan@email.com','081234567894'),
('','4523210089','Putri Ayu Lestari','2002-01-12','putri.ayu@email.com','081234567895'),
('','4522210014','Farhan Rizky Saputra','2001-09-17','farhan.rizky@email.com','081234567896'),
('','4523210056','Siti Nurhaliza','2000-08-30','siti.nurhaliza@email.com','081234567897'),
('','4522210015','Hendra Setiawan','1999-12-05','hendra.setiawan@email.com','081234567898'),
('','4523210066','Zahra Amelia Putri','2002-04-22','zahra.amelia@email.com','081234567899'),
('','4522210016','Rizal Muhammad Akbar','2001-03-10','rizal.akbar@email.com','081234567900'),
('','4523210073','Aulia Prameswari','2002-06-14','aulia.prameswari@email.com','081234567901'),
('','4522210017','Fajar Hidayat','2000-11-22','fajar.hidayat@email.com','081234567902'),
('','4523210090','Intan Maharani','1999-07-08','intan.maharani@email.com','081234567903'),
('','4522210018','Bagas Pratama','2001-12-18','bagas.pratama@email.com','081234567904'),
('','4523210080','Rina Lestari','2002-08-09','rina.lestari@email.com','081234567905'),
('','4522210019','Yoga Setiawan','2000-05-30','yoga.setiawan@email.com','081234567906'),
('','4523210075','Karina Ayu Susanti','2001-09-04','karina.susanti@email.com','081234567907'),
('','4522210020','Arif Dwi Saputra','1999-02-21','arif.saputra@email.com','081234567908'),
('','4523210085','Lina Widyaningsih','2002-01-15','lina.widyaningsih@email.com','081234567909'),
('','4522210021','Bima Cahya Putra','2001-04-10','bima.cahya@email.com','081234567910'),
('','4523210068','Rani Maharani','2000-10-07','rani.maharani@email.com','081234567911'),
('','4522210022','Dian Permata Sari','2002-03-12','dian.permata@email.com','081234567912'),
('','4523210091','Arini Cahyaningtyas','2000-07-24','arini.cahyaningtyas@email.com','081234567913'),
('','4522210023','Galang Pratama','1999-06-28','galang.pratama@email.com','081234567914'),
('','4523210082','Nadya Kartika Putri','2001-12-13','nadya.kartika@email.com','081234567915'),
('','4522210024','Rizky Ahmad Fauzi','2000-09-19','rizky.fauzi@email.com','081234567916'),
('','4523210087','Vina Amelia Sari','2002-11-11','vina.amelia@email.com','081234567917'),
('','4522210025','Dandi Setiawan','2001-05-06','dandi.setiawan@email.com','081234567918'),
('','4523210092','Rahman Hakim','2000-03-27','rahman.hakim@email.com','081234567919');
```
![Insert-Table-Anggota](/Gambar/4.png)
![Insert-Table-Anggota](/Gambar/5.png)
![Show-Insert-Table-Anggota](/Gambar/6.png)
![Show-Insert-Table-Anggota](/Gambar/7.png)

### Step 4: Membuat Table divisi (`divisi`)
```sql
CREATE TABLE divisi (
    ID_Divisi INT PRIMARY KEY AUTO_INCREMENT,
    Nama_Divisi Varchar(225),
    Ketua_Divisi Varchar(225)
);
```
![Create-Table-divisi](/Gambar/8.png)
![Show-Table-divisi](/Gambar/9.png)

### Step 5: Memasukan data ke dalam Table divisi 
```sql
INSERT INTO divisi (ID_Divisi, nama_divisi, ketua_divisi) VALUES 
('','Pendidikan','Gino Putra Widana'),
('','Penelitian','Rizky Nuril Ikhsan'),
('','Kaderisasi','Emyely Nemy Agustine'),
('','Pengembangan','Siti Nurhaliza Fahmi'),
('','Kerjasama Akademik','Haryo Bintang Alfareza'),
('','Inovasi Teknologi','Daffa Muhammad Pratama'),
('','Publikasi Ilmiah','Rizka Adelia Wijaya'),
('','Bimbingan Belajar','Aulia Rahayu Kartika'),
('','Pengelolaan Perpustakaan','Adi Nugroho Saputra'),
('','Pengembangan Kurikulum','Farah Indira Putri'),
('','Sumber Daya Akademik','Naufal Yudha Setiawan'),
('','Program Studi Luar Kampus','Nadya Maulida Ayu'),
('','Pelatihan Keterampilan','Bayu Alif Ramadhan'),
('','Evaluasi Akademik','Andini Cahya Permata'),
('','Pusat Informasi Mahasiswa','Bimo Arya Saputra'),
('','Manajemen Penelitian','Zahra Anindita Ramadhani'),
('','Pengabdian Masyarakat','Fikri Ahmad Ramzi'),
('','Pembinaan Prestasi','Putri Maharani Dewi'),
('','Organisasi Kemahasiswaan','Rendi Maulana Setyo'),
('','Pengelolaan Laboratorium','Sabrina Hanifa Lestari');
```
![Insert-Table-divisi](/Gambar/10.png)
![Show-Insert-Table-divisi](/Gambar/11.png)

### Step 6: Membuat Table Ketua_Pelaksana (`Ketua_Pelaksana`) 
```sql
CREATE TABLE Ketua_Pelaksana (
    ID_Ketua_Pelaksana INT PRIMARY KEY AUTO_INCREMENT,
    NPM BIGINT,
    Nama VARCHAR(225),
    Nomer_Telepon BIGINT
);
```
![Create-Table-Ketua_Pelaksana](/Gambar/12.png)
![Show-Table-Ketua_Pelaksana](/Gambar/13.png)

### Step 7: Memasukan data ke dalam Table Ketua_Pelaksana 
```sql
INSERT INTO Ketua_Pelaksana (ID_Ketua_Pelaksana, NPM, Nama, Nomer_Telepon) VALUES
('','4523210072','Sabrina Hanifa Lestari1234567800'),
('','4523210128','Rizky Nuril Ikhsan','081234567801'),
('','4522210002','Emyely Nemy Agustine','081234567802'),
('','4523210127','Siti Nurhaliza Fahmi','081234567803'),
('','4522210003','Haryo Bintang Alfareza','081234567804'),
('','4523210113','Daffa Muhammad Pratama','081234567805'),
('','4522210004','Rizka Adelia Wijaya','081234567806'),
('','4523210098','Aulia Rahayu Kartika','081234567807'),
('','4522210005','Adi Nugroho Saputra','081234567808'),
('','4523210077','Farah Indira Putri','081234567809'),
('','4522210006','Naufal Yudha Setiawan','081234567810'),
('','4523210069','Nadya Maulida Ayu','081234567811'),
('','4522210007','Bayu Alif Ramadhan','081234567812'),
('','4523210130','Andini Cahya Permata','081234567813'),
('','4522210008','Bimo Arya Saputra','081234567814'),
('','4523210126','Zahra Anindita Ramadhani','081234567815'),
('','4522210009','Fikri Ahmad Ramzi','081234567816'),
('','4523210049','Putri Maharani Dewi','081234567817'),
('','4522210010','Rendi Maulana Setyo','081234567818'),
('','4523210072','Sabrina Hanifa Lestari','081234567819');
```
![Insert-Table-Ketua_Pelaksana](/Gambar/14.png)
![Show-Insert-Ketua_Pelaksana](/Gambar/15.png)

### Step 8: Membuat Table Peserta (`Peserta`) 
```sql
CREATE TABLE Peserta (
    ID_Peserta INT PRIMARY KEY AUTO_INCREMENT,
    Nama VARCHAR(225),
    NPM BIGINT
);
```
![Create-Table-Peserta](/Gambar/16.png)
![Show-Table-Peserta](/Gambar/17.png)

### Step 9: Memasukan data ke dalam Table Peserta
```sql
INSERT INTO Peserta (Nama, NPM) VALUES
('Ahmad Fauzan', 4522210001),
('Bagas Pratama', 4522210002),
('Citra Dewi', 4522210003),
('Dian Purnama', 4522210004),
('Eka Sari', 4522210005),
('Fajar Nugroho', 4522210006),
('Gita Ayu', 4522210007),
('Hendra Saputra', 4522210008),
('Indah Lestari', 4522210009),
('Joko Santoso', 4522210010),
('Kiki Amalia', 4523210011),
('Lina Permata', 4523210012),
('Mira Wulandari', 4523210013),
('Novi Rahmawati', 4523210014),
('Oka Putra', 4523210015),
('Panca Wirawan', 4523210016),
('Qory Maulida', 4523210017),
('Raka Pratama', 4523210018),
('Sari Amelia', 4523210019),
('Tio Wahyudi', 4523210020),
('Umi Salamah', 4524210021),
('Vina Anggraini', 4524210022),
('Wahyu Saputra', 4524210023),
('Xenia Puspita', 4524210024),
('Yoga Pratama', 4524210025),
('Zahra Aulia', 4524210026),
('Ardiansyah', 4524210027),
('Bunga Sari', 4524210028),
('Cahyo Putra', 4524210029),
('Dewi Kumalasari', 4524210030),
('Erwin Syahputra', 4524210031),
('Fani Oktaviani', 4524210032),
('Gilang Mahardika', 4524210033),
('Hafiz Ramadan', 4524210034),
('Ika Susanti', 4524210035);
```
![Insert-Table-Peserta](/Gambar/18.png)
![Insert-Table-Peserta](/Gambar/19.png)
![Show-Insert-Peserta](/Gambar/20.png)
![Show-Insert-Peserta](/Gambar/21.png)
![Show-Insert-Peserta](/Gambar/22.png)


