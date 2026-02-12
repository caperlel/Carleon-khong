<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Carleon Khong</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #00c9c8, #0097a7);
            color: #fff;
            margin: 0;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 20px;
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
        }

        nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            transition: 0.3s;
        }

        nav a:hover {
            color: #002f34;
        }

        /* Hero */
        .hero {
            padding: 80px 0;
            text-align: center;
        }

        .hero img {
            width: 180px;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-weight: 700;
            font-size: 42px;
        }

        .hero span {
            color: #002f34;
        }

        /* Glass Card */
        .card-modern {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(15px);
            border: none;
            border-radius: 20px;
            padding: 40px;
            transition: 0.3s;
        }

        .card-modern:hover {
            transform: translateY(-10px);
            background: rgba(255,255,255,0.2);
        }

        /* Projects */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            font-weight: 600;
            border: 2px dashed rgba(255,255,255,0.5);
            transition: 0.4s;
        }

        .project-card:hover {
            background: rgba(255,255,255,0.3);
            border: 2px solid #00ffff;
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0,255,255,0.4);
        }

        .project-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 15px;
            margin-bottom: 15px;
        }

        .project-card h5 {
            margin-bottom: 8px;
            font-weight: 700;
        }

        .project-card p {
            font-size: 0.9rem;
            color: #e0f7fa;
        }

        /* Footer */
        .footer-modern {
            margin-top: 80px;
            background: rgba(0,0,0,0.25);
            backdrop-filter: blur(20px);
        }

        .footer-modern p {
            opacity: 0.85;
        }

        .social-icons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            margin: 0 8px;
            border-radius: 50%;
            background: rgba(255,255,255,0.15);
            color: white;
            font-size: 20px;
            transition: 0.3s;
            text-decoration: none;
        }

        .social-icons a:hover {
            background: #00ffff;
            color: #002f34;
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,255,255,0.5);
        }

        .copyright {
            background: rgba(0,0,0,0.4);
            font-size: 14px;
        }
    </style>
</head>

<body>

<!-- Navbar -->
<header>
    <nav>
        <a href="#">Beranda</a>
        <a href="#about">Tentang Saya</a>
        <a href="#projects">Project</a>
        <a href="#contact">Kontak</a>
    </nav>
</header>

<!-- Hero -->
<section class="hero container">
    <img src="xd/Screenshot 2026-02-12 153124.png" alt="Koenigsegg Gemera">
    <h1>Portfolio</h1>
    <h2><span>Carleon</span> Khong</h2>
    <p>Freelance Web Developer</p>
</section>

<!-- About -->
<section id="about" class="container mb-5">
    <div class="card-modern text-center">
        <h3 class="mb-3">Tentang Saya</h3>
        <p>
            Saya adalah seorang profesional di bidang Web Development dengan pengalaman lebih dari 2 tahun.
            Memiliki keahlian utama dalam HTML, CSS, JavaScript dan UI/UX.
            Saya berkomitmen menghadirkan solusi kreatif dan efisien di setiap proyek.
        </p>
    </div>
</section>

<!-- Projects -->
<section id="projects" class="container py-5">
    <h3 class="text-center mb-5 fw-bold">Project Saya</h3>
    <div class="projects-grid">
        <div class="project-card">
            <img src="xd/download.jpg" alt="Project 1" class="project-img">
            <h5>Project 1</h5>
            <p>Website company profile modern dan responsif.</p>
        </div>
        <div class="project-card">
            <img src="xd/Screenshot 2026-02-12 150356.png" alt="Project 2" class="project-img">
            <h5>Project 2</h5>
            <p>Desain UI/UX untuk aplikasi mobile.</p>
        </div>
        <div class="project-card">
            <img src="xd/download (1).jpg" alt="Project 3" class="project-img">
            <h5>Project 3</h5>
            <p>Toko online dengan sistem pembayaran terintegrasi.</p>
        </div>
        <div class="project-card">
            <img src="xd/images.jpg" alt="Project 4" class="project-img">
            <h5>Project 4</h5>
            <p>Dashboard analitik untuk data perusahaan.</p>
        </div>
        <div class="project-card">
            <img src="xd/download (2).jpg" alt="Project 5" class="project-img">
            <h5>Project 5</h5>
            <p>Portfolio interaktif dengan animasi modern.</p>
        </div>
        <div class="project-card">
            <img src="xd/download (3).jpg" alt="Project 6" class="project-img">
            <h5>Project 6</h5>
            <p>Landing page kreatif untuk kampanye produk.</p>
        </div>
    </div>
</section>

<!-- Footer -->
<footer id="contact" class="footer-modern">
    <div class="container py-5">
        <div class="row text-center text-md-start">

            <div class="col-md-4 mb-4">
                <h5 class="fw-bold mb-3">Carleon Khong</h5>
                <p>
                    Freelance Web Developer yang berfokus pada pembuatan website modern,
                    responsive, dan user-friendly.
                </p>
            </div>

            <div class="col-md-4 mb-4">
                <h5 class="fw-bold mb-3">Kontak</h5>
                <p><i class="bi bi-whatsapp"></i> 0923 xxxx xxxx</p>
                <p><i class="bi bi-envelope-fill"></i> overtime.std@gmail.com</p>
                <p><i class="bi bi-geo-alt-fill"></i> Jl. Jalan Santai Tapi Sampai</p>
            </div>

            <div class="col-md-4 mb-4 text-center">
                <h5 class="fw-bold mb-3">Sosial Media</h5>
                <div class="social-icons">
                    <a href="#"><i class="bi bi-instagram"></i></a>
                    <a href="#"><i class="bi bi-facebook"></i></a>
                    <a href="#"><i class="bi bi-github"></i></a>
                </div>
            </div>

        </div>
    </div>

    <div class="text-center py-3 copyright">
        © 2026 Carleon Khong | All Rights Reserved
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
