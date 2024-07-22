# SkillsBasedHiringv2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills-Based Job Board</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: #007BFF;
            color: white;
        }
        .hero h1 {
            font-size: 36px;
            margin: 0;
        }
        .hero p {
            font-size: 18px;
            margin: 10px 0;
        }
        .hero img {
            max-width: 100%;
            height: auto;
            margin-top: 20px;
        }
        .benefits, .cta, .signup, .additional-info, .footer {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
        }
        .benefits h2, .cta h2, .signup h2, .additional-info h2 {
            font-size: 28px;
            color: #007BFF;
        }
        .benefits ul, .additional-info ul {
            list-style-type: none;
            padding: 0;
        }
        .benefits ul li, .additional-info ul li {
            padding: 10px 0;
            font-size: 18px;
        }
        .cta {
            text-align: center;
        }
        .cta button, .signup button {
            padding: 15px 30px;
            font-size: 18px;
            background: #28A745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .cta button:hover, .signup button:hover {
            background: #218838;
        }
        .signup input {
            width: calc(50% - 22px);
            padding: 10px;
            margin: 5px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .signup input[type="file"] {
            width: calc(100% - 22px);
        }
        .footer {
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hero">
            <h1>Discover Your Next Career Move Without Even Looking</h1>
            <p>Join the Premier Skills-Based Job Board for Passive Candidates</p>
            <img src="https://via.placeholder.com/1000x300" alt="Hero Image">
        </div>
        <div class="benefits">
            <h2>Benefits</h2>
            <ul>
                <li>Tailored Matches: Receive job offers that perfectly match your skill set.</li>
                <li>Confidential & Secure: Your job search is private and confidential.</li>
                <li>No Active Searching: Opportunities come to you based on your skills and preferences.</li>
                <li>Exclusive Offers: Access to exclusive job opportunities not advertised elsewhere.</li>
                <li>Free to Join: Signing up is quick, easy, and completely free.</li>
            </ul>
        </div>
        <div class="cta">
            <h2>Sign Up Today and Get Matched with Your Ideal Job!</h2>
            <button>Join Now</button>
        </div>
        <div class="signup">
            <h2>Sign-Up Form</h2>
            <form>
                <input type="text" placeholder="Name" required>
                <input type="email" placeholder="Email" required>
                <input type="text" placeholder="Primary Skill/Role" required>
                <input type="text" placeholder="Years of Experience" required>
                <input type="file">
                <button type="submit">Join Now</button>
            </form>
        </div>
        <div class="additional-info">
            <h2>How It Works</h2>
            <ul>
                <li>Create Your Profile: Fill out a quick profile with your skills and preferences.</li>
                <li>Get Matched: Our advanced algorithm matches you with job opportunities that fit your skills.</li>
                <li>Receive Offers: Get notified of job offers and opportunities that match your profile.</li>
            </ul>
        </div>
        <div class="footer">
            <p>Terms of Service | Privacy Policy | Contact Us</p>
        </div>
    </div>
</body>
</html>
