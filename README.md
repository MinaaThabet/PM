<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meet Our Awesome Team</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #3D4D55, #B58863);
            color: #D3C3B9;
        }
        header {
            background-color: #222;
            color: #D3C3B9;
            text-align: center;
            padding: 20px 0;
            font-size: 36px;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .team-section {
            padding: 50px 20px;
        }
        .team-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: nowrap; /* Ensure items don't wrap */
        }
        .team-member {
            background-color: #3D4D55;
            border: 3px solid #A75E4C;
            border-radius: 16px;
            overflow: hidden;
            flex: 1 1 0; /* All cards share equal width */
            max-width: 320px;
            min-width: 280px;
            text-align: center;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeIn 1.5s ease;
        }
        .team-member:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
        }
        .team-member img {
            width: 100%;
            height: auto;
            border-bottom: 3px solid #A75E4C;
        }
        .team-member .name {
            background-color: #222;
            color: #D3C3B9;
            padding: 15px;
            font-size: 22px;
            font-weight: bold;
        }
        .team-member .name a {
            color: #D3C3B9;
            text-decoration: none;
        }
        .team-member .name a:hover {
            text-decoration: underline;
        }
        .team-member .title {
            font-size: 16px;
            color: #B58863;
            margin: 10px 0;
        }
        .team-member .description {
            font-size: 14px;
            color: #D3C3B9;
            padding: 0 20px 20px;
        }
        footer {
            background-color: #222;
            color: #D3C3B9;
            text-align: center;
            padding: 20px 0;
        }
        footer a {
            text-decoration: none;
            color: #B58863;
            margin: 0 10px;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .footer-icons {
            margin-top: 10px;
        }
        .footer-icons span {
            font-size: 16px;
            margin-right: 15px;
        }
        .chat-icon {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #B58863;
            color: #222;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s;
        }
        .chat-icon:hover {
            background-color: #A75E4C;
        }
        .chat-popup {
            position: fixed;
            bottom: 90px;
            right: 20px;
            background-color: #3D4D55;
            border: 2px solid #A75E4C;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 15px;
            width: 300px;
            display: none;
            z-index: 1000;
        }
        .chat-popup textarea {
            width: 100%;
            height: 80px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px;
            font-size: 14px;
        }
        .chat-popup button {
            background-color: #B58863;
            color: #222;
            border: none;
            border-radius: 4px;
            padding: 10px;
            cursor: pointer;
            font-size: 14px;
            width: 100%;
        }
        .chat-popup button:hover {
            background-color: #A75E4C;
        }
        @media (max-width: 1024px) {
            .team-container {
                flex-wrap: wrap; /* Allow wrapping for smaller screens */
            }
            .team-member {
                flex: 1 1 calc(50% - 30px); /* Show two cards per row for mid-sized screens */
                max-width: 100%;
            }
        }
        @media (max-width: 768px) {
            .team-member {
                flex: 1 1 100%; /* Stack cards vertically for small screens */
            }
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        Meet Our Awesome Team
    </header>
    <section class="team-section">
        <div class="team-container">
            <div class="team-member">
                <img src="ferry.jpeg" alt="Farieda Abdallah">
                <div class="name"><a href="farieda_portfolio.html">Farieda Abdallah</a></div>
                <div class="title">Business Analytics Major</div>
                <div class="description">Egyptian Russian University, Class of 2025. Passionate about turning data into actionable insights for global impact.</div>
            </div>
            <div class="team-member">
                <img src="my pic.jpeg" alt="Mina Thabet">
                <div class="name"><a href="mina_portfolio.html">Mina Thabet</a></div>
                <div class="title">Business Analytics Major</div>
                <div class="description">Egyptian Russian University, Class of 2025. Skilled in predictive modeling and data-driven decision-making.</div>
            </div>
            <div class="team-member">
                <img src="zahraa.jpeg" alt="Zahraa Abdelhalim">
                <div class="name"><a href="zahraa_portfolio.html">Zahraa Abdelhalim</a></div>
                <div class="title">Business Analytics Major</div>
                <div class="description">Egyptian Russian University, Class of 2025. Dedicated to leveraging data for innovation and transformative solutions.</div>
            </div>
        </div>
    </section>
    <footer>
        <div>Contact Us:</div>
        <div class="footer-icons">
            <span>📧 <a href="214096@eru.edu.eg.com">Farieda</a></span>
            <span>📧 <a href="214020@eru.edu.eg.com">Mina</a></span>
            <span>📧 <a href="214052@eru.edu.eg.com">Zahraa</a></span>
        </div>
    </footer>
    <div class="chat-icon" onclick="toggleChatPopup()">💬</div>
    <div class="chat-popup" id="chatPopup">
        <textarea id="chatInput" placeholder="Type your question..."></textarea>
        <button onclick="handleChatSubmit()">Send</button>
    </div>
    <script>
        function toggleChatPopup() {
            const chatPopup = document.getElementById('chatPopup');
            chatPopup.style.display = chatPopup.style.display === 'block' ? 'none' : 'block';
        }

        function handleChatSubmit() {
            const chatInput = document.getElementById('chatInput');
            const question = chatInput.value.trim();

            if (question) {
                alert(`Question submitted: ${question}`);
                chatInput.value = ''; // Clear the input after submission
            } else {
                alert("Please enter a question before submitting.");
            }
        }
    </script>
</body>
</html>
