# Lab 6 Web

## Nama   : Luthfi Al Ridwan
## NIM    : 312010112
## Kelas  : TI.20.A.1
## Matkul : Pemrograman Web

## 1. Membuat struktur dasar dokumen HTML
Berikut adalah contoh struktur dasar HTML menggunakan framework Bootstrap :

      <!doctype html>
      <html lang="en">
        <head>
          <!-- Required meta tags -->
          <meta charset="utf-8">
          <meta name="viewport" content="width=device-width, initial-scale=1">

          <!-- Bootstrap CSS -->
          <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

          <title>CSS Framework</title>
        </head>
        <body>
          <!-- Optional JavaScript; choose one of the two! -->

          <!-- Option 1: Bootstrap Bundle with Popper -->
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

          <!-- Option 2: Separate Popper and Bootstrap JS -->
          <!--
          <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
          -->
        </body>
      </html>
      
      
      
# 2. Membuat Container
Container berfungsi untuk membungkus blok di dalamnya, sehingga terlihat rapi terhadap ukuran layar. Berikut adalah code nya :

      <!-- Container -->
          <div class="container">

          </div>
          
          
# 3. Membuat Card
Card adalah sebuah container yang fleksibel untuk content. Berikut adalah code nya :

      <div class="container shadow-lg">
        <div class="card-body">
          <h1 class="text-muted py-3">
            Web Pemrograman
            <img src="img/upb.png" class="card-img-top rounded-circle" alt="upb" style="width: 100px" />
          </h1>
        </div>
      </div>
          
Berikut adalah tampilan nya :
 
![1 - Membuat Card](https://user-images.githubusercontent.com/73066008/164877778-40bc1eba-64c2-459f-a387-1c614935792f.png)
 
# 4. Membuat Navigasi
Navbar atau navigasi bar merupakan salah satu element pada HTML yang dibuat untuk mempresentasikan link navigasi. Berikut adalah code nya :

       <nav class="navbar-container-md" style="background-color: #1f5faa">
              <ul class="nav nav-pills">
                <li class="nav-item">
                  <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">Article</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-light" href="#">Contact</a>
                </li>
              </ul>
            </nav>
            
Berikut adalah tampilan nya : 

![2 - Membuat Navigasi](https://user-images.githubusercontent.com/73066008/164877782-33f34be2-c025-419b-9414-801e36bf7709.png)

# 5. Membuat Card section description
Selanjutnya membuat card body dengan isi section description atau isi konten deskripsi tertentu. Berikut adalah code nya :

       <div class="card" style="width: 80, 1rem; padding: 50px 20px; background-color: #e4e4e5; border-radius: 0">
              <div class="card-body">
                <h1 class="card-title pb-4" style="font-weight: bold">Layout sederhana</h1>
                <p class="card-text">Ini adalah contoh layout sederhana menggunakan bootstrap pada mata kuliah Pemrograman Web.</p>
              </div>
            </div>
            
Berikut adalah tampilan nya :

![3 - Membuat Card Section](https://user-images.githubusercontent.com/73066008/164877784-e6718d26-f247-4578-b3dc-6b90ad26ad38.png)

# 6. Membuat (Card 1, Card 2, Card 3) dan Widget dengan Grid Row dan Col
Menambahkan Card 1, Card 2 dan Card 3 dengan menggunakan grid row dan col dan juga menggunakan beberapa class dalam bootstrap. Berikut adalah code nya :

       <!-- Row Content 1 -->
            <div class="row">
              <!-- card 1 -->
              <div class="col-3">
                <div class="col mt-4">
                  <div class="card" style="width: 18rem; border: 0">
                    <img src="img/html.png" class="card-img-top rounded-circle" alt="html" style="width: 200px" />
                    <div class="card-body">
                      <h5 class="card-title">HTML</h5>
                      <p class="card-text">Hypertext Markup Language adalah bahasa markah standar untuk dokumen yang dirancang untuk ditampilkan di peramban internet.</p>
                      <a href="#" class="btn btn-primary">View detail</a>
                    </div>
                  </div>
                </div>
              </div>
              
              <!-- card 2 -->
              <div class="col-3">
                <div class="col mt-4">
                  <div class="card" style="width: 18rem; border: 0">
                    <img src="img/css.png" class="card-img-top rounded-circle" alt="css" style="width: 200px" />
                    <div class="card-body">
                      <h5 class="card-title">CSS</h5>
                      <p class="card-text">Cascading Style Sheet merupakan aturan untuk mengatur beberapa komponen dalam sebuah web sehingga akan lebih terstruktur.</p>
                      <a href="#" class="btn btn-primary">View detail</a>
                    </div>
                  </div>
                </div>
              </div>
              
              <!-- card 3 -->
              <div class="col-3">
                <div class="col mt-4">
                  <div class="card" style="width: 18rem; border: 0">
                    <img src="img/js.png" class="card-img-top rounded-circle" alt="js" style="width: 200px" />
                    <div class="card-body">
                      <h5 class="card-title">Javascript</h5>
                      <p class="card-text">
                        JavaScript adalah bahasa pemrograman tingkat tinggi dan dinamis. JavaScript populer di internet dan dapat bekerja di sebagian besar penjelajah web populer seperti Google Chrome, Internet Explorer, Mozilla Firefox, Netscape
                        dan Opera.
                      </p>
                      <a href="#" class="btn btn-primary">View detail</a>
                    </div>
                  </div>
                </div>
              </div>

Berikut adalah tempilan nya : 

![4 - Membuat Card 1, 2 dan 3](https://user-images.githubusercontent.com/73066008/164877785-ae25e47f-9bc5-4e38-97b7-cec9cfa184a8.png)

# Widget Header
Widget adalah item yang ditambahkan ke sidebar pada suatu halaman web. Berikut adalah code nya :

       <!-- Widget Header -->
              <div class="col-3">
                <div class="list-group my-4" style="border-radius: 0">
                  <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold"> Daftar Situs </a>
                  <a href="www.ecampus.pelitabangsa.ac.id" class="list-group-item list-group-item-action">E-Campus</a>
                  <a href="www.google.com" class="list-group-item list-group-item-action">Google</a>
                  <a href="www.getbootstrap.com" class="list-group-item list-group-item-action">Bootstrap</a>
                  <a href="www.github.com" class="list-group-item list-group-item-action">Github</a>
                  <a href="www.youtube.com" class="list-group-item list-group-item-action">Youtube</a>
                </div>
 
 # Widget Teks
 
        <!-- Widget Text -->
                <div class="list-group my-4" style="border-radius: 0; border: 1px #eee">
                  <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold"> Pemrograman Web </a>
                  <a href="#" class="list-group-item list-group-item-action">
                    <p>Pemrograman web adalah proses pembuatan instruksi-instruksi untuk menciptakan program/aplikasi berbasis internet yang dapat diakses melalui browser.</p>
                  </a>
                </div>
              </div>
            </div>
            
Berikut adalah tampilan nya :

![5 - Membuat Widget Header dan Widget Teks](https://user-images.githubusercontent.com/73066008/164877788-81ad6f1c-361a-4a8d-a42c-c68501acd701.png)

# Membuat Row Content ( Section 1 dan 2 )
Lalu tambahkan section 1 dan 2 dibungkus row dan juga col. Berikut adalah code nya :

      <!-- Row Content 2 -->
            <div class="row">
             
             <!-- Section 1 -->
              <div class="col-8-md">
                <div class="card mb-3" style="width: 900px; height: 200px; border: 0">
                  <div class="row g-0">
                    <div class="col-md-4">
                      <img src="img/upb1.jpg" class="img-fluid rounded-start" alt="..." />
                    </div>
                    <div class="col-md-8">
                      <div class="card-body">
                        <h2 class="card-title" style="font-weight: bold">Universitas Pelita Bangsa</h2>
                        <p class="card-text" style="text-align: left">
                          Universitas Pelita Bangsa (UPB) merupakan perguruan tinggi baru hasil perubahan bentuk dari penggabungan antara Sekolah Tinggi Ilmu Ekonomi (STIE) dan Sekolah Tinggi Teknik (STT) sesuai dengan Surat Keputusan Menteri
                          Pendidikan Nasional Republik Indonesia Nomor : 664/KPTI/I/2019 tanggal 2 Agustus 2019.
                        </p>
                        <p class="card-text"><small class="text-muted"></small></p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <!-- Row Content 3 -->
            <div class="row">
             
             <!-- Section 2 -->
              <div class="col-8-lg me-5">
                <div class="card mb-3" style="width: 900px; height: 200px; border: 0">
                  <div class="row g-0">
                    <div class="col-md-8">
                      <div class="card-body">
                        <h2 class="card-title" style="font-weight: bold">Motto Universitas Pelita Bangsa</h2>
                        <p class="card-text">
                          Motto Universitas Pelita Bangsa adalah MEGAH yang bermaksud :<br />
                          M : Moral tinggi<br />
                          E : Entrepreneur<br />
                          G : Gigih dalam berkarya<br />
                          A : Ahli di bidangnya<br />
                          H : Harapan bangsa
                        </p>
                        <p class="card-text"><small class="text-muted"></small></p>
                      </div>
                    </div>
                    <div class="col-md-4">
                      <img src="img/upb2.jpg" class="img-fluid rounded-start" alt="picture" width="250" />
                    </div>
                  </div>
                </div>
              </div>
            </div>

Berikut adalah tampilan nya :

![6 - Membuat Row Content (Section 1 dan 2)](https://user-images.githubusercontent.com/73066008/164878933-bc010add-05c6-4e1d-8b6b-038e0ed99103.png)

# 7. Membuat Card Footer
Selanjutnya membuat card footer yaitu elemen struktural yang digunakan untuk mengidentifikasi bagian catatan kaki sebuah halaman web. Berikut adalah code nya :

       <div class="card-footer text-center" style="background-color: #1d1d1d; color: #eee">
              <p>© 2022 - Universitas Pelita Bangsa</p>
            </div>

Berikut adalah tampilan nya :

![7 - Membuat Card Footer](https://user-images.githubusercontent.com/73066008/164878936-7f528273-d24c-4048-a29f-64d74d94148e.png)
