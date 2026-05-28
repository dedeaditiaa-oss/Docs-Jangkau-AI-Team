# ⚙️ Pengaturan Umum Bot AI

Halaman ini menjelaskan panduan dasar pembuatan dan pengaturan awal yang berlaku secara umum untuk seluruh tipe Bot AI di platform Jangkau AI

---

## 🚀 Tahap Awal: Membuat Bot AI Baru

Untuk memulai pembuatan Bot AI (misalnya template *Lead Generation*), ikuti langkah berikut:

1. Masuk ke dashboard Jangkau AI lalu klik tombol **Bot AI** pada panel di sebelah kiri.
2. Klik **+ Buat Bot AI**
3. Masukkan **Nama Bot AI** sesuai preferensi Anda.
4. Pada pilihan **Tipe Bot AI**, pilih **Single Agent**.
5. Pada pilihan **Template Bot AI**. Terdapat 4 jenis bot yang bisa anda pilih sesuai dengan kebutuhan anda :
      * Booking/Reservasi
      * Support Helpdesk
      * Lead Generation
      * Chat Commerce 

![Form Pembuatan Bot AI](assets/umum-1.png)

---

## 📝 Komponen Pengaturan Utama

Setelah bot berhasil dibuat, Anda akan diarahkan ke halaman konfigurasi dasar. Berikut adalah bagian-bagian penting yang wajib Anda isi:

### 1. Nama Bot AI
Kolom identitas digital untuk bot Anda. Nama ini bebas ditentukan dan dapat disesuaikan dengan kebutuhan internal perusahaan.

![Nama Bot AI](assets/umum-2.png)


### 2. Tujuan dan Fokus 
Bagian ini adalah Prompting utama dan inti dari Bot AI Anda. Tuliskan instruksi mendetail mengenai tugas utama, apa yang harus dilakukan, dan apa  yang harus dicapai oleh bot tersebut. 

Berikut adalah template ketika anda membuka menu umum :

![Template Tujuan dan Fokus](assets/umum-3.png)

### 3. Gaya Bahasa
Menentukan kepribadian dan cara berkomunikasi Bot AI saat berinteraksi dengan pelanggan. 

!!! quote "Rekomendasi Template Gaya Bahasa"
    * Berbicara dengan hangat seperti seorang konsultan untuk memberikan layanan dan solusi kepada pelanggan.
    * Respon dengan bahasa Indonesia kecuali pelanggan memakai bahasa lain.
    * Sampaikan informasi yang jelas dan ringkas, gunakan emoji yang profesional tetapi tidak berlebihan.

### 4. Informasi Bisnis Anda
Berikan basis pengetahuan kontekstual mengenai operasional bisnis Anda agar AI tidak memberikan jawaban yang keliru (*hallucination*).
> **Contoh Input:**  
> *"Toko buka setiap hari Senin sampai Jumat, buka mulai jam 09.00 hingga 17.00 WIB."*

---

## 🔀 Fitur Aktifkan Pengalihan (Human Handover)

Fitur ini berfungsi sebagai jaring pengaman. Saat diaktifkan, Bot AI akan meneruskan *room chat* ke agen manusia secara otomatis berdasarkan kondisi-kondisi darurat tertentu yang telah ditentukan.

![Pengaturan Pengalihan Agen](assets/image_a19202.png)

### ⚠️ Kondisi Pengalihan Standar
Bot akan otomatis berhenti menjawab dan memanggil Tim CS/Agen manusia jika mendeteksi situasi berikut:
* Customer menunjukkan ketidakpuasan terhadap jawaban yang diberikan (seperti menanyakan hal yang sama terus menerus tanpa mendapatkan jawaban yang memuaskan).
* Customer menggunakan bahasa yang kurang sopan atau mengancam.
* Bot AI tidak dapat menjawab pertanyaan atau permintaan pelanggan berdasarkan *tools* atau pengetahuan (*knowledge base*) yang tersedia.
* Customer meminta secara eksplisit untuk berbicara dengan agen manusia.

---

## 🧪 Simulator Uji Coba Bot

Di sebelah kanan panel pengaturan, terdapat *widget* simulator obrolan langsung. 

Setiap kali Anda selesai mengubah pengaturan di atas atau memperbarui basis data informasi bisnis, Anda dapat langsung melakukan tes percakapan di box ini untuk memastikan respon AI sudah sesuai sebelum disebarkan ke website asli.

![Widget Simulator Chat](assets/image_a19239.png)