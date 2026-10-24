<!DOCTYPE html>
<html lang="id">
<head>
    <title>PT Anagata Group - Profil Perusahaan</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8fafc;
            color: #334155;
            line-height: 1.6;
        }

        /* HEADER */
        header {
            background-color: #0a192f;
            color: white;
            padding: 25px 0;
            text-align: center;
            border-bottom: 4px solid #0284c7;
        }
        .header-content {
            width: 85%;
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .logo-svg {
            width: 120px;
            height: auto;
            margin-bottom: 10px;
        }
        header h1 {
            font-size: 2.2em;
            letter-spacing: 2px;
            font-weight: 800;
        }
        header .sub-brand {
            color: #38bdf8;
            font-size: 1.1em;
            letter-spacing: 4px;
            font-weight: 700;
        }
        header p {
            font-size: 0.9em;
            color: #cbd5e1;
            margin-top: 5px;
        }

        /* NAVIGASI 3 HALAMAN */
        nav {
            background-color: #1e293b;
            display: flex;
            justify-content: center;
            padding: 12px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        nav a {
            color: #cbd5e1;
            text-decoration: none;
            padding: 8px 22px;
            margin: 0 6px;
            font-weight: 600;
            font-size: 0.95em;
            border-radius: 6px;
            transition: all 0.3s ease;
        }
        nav a:hover, nav a.active {
            background-color: #0284c7;
            color: #ffffff;
            font-weight: bold;
        }

        /* CONTAINER UTAMA */
        .container {
            width: 85%;
            max-width: 900px;
            margin: 35px auto;
        }

        /* CARD PROFIL PERUSAHAAN */
        .profile-card {
            background: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
            border-top: 5px solid #0284c7;
        }
        .section-title {
            color: #0a192f;
            font-size: 1.4em;
            font-weight: 800;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-transform: uppercase;
        }
        .profile-card p {
            font-size: 1em;
            color: #475569;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* HIGHLIGHT BOX */
        .highlight-box {
            background-color: #f1f5f9;
            border-left: 4px solid #0284c7;
            padding: 20px;
            border-radius: 6px;
            margin-top: 25px;
        }
        .highlight-box h3 {
            color: #0a192f;
            font-size: 1.1em;
            margin-bottom: 10px;
        }
        .highlight-box ul {
            list-style: none;
        }
        .highlight-box li {
            padding: 4px 0;
            font-size: 0.95em;
            color: #334155;
        }
        .highlight-box li::before {
            content: "✓ ";
            color: #0284c7;
            font-weight: bold;
        }

        /* KONTAK SECTION */
        .contact-section {
            background: #0a192f;
            color: white;
            padding: 30px 40px;
            border-radius: 12px;
        }
        .contact-section h3 {
            color: #38bdf8;
            margin-bottom: 15px;
            font-size: 1.2em;
        }
        .contact-section p {
            font-size: 0.9em;
            color: #cbd5e1;
            margin-bottom: 6px;
        }

        /* FOOTER */
        footer {
            background-color: #020c1b;
            color: #94a3b8;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 0.85em;
        }
    </style>
</head>
<body>

    <!-- JUDUL HEADER & LOGO -->
    <header>
        <div class="header-content">
            <svg class="logo-svg" viewBox="0 0 300 180" xmlns="http://www.w3.org/2000/svg">
                <polygon points="40,140 105,50 170,140" fill="#38bdf8" />
                <polygon points="100,140 175,20 250,140" fill="#0284c7" />
                <polygon points="175,20 160,45 190,45" fill="#38bdf8" />
                <polygon points="170,140 220,70 270,140" fill="#0a192f" />
            </svg>
            <h1>ANAGATA <span class="sub-brand">GROUP</span></h1>
            <p>IT SERVICES COMPANY — Solusi IT untuk Masa Depan Bisnis Anda</p>
        </div>
    </header>

    <!-- NAVIGASI 3 HALAMAN -->
    <nav>
        <a href="index.html" class="active">Beranda</a>
        <a href="layanan.html">Layanan</a>
        <a href="proyek.html">Paket & Harga</a>
    </nav>

    <main class="container">
        <!-- PROFIL PERUSAHAAN (TENTANG KAMI) -->
        <section class="profile-card">
            <div class="section-title">Tentang Kami</div>
            
            <p><strong>PT Anagata Group</strong> — <em>Driving Digital Excellence, Shaping the Future.</em></p>
            
            <p>Mengusung nama <strong>ANAGATA</strong> dari bahasa Sanskerta yang berarti <em>'masa depan'</em>, kami berfokus membantu para pelaku industri menavigasi era digital dengan percaya diri. Kami menghadirkan solusi teknologi terpadu yang dirancang secara strategis untuk menciptakan bisnis yang lebih efisien, adaptif, dan berdaya saing tinggi.</p>

            <div class="highlight-box">
                <h3>Kenapa Memilih PT Anagata Group ?</h3>
                <ul>
                    <li>Tim Berpengalaman & Profesional</li>
                    <li>Harga Kompetitif & Transparan</li>
                    <li>Support Cepat & Garansi Terjamin</li>
                    <li>Teknologi Terbaru & Scalable</li>
                </ul>
            </div>
        </section>

        <!-- KONTAK PERUSAHAAN -->
        <section class="contact-section">
            <h3>Hubungi Kami</h3>
            <p><strong>PT ANAGATA GROUP - IT Services</strong></p>
            <p><strong>Kantor:</strong> Jl. Jend. Sudirman Kav. 52-53, SCBD, Jakarta Selatan 12190</p>
            <p><strong>Email:</strong> hello@anagatagroup.co.id | <strong>WA:</strong> +62 21 8888 7777</p>
            <p><strong>Website:</strong> www.anagatagroup.co.id</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 PT Anagata Group. Membangun Masa Depan, Hari Ini.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
    <title>PT Anagata Group - Layanan Jasa IT</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8fafc;
            color: #334155;
            line-height: 1.6;
        }
        header {
            background-color: #0a192f;
            color: white;
            padding: 20px 0;
            text-align: center;
            border-bottom: 4px solid #0284c7;
        }
        header h1 {
            font-size: 1.8em;
            letter-spacing: 1px;
        }
        nav {
            background-color: #1e293b;
            display: flex;
            justify-content: center;
            padding: 12px;
        }
        nav a {
            color: #cbd5e1;
            text-decoration: none;
            padding: 8px 22px;
            margin: 0 6px;
            font-weight: 600;
            font-size: 0.95em;
            border-radius: 6px;
        }
        nav a:hover, nav a.active {
            background-color: #0284c7;
            color: #ffffff;
            font-weight: bold;
        }
        .container {
            width: 85%;
            max-width: 900px;
            margin: 35px auto;
        }
        .slide-card {
            background: #ffffff;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.05);
            border-top: 5px solid #0284c7;
        }
        .section-title {
            color: #0a192f;
            font-size: 1.3em;
            font-weight: 800;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            margin-bottom: 25px;
        }
        .service-item {
            background: #f8fafc;
            padding: 18px 20px;
            border-radius: 8px;
            margin-bottom: 15px;
            border-left: 4px solid #0a192f;
        }
        .service-item h3 {
            color: #0a192f;
            font-size: 1.05em;
            margin-bottom: 5px;
        }
        .service-item p {
            font-size: 0.9em;
            color: #64748b;
        }
        footer {
            background-color: #020c1b;
            color: #94a3b8;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 0.85em;
        }
    </style>
</head>
<body>

    <header>
        <h1>PT ANAGATA GROUP</h1>
    </header>

    <nav>
        <a href="index.html">Beranda</a>
        <a href="layanan.html" class="active">Layanan</a>
        <a href="proyek.html">Paket & Harga</a>
    </nav>

    <main class="container">
        <section class="slide-card">
            <div class="section-title">Layanan Jasa IT Kami</div>

            <div class="service-item">
                <h3>01. SOFTWARE DEVELOPMENT</h3>
                <p>Aplikasi Web, Mobile Apps, ERP & Custom System sesuai kebutuhan bisnis Anda.</p>
            </div>

            <div class="service-item">
                <h3>02. IT CONSULTING & STRATEGY</h3>
                <p>Konsultasi transformasi digital & roadmap teknologi bisnis jangka panjang.</p>
            </div>

            <div class="service-item">
                <h3>03. CLOUD & INFRASTRUCTURE</h3>
                <p>Migrasi cloud, manajemen server, & pemeliharaan (maintenance) sistem 24/7.</p>
            </div>

            <div class="service-item">
                <h3>04. CYBERSECURITY</h3>
                <p>Keamanan data, audit sistem, & proteksi penuh dari ancaman siber.</p>
            </div>

            <div class="service-item">
                <h3>05. UI/UX DESIGN & BRANDING</h3>
                <p>Desain modern, user-friendly, & identitas digital profesional.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 PT Anagata Group. Solusi IT Terpadu & Terpercaya.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
    <title>PT Anagata Group - Paket & Harga</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8fafc;
            color: #334155;
            line-height: 1.6;
        }
        header {
            background-color: #0a192f;
            color: white;
            padding: 20px 0;
            text-align: center;
            border-bottom: 4px solid #0284c7;
        }
        header h1 {
            font-size: 1.8em;
            letter-spacing: 1px;
        }
        nav {
            background-color: #1e293b;
            display: flex;
            justify-content: center;
            padding: 12px;
        }
        nav a {
            color: #cbd5e1;
            text-decoration: none;
            padding: 8px 22px;
            margin: 0 6px;
            font-weight: 600;
            font-size: 0.95em;
            border-radius: 6px;
        }
        nav a:hover, nav a.active {
            background-color: #0284c7;
            color: #ffffff;
            font-weight: bold;
        }
        .container {
            width: 85%;
            max-width: 900px;
            margin: 35px auto;
        }
        .slide-card {
            background: #ffffff;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.05);
            border-top: 5px solid #0284c7;
            overflow-x: auto;
        }
        .section-title {
            color: #0a192f;
            font-size: 1.3em;
            font-weight: 800;
            margin-bottom: 5px;
        }
        .section-subtitle {
            font-size: 0.85em;
            color: #64748b;
            margin-bottom: 20px;
        }
        .price-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.82em;
            margin-bottom: 20px;
        }
        .price-table th, .price-table td {
            border: 1px solid #cbd5e1;
            padding: 10px;
            text-align: left;
        }
        .price-table th {
            background-color: #0a192f;
            color: white;
            text-align: center;
        }
        .price-table td.highlight {
            background-color: #fef9c3;
        }
        .sub-desc {
            display: block;
            font-size: 0.85em;
            color: #64748b;
        }
        .notes-box {
            background: #f1f5f9;
            padding: 15px;
            border-radius: 6px;
            font-size: 0.8em;
        }
        .notes-box h4 {
            color: #0a192f;
            margin-bottom: 5px;
        }
        .notes-box ul {
            padding-left: 15px;
        }
        footer {
            background-color: #020c1b;
            color: #94a3b8;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 0.85em;
        }
    </style>
</head>
<body>

    <header>
        <h1>PT ANAGATA GROUP</h1>
    </header>

    <nav>
        <a href="index.html">Beranda</a>
        <a href="layanan.html">Layanan</a>
        <a href="proyek.html" class="active">Paket & Harga</a>
    </nav>

    <main class="container">
        <section class="slide-card">
            <div class="section-title">Paket Layanan Jasa IT</div>
            <div class="section-subtitle">Harga kompetitif & transparan untuk kebutuhan bisnis Anda di Jakarta</div>

            <table class="price-table">
                <thead>
                    <tr>
                        <th>LAYANAN</th>
                        <th>STARTER</th>
                        <th style="background-color: #0284c7;">BUSINESS (Best)</th>
                        <th>ENTERPRISE</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Website Company Profile</strong><span class="sub-desc">(Desain + Domain + Hosting)</span></td>
                        <td><strong>Rp 5 Jt</strong><span class="sub-desc">1 Tahun</span></td>
                        <td class="highlight"><strong>Rp 12 Jt</strong><span class="sub-desc">2 Tahun + SEO</span></td>
                        <td><strong>Custom</strong></td>
                    </tr>
                    <tr>
                        <td><strong>Aplikasi Web Custom</strong><span class="sub-desc">(ERP, CRM, Sistem)</span></td>
                        <td><strong>Rp 15 Jt</strong><span class="sub-desc">Basic</span></td>
                        <td class="highlight"><strong>Rp 35 Jt</strong><span class="sub-desc">Standard + API</span></td>
                        <td><strong>Rp 75 Jt+</strong><span class="sub-desc">Enterprise</span></td>
                    </tr>
                    <tr>
                        <td><strong>Mobile Apps (Android/iOS)</strong></td>
                        <td><strong>Rp 25 Jt</strong><span class="sub-desc">Basic</span></td>
                        <td class="highlight"><strong>Rp 45 Jt</strong><span class="sub-desc">1 Platform</span></td>
                        <td><strong>Rp 90 Jt+</strong><span class="sub-desc">2 Platform</span></td>
                    </tr>
                    <tr>
                        <td><strong>IT Maintenance</strong><span class="sub-desc">(Support & Server)</span></td>
                        <td><strong>Rp 2 Jt/bln</strong><span class="sub-desc">8x5</span></td>
                        <td class="highlight"><strong>Rp 5 Jt/bln</strong><span class="sub-desc">24/7 + SLA</span></td>
                        <td><strong>Rp 10 Jt/bln</strong><span class="sub-desc">Dedicated</span></td>
                    </tr>
                    <tr>
                        <td><strong>Konsultasi IT</strong></td>
                        <td><strong>Free 1 Jam</strong></td>
                        <td class="highlight"><strong>Rp 1 Jt / sesi</strong></td>
                        <td><strong>Retainer</strong></td>
                    </tr>
                </tbody>
            </table>

            <div class="notes-box">
                <h4>CATATAN PENTING:</h4>
                <ul>
                    <li>Harga di atas adalah estimasi untuk wilayah Jakarta. Harga final setelah analisa kebutuhan.</li>
                    <li>Free konsultasi awal & garansi bug 3 bulan untuk semua paket Business & Enterprise.</li>
                    <li>Support cepat via WhatsApp & Email, SLA 24 jam.</li>
                    <li>Harga belum termasuk PPN 11%.</li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 PT Anagata Group. Solusi IT untuk Masa Depan Bisnis Anda.</p>
    </footer>

</body>
</html>
