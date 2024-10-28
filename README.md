Project Description : Membuat Web UI automation framework dengan Selenium
  Project ini membuat kerangka pengujian UI Web menggunakan Cucumber, Java, Gradle, Selenium
  Tujuan Project ini adalah untuk melakukan automasi pada pengujian WEB UI
  Project hanya mendukung Java Development Kit versi 17 ke atas
  Project ini menggunakan pola desain POM (Page Object Model)
  Setiap halaman web dari aplikasi yang diuji direpresentasikan sebagai kelas Java yang terpisah. 
  Setiap Kelas akan berisi semua locator dan metode yang diperlukan untuk berinteraksi dengan elemen di halaman tersebut.
  Test Case menggunakan Gherkin syntax, yang merupakan format bahasa alami untuk menggambarkan tes. 
  Test case harus menjelaskan perilaku yang diharapkan dari aplikasi dalam hal fitur dan persyaratannya.
  Cucumber library untuk mendukung kasus pengujian Gherkin, menjalankannya, dan membuat laporan.
  Rangkaian pengujian otomatis ini mencakup tests positif (positive), negatif (negative), dan batas (boundaries). 
  Pengujian ini harus memverifikasi fungsionalitas aplikasi, memeriksa apakah aplikasi berperilaku seperti yang diharapkan dalam skenario yang berbeda.

Project ini menggunakan website https://www.saucedemo.com/v1/index.html 
  Untuk running testing pada project ini, bisa ketik diterminal --> call gradlew webTest 
  Terdapat 2 feature file dalam project ini untuk testing fitur login dan fitur add item to shopping cart yang bisa dilihat pada src/test/resources

Berikut hasil run dari project ini:
![Screenshot 2024-10-27 212909](https://github.com/user-attachments/assets/2c054392-bcbb-4987-a100-82a14b027363)
