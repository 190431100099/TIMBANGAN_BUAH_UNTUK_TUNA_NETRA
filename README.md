🎛️ TIMBANGAN BUAH UNTUK TUNA NETRA  
Klasifikasi Jenis Buah Menggunakan CNN dan Arduino Uno

📝 Deskripsi Proyek  
Proyek ini bertujuan untuk membantu penyandang tuna netra dalam mengenali jenis buah berdasarkan berat dan citra visual buah menggunakan teknologi CNN (Convolutional Neural Network) yang terintegrasi dengan Arduino Uno.  
Timbangan ini tidak hanya menampilkan berat buah, tetapi juga mampu mengidentifikasi jenis buah dan memberikan umpan balik berupa suara atau teks yang dapat diakses oleh pengguna tunanetra.

🍎 Buah yang Digunakan  
Model CNN dilatih menggunakan empat jenis buah sebagai data uji coba:  
• 🥑 Alpukat  
• 🌰 Durian  
• 🍊 Jeruk  
• 🍊 Orange (Jeruk Import)  

Setiap jenis buah difoto dalam berbagai kondisi pencahayaan dan sudut pandang, lalu dikombinasikan dengan data berat hasil pembacaan sensor load cell untuk meningkatkan akurasi klasifikasi.

⚙️ Teknologi yang Digunakan  
• Arduino Uno — sebagai pengendali utama pembacaan sensor berat.  
• Load Cell + HX711 — untuk mengukur massa buah.  
• Python & TensorFlow/Keras — untuk melatih dan menjalankan model CNN.  
• Serial Communication (UART) — untuk menghubungkan Arduino dengan sistem klasifikasi di komputer.  
• Text-to-Speech (TTS) — untuk memberikan output suara kepada pengguna.  

🧠 Metode CNN  
Model CNN memproses citra buah untuk mengekstraksi ciri visual unik seperti warna, tekstur, dan bentuk. Hasil klasifikasi digabungkan dengan data berat dari sensor untuk memberikan identifikasi buah yang lebih presisi.

📊 Hasil dan Uji Coba  
Uji coba dilakukan menggunakan set data empat buah di atas dengan berbagai kondisi pencahayaan. Model menunjukkan tingkat akurasi yang baik dalam mengenali jenis buah dari gambar dan berat yang diberikan.

🚀 Tujuan  
• Membantu penyandang tuna netra dalam mengenali jenis buah secara mandiri.  
• Menggabungkan sistem pengukuran berat dan pengenalan citra digital dalam satu alat terintegrasi.  
• Menerapkan teknologi AI dan IoT untuk kebutuhan aksesibilitas.
