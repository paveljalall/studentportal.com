<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portal</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #0074D9;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #0056b3;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: inline-block;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.1em;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        main {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #0074D9;
            margin-bottom: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        table th,
        table td {
            padding: 10px;
            text-align: left;
            border: 1px solid #ddd;
        }

        table th {
            background-color: #0074D9;
            color: white;
        }

        aside ul {
            list-style: square inside;
            padding: 0;
        }

        form label {
            font-weight: bold;
            margin-bottom: 5px;
            display: block;
        }

        form input[type="text"],
        form input[type="email"],
        form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0 20px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        form button {
            background-color: #0074D9;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #0056b3;
        }

        video,
        audio {
            display: block;
            margin: 10px 0;
        }

        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            nav ul li {
                display: block;
                margin: 5px 0;
            }

            table th,
            table td {
                font-size: 0.9em;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to the Student Portal</h1>
        <p>Your one-stop destination for all academic updates and resources.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#announcements">Announcements</a></li>
            <li><a href="#resources">Resources</a></li>
            <li><a href="#feedback">Feedback</a></li>
        </ul>
    </nav>

    <main>
        <section id="announcements">
            <h2>Latest Announcements</h2>
            <p>Stay updated with the latest news and notifications from the college.</p>
        </section>

        <section id="resources">
            <h2>Resources</h2>
            <table>
                <thead>
                    <tr>
                        <th>Resource</th>
                        <th>Description</th>
                        <th>Link</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Library</td>
                        <td>Access our digital library.</td>
                        <td><a href="https://library.example.com">Visit</a></td>
                    </tr>
                    <tr>
                        <td>Workshops</td>
                        <td>Enroll in upcoming workshops.</td>
                        <td><a href="https://workshops.example.com">Learn More</a></td>
                    </tr>
                </tbody>
            </table>
        </section>

        <aside>
            <h2>Upcoming Events</h2>
            <ul>
                <li>Science Fair - Nov 25</li>
                <li>Guest Lecture on AI - Dec 1</li>
                <li>Sports Day - Dec 10</li>
            </ul>
        </aside>

        <section id="feedback">
            <h2>Feedback Form</h2>
            <form action="/submit-feedback" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">

                <label for="email">Email:</label>
                <input type="email" id="email" name="email">

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5"></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>

        <section>
            <h2>Media</h2>
            <video controls width="400">
                <source src="./video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <audio controls>
                <source src="./video.mp4" type="audio/mp4">
                Your browser does not support the audio tag.
            </audio>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Student Portal. All rights reserved.</p>
    </footer>

</body>

</html>
