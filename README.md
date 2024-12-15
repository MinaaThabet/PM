# PM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Profile</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            margin: 0;
            padding: 0;
            background-color: #f4f9f4;
            color: #333;
        }
        header, footer {
            background-color: #228B22;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .team {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }
        .member {
            background: white;
            border: 2px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .member:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .project {
            width: 250px;
            margin: 10px;
            text-align: center;
        }
        .contact {
            text-align: center;
            padding: 20px;
        }
        .contact-icons {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .contact-icons a {
            color: #228B22;
            font-size: 1.5em;
            text-decoration: none;
        }
        .qna-section {
            padding: 20px;
            text-align: center;
        }
        .qna-box {
            width: 80%;
            height: 150px;
            margin: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Meet Our Team</h1>
    </header>

    <section class="team">
        <div class="member">
            <img src="ferry.jpeg" alt="Fareida Abdallah">
            <h2>Fareida Abdallah</h2>
            <p>Business Analyst</p>
            <p>Experience: SQL, Database Design, Churn Prediction</p>
            <p>Previous Projects: Spotify, Uber, Customer Churn Prediction</p>
        </div>
        <div class="member">
            <img src="my pic.jpeg" alt="Mina Thabet">
            <h2>Mina Thabet</h2>
            <p>Business Analyst</p>
            <p>Experience: Power BI, Python, SQL</p>
            <p>Previous Projects: Hotel Management, Spotify Analysis, Retail Analysis</p>
        </div>
        <div class="member">
            <img src="zahraa.jpeg" alt="Zahraa Abdelhalim">
            <h2>Zahraa Abdelhalim</h2>
            <p>Business Analyst</p>
            <p>Experience: Machine Learning, Data Visualization</p>
            <p>Previous Projects: Cardiovascular Risk, IoT Security, Hotel Management</p>
        </div>
    </section>

    <section class="projects">
        <div class="project">
            <img src="Spotify.jpeg" alt="Project 1" style="width: 100%; border-radius: 10px;">
            <h3>Spotify Analysis</h3>
        </div>
        <div class="project">
            <img src="Spotify.jpeg" alt="Project 2" style="width: 100%; border-radius: 10px;">
            <h3>Customer Churn Prediction</h3>
        </div>
        <div class="project">
            <img src="iot security.jpeg" alt="Project 3" style="width: 100%; border-radius: 10px;">
            <h3>IoT Security</h3>
        </div>
    </section>

    <section class="contact">
        <h2>Contact Us</h2>
        <div class="contact-icons">
            <a href="mailto:fareida238@gmail.com">📧</a>
            <a href="mailto:minathabetnaeem@gmail.com">📧</a>
            <a href="mailto:zahraahaliim@gmail.com">📧</a>
        </div>
    </section>

    <section class="qna-section">
        <h2>Ask Us Any Question</h2>
        <textarea class="qna-box" placeholder="Type your question here..."></textarea>
    </section>

    <footer>
        <p>&copy; 2024 Our Team. All rights reserved.</p>
    </footer>
</body>
</html>
