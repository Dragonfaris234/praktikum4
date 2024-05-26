# praktikum4
Tugas Praktikum  
1.	Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !  
2.	Tampilkan pegawai yang tunjangannya NULL!  
3.	Tampilkan pegawai yang tunjangannya tidak NULL!  
4.	Tampilkan/hitung jumlah baris/record tabel pegawai!  
5.	Tampilkan/hitung jumlah total gaji di tabel pegawai!  
6.	Tampilkan/hitung rata-rata gaji pegawai!  
7.	Tampilkan gaji terkecil!  
8.	Tampilkan gaji terbesar!
![Picture1](https://github.com/Dragonfaris234/praktikum4/assets/170435240/dc08135b-99a1-4a8d-81c9-b8a355b4be65)
Tugas Praktikum  
1.	Tampilkan jumlah hewan yang dimiliki setiap owner.  
2.	Tampilkan jumlah hewan berdasarkan spesies  
3.	Tampilkan jumlah hewan berdasarkan jenis kelamin  
4.	Tampilkan jumlah hewan berdasarkan spesies dan jenis kelamin  
5.	Tampilkan jumlah hewan berdasarkan spesis (cat dan dog saja) dan jenis kelamin  
6.	Tampilkan jumlah hewan berdasarkan jenis kelamin yang diketahui saja 
 
Evaluasi dan Pertanyaan  
•	Tulis semua perintah-perintah SQL percobaan di atas beserta outputnya!  
•	Beri kesimpulan Anda 
 ![Picture2](https://github.com/Dragonfaris234/praktikum4/assets/170435240/df2137f8-ce97-4a19-b120-9cbe895b6d30)
 MEMBUAT TABLE PEGAWAI 
CREATE TABLE pegawai (idpegawai VARCHAR(5), nama_depan VARCHAR(50), nama_belakang VARCHAR(50), email VARCHAR(100), telepon VARCHAR(15), tgl_kontrak DATE, id_job VARCHAR(5), gaji INT, tunjangan INT);  
MEMASUKAN DATA KEDALAM TABLE PEGAWAI 
INSERT INTO pegawai (idpegawai, nama_depan, nama_belakang, email, telepon, tgl_kontrak, id_job, gaji, tunjangan) VALUES ('E001', 'Ferry', 'gustiawan', 
'ferry@yahoo.com', '07117059004', '2005-09-01', 'L0001', 2000000, 500000), ('E002', 'aris', 
'ganiardi', 'aris@yahoo.com', '081312345678', '2006-09-01', 'L0002', 2000000, 200000), 
('E003', 'faiz', 'ahnad', 'faiz@gmail.com', '081367384322', '2006-10-01', 'L0003', 1500000, 
NULL), ('E004', 'emna', 'bunton', 'enna@gmail.com', '081363484342', '2006-10-01', 'L0004', 
1500000, 9), ('E005', 'mike', 'scoff', 'mike@plasa.com', '08163454555', '2007-09-01', 'L0005', 
1250000, 9), ('E006', 'lincoln', 'burrows', 'linc@yahoo.com', '08527388432', '2008-09-01', 'L0006', 1750000, NULL); 
![Picture3](https://github.com/Dragonfaris234/praktikum4/assets/170435240/7d6d9b22-0b6d-4bf9-a74b-870aa247612f)
1.	SELECT * FROM pegawai WHERE gaji <> 2000000 AND gaji <> 1250000; 
![Picture4](https://github.com/Dragonfaris234/praktikum4/assets/170435240/157383eb-73f9-45b9-bede-327804ad067b)
2.	Tampilkan pegawai yang tunjangannya NULL! 
![Picture5](https://github.com/Dragonfaris234/praktikum4/assets/170435240/0ee9f2ad-11f8-4495-b353-cb1b7f1acb83)
3.	Tampilkan pegawai yang tunjangannya tidak NULL! 
![Picture6](https://github.com/Dragonfaris234/praktikum4/assets/170435240/8351b968-50bd-4efa-b615-9092b5d24cae)
4.	Tampilkan/hitung jumlah baris/record tabel pegawai! 
![Picture7](https://github.com/Dragonfaris234/praktikum4/assets/170435240/60d16dd6-c5ee-4200-80d7-3d21bc04536b)
5.	Tampilkan/hitung jumlah total gaji di tabel pegawai! 
![Picture8](https://github.com/Dragonfaris234/praktikum4/assets/170435240/03e3ca90-d442-4453-ae61-ed8cb364f2e2)
6.	Tampilkan/hitung rata-rata gaji pegawai! 
![Picture9](https://github.com/Dragonfaris234/praktikum4/assets/170435240/b8489bee-3126-4a81-ac71-90be6cf8b41f)
7.	Tampilkan gaji terkecil! 
![Picture10](https://github.com/Dragonfaris234/praktikum4/assets/170435240/37ec1e2f-55bb-42ca-8b90-dfe26b214dce)
8.	Tampilkan gaji terbesar! 
![Picture11](https://github.com/Dragonfaris234/praktikum4/assets/170435240/0afc18dc-18e8-4fe3-9af3-a4e94e7cf6a0)
Bagian 2 
Membuat Table Hewan 
CREATE TABLE hewan (id INT PRIMARY KEY AUTO_INCREMENT, p1 
VARCHAR(50), p2 VARCHAR(50), p3 VARCHAR(50), p4 VARCHAR(50), p5 
VARCHAR(50), p6 VARCHAR(50), p7 VARCHAR(50), p8 VARCHAR(50), p9 VARCHAR(50), name VARCHAR(50), owner VARCHAR(50), species VARCHAR(50), sex VARCHAR(1));
![Picture12](https://github.com/Dragonfaris234/praktikum4/assets/170435240/a9dae026-a396-4417-9cb4-9d2dbc558adc)
Memasukan Data Kedalam Table Hewan 
INSERT INTO hewan (p1, p2, p3, p4, p5, p6, p7, p8, p9, name, owner, species, sex) 
VALUES ('Puffball', 'Claws', 'Fluffy', 'Buffy', 'Fang', 'Bowser', 'Chirpy', NULL, NULL, 
'Puffball', 'Diane', 'Hamster', 'f'), (NULL, 'Gwen', 'Haro 1d', 'Haro 1d', 'Benny', NULL, 
NULL, NULL, NULL, 'Claws', 'Gwen', 'cat', 'm'), (NULL, NULL, 'Haro 1d', NULL, 'Slim', 
NULL, NULL, NULL, NULL, 'Fluffy', 'Haro 1d', 'cat', 'f'), (NULL, NULL, NULL, NULL, 
'Whistler', NULL, NULL, NULL, NULL, 'Buffy', 'Haro 1d', 'dog', 'm'), (NULL, NULL, 
NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'Fang', 'Benny', 'dog', 'f'), (NULL, 
NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'Bowser', 'Gwen', 'bird', 'm'), 
(NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'Chirpy', 'Benny', 
'bird', 'm'), (NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 
'Diane', 'snake', 'f'), (NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL, 'Gwen', NULL, 'm'); 
![Picture13](https://github.com/Dragonfaris234/praktikum4/assets/170435240/881e2787-450b-482a-a17c-870bb5f099b2)
1.	Tampilkan jumlah hewan yang dimiliki setiap owner. 
![Picture14](https://github.com/Dragonfaris234/praktikum4/assets/170435240/bcf92688-4065-40d6-b140-8a2d31100e27)
2.	Tampilkan jumlah hewan berdasarkan spesies 
![Picture15](https://github.com/Dragonfaris234/praktikum4/assets/170435240/233f702b-ca5f-4283-bc13-b16ad11bedaa)
3.	Tampilkan jumlah hewan berdasarkan jenis kelamin 
![Picture16](https://github.com/Dragonfaris234/praktikum4/assets/170435240/8dcb52b8-21da-48fb-957e-a5a9616e377b)
4.	Tampilkan jumlah hewan berdasarkan spesies dan jenis kelamin 
![Picture17](https://github.com/Dragonfaris234/praktikum4/assets/170435240/1527b7b1-e207-442e-afb2-e86d2478c83e)
