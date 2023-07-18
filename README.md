<!DOCTYPE html>
<html>
<head>
    <title>Web Sitesi</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script src="script.js"></script>
</head>
<body>
    <header>
        <h1>Web Sitesi Başlığı</h1>
        <nav>
            <ul>
                <li><a href="#">Anasayfa</a></li>
                <li><a href="#">Hakkımızda</a></li>
                <li><a href="#">Hizmetler</a></li>
                <li><a href="#">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Hoş Geldiniz!</h2>
            <p>Web sitemize hoş geldiniz. Burada hakkımızda, hizmetlerimiz ve iletişim bilgilerimiz hakkında bilgi bulabilirsiniz.</p>
        </section>
    </main>

    <footer>
        &copy; 2023 Web Sitesi. Tüm hakları saklıdır.
    </footer>
</body>
</html>
/* Genel Stil */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}
