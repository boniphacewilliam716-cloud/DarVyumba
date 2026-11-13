# DarVyumba
​"DarVyumba is a modern web application designed to simplify house and room hunting. It features regional location filtering, encrypted client-to-owner verification workflows, and an intuitive user dashboard built for seamless property searching.
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f7f6;
    color: #333;
}

/* Header Styling */
header {
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 5%;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header .logo span {
    color: #00d2ff;
}

header nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 15px;
}

header nav a.btn-cta {
    background: #00d2ff;
    padding: 8px 16px;
    border-radius: 4px;
    color: #0f2027;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background: linear-gradient(rgba(15, 32, 39, 0.8), rgba(44, 83, 100, 0.8)), url('hero-bg.jpg') center/cover;
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.hero h1 {
    font-size: 32px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 16px;
    margin-bottom: 30px;
    color: #cfd8dc;
}

.search-box {
    display: inline-flex;
    background: rgba(255, 255, 255, 0.2);
    backdrop-filter: blur(10px);
    padding: 8px;
    border-radius: 50px;
    width: 100%;
    max-width: 500px;
}

.search-box input {
    flex: 1;
    border: none;
    background: transparent;
    padding: 10px 15px;
    color: white;
    font-size: 16px;
    outline: none;
}

.search-box input::placeholder {
    color: #e0e0e0;
}

.search-box button {
    background: #00d2ff;
    border: none;
    padding: 10px 25px;
    border-radius: 25px;
    color: #0f2027;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

.search-box button:hover {
    background: #00a8cc;
}

/* Main Content & Cards */
.container {
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
}

.container h2 {
    margin-bottom: 25px;
    font-size: 24px;
    color: #203a43;
}

.room-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
}

.room-card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    transition: transform 0.3s;
}

.room-card:hover {
    transform: translateY(-5px);
}

.room-img {
    height: 180px;
    background-size: cover;
    background-position: center;
    background-color: #ddd;
}

.room-details {
    padding: 20px;
}

.room-details h3 {
    font-size: 18px;
    margin-bottom: 8px;
    color: #2c5364;
}

.room-details .location {
    font-size: 14px;
    color: #666;
    margin-bottom: 10px;
}

.room-details .price {
    font-size: 16px;
    font-weight: bold;
    color: #009688;
    margin-bottom: 15px;
}

.btn-details {
    display: block;
    text-align: center;
    background: #203a43;
    color: white;
    padding: 10px;
    text-decoration: none;
    border-radius: 5px;
    font-size: 14px;
    transition: 0.3s;
}

.btn-details:hover {
    background: #0f2027;
}

.no-results {
    grid-column: 1 / -1;
    text-align: center;
    padding: 40px;
    color: #666;
    font-size: 16px;
}

/* Footer */
footer {
    background: #0f2027;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 50px;
    font-size: 14px;
}
