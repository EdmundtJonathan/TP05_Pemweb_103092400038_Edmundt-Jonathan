"# TP05_Pemweb_103092400038_Edmundt-Jonathan" 
1. Pengertian Bootstrap
Jelaskan apa itu Bootstrap dan apa kegunaannya!
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik, rapi, dan responsif. Bootstrap menyediakan berbagai komponen dan class siap pakai, seperti tombol, navbar, form, tabel, dan layout, sehingga developer tidak perlu membuat semua desain dari awal menggunakan CSS.

2. Memasang Bootstrap 
Ada beberapa cara untuk mengimpor atau menggunakan Bootstrap pada project. Sebutkan caracaranya!
- Menggunakan CDN (Content Delivery Network), yaitu dengan menambahkan link CSS dan JavaScript Bootstrap dari internet ke dalam file HTML.
- Mengunduh file Bootstrap, yaitu dengan mengunduh file CSS dan JavaScript Bootstrap, kemudian menyimpannya di dalam folder project.
- Menggunakan npm, yaitu memasang Bootstrap melalui Node Package Manager menggunakan perintah npm install bootstrap.
- Menggunakan package manager atau framework, yaitu mengintegrasikan Bootstrap melalui tools pengelolaan project yang mendukung Bootstrap.

3. Grid dan Breakpoint
Jelaskan mengenai class grid dan kegunaan breakpoint! 
Grid adalah sistem tata letak pada Bootstrap yang digunakan untuk mengatur posisi dan ukuran elemen website dalam bentuk baris (row) dan kolom (column). Sistem grid Bootstrap menggunakan 12 kolom sehingga pembagian layout menjadi lebih mudah dan fleksibel.
Breakpoint adalah batas ukuran lebar layar yang digunakan untuk menyesuaikan tampilan website pada berbagai perangkat, seperti HP, tablet, dan komputer. Contoh class breakpoint pada Bootstrap adalah col-sm-, col-md-, col-lg-, col-xl-, dan col-xxl-. Dengan breakpoint, tampilan website dapat menyesuaikan ukuran layar perangkat yang digunakan.

4. Class Bootstrap
   Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya!
Bootstrap menyediakan berbagai class yang dapat digunakan untuk mempermudah pembuatan tampilan website. Contohnya, class container digunakan untuk mengatur wadah konten website, row digunakan untuk membuat baris dalam sistem grid, dan col digunakan untuk membagi layout menjadi beberapa kolom. Selain itu, class btn digunakan untuk membuat tombol, text-center digunakan untuk membuat teks rata tengah, bg-primary digunakan untuk memberikan warna latar belakang biru, dan img-fluid digunakan untuk membuat gambar responsif agar menyesuaikan ukuran layar perangkat.

5. Gambar Responsif
Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar perangkat?
Untuk membuat gambar pada website responsif, dapat menggunakan class img-fluid yang disediakan oleh Bootstrap. Class ini membuat gambar menyesuaikan ukuran wadahnya sehingga tidak melebihi lebar elemen pembungkus dan tetap mempertahankan rasio gambar. Contoh pada HTML: <img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">
