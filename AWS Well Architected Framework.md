# AWS Well Architected Framework

Arsitektur adalah seni dan ilmu merancang dan membangun struktur besar. Sistem besar membutuhkan arsitek untuk mengelola ukuran dan kompleksitasnya. Arsitek cloud terlibat dengan pembuat keputusan untuk mengidentifikasi tujuan bisnis, menyelaraskan hasil teknologi dengan tujuan tersebut, dan bekerja dengan tim pengiriman untuk mengimplementasikan solusi yang sesuai. AWS Well-Architected Framework mendokumentasikan serangkaian pertanyaan dasar yang memungkinkan kita memahami apakah arsitektur tertentu selaras dengan praktik terbaik cloud. Kerangka Kerja yang Dirancang dengan Baik memberikan pendekatan yang konsisten untuk mengevaluasi sistem terhadap kualitas yang kita harapkan dari sistem berbasis cloud modern dan perbaikan yang diperlukan untuk mencapai kualitas terbaik. Kerangka Kerja AWS Well-Architected membantu arsitek cloud menilai dan meningkatkan arsitektur kita dan mendapatkan pemahaman yang lebih baik tentang bagaimana keputusan desain dapat memengaruhi bisnis. Ini memberikan serangkaian pertanyaan yang dikembangkan oleh pakar AWS untuk membantu pelanggan berpikir kritis tentang arsitektur mereka, seperti "Apakah infrastruktur Anda mengikuti praktik terbaik?"
Saat teknologi cloud terus berkembang, dan saat AWS terus belajar lebih banyak dari bekerja dengan pelanggan, definisi arsitektur yang baik terus ditingkatkan dan disempurnakan.

Pointnya adalah :

- Meningkatkan kesadaran praktik terbaik arsitektur
- Mengalamatkan sebuah pondasi khusunya di area tertentu yang sering bermsalah
- Mengevaluasi arsitektur menggunakan seperangkat prinsip yang konsisten

Tujuan dari memahami Well Architected Framework untuk meningkatkan kewaspaan bagaimana best pratice dari Arsitek itu sendiri, Khususnya bagi Cloud Architect

## AWS Well Architected Framework Futures

### Does Not Provide :

    * Cara implementasi secara datail
    * Architectural Pattern

ini dikarenakan setiap aplikasi memiliki arsitecture tersendiri oleh karena itu AWS Well Architected Framework tidak mewakili itu, tetapi.

### Does Provide :

    * Pertanyaan yang langsung tepat sasaran yang sekarang dibutuhkan, seperti scallingnya sudah benarkah ?, securitnya sudah amankah ?
    * AWS akan menyediakan servis dan solusi yang relevan setiap pertanyaan.
    * Referensi yang sumber yang relevan

## AWS Well Architected Framework Pillars

AWS Well Architected Framework memiliki 5 Pilar :

1. Operational Exelence : Fokus untuk deliver business value.
2. Security : Untuk melindungi dan memonitoring system.
3. Reability : Melindungi dari kesalahan dan memitimigasi jika terjadi bencana.
4. Performance Eficiency : Menggunakan resource secara hemat (spraingly).
5. Cost Optimazation : Mengeliminasi biaya yang tidak dibutuhkan.

### Operational Exelence

Kemampuan untuk memonitor sebuah system dengan tujuan :

    - Deliver business value
    - Untuk meningkatkan support berkelanjutan dan prosedur

untuk membentuk Operasi yang baik beberapa prinsip terbaiknya adalah

    - Perform operation as a code : Mengoperasikan dengan coding
    - Membuat Dokumentasi
    - Melakukan operasi sesering mungkin, kecil yang bisa di kembalikan jika gagal.
    - Memperbaiki prosedur sesering mungkin jika salah.
    - Antisiapsi failure
    - Belajar daris semua kejadian dan failure yang sudah lewat.

### Security

kemampuan untuk :

    * memonitor dan protect :

    - informasi
    - system
    - Assets

    * Ketika deliver business value harus mampu melewati

    - Risk Management
    - Bisa melaklukan mitigasi strategi (Mitigation Strategy)

Topic Key :

- Identifiying and managing who can do what.
- Establishing control to detect security events.
- Protect system dan service
- Protecting Confidentiality and Integrity of data.

Terdapat 5 kunci area pada cloud security :

1. Identity and Acces Management (IAM)
2. Detective Control
3. Infrastructure Protection
4. Data Protection
5. Incedent Response

Prinsip dari Cloud Security :

1. Implement security at all layer > Memperbanyak layer agar security aman.
2. Enable Tracebility > Mudah di lacak
3. Implement the principle of the least privilege > Tidak memberikan akses yang lebar kepada pengguna
4. Focus on securing your systemn > Fokus mengamankan pengamanan
5. Automate

### Reability

Kemampuan system untuk :

- Recover of infrastructure or service failure > Service/Apk tetap tersedia dalam keadaan apapun
- Dinamically equire computing resources meet demand. > secara dinamis mendapatkan resource sesuai kebutuhan.
- Mitigate Disruptions such as - Misconfiguration & Transient Network Issue (Masalah Jaringa Sementara)

Terdapat 3 Kunci dari Reability :

1. Foundations
2. Change Management
3. Failure Management

Sehinggah kita dapat mengantisipasi, merespon dan mencegah kesalahan.

Prinsip dari gambaran Reability :

1. Test Recovery Procedurs
2. Automatically Recover
3. Scale Horizontally
4. Stop Guessing Capacity
5. Manage Change in Automation

### Performance Efficiency

kemampuan :

- Use computing resources efficiently to meet system requirements > Menggunakan sumberdaya yang sesuai
- Maintain taht efficiency ad demand change and technologies evolve > Mampu melakukan maintenance yang efisien sesuai perubahan kebutuhan dan perkembangan teknologi.
