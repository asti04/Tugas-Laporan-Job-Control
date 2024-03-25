<div style="text-align: center;">
    <h1> Laporan Praktikum Sistem Operasi "Job Control" </h1>
</div>
Nama   : Asti Ratna Shely
NIM    : 09030582226027
Kelas  : TK4A

1. Eksekusi seluruh profile yang ada :   a. Edit file  profile  /etc/profile  dan  tampilkan pesan  sebagai berikut  :    echo  “Profile dari /etc/profile” 
   ![c1](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/b59f901f-5c2d-4c3d-b690-a64320c20006)
  ![c2](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/87b6f91d-f909-4e1c-98ea-bfb29a4a1437)

2. Asumsi nama anda stD02001, maka edit seua profile yang ada yaitu :
   
   a)/home/stD02001/.bash_profile
   
   ![c3](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/fe7a4b2e-999e-4ec9-9a89-90fa5f855607)
   
   b)/home/. stD02001/.bash_login
      
   ![c4](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/f3b78f37-495a-48ce-8fc0-860d8d5ff751)
   
   c)/home/mahasiswa/.profile
   
   ![c5](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/9a339ce5-fc9d-4c18-9ecb-7ed6559a7f1c)
   
   d)/home/mahasiswa/.bashrc
   
    ![c6](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/46756bb3-60c2-4d5d-bad0-f5f91826bbc7)

4. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:
    ![c7](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/22912fee-8874-4a3d-8092-c7bd13648dd7)
   ![c8](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/6db6d28c-8d23-42e7-a57d-ae924a49a57e)


5. masukan "su mahasiswa" dan "exit, kemudian gunakan opsi sebagai berikut " su - mahasiswa" dan "exit"
   ![c9](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/7ff96bf5-da0f-4597-98f8-22ccaefd4dc2)

6. prompt string (PS)
   
  ![C10](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/75d513ae-12ab-46c0-917c-492084624533)
  
   syntax diatas berfungsi untuk menampilkan informasi sesuai dengan option perintah seperti d adalah data (tanggal), t adalah time (waktu), u adalah user (pengguna).

6. Logout
   Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout
   ![c11](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/e6d9f9c3-0582-4a7f-bcba-d0c3b4ecf6b9)

7. Bash Script
   Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
   
   a) p1.sh
   
     ![c12](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/dfae14ff-0b0b-433f-9dfa-79781fbb7b30)
   
   b) p2.sh
   
     ![c13](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/fc92b705-3ac1-4d70-bf72-82081e8011f8)
   
   c) p3.sh
   
      ![c14](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/c06fe4a6-d486-40b8-a46c-cbfd1fa01eaf)

8. Jalankan script tersebut sebagai berikut :
   
   ![c15](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/b4667737-d239-4944-8ecf-0aeaa2199d80)

9. kemudian masukan kode "./p1.sh ; ./p3.sh ; ./p2.sh"
    
    ![c16](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/38be4f48-d392-448e-8407-6e973cfba493)

10. kemudian dilanjutkan memasukkan kode "./p1.sh &"
    
    ![c16](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/2249eb32-bdc0-4730-a270-069f937ae930)

11. masukkan kode "./p1.sh $ ./p2.sh & ./p3.sh &"
    
    ![c18](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/8d0b6fca-df0c-438f-82af-e511c2b928d7)

12. masukkan kode "(./p1.sh ; ./p3.sh) &"
    
    ![c19](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/b6c9a445-edb9-4199-bf45-f2932d569ec4)

13. jobs
    
    a) Buat shell-script yang melakukan loop dengan nama pwaktu.sh,  setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.\
    
    ![c20](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/8d3b12d2-347a-4790-9199-9a97e052762d)

    b) Jalankan  sebagai  background;  kemudian  jalankan  satu  program  (utilitas  find)  di background sebagai berikut :
    
    ![c21](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/6bad79e9-c2e2-4572-8fee-59115bbe0b1b)
    
    c) Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background
    
    ![c22](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/82176e19-4c1a-491b-9b92-e6f97a7a382c)
    
    d) Stop program background dengan utilitas kil
    
    ![c23](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/d63219f6-7f5f-4c49-bdf4-3e5353687a01)
    ![c24](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/5202b17e-2ed4-41a7-8b98-7c782f46493b)

14. History
    
    a) Ganti nilai HISTSIZE dari 1000 menjadi 20
    
    ![c25](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/327f057d-ff23-4d9a-926f-4366551e32a7)
    
    b) Gunakan  fasilitas  history  dengan  mengedit  instruksi  baris  ke  5  dari  instruksi  yang terakhir dilakukan
    
    ![c26](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/6ccf8063-7626-4c9b-96db-02e47dc44dd7)
    
    c) Ulangi instruksi yang terakhir.  Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer
    
    ![c27](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/7d853699-2c87-4107-a1b8-013700c8d0a9)
    
    d) Ulangi instruksi pada history bufer nomor 150
    
    ![c28](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/75883f78-1938-4bc6-bd5b-f36b43bed01f)
    
    e) Ulangi instruksi dengan prefix “ls”
    
    ![c29](https://github.com/asti04/Tugas-Laporan-Job-Control/assets/126399070/a02564ab-2cc1-4d26-b926-833757926184)







    











   



   






