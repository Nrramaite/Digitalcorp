/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

/* Navbar Styles */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: blue;
}

.logo {
    color: white;
    font-size: 24px;
}

.nav-links li {
    display: inline;
    margin-left: 20px;
}

.nav-links a {
    text-decoration: none;
    color: white;
}

/* Hero Section Styles */
.hero {
    background-color: red;
    color: white;
    text-align: center;
    padding: 60px 20px;
}

.hero h1 {
    margin-bottom: 20px;
}

.hero p {
    margin-bottom: 40px;
}

button {
    padding: 10px 20px;
    background-color: white;
    border: none;
    color: blue;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #f2f2f2;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    position: absolute;
    width: 100%;
    bottom: 0;
}
