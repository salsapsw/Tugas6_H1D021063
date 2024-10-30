1. ![image](https://github.com/user-attachments/assets/4fe1fe71-e924-483a-b15c-331a72314ac5)

2. ![image](https://github.com/user-attachments/assets/0bfdf7fd-1fe0-4088-858a-2835dc167001)

Penjelasan
1. Menambahkan button "Kenalan Yuk" dengan menggunakan ion-button.
   ![image](https://github.com/user-attachments/assets/17d21ed3-b34c-4a9d-9747-01603a4e1866)
   ion-button ditambahkan didalam ion-content untuk menampilkan card ketika di klik
   *ngIf="!showDetails" itu dipakai untuk menyembunyikan button ketika card ditampilkan
   (click)="toggleDetails()" itu dipakai untuk memanggil metod toogleDetails() ketika buttonnya di klik jadi akan mengubah showDetails nya jadi true
   
2. Menggunakan card setelah button di klik untuk menampilkan informasi nama dan NIM.
   ![image](https://github.com/user-attachments/assets/406cb26a-6d0d-45c1-a0a4-c128d44c2fad)
   card akan muncul ketika button di klik
   *ngIf="showDetails" itu dipakai untuk menampilkan kartu hanya ketika showDetails adalah true
   <ion-card> adalah komponen ionic untuk membuat kartu
   <ion-card-content> itu bagian dalam kartu tempat informasinya ditempatin
   <ion-button> back to home untuk kembali lagi ke tampilan awal dengan menyembunyikan detailnya dan memanggil metod toggleDetails()

 3. ![image](https://github.com/user-attachments/assets/4cc5a094-7666-413a-9385-9157f6dc62fc)
    ini di folder.page.ts untuk mengubah status showDetails
