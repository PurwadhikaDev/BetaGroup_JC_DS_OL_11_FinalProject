# BetaGroup_JC_DS_OL_11_FinalProject

### BANK MARKETING CAMPAIGN

Ghany Salam

Ferry Hermawan Kristianto

Business Context:

Term deposit, juga dikenal sebagai deposito berjangka adalah produk keuangan yang ditawarkan oleh bank dan lembaga keuangan lainnya kepada nasabah mereka. Dalam term deposit, nasabah setuju untuk menyetor sejumlah uang tertentu ke dalam rekening khusus untuk jangka waktu yang telah ditentukan, yang bisa berkisar dari beberapa bulan hingga beberapa tahun. Selama periode ini, dana nasabah menjadi tidak dapat dicairkan atau hanya bisa dicairkan dengan biaya tambahan yang biasa disebut denda. Term deposit menguntungkan bagi bank karena mereka dapat menggunakan dana yang diterima dari nasabah dalam bentuk deposito ini untuk untuk diinvestasikan uangnya pada produk keuangan lain yang memberikan rate of return (RoR) yang lebih tinggi daripada yang dibayarkan bank kepada nasabah atas penggunaan dananya. Selisih antara tingkat suku bunga yang mereka bayarkan kepada nasabah dan yang mereka terima dari peminjam adalah salah satu sumber keuntungan bagi bank. Selain itu, deposito memberikan stabilitas dalam sumber dana bank, membantu mereka memenuhi persyaratan permodalan yang diatur oleh otoritas pengawas, dan mendukung pertumbuhan bisnis mereka. Dalam marketing term deposit, bagaimana menyeleksi dan mengidentifikasi nasabah yang paling sesuai dan berpotensi untuk produk tersebut. Tujuan dari marketing ini adalah untuk menciptakan campaign marketing yang efisien dan efektif, yang mengarah pada peningkatan konversi nasabah baru dalam produk term deposit.  Dengan mengefektifkan seleksi calon nasabah potensial, bank dapat menghemat waktu, sumber daya, dan biaya marketing sambil meningkatkan kemungkinan penarikan nasabah baru dan pertumbuhan bisnis mereka.

Target :

No (0) : Nasabah tidak membuka deposito berjangka

Yes (1) : Nasabah membuka deposito berjangka

Problem Statement

Berdasarkan konteks diatas, kesulitan utama yang dihadapi Bank Portugal adalah menentukan pelanggan mana yang lebih mungkin untuk berlangganan produk deposito berjangka. Tanpa pemahaman yang jelas tentang karakteristik pelanggan yang cenderung menerima penawaran, bank berisiko mengalokasikan sumber daya untuk menargetkan pelanggan yang kurang atau tidak tertarik, yang mengakibatkan rendahnya tingkat konversi dengan proporsi nasabah yang tertarik untuk membuka deposito berjangka hanya 11.26% dari total nasabah yang dihubungi pada campaign sebelumnya sejumlah 41.188 nasabah.

Berdasarkan pengamatan terhadap fitur-fitur dalam dataset, terlihat bahwa terdapat sekitar lima fitur yang menunjukkan jumlah nasabah yang besar pada nilai tertentu, namun ketika dipertimbangkan dalam konteks tingkat konversi membuka deposito berjangka, angka tersebut justru rendah. Disamping itu, seringnya interaksi yang dilakukan dengan nasabah yang pada akhirnya tidak berminat membuka deposito berjangka bisa berdampak buruk terhadap persepsi dan reputasi bank.

Dalam konteks ini, diperlukan solusi Machine Learning (ML) sebagai pendekatan untuk mengatasi permasalahan ini. Penggunaan Machine Learning diharapkan dapat membantu bank mengidentifikasi pola-pola yang sulit dilihat secara manual, meningkatkan pemahaman tentang karakteristik pelanggan yang berpotensi, dan pada gilirannya, meningkatkan efektivitas campaign marketing untuk meningkatkan tingkat konversi nasabah yang membuka deposito berjangka.

Goals

Sebagai Data Scientist dari perusahaan konsultan XYZ, kami ditugaskan oleh klien kami (Bank Portugal) untuk mengidentifikasi faktor-faktor yang mempengaruhi nasabah dalam membuka deposito berjangka. Dengan menggunakan teknik analisis data dan machine learning, kita bertujuan untuk:

- Menganalisis karakteristik demografis dan perilaku transaksi (umur, pekerjaan, status pernikahan, pendidikan, mempunyai kredit atau tidak, mempunyai kpr atau tidak dan mempunyai pinjaman pribadi atau tidak) nasabah yang mempengaruhi keputusan mereka dalam membuka deposito berjangka.
- Menganalisis karakteristik nasabah saat dihubungi dilakukan agen marketing bank (tipe komunikasi, bulan terakhir dihubungi, hari terakhir dihubungi, durasi saat dihubungi) dalam mempengaruhi keputusan mereka untuk membuka deposito berjangka.
- Menganalisis karakteristik nasabah selama campaign marketing yang dilakukan bank (berapa kali dihubungi, jumlah hari setelah terakhir dihubungi dan hasil keputusan dari campaign sebelumnya) dalam mempengaruhi keputusan mereka untuk membuka deposito berjangka.
- Menganalisis karakteristik situasi ekonomi negara portugal (tingkat variasi pekerjaan, indeks harga, indeks kepercayaan konsumen, jumlah karyawan dan suku bunga euro) dalam mempengaruhi keputusan nasabah untuk membuka deposito berjangka.

Berdasarkan masalah diatas, kita akan membangun model prediktif yang dapat mengklasifikasikan nasabah berdasarkan kemungkinan mereka untuk membuka deposito berjangka dengan target recallnya di angka 80%. Selanjutnya kita dapat memberikan insights kepada stakeholders untuk meningkatkan efektivitas campaign marketing Bank Portugal di masa depan.

List of contents:
- Business Context and Problem Statement
- Data Understanding
- Exploratory Data Analysis
- Data Preparation & Feature Engineering
- Machine Learning Model Benchmarking
- Hyperparameter Tuning
- Conclusion and Recommendation

Link Tableau: https://public.tableau.com/app/profile/ferry.hermawan.kristianto/viz/Book11_17021831033800/Dashboard22?publish=yes