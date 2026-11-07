# Day-1-Hitman-Absolution_Sakti_Araffi_Hadi_Kustanto

Sakti Araffi Hadi Kustanto. Repository milik Sakti Araffi. Repository ini digunakan untuk menyimpan catatan dan rangkuman materi kegiatan workshop TIK pada Day 1. Dalam workshop ini, materi yang dipelajari adalah Prompt Engineering serta penggunaan Git dan GitHub untuk mengelola perubahan dan menyimpan proyek secara daring. Prompt Engineering membahas cara memberikan instruksi kepada AI agar hasil yang diberikan lebih sesuai dengan kebutuhan. Sementara itu, Git dan GitHub membantu proses pencatatan perubahan, penyimpanan repository, dan kolaborasi dalam pengerjaan proyek.

## Peran dan konteks

Prompt yang baik perlu memberikan peran dan konteks yang jelas kepada AI. Berdasarkan contoh pada materi workshop, AI dapat diberi peran sebagai pihak yang membantu membuat aplikasi web sederhana berupa *student task planner* untuk mahasiswa tahun pertama. Aplikasi tersebut ditujukan untuk membantu pengguna mencatat tugas dan mengingat tenggat waktu.

## Goal atau tugas

Membuat aplikasi *student task planner* yang membantu mahasiswa tahun pertama mengelola daftar tugas, mengetahui batas waktu pengumpulan, serta melihat status penyelesaian setiap tugas.

## Requirements

* Menampilkan daftar contoh tugas atau assignment.
* Setiap tugas memuat judul, tanggal tenggat, dan status penyelesaian.
* Pengguna dapat menandai tugas yang sudah selesai.
* Menyediakan penyaring daftar tugas berdasarkan kategori semua tugas, tugas yang belum selesai, dan tugas yang sudah selesai.
* Menggunakan tampilan yang sederhana, mudah dibaca, dan responsif.

## Constraints

* Menggunakan HTML, CSS, dan JavaScript tanpa framework tambahan (*vanilla JavaScript*).
* Membuat implementasi yang sederhana agar mudah dipahami oleh pemula.
* Menghindari penggunaan library dan ketergantungan eksternal yang tidak diperlukan.
* Menyusun kode dengan rapi serta menjelaskan fungsi setiap file.

## Output atau format

AI diminta memberikan kode lengkap untuk setiap file, menjelaskan cara menjalankan aplikasi, dan menerangkan cara menguji fungsi utama yang tersedia. Hasil aplikasi tidak boleh dinyatakan berhasil sebelum perilakunya benar-benar diperiksa.

## Keuntungan dari prompt engineering (rekayasa prompt)

1. Membantu meningkatkan performa model AI sehingga jawaban yang dihasilkan lebih sesuai dengan kebutuhan.
2. Membantu mengurangi bias dan respons yang bersifat ofensif.
3. Memberikan kontrol yang lebih baik terhadap hasil serta membuat respons AI lebih mudah diarahkan.
4. Membantu menghasilkan pengalaman penggunaan AI yang lebih baik.

## Git

Git merupakan *version control system* atau sistem pengontrol versi yang digunakan untuk mencatat perubahan pada file atau proyek. Dengan Git, pengguna dapat mengetahui perubahan yang dilakukan, waktu perubahan, dan pihak yang melakukannya. Materi workshop juga menjelaskan bahwa Git dikembangkan oleh Linus Torvalds pada tahun 2005.

## Git workflow

1. **Git directory** merupakan bagian tempat Git menyimpan metadata dan basis data objek suatu proyek. Informasi ini digunakan Git untuk mengelola riwayat perubahan proyek.
2. **Staging area** merupakan tempat untuk menyiapkan perubahan yang akan dimasukkan ke dalam *commit* berikutnya. Pada tahap ini, pengguna menentukan file atau perubahan yang akan disimpan.
3. **Working directory/tree** merupakan salinan proyek yang sedang dikerjakan di komputer. File di dalamnya dapat dibuka, digunakan, dan diubah oleh pengguna.

## git vs github

Git adalah sistem pengontrol versi yang digunakan untuk melacak dan mengelola perubahan proyek secara lokal. GitHub adalah platform berbasis web yang digunakan untuk menyimpan repository Git secara daring serta mendukung kolaborasi. Dengan demikian, Git membantu mencatat perubahan proyek, sedangkan GitHub menjadi tempat untuk menyimpan dan membagikan repository tersebut secara online.

## Perintah Dasar Git (Essential Git Commands)

Berikut beberapa perintah dasar yang digunakan untuk mengelola proyek melalui Git di komputer lokal:

1. `git init`: Membuat atau menginisialisasi repository Git baru pada folder proyek.
2. `git add .`: Memasukkan perubahan file di dalam folder proyek ke *staging area* agar siap disimpan.
3. `git commit -m "pesan"`: Menyimpan perubahan yang sudah berada di *staging area* ke dalam riwayat Git dengan disertai pesan atau keterangan perubahan.

## Perintah Git ke GitHub (Remote Commands)

Perintah berikut digunakan dalam proses menghubungkan repository lokal dengan GitHub dan melakukan pertukaran perubahan:

1. `git remote add <name> <url>`: Menambahkan alamat repository jarak jauh (*remote repository*) agar repository lokal dapat terhubung dengan repository di GitHub.
2. `git push origin main`: Mengirim *commit* dari branch `main` pada komputer lokal ke repository GitHub.
3. `git pull origin main`: Mengambil perubahan terbaru dari branch `main` di GitHub dan menggabungkannya ke branch lokal yang sedang digunakan.

## Pendapat Pribadi tentang Day 1 Proyek Workshop

Menurut saya, kegiatan workshop Day 1 memberikan pengetahuan baru mengenai cara menggunakan AI dengan instruksi yang lebih terarah melalui Prompt Engineering. Selain itu, saya menjadi lebih memahami fungsi Git dan GitHub dalam mencatat perubahan serta menyimpan proyek secara daring. Materi dan praktik yang diberikan bermanfaat sebagai bekal untuk membuat, mengelola, dan mendokumentasikan proyek dengan lebih terstruktur.
