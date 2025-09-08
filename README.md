<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f3f3;
        }

        header {
            background-color: #0899f3;
            color: #0c0c0c;
            padding: 10px 0;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            display: block;
            margin: 20px auto;
        }

        h1, h2, h3, h4 {
            text-align: center;
        }

        .section {
            background: #ffffff;
            margin: 50px 0;
            padding: 50px;
            border-radius: 50px;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #35424a;
            color: #ffffff;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        video {
            display: block;
            margin: 10px auto;
            border: 2px solid #35424a;
            border-radius: 5px;
        }

        .video-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .video-grid div {
            text-align: center;
        }

        main {
            text-align: center;
        }

        li {
            text-align: left;
            margin-left: 40%;
        }
    </style>
</head>

<body>
    <header>
        <h1>My Portfolio</h1>
    </header>

    <div class="container">
        <img src="WhatsApp Image 2025-09-08 at 14.07.06_784263ca.jpg" alt="Profile Picture" class="profile-img">
        <h1>ANIL KUMAR BUDIGE</h1>

        <main>
            <div class="section">
                <h2>My Skills</h2>
                <li>Passionate in mobile photography &amp; videography</li>
                <li>Mobile editor</li>
                <li>Photo editing</li>
                <li>Video editing</li>
            </div>

            <div class="section">
                <h2>Applications</h2>
                <h3>Photo editing applications</h3>
                <li>Piscart</li>
                <li>Literoom</li>
                <li>Snapseed</li>
                <li>Canva</li>
                <h4>Video editing applications</h4>
                <li>Kinemaster</li>
                <li>VN &amp; Inshot</li>
            </div>

            <div class="section">
                <h2>My Video Edits</h2>

                <div class="video-grid">
                    <div>
                        <h3>First Video</h3>
                        <video width="320" height="240" controls>
                            <source src="edit1.mp4" type="video/mp4">
                            Your browser does not support HTML video.
                        </video>
                    </div>

                    <div>
                        <h3>Second Video</h3>
                        <video width="320" height="240" controls>
                            <source src="edit2.mp4" type="video/mp4">
                            Your browser does not support HTML video.
                        </video>
                    </div>

                    <div>
                        <h3>Third Video</h3>
                        <video width="320" height="240" controls>
                            <source src="edit3.mp4" type="video/mp4">
                            Your browser does not support HTML video.
                        </video>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2>Contact</h2>
                <p>anilbudige01@gmail.com</p>
                <p>9640591027</p>
            </div>
        </main>
    </div>

    <footer>
        <p>© 2025 ANIL KUMAR. All rights reserved.</p>
    </footer>
</body>

</html>

























