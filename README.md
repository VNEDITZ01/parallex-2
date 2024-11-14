<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h2 class="logo">Logo</h2>
        <nav class="navigation">
            <a href="#" class="active">Home</a>
            <a href="#">About</a>
            <a href="#">Service</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    

    <section class="Parallax">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\hill1.png" id="hill1" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\hill2.png" id="hill2" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\hill3.png" id="hill3" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\hill4.png" id="hill4" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\hill5.png" id="hill5" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\tree.png" id="tree" alt="#">
        <h2 id="text">AMAZON FOREST</h2>
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\leaf.png" id="leaf" alt="#">
        <img src="c:\Users\Hp\OneDrive\Desktop\coding\Start Project Parallax Scrolling Website\plant.png" id="plant" alt="#">
    </section>

    <section class="sec">
        <h2>Parallax Scrolling Website</h2>
        <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.<br><br>

            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.<br><br>
            
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.<br><br>

            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis, eaque! Quod consectetur veniam pariatur, provident similique nam at odit perferendis tempora sunt eius, facilis quaerat nulla nemo voluptas hic quisquam.<br><br>
        </p>
    </section>

    <script src="script.js"></script>
</body>
</html>


  css

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    min-height: 100vh;
    background: #f9f9f9;
    overflow-x: hidden;
}

header {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    padding: 30px 100px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    z-index: 100;
}

.logo {
    font-size: 2em;
    color: #359381;
    font-weight: 600;
    margin-right: 400px;
}

.navigation a {
    text-decoration: none;
    color: #359381;
    padding: 6px 15px;
    border-radius: 20px;
    margin: 0px 10px;
    font-weight: 600;
}

.navigation a:hover, .navigation a.active {
    background: #359381;
    color: white;
}

.Parallax {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden; /* Hide overflow */
}

#text {
    position: absolute;
    font-size: 5em;
    color: #fff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    
}

.Parallax img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    pointer-events: none;
}

.sec {
    position: relative;
    background: #003329;
    padding: 100px;
}

.sec h2 {
    font-size: 3em;
    color: white;
}

.sec p {
    font-size: 1em;
    color: #fff;
    font-weight: 300;
}


js
document.addEventListener('DOMContentLoaded', () => {
    let text = document.getElementById('text'); 
    let leaf = document.getElementById('leaf');
    let hill1 = document.getElementById('hill1');
    let hill4 = document.getElementById('hill4');
    let hill5 = document.getElementById('hill5');

    window.addEventListener('scroll', () => {
        let value = window.scrollY;

        text.style.marginTop = value * 2.5 + 'px';
        leaf.style.top = value * -1.5 + 'px';
        leaf.style.left = value * 1.5 + 'px';
        hill5.style.left = value * 1.5 + 'px';
        hill4.style.left = value * -1.5 + 'px'; // Adjust as needed
        hill1.style.top = value * 1 + 'px'; // Adjust as needed
    });
});
