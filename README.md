<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glasses Store</title>
  <link rel="stylesheet" href="./style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
</head>
<body>
    <div div class="navbar">
        <p>Achetez Meti au 20 rue des Martyrs Paris 9</p>
    </div>
<nav>
    <div class="nav_block">
        <div class="container_nav_screen">
            <div class="nav_section">
                 <div class="nav_section-left disFlex">
                <div class="nav_link">
                    <a href="">Optiques</a>
                </div>
                <div class="nav_link">
                    <a href="">Solries</a>
                </div>
                <div class="nav_link">
                    <a href="">Voir Juste</a>
                </div>
                </div>
                <div class="nav_section-right disFlex">
                <div class="nav_link">
                    <a href="">Wishlist</a>
                </div>
                <div class="nav_link">
                    <a href="">Examen de vue</a>
                </div>
                <div class="nav_link"><a href="">Panier</a>
                </div>
            </div>
            </div>
            <div class="nav_center disFlex">
                <h1 class="first_header" >VOIR JUSTE</h1>
                <button class="first_btn">
                    <p class="text_btn">Nos meilleures ventes</p>
                </button>
            </div>
        </div>
    </div>
</nav>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto';
    text-decoration: none;
}

.container {
    max-width: 1024px;
    margin: 0 auto;
}

.navbar {
    font-size: 12px;
    font-weight: 400;
    text-align: center;
    align-items: center;
    color: #1A1818;
    text-transform: uppercase;
    padding: 8px 0;
}

.disFlex {
    display: flex;
}

.container_nav_screen {
    display: flex;
    flex-direction: column;
    height: 100vh;
}

.nav_block {
    background-color: #5A5250;
    padding: 1%;
}

.nav_section {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-transform: uppercase;
    color: #1A1818;
    mix-blend-mode: multiply;
}

.nav_section-left {
    justify-content: flex-start;
    gap: 18px;
    margin-left: 5%;
}

.nav_section-right {
    justify-content: flex-end;
    gap: 18px;
    margin-right: 2%;
}

.nav_center {
    flex-direction: column;
    align-items: center;
    flex-grow: 1;
    justify-content: center;
    color: #FFFFFF;
}

.first_header {
    font-size: 54px;
    font-weight: 400;
    line-height: 60.75px;
}

.first_btn {
    flex-direction: row;
    border: none;
    border-radius: 30px;
    background: #A05B4E;
    margin: 26px;
}

.text_btn {
    font-size: 12px;
    font-weight: 400;
    line-height: 14.4px;
    letter-spacing: 0.6000000238418579px;
    padding: 13px 21px 12px 21px;
    color: #FFFFFF;
    text-transform: uppercase;
}
