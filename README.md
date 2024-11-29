<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Website Sederhana</title>
    <!-- Latest compiled and minified CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Latest compiled JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <!-- font awesome -->
    <script src="https://kit.fontawesome.com/31149d48b0.js" crossorigin="anonymous"></script>
    <style>
        #footer {
            background-color: #000;
            /* Warna latar belakang hitam */
            color: #fff;
            /* Warna teks putih */
            padding: 0px 0;
            /* Padding atas dan bawah */
            text-align: center;
            /* Teks di tengah */
        }

        .social-icons a {
            color: #fff;
            /* Warna ikon putih */
            margin: 0 10px;
            /* Jarak antar ikon */
            font-size: 24px;
            /* Ukuran ikon */
        }

        .social-icons a:hover {
            color: #ccc;
            /* Warna saat hover */
        }

        /* Background colors for each section */
        #home {
            background-color: #3D52A0;
            /* Light gray */
            margin-bottom: 10px;
            /* Jarak bawah */
        }

        #profil {
            background-color: #7091E6;
            /* Slightly darker gray */
            margin-bottom: 10px;
            /* Jarak bawah */
        }

        #galeri {
            background-color: #8697C4;
            /* Even darker gray */
            margin-bottom: 10px;
            /* Jarak bawah */
        }

        #contact {
            background-color: #ADBBDA;
            /* Light blue-gray */
            margin-bottom: 10px;
            /* Jarak bawah */
        }

        /* Tambahkan margin bawah pada navbar */
        .navbar {
            margin-bottom: 40px;
            /* Jarak bawah navbar */
            background-color: #000;
            /* Warna latar belakang hitam */
        }

        .navbar-dark .navbar-nav .nav-link {
            color: #fff;
            /* Warna teks link navbar */
        }

        .navbar-dark .navbar-nav .nav-link:hover {
            color: blue;
            /* Warna teks link saat hover */
        }

        /* Mengubah warna teks di section */
        #home h2,
        #home p,
        #profil h2,
        #profil p,
        #galeri h2,
        #galeri p,
        #contact h1 {
            color: #fff;
            /* Warna teks putih */
        }
    </style>
</head>

<body>
    <div class="container">
        <header>
            <h1>Profile Website</h1>
            <!-- jumbotron -->
            <div class="container mt-3">
                <div class="mt-4 p-5 bg-primary text-white rounded">
                    <h1>Get to Know Dinni Anisyah</h1>
                    <p>I have a strong understanding of social and economic dynamics, and want to leverage this
                        knowledge to create positive change.</p>
                </div>
            </div>

            <nav class="navbar navbar-expand-sm navbar-dark rounded mt-3">
                <div class="container-fluid">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" href="index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="profil.html">Profil</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="galeri.html">Galeri</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="kontak.html">kontak</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </header>

        <section id="home" class="text-center p-5">
            <h2>Home</h2>
            <p>Welcome To Our Profile Website</p>
        </section>

        <section id="profil" class="text-center p-5">
            <h2>Profile</h2>
            <p>Hello, I'm Dinni Annisyah!</p>
            <p>I am Dinni Anisyah, the owner of Toko Ngemil Geh Yu. I am passionate about culinary and want to
                share delicious and satisfying flavors with the community. At Ngemil Geh Yu, we serve high-quality
                dishes with fresh ingredients and authentic flavors. I always strive to learn and grow, presenting new,
                innovative menus and providing a pleasant dining experience for every customer.</p>
        </section>

        <!-- Galeri Section -->
        <section id="galeri" class="text-center p-5">
            <div class="container">
                <h2>Gallery</h2>

                <div class="row">
                    <div class="col-md-4">
                        <img src="1.jpg" class="img-fluid gallery-img" alt="Gambar 1">
                    </div>
                    <div class="col-md-4">
                        <img src="2.jpg" class="img-fluid gallery-img" alt="Gambar 2">
                    </div>
                    <div class="col-md-4">
                        <img src="3.jpg" class="img-fluid gallery-img" alt="Gambar 3">
                    </div>
                    <div class="col-md-4">
                        <img src="4.jpg" class="img-fluid gallery-img" alt="Gambar 4">
                    </div>
                    <div class="col-md-4">
                        <img src="5.jpg" class="img-fluid gallery-img" alt="Gambar 5">
                    </div>
                    <div class="col-md-4">
                        <img src="6.jpg" class="img-fluid gallery-img" alt="Gambar 6">
                    </div>
                    <div class="col-md-4">
                        <img src="7.jpg" class="img-fluid gallery-img" alt="Gambar 7">
                    </div>
                    <div class="col-md-4">
                        <img src="8.jpg" class="img-fluid gallery-img" alt="Gambar 8">
                    </div>
                    <div class="col-md-4">
                        <img src="9.jpg" class="img-fluid gallery-img" alt="Gambar 9">
                    </div>
                    <div class="col-md-4">
                        <img src="10.jpg" class="img-fluid gallery-img" alt="Gambar 10">
                    </div>
                    <div class="col-md-4">
                        <img src="11.jpg" class="img-fluid gallery-img" alt="Gambar 11">
                    </div>

                </div>
            </div>
        </section>
        <!-- contact section-->
        <section id="contact">
            <div class="container mt-3 contactContent">
                <h1 class="text-center">Contact Me</h1>

                <div class="row mt-4">
                    <div class="col-lg-6">
                        <!-- to edit google map goto https://www.embed-map.com type your location, generate html code and copy the html  -->
                        <div style="text-decoration:none; overflow:hidden;max-width:100%;width:500px;height:500px;">
                            <div id="embed-map-display" style="height:100%; width:100%;max-width:100%;"><iframe
                                    style="height:100%;width:100%;border:0;" frameborder="0"
                                    src="https://www.google.com/maps/embed/v1/place?q=cilegon&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8"></iframe>
                            </div><a class="googl-ehtml" href="https://www.bootstrapskins.com/themes"
                                id="get-data-for-map">premium bootstrap themes</a>
                            <style>
                                #embed-map-display img {
                                    max-height: none;
                                    max-width: none !important;
                                    background: none !important;
                                }
                            </style>
                        </div>

                    </div>
                </div>
                <br>
                <div class="col-lg-6">
                    <!-- form fields -->
                    <form>
                        <input type="text" class="form-control form-control-lg" placeholder="Name">
                        <input type="email" class="form-control mt-3" placeholder="Email">
                        <input type="text" class="form-control mt-3" placeholder="Subject">
                        <div class="mb-3 mt-3">
                            <textarea class="form-control" rows="5" id="comment" name="text"
                                placeholder="Project Details"></textarea>
                        </div>
                    </form>
                    <button type="button" class="btn btn-success mt-3">Contact Me</button>
                    <br>
                </div>

            </div>
    </div>
    </section>

    <!-- footer section-->
    <footer id="footer">
        <div class="container-fluid">
            <div class="social-icons mt-4">
                <a href="https://www.facebook.com/" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://www.linkedin.com/" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://www.tiktok.com/" target="_blank"><i class="fab fa-tiktok"></i></a>
            </div>
            <p class="mt-3">&copy; 2024 Dinni Anisyah. All rights reserved.</p>
        </div>
    </footer>
    </div>
</body>

</html>
