* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: linear-gradient(to right, #5c5c5c 360px, #fff 20px, #fff calc(100% - 360px), #5c5c5c calc(100% - 360px));
    padding: 0 20px;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    position: relative;
}

header {
    background-color: #000;
    color: white;
    text-align: center;
    padding: 2em 1em;
    width: calc(100% + 40px);
    margin: 0 -20px;
    height: 200px;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    margin: 1em 0 0 0;
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
}

main {
    padding: 2em;
    font-size: 1.2em;
    line-height: 1.5;
}

.foto table {
    width: 100%;
    border-collapse: collapse;
    margin: 2em 0;
}

.foto img {
    max-width: 100%;
    height: auto;
    display: block;
}

.foto td {
    padding: 1em;
    vertical-align: top;
}

.texto {
    font-size: 1.2em;
}

.space1,
.space2 {
    text-align: center;
    padding: 1em;
}

footer {
    background-color: #f1f1f1;
    text-align: center;
    padding: 1em 0;
    font-size: 0.9em;
    color: #555;
}
