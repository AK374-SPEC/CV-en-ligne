# CV-en-ligne
Projet de CV en ligne. Contient un fichier HTML, un fichier CSS pour le style, et une image de profil.

/* Fichier CSS pour le CV en ligne */

body {
    font-family: 'Lato', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

.cv-container {
    max-width: 800px;
    margin: 20px auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

header {
    text-align: center;
    margin-bottom: 20px;
}

header .photo-container {
    width: 120px;
    height: 120px;
    margin: 0 auto 10px;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

header .photo-container img {
    width: 100%;
    height: auto;
}

header h1 {
    font-size: 24px;
    margin: 10px 0;
}

header h2 {
    font-size: 18px;
    font-weight: 400;
    color: #666;
    margin-bottom: 10px;
}

header .contact a {
    text-decoration: none;
    color: #007bff;
    margin: 0 5px;
}

header .contact a:hover {
    text-decoration: underline;
}

section {
    margin-bottom: 20px;
}

section h3 {
    font-size: 20px;
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
    margin-bottom: 10px;
}

section ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

section ul li {
    margin: 5px 0;
}

footer {
    text-align: center;
    margin-top: 20px;
    font-size: 14px;
    color: #666;
}
