# andi-setiawan.github.io/
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nama Anda | Portofolio Pengembang</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Nama Anda</div>
            <ul>
                <li><a href="#about">Tentang Saya</a></li>
                <li><a href="#projects">Proyek</a></li>
                <li><a href="#skills">Keahlian</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <div class="hero-content">
                <h1>Halo, saya [Nama Anda]</h1>
                <p>Seorang [Peran Anda, misal: Pengembang Perangkat Lunak] dengan fokus pada [Teknologi/Bidang Anda].</p>
                <a href="#projects" class="btn-primary">Lihat Proyek Saya</a>
            </div>
            <div class="hero-image">
                <img src="images/profile.jpg" alt="Foto Profil Anda">
            </div>
        </section>

        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Saya adalah seorang [peran Anda] yang antusias dengan [minat Anda, misal: membangun solusi web yang inovatif dan efisien]. Dengan pengalaman selama [jumlah] tahun di bidang [bidang Anda, misal: pengembangan full-stack], saya memiliki keahlian dalam [sebutkan keahlian utama, misal: JavaScript, React, Node.js, dan database SQL/NoSQL].</p>
            <p>Saya percaya pada [filosofi kerja Anda, misal: kode yang bersih, pembelajaran berkelanjutan, dan kolaborasi tim].</p>
            <a href="https://www.linkedin.com/in/yourlinkedinprofile/" target="_blank" class="btn-secondary"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="https://github.com/yourusername" target="_blank" class="btn-secondary"><i class="fab fa-github"></i> GitHub</a>
        </section>

        <section id="projects">
            <h2>Proyek</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Nama Proyek 1</h3>
                    <img src="images/project1-thumbnail.jpg" alt="Thumbnail Proyek 1">
                    <p>Deskripsi singkat proyek ini. Apa yang Anda lakukan dan teknologi yang digunakan.</p>
                    <div class="project-links">
                        <a href="https://github.com/yourusername/project-repo-1" target="_blank"><i class="fab fa-github"></i> Kode</a>
                        <a href="https://yourusername.github.io/project-repo-1-demo/" target="_blank"><i class="fas fa-external-link-alt"></i> Demo Langsung</a>
                    </div>
                </div>
                <div class="project-card">
                    <h3>Nama Proyek 2</h3>
                    <img src="images/project2-thumbnail.jpg" alt="Thumbnail Proyek 2">
                    <p>Deskripsi singkat proyek ini. Apa yang Anda lakukan dan teknologi yang digunakan.</p>
                    <div class="project-links">
                        <a href="https://github.com/yourusername/project-repo-2" target="_blank"><i class="fab fa-github"></i> Kode</a>
                        </div>
                </div>
                </div>
        </section>

        <section id="skills">
            <h2>Keahlian</h2>
            <div class="skills-category">
                <h3>Bahasa Pemrograman</h3>
                <ul>
                    <li><i class="fab fa-js-square"></i> JavaScript</li>
                    <li><i class="fab fa-python"></i> Python</li>
                    <li><i class="fab fa-java"></i> Java</li>
                    </ul>
            </div>
            <div class="skills-category">
                <h3>Framework & Library</h3>
                <ul>
                    <li><i class="fab fa-react"></i> React.js</li>
                    <li><i class="fab fa-node-js"></i> Node.js (Express)</li>
                    <li><i class="fab fa-html5"></i> HTML & CSS</li>
                    </ul>
            </div>
            <div class="skills-category">
                <h3>Tools & Platform</h3>
                <ul>
                    <li><i class="fab fa-git-alt"></i> Git & GitHub</li>
                    <li><i class="fab fa-docker"></i> Docker</li>
                    <li><i class="fas fa-database"></i> PostgreSQL, MongoDB</li>
                    </ul>
            </div>
        </section>

        <section id="contact">
            <h2>Hubungi Saya</h2>
            <p>Tertarik untuk berkolaborasi atau memiliki pertanyaan? Jangan ragu untuk menghubungi saya!</p>
            <div class="contact-links">
                <a href="mailto:your.email@example.com"><i class="fas fa-envelope"></i> your.email@example.com</a>
                <a href="https://www.linkedin.com/in/yourlinkedinprofile/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Nama Anda. Hak Cipta Dilindungi.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
4. Contoh Kode: style.css Dasar
File: css/style.css

CSS

/* General Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    padding: 0;
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
    max-width: 1000px;
    margin: auto;
}

section {
    padding: 40px 0;
    border-bottom: 1px solid #ddd;
}

section:last-child {
    border-bottom: none;
}

h1, h2 {
    color: #333;
    text-align: center;
    margin-bottom: 30px;
}

.btn-primary, .btn-secondary {
    display: inline-block;
    background: #007bff;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    transition: background 0.3s ease;
}

.btn-secondary {
    background: #6c757d;
    margin-right: 10px;
}

.btn-primary:hover, .btn-secondary:hover {
    background: #0056b3;
}

/* Hero Section */
#hero {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
    text-align: left;
    flex-wrap: wrap;
}

#hero .hero-content {
    max-width: 600px;
}

#hero .hero-image img {
    max-width: 250px;
    border-radius: 50%;
    border: 5px solid #007bff;
}

/* Projects Section */
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.project-card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project-card img {
    max-width: 100%;
    border-radius: 5px;
    margin-bottom: 15px;
}

.project-card h3 {
    margin-top: 0;
    color: #007bff;
}

.project-links a {
    margin: 0 10px;
    color: #007bff;
    text-decoration: none;
}

.project-links a:hover {
    text-decoration: underline;
}

/* Skills Section */
.skills-category {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 20px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

.skills-category ul {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
}

.skills-category ul li {
    background: #e9e9e9;
    padding: 8px 15px;
    border-radius: 20px;
    font-size: 0.9em;
    display: flex;
    align-items: center;
    gap: 5px;
}

.skills-category h3 {
    text-align: center;
    color: #555;
    margin-bottom: 20px;
}

/* Contact Section */
.contact-links {
    text-align: center;
    margin-top: 20px;
}

.contact-links a {
    display: inline-block;
    margin: 0 15px;
    color: #007bff;
    text-decoration: none;
    font-size: 1.1em;
}

.contact-links a:hover {
    text-decoration: underline;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
    margin-top: 40px;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin-bottom: 10px;
    }

    #hero {
