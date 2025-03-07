<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        /* Import Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(to right, #667eea, #764ba2);
        }

        /* Profile Card Styling */
        .profile-card {
            background: #fff;
            width: 350px;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
        }

        /* Hover Effect */
        .profile-card:hover {
            transform: scale(1.08);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        /* Profile Image */
        .profile-image img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 5px solid #764ba2;
            transition: transform 0.3s ease-in-out;
        }

        /* Image Hover Effect */
        .profile-card:hover .profile-image img {
            transform: rotate(5deg) scale(1.1);
        }

        h2 {
            margin: 15px 0 5px;
            font-size: 24px;
            color: #333;
            font-weight: 600;
        }

        .designation {
            font-size: 16px;
            color: #777;
            margin-bottom: 12px;
            font-weight: 500;
        }

        .bio {
            font-size: 14px;
            color: #555;
            margin-bottom: 20px;
        }

        /* Social Media Icons */
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .social-icons a {
            color: #764ba2;
            font-size: 22px;
            transition: transform 0.3s ease-in-out, color 0.3s ease-in-out;
        }

        .social-icons a:hover {
            color: #667eea;
            transform: scale(1.2);
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <div class="profile-image">
            <img src="profile.png" alt="Noorul Ruwaitha">
        </div>
        <h2>Noorul Ruwaitha</h2>
        <p class="designation">Graphic Designer & Content Writer</p>
        <p class="bio">Creative and passionate about design. I love turning ideas into visually appealing graphics and crafting engaging content.</p>
        
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </div>

</body>
</html>
