<html lang="en">
<head>
    <style>
        /* General body styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: white;
            color: orange;
        }

        /* Header styles */
        header {
            background-color: orange;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
            color: white;
            font-size: 2.5em;
            font-weight: bold;
        }

        /* Container for sidebar and content */
        .container {
            display: flex;
        }

        /* Sidebar styling */
        .sidebar {
            width: 200px;
            background-color: black;
            padding: 20px;
        }

        .sidebar ul {
            list-style-type: none;
            padding: 0;
        }

        .sidebar ul li {
            margin-bottom: 10px;
        }

        .sidebar ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .sidebar ul li a:hover {
            color: orange;
        }

        /* Main content area */
        .content {
            flex-grow: 1;
            padding: 20px;
            background-color: white; /* Set the background color to white */
            color: black; /* Set the text color to black */
        }

        /* Footer styling */
        footer {
            background-color: orange;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        footer nav ul {
            list-style-type: none;
            padding: 0;
        }

        footer nav ul li {
            display: inline;
            margin: 0 10px;
        }

        footer nav ul li a {
            color: white;
            text-decoration: none;
        }

        footer nav ul li a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <!-- Removed the <h1>BrightBlog</h1> -->
    </header>

    <div class="container">
        <aside class="sidebar">
            <nav>
                <ul>
                    <li><a href="/home">Home</a></li>
                    <li><a href="/about">About</a></li>
                    <li><a href="/blog">Blog</a></li>
                    <li><a href="/contact">Contact</a></li>
                </ul>
            </nav>
        </aside>

        <main class="content">
            <article>
                <hgroup>
                    <h2>Welcome to BrightBlog!</h2>
                    <h3>My Couch Coder Experience</h3>
                </hgroup>

                <section>
                    <p>For a month: 13th August to 13th September 2024</p>
                </section>

                <section>
                    <h3>My Coding Journey</h3>
                    <p>
                        Over the course of a month, I embarked on a coding journey that was both exciting and challenging. I decided to dive deep into web development, starting with HTML and CSS. As a beginner, I was initially overwhelmed, but the structured lessons made everything much more manageable.
                    </p>
                    <p>
                        I began with the basics of HTML, learning how to structure a webpage using tags like <code>&lt;div&gt;</code>, <code>&lt;header&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code>. This opened my eyes to how a simple web page is built and laid the foundation for understanding website structure.
                    </p>
                    <p>
                        Next, I dove into CSS. I learned how to style the layout of my webpage, from adding colors and fonts to positioning elements on the screen. I particularly enjoyed experimenting with different color schemes (like this white, orange, and black theme!) and playing around with CSS properties like <code>display: flex</code> and <code>text-align</code> to create a clean, modern look.
                    </p>
                    <p>
                        The journey wasn’t without its challenges, but watching my code come to life with every little change was incredibly rewarding. By the end of the course, I had built this very blog, and I’m excited to continue expanding my knowledge of web development.
                    </p>
                </section>
            </article>
        </main>
    </div>

    <footer>
        <h2>Sign up for more Brightnetwork info!</h2>
        <form action="" method="POST">
            <label for="first_name">First Name:</label><br>
            <input type="text" id="first_name" name="first_name" required><br><br>
            <label for="last_name">Last Name:</label><br>
            <input type="text" id="last_name" name="last_name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" required><br><br>
            <label for="country">Country:</label><br>
            <select id="country" name="country">
                <option value="england">England</option>
                <option value="scotland">Scotland</option>
                <option value="wales">Wales</option>
                <option value="northern_ireland">Northern Ireland</option>
            </select><br><br>
            <label for="bio">Biography:</label><br>
            <textarea id="bio" name="bio" rows="4" cols="50"></textarea><br><br>
            <input type="checkbox" id="subscribe" name="subscribe">
            <label for="subscribe">Subscribe to newsletter</label><br><br>
            <input type="submit" value="Submit">
        </form>

        <section>
            <h2>Important Files</h2>
            <nav>
                <ul>
                    <li><a href="/">Privacy Policy</a></li>
                    <li><a href="/">Terms & Conditions</a></li>
                    <li><a href="/">Cookie Policy</a></li>
                </ul>
            </nav>
        </section>

        <h2>Author: Tulika Chatterjee</h2>
        <h3>Last posted: 2024-09-06</h3>
        <a href="https://www.brightnetwork.co.uk/" target="_blank">https://www.brightnetwork.co.uk/</a>
    </footer>
</body>
</html>
