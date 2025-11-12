# ANNAMACHARYA-UNIVERSITY-WEBSITE<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Annamacharya University</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header-top {
            background-color: #FF5722;
            color: white;
            padding: 10px 20px;
            font-size: 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header-top .contact-info {
            display: flex;
            gap: 15px;
        }
        .header-top .contact-info span,
        .header-top .contact-info a {
            color: white;
            text-decoration: none;
        }
        .header-main {
            background-color: white;
            text-align: center;
            padding: 15px;
        }
        .header-main h1 {
            color: #2c2f66;
            font-size: 36px;
            margin: 0;
            font-weight: bold;
        }
        .header-main p {
            margin: 5px 0;
            color: #333;
            font-weight: 700;
        }
        .nav-bar {
            background-color: #222a56;
            display: flex;
            align-items: center;
            padding: 10px 20px;
            color: white;
            font-size: 16px;
        }
        .nav-bar ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
            gap: 20px;
            flex-grow: 1;
        }
        .nav-bar li {
            position: relative;
            cursor: pointer;
        }
        .nav-bar li a {
            color: white;
            text-decoration: none;
            padding: 5px;
        }
        .button-group {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .button-group button {
            background-color: #0d1a47;
            color: white;
            border: none;
            padding: 8px 15px;
            cursor: pointer;
            font-weight: bold;
        }
        .button-group button:hover {
            background-color: #1b2a6c;
        }
        .button-highlight {
            background-color: #FF5722;
            padding: 10px 15px;
            margin-left: 15px;
            cursor: pointer;
        }
        .button-highlight:hover {
            background-color: #e04e1c;
        }
        .search-icon {
            margin-left: 10px;
            cursor: pointer;
        }
        .hero-section {
            display: flex;
            background: url('banner-image.jpg') no-repeat center center/cover;
            color: #2c2f66;
            padding: 40px 20px;
            align-items: center;
            gap: 40px;
        }
        .hero-text {
            max-width: 50%;
        }
        .hero-text h2 {
            color: #FF5722;
            font-weight: bold;
        }
        .hero-text h3 {
            font-weight: 700;
        }
        .hero-buttons button {
            background-color: #FF5722;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-right: 10px;
            font-weight: bold;
            cursor: pointer;
        }
        .hero-buttons button:hover {
            background-color: #e04e1c;
        }
        .logo {
            width: 100px;
            height: auto;
            margin-right: 15px;
        }
    </style>
</head>
<body>
    <div class="header-top">
        <div class="contact-info">
            <span>📞 +91 8565251252 / 9154147257 | ✉ info@annamacharyauniversity.edu.in</span>
        </div>
        <div class="button-group">
            <button>Fee Payment</button>
            <button>Exam Results</button>
        </div>
    </div>
    <div class="header-main">
        <img src="https://annamacharyauniversity.edu.in/images/logo.png" alt="Annamacharya University Logo" class="logo">
        <h1>ANNAMACHARYA UNIVERSITY</h1>
        <p>Estd. under Andhra Pradesh</p>
        <p><strong>Private Universities (Establishment and Regulation) Act, 2016</strong></p>
        <p>(University listed in UGC as per section 2(f) of the UGC Act, 1956)</p>
    </div>
    <nav class="nav-bar">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About ▼</a></li>
            <li><a href="#">Schools ▼</a></li>
            <li><a href="#">University ▼</a></li>
            <li><a href="#">Research ▼</a></li>
            <li><a href="#">Admissions ▼</a></li>
            <li><a href="#">Placements ▼</a></li>
            <li><a href="#">Downloads ▼</a></li>
            <li><a href="#">Careers@AU</a></li>
        </ul>
        <div class="button-highlight">
            Student Certificate Verification Procedure
        </div>
        <div class="search-icon">🔍</div>
    </nav>
    <section class="hero-section">
        <div class="hero-text">
            <h2>ANNAMACHARYA UNIVERSITY</h2>
            <h3>Admission/Scholarship Test<br>Online Test on</h3>
            <div class="hero-buttons">
                <button>Register</button>
                <button>For Admission Enquiry</button>
            </div>
        </div>
        <div>
            <img src="students-photo.jpg" alt="Students" style="max-width: 400px;">
        </div>
    </section>
</body>
</html>
