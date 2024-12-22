 **1. Develop the HTML page named as “Myfirstwebpage.html”. Add the following tags with relevant content. Set the title of the page as “My First Web Page” Within the body use the following tags:**
a) Moving text = “Basic HTML Tags”
b) Different heading tags (h1 to h6)
c) Paragraph
d) Horizontal line
e) Line Break
f) Block Quote
g) Pre tag
h) Different Logical Style (, , etc..)

PROGRAM:

<!DOCTYPE html>

<head>
    <title>My First Web Page | vtucode</title>
</head>

<body>
    <!-- Moving text -->
    <marquee>Welcome to vtucode</marquee>

    <!-- Different heading tags -->
    <h1>This is an H1 heading</h1>
    <h2>This is an H2 heading</h2>
    <h3>This is an H3 heading</h3>
    <h4>This is an H4 heading</h4>
    <h5>This is an H5 heading</h5>
    <h6>This is an H6 heading</h6>

    <!-- Paragraph -->
    <p>This is a paragraph demonstrating the use of the paragraph tag in HTML.</p>

    <!-- Horizontal line -->
    <hr>

    <!-- Line break -->
    <p>This is a line of text before the break.<br>This is a line of text after the break.</p>

    <!-- Block Quote -->
    <blockquote>
        This is a blockquote. It is used to display a quotation or excerpt from another source.
    </blockquote>

    <!-- Pre tag -->
    <pre>
This is preformatted text.
It preserves spaces and line breaks.</pre>

    <!-- Different Logical Style tags -->
    <p>This is <b>bold</b> text.</p>
    <p>This is <i>italicized</i> text.</p>
    <p>This is <u>underlined</u> text.</p>
    <p>This is <sup>superscript</sup> text.</p>
    <p>This is <sub>subscript</sub> text.</p>
    <p>This is <em>emphasized</em> text.</p>
    <p>This is <strong>strong</strong> text.</p>
    <p>This is <mark>highlighted</mark> text.</p>
    <p>This is <small>small</small> text.</p>
    <p>This is <del>deleted</del> text.</p>
    <p>This is <ins>inserted</ins> text.</p>
    <p>This is <code>inline code</code> text.</p>
</body>

</html>

2. Develop the HTML page named as “Table.html” to display your class time table.
a) Provide the title as Time Table with table header and table footer, row-span and col-span etc.
b) Provide various colour options to the cells (Highlight the lab hours and elective hours with different colors.)
c) Provide colour options for rows.

PROGRAM:

<!DOCTYPE html>

<head>

    <title>Time Table | vtucode</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        th,
        td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #f4f4f4;
            color: #333;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tr:nth-child(odd) {
            background-color: #e6f7ff;
        }

        .lab-hour {
            background-color: #ffcccc;
        }

        .elective-hour {
            background-color: #ccffcc;
        }

        .highlight {
            font-weight: bold;
            color: #d63384;
        }

        tfoot {
            background-color: #e0e0e0;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <h1 style="text-align: center;">Time Table</h1>

    <table>
        <thead>
            <tr>
                <th>Day/Time</th>
                <th>9:00 - 10:00</th>
                <th>10:00 - 11:00</th>
                <th>11:00 - 12:00</th>
                <th>12:00 - 1:00</th>
                <th>Lunch Break</th>
                <th>2:00 - 3:00</th>
                <th>3:00 - 4:00</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td>Math</td>
                <td>English</td>
                <td class="lab-hour">Physics Lab</td>
                <td>Elective</td>
                <td rowspan="5" class="highlight">Break</td>
                <td class="elective-hour">Elective</td>
                <td>History</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td class="elective-hour">Elective</td>
                <td>Biology</td>
                <td>Math</td>
                <td class="lab-hour">Chemistry Lab</td>
                <td>Geography</td>
                <td>PE</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>History</td>
                <td class="lab-hour">Computer Lab</td>
                <td>English</td>
                <td>Math</td>
                <td>Physics</td>
                <td class="elective-hour">Elective</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td>PE</td>
                <td>History</td>
                <td>Geography</td>
                <td class="elective-hour">Elective</td>
                <td>Biology</td>
                <td>Math</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td class="lab-hour">Biology Lab</td>
                <td>Math</td>
                <td>English</td>
                <td>Physics</td>
                <td class="elective-hour">Elective</td>
                <td>Chemistry</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="8">End of Timetable</td>
            </tr>
        </tfoot>
    </table>

</body>

</html>

# **3. Develop an external style sheet named as “style.css” and provide different styles for h2, h3, hr, p, div, span, time, img & a tags. Apply different CSS selectors for tags and demonstrate the significance of each.

PROGRAM:

Note: make two file one is style.css and other is index.html then copy and paste the below code for different file.

index.html

<!DOCTYPE html>

<head>
    <title>Styled HTML Page | vtucode</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h2>Main Heading</h2>
    <h3>Subheading</h3>
    <hr>
    <p>This is a paragraph demonstrating the basic text styling applied by CSS.</p>

    <div>
        This is a styled <strong>div</strong> element with padding and a light border. Inside the div, we can also use
        <span>span elements</span> that have their own styles, like this bold and orange text.
    </div>

    <p>Current time: <time>10:30 AM</time></p>

    <img src="https://vtucode.in/wp-content/uploads/2024/08/Web-Technology-Lab.jpg" alt="Placeholder Image">

    <p>Visit <a href="https://vtucode.in">vtucode.in</a> to learn more about our services.</p>

    <p class="highlight">This paragraph is highlighted with a yellow background.</p>
    <p class="center">This text is centered using a class selector.</p>

    <p id="special-paragraph">This is a special paragraph with unique styles applied through an ID selector.</p>

</body>

</html>

style.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

h2 {
    color: #2c3e50;
    font-size: 2em;
    margin-bottom: 10px;
}

h3 {
    color: #34495e;
    font-size: 1.5em;
    margin-bottom: 8px;
}

hr {
    border: 0;
    height: 2px;
    background-color: #e74c3c;
    margin: 20px 0;
}

p {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 10px 0;
}

div {
    padding: 15px;
    border: 1px solid #bdc3c7;
    background-color: #ecf0f1;
}

span {
    color: #e67e22;
    font-weight: bold;
}

time::before {
    content: '⏰ ';
    color: #16a085;
}

img {
    margin-left: 15px;
    height: 300px;
    width: 400px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    max-width: 100%;
}

a {
    text-decoration: none;
    color: #ea0e4c;
}

a:hover {
    color: #6200ee;
    text-decoration: underline;
}

.highlight {
    background-color: yellow;
    padding: 3px;
}

.center {
    text-align: center;
}

#special-paragraph {
    font-size: 1.2em;
    color: #8e44ad;
    background-color: #f5f5f5;
    padding: 10px;
    border-left: 5px solid #8e44ad;
}

h2,
h3,
p {
    margin-left: 20px;
}


# **4. Develop HTML page named as “registration.html” having variety of HTML input elements with background colors, table for alignment & provide font colors & size using CSS styles.

PROGRAM:

<!DOCTYPE html>

<head>
    <title>Registration Form | vtucode</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 100%;
            max-width: 600px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        h2 {
            text-align: center;
            color: #333;
            margin: 0;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 5px;
            margin-bottom: 10px;
        }

        label {
            font-size: 14px;
            color: #555;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="date"],
        select,
        textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
        }

        .gender-options {
            display: flex;
            gap: 10px;
            align-items: center;
        }

        input[type="submit"],
        input[type="reset"] {
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            flex: 1;
        }

        .button-group {
            display: flex;
            gap: 10px;
            justify-content: center;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
        }

        input[type="reset"] {
            background-color: #f44336;
            color: white;
        }

        .form-group textarea {
            margin-bottom: 10px;
        }
    </style>
</head><body>
    <div class="container">
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="firstName">First Name:</label>
                <input type="text" id="firstName" name="firstName" required>
            </div>
            <div class="form-group">
                <label for="lastName">Last Name:</label>
                <input type="text" id="lastName" name="lastName" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob">
            </div>
            <div class="form-group">
                <label>Gender:</label>
                <div class="gender-options">
                    <input type="radio" id="male" name="gender" value="male">
                    <label for="male">Male</label>
                    <input type="radio" id="female" name="gender" value="female">
                    <label for="female">Female</label>
                </div>
            </div>
            <div class="form-group">
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="usa">USA</option>
                    <option value="canada">Canada</option>
                    <option value="uk">UK</option>
                    <option value="india">India</option>
                </select>
            </div>
            <div class="form-group">
                <label for="bio">Bio:</label>
                <textarea id="bio" name="bio" rows="4"></textarea>
            </div>
            <div class="button-group">
                <input type="submit" value="Register">
                <input type="reset" value="Reset">
            </div>
        </form>
    </div>
</body>

</html>

# **5. Develop HTML page named as “newpaper.html” having variety of HTML semantic elements with background colors, text-colors & size for figure, table, aside, section, article, header, footer… etc.

PROGRAM:

<!DOCTYPE html>

<head>
    <title>Newspaper Page | vtucode</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            padding: 20px;
            font-family: 'Arial', sans-serif;
            color: #000000;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            margin-bottom: 30px;
            border-radius: 10px;
            align-items: center;
            background-color: #7b38f7;
            color: #fff;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header a {
            font-size: 25px;
            font-weight: 600;
            color: #fff;
            text-decoration: none;
        }


        nav {
            display: flex;
            gap: 20px;
            color: #fff;
            text-align: center;
        }

        nav a {
            font-size: 18px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .content {
            display: flex;
            justify-content: space-between;
            flex: 1;
            margin: auto;
            padding: 20px 0;
            gap: 20px;
            position: relative;
        }

        .main-content {
            cursor: pointer;
            flex: 1;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            background-color: #fff;
            border-radius: 12px;
            padding: 25px;
            box-shadow: rgba(9, 30, 66, 0.25) 0px 1px 1px, rgba(9, 30, 66, 0.13) 0px 0px 1px 1px;
        }

        aside {
            border: 1px solid #ccc;
            padding: 20px;
            width: 350px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: -webkit-sticky;
            position: sticky;
            top: 20px;
            color: #333;
            right: 0;
            margin-left: 20px;
        }


        .related-news h3 {
            text-align: center;
            border-radius: 7px;
            padding: 8px;
            background: #000;
            color: #ffffff;
            font-size: 1.4em;
            margin-bottom: 15px;
        }

        .related-news ul {
            list-style: outside;
            padding: 7px;
            margin: 0;
        }

        .related-news li {
            margin-bottom: 12px;
        }

        .related-news a {
            text-decoration: none;
            color: #7b38f7;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .related-news a:hover {
            text-decoration: underline;
        }


        footer {
            border-radius: 10px;
            background-color: #7b38f7;
            color: #fff;
            padding: 20px;
            font-weight: 500;
            text-align: center;
            margin-top: auto;
            font-size: 18px;
        }

        article {
            transition: all 0.3s ease;
            background-color: #fff;
            padding: 15px;
            box-shadow: rgba(9, 30, 66, 0.25) 0px 1px 1px, rgba(9, 30, 66, 0.13) 0px 0px 1px 1px;
            border-radius: 7px;
            color: #000000;
        }

        figure {
            background-color: #fafafa;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
            margin: 0;
        }

        figcaption {
            font-size: 0.9em;
            color: #666;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        section {
            padding: 20px;
            width: 100%;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: rgba(9, 30, 66, 0.25) 0px 1px 1px, rgba(9, 30, 66, 0.13) 0px 0px 1px 1px;
        }

        section h2 {
            color: #fff;
            background: #000;
            font-size: 24px;
            border-radius: 10px;
            text-align: center;
            padding: 10px;
            margin-bottom: 30px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        caption {
            font-size: 18px;
            margin-bottom: 10px;
            color: #555;
        }

        thead {
            background-color: #007BFF;
            color: #fff;
        }

        th,
        td {
            padding: 12px;
            text-align: left;
        }

        th {
            font-weight: bold;
        }

        tbody tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tbody tr:hover {
            background-color: #eaeaea;
        }

        @media (max-width: 600px) {

            th,
            td {
                padding: 8px;
                font-size: 14px;
            }
        }

        caption {
            background-color: #d9d9d9;
            padding: 10px;
            font-weight: bold;
            border-bottom: 2px solid #ddd;
            border-radius: 8px 8px 0 0;
            font-size: 1.1em;
            color: #333;
        }

        section {
            margin-top: 40px;
            margin-bottom: 50px;
        }

        article h2 {
            color: #7b38f7;
            font-size: 1.3em;
            margin-bottom: 12px;
        }

        article p {
            text-align: left;
            line-height: 1.2;
            margin-top: 10px;
        }


        article:hover {
            background-color: #e7ddfb;
        }

        @media (max-width: 768px) {
            .content {
                flex-direction: column;
                padding: 10px;
            }

            aside {
                width: 100%;
                margin-top: 20px;
                position: static;
                margin-left: 0;
            }

            .main-content {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>
    <header>

        <a href="#">Newspaper</a>

        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
            <a href="#">Services</a>
            <a href="#">Marketing</a>
            <a href="#">Updates</a>
        </nav>

    </header>

    <div class="content">
        <main class="main-content">
            <article>
                <h2>Article Title 1</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the first article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>

            <article>
                <h2>Article Title 2</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the second article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>

            <article>
                <h2>Article Title 3</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the third article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>

            <article>
                <h2>Article Title 4</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the fourth article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>

            <article>
                <h2>Article Title 5</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the fourth article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>


            <article>
                <h2>Article Title 6</h2>
                <figure>
                    <img src="https://via.placeholder.com/600x400" alt="Placeholder Image">
                    <figcaption>Image Caption</figcaption>
                </figure>
                <p>This is the content of the fourth article. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </article>

        </main>



        <aside class="related-news">
            <h3>Related News</h3>
            <ul>
                <li><a href="#">Related News 1</a></li>
                <li><a href="#">Related News 2</a></li>
                <li><a href="#">Related News 3</a></li>
            </ul>
        </aside>

    </div>

    <section>
        <h2>Recent Posts</h2>
        <div>
            <table>
                <caption>List of Posts</caption>
                <thead>
                    <tr>
                        <th>Post Title</th>
                        <th>Date</th>
                        <th>Author</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Post 1</td>
                        <td>2024-08-30</td>
                        <td>Author 1</td>
                    </tr>
                    <tr>
                        <td>Post 2</td>
                        <td>2024-08-29</td>
                        <td>Author 2</td>
                    </tr>
                    <tr>
                        <td>Post 3</td>
                        <td>2024-08-28</td>
                        <td>Author 3</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <footer>
        <p>© 2024 Newspaper. All rights reserved.</p>
    </footer>
</body>

</html>

# **6. Apply HTML, CSS and JavaScript to design a simple calculator to perform the following operations: sum, product, difference, remainder, quotient, power, square-root and square.

PROGRAM:

<!DOCTYPE html>

<head>
    <title>Simple Calculator | vtucode</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .calculator {
            background: #fff;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 320px;
            text-align: center;
        }

        h1 {
            border-radius: 8px;
            background: #000;
            font-size: 24px;
            padding: 10px;
            color: #ffffff;
            margin-bottom: 30px;
        }

        input,
        select,
        button {
            width: 100%;
            margin: 10px 0;
            padding: 12px;
            border: 1px solid #0808081d;
            border-radius: 8px;
            font-size: 16px;
            box-sizing: border-box;
            transition: border-color 0.3s, box-shadow 0.3s;
        }


        #operation {
            cursor: pointer;
        }


        input:focus,
        select:focus,
        button:focus {
            outline: none;
            border-color: #007bff;
            box-shadow: 0 0 0 3px rgba(38, 143, 255, 0.25);
        }

        option {
            background-color: #fff;
            color: #000;
            padding: 10px;
            border: none;
        }

        option:hover {
            background-color: #f1f1f1;
        }

        button {
            background-color: #007bff;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 18px;
            transition: box-shadow 0.3s, transform 0.3s;
        }

        button:hover {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }

        button:focus {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }


        #result.error {
            background: #ffdddd;
            border-color: #ff0000;
        }

        #result.success {
            font-size: 17px;
            font-weight: 500;
            color: #000;
            background: #6ef08d38;
            border-color: #47e56d;
        }

        #result {
            font-size: 18px;
            color: #000000;
            border-radius: 8px;
            background: #afffe2;
            border: 1px solid #ccc;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: opacity 0.5s, transform 0.5s;
            opacity: 0;
            transform: translateY(-20px);
        }


        #result.show {
            cursor: not-allowed;
            opacity: 1;
            margin-top: 20px;
            padding: 15px;
            transform: translateY(0);
        }

    </style>
</head>

<body>
    <div class="calculator">
        <h1>Simple Calculator</h1>
        <form id="calculator-form">
            <input type="number" id="num1" placeholder="Enter first number" required>
            <input type="number" id="num2" placeholder="Enter second number" required>
            <select id="operation" required>
                <option value="">Select Operation</option>
                <option value="sum">Sum</option>
                <option value="product">Product</option>
                <option value="difference">Difference</option>
                <option value="remainder">Remainder</option>
                <option value="quotient">Quotient</option>
                <option value="power">Power</option>
                <option value="sqrt">Square Root</option>
                <option value="square">Square</option>
            </select>
            <button type="button" onclick="calculate()">Calculate</button>
        </form>
        <div id="result"></div>
    </div>
    <script>
        function calculate() {
            const num1 = parseFloat(document.getElementById('num1').value);
            const num2 = parseFloat(document.getElementById('num2').value);
            const operation = document.getElementById('operation').value;
            let result = '';
            let resultClass = 'success';

            if (isNaN(num1) || isNaN(num2)) {
                result = 'Please enter valid numbers.';
                resultClass = 'error';
            } else {
                switch (operation) {
                    case 'sum':
                        result = `Sum: ${num1 + num2}`;
                        break;
                    case 'product':
                        result = `Product: ${num1 * num2}`;
                        break;
                    case 'difference':
                        result = `Difference: ${num1 - num2}`;
                        break;
                    case 'remainder':
                        result = `Remainder: ${num1 % num2}`;
                        break;
                    case 'quotient':
                        if (num2 === 0) {
                            result = 'Cannot divide by zero';
                            resultClass = 'error';
                        } else {
                            result = `Quotient: ${num1 / num2}`;
                        }
                        break;
                    case 'power':
                        result = `Power: ${Math.pow(num1, num2)}`;
                        break;
                    case 'sqrt':
                        if (num1 < 0 || num2 < 0) {
                            result = 'Square root is not defined for negative numbers';
                            resultClass = 'error';
                        } else {
                            result = `Square Root of ${num1}: ${Math.sqrt(num1)} <br> Square Root of ${num2}: ${Math.sqrt(num2)}`;
                        }
                        break;
                    case 'square':
                        result = `Square of ${num1}: ${Math.pow(num1, 2)} <br> Square of ${num2}: ${Math.pow(num2, 2)}`;
                        break;
                    default:
                        result = 'Please select an operation.';
                        resultClass = 'error';
                }
            }

            const resultDiv = document.getElementById('result');
            resultDiv.innerHTML = result;
            resultDiv.classList.remove('show', 'error', 'success');
            resultDiv.classList.add(resultClass, 'show');
        }

    </script>
</body>

</html>

# **7. Develop JavaScript program (with HTML/CSS) for:
a) Converting JSON text to JavaScript Object.
b) Convert JSON results into a date.
c) Converting From JSON To CSV and CSV to JSON.
d) Create hash from string using crypto.createHash() method.

PROGRAM:

<!DOCTYPE html>

<head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js"></script>
    <title>Simple Converter | vtucode</title>
    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #000000;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            padding: 20px;
        }

        .head-title h1 {
            font-size: 28px;
            padding: 10px;
            color: #fff;
            margin-bottom: 50px;
        }

        .head-title {
            width: 100%;
            background: #000;
            text-align: center;
            border-radius: 10px;
        }

        .section {
            margin-bottom: 40px;
            padding: 20px;
            border-radius: 8px;
            background: #fff;
            box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
            transition: all 0.3s;
            overflow: hidden;
        }

        .section h2 {
            color: #000000;
            font-size: 20px;
            margin-bottom: 15px;
        }


        textarea {
            font-size: 14px;
            width: 100%;
            height: 120px;
            margin-bottom: 15px;
            padding: 12px;
            border-radius: 8px;
            border: 1px solid #00000022;
            box-sizing: border-box;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        textarea:focus {
            background: transparent;
            border: 1px solid #00000022;
            border-color: #007BFF;
            box-shadow: 0 0 12px rgba(0, 123, 255, 0.5);
            outline: none;
        }

        input[type="text"] {
            width: calc(100% - 24px);
            padding: 12px;
            border-radius: 8px;
            border: 1px solid #ddd;
            box-sizing: border-box;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
            margin-bottom: 15px;
        }

        input[type="text"]:focus {
            border-color: #007BFF;
            box-shadow: 0 0 8px rgba(0, 123, 255, 0.5);
            outline: none;
        }

        button {
            display: inline-block;
            padding: 15px 15px;
            margin: 10px 0;
            font-weight: 600;
            border: none;
            border-radius: 7px;
            background-color: #007BFF;
            color: #fff;
            cursor: pointer;
            font-size: 16px;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }

        button:hover {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007BFF;
        }

        button:focus {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007BFF;
        }

        pre {
            display: none;
            background: #f8f9fa;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 8px;
            overflow: auto;
            transition: opacity 0.3s ease;
        }

        .error {
            margin-top: 10px;
            font-size: 14px;
            color: #000;
            background: #ffdddd;
            border-color: #ff0000;
            padding: 10px;
        }

        .success {
            margin-top: 10px;
            font-size: 14px;
            color: #000;
            background: #6ef08d38;
            border-color: #47e56d;
            padding: 10px;
        }

        .adjust-area {
            margin-top: 30px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="head-title">
            <h1>Simple Converter</h1>
        </div>
        <div class="section">
            <h2>1. Convert JSON Text to JavaScript Object</h2>
            <textarea id="jsonInput" placeholder="Enter JSON here..."></textarea>
            <button onclick="convertJsonToObject()">Convert JSON</button>
            <pre id="jsonOutput" class="output"></pre>
        </div>

        <div class="section">
            <h2>2. Convert JSON Results into Date</h2>
            <textarea id="jsonDateInput" placeholder='Enter JSON with date in "yyyy-mm-dd" format'></textarea>
            <button onclick="convertJsonToDate()">Convert to Date</button>
            <pre id="jsonDateOutput" class="output"></pre>
        </div>

        <div class="section">
            <h2>3. Convert JSON to CSV and CSV to JSON</h2>
            <textarea id="jsonCsvInput" placeholder="Enter JSON for CSV conversion..."></textarea>
            <button onclick="convertJsonToCsv()">JSON to CSV</button>
            <pre id="csvOutput" class="output"></pre>
            <textarea id="csvInput" placeholder="Enter CSV here..." class="adjust-area"></textarea>
            <button onclick="convertCsvToJson()">CSV to JSON</button>
            <pre id="jsonCsvOutput" class="output"></pre>
        </div>

        <div class="section">
            <h2>4. Create Hash from String</h2>
            <input type="text" id="hashInput" placeholder="Enter string to hash">
            <button onclick="createHash()">Create Hash</button>
            <pre id="hashOutput" class="output"></pre>
        </div>
    </div>

    <script>
        function showResult(id, text, isSuccess) {
            const element = document.getElementById(id);
            element.textContent = text;
            element.className = isSuccess ? 'success' : 'error';
            element.style.display = 'block';
            element.style.opacity = '1';
        }

        function convertJsonToObject() {
            const jsonInput = document.getElementById('jsonInput').value;
            try {
                const jsonObject = JSON.parse(jsonInput);
                showResult('jsonOutput', JSON.stringify(jsonObject, null, 2), true);
            } catch (error) {
                showResult('jsonOutput', 'Invalid JSON', false);
            }
        }

        function convertJsonToDate() {
            const jsonDateInput = document.getElementById('jsonDateInput').value;
            try {
                const data = JSON.parse(jsonDateInput);
                if (data.date && !isNaN(new Date(data.date).getTime())) {
                    const date = new Date(data.date);
                    showResult('jsonDateOutput', date.toString(), true);
                } else {
                    showResult('jsonDateOutput', 'Invalid Date Format', false);
                }
            } catch (error) {
                showResult('jsonDateOutput', 'Invalid JSON', false);
            }
        }

        function convertJsonToCsv() {
            const jsonInput = document.getElementById('jsonCsvInput').value;
            try {
                const jsonArray = JSON.parse(jsonInput);
                if (Array.isArray(jsonArray) && jsonArray.length > 0) {
                    const keys = Object.keys(jsonArray[0]);
                    const csv = [
                        keys.join(','),
                        ...jsonArray.map(row => keys.map(key => JSON.stringify(row[key])).join(','))
                    ].join('\n');
                    showResult('csvOutput', csv, true);
                } else {
                    showResult('csvOutput', 'Invalid JSON: Expected an array with objects.', false);
                }
            } catch (error) {
                showResult('csvOutput', 'Invalid JSON', false);
            }
        }

        function convertCsvToJson() {
            const csvInput = document.getElementById('csvInput').value;
            try {
                const lines = csvInput.trim().split('\n');
                if (lines.length > 1) {
                    const keys = lines[0].split(',');
                    if (keys.length > 0) {
                        const jsonArray = lines.slice(1).map(line => {
                            const values = line.split(',');
                            return keys.reduce((obj, key, index) => {
                                obj[key] = values[index];
                                return obj;
                            }, {});
                        });
                        showResult('jsonCsvOutput', JSON.stringify(jsonArray, null, 2), true);
                    } else {
                        showResult('jsonCsvOutput', 'Invalid CSV: No columns found.', false);
                    }
                } else {
                    showResult('jsonCsvOutput', 'Invalid CSV: No data found.', false);
                }
            } catch (error) {
                showResult('jsonCsvOutput', 'Invalid CSV', false);
            }
        }

        function createHash() {
            const hashInput = document.getElementById('hashInput').value.trim();
            if (hashInput.length > 0) {
                const hash = CryptoJS.SHA256(hashInput).toString();
                showResult('hashOutput', hash, true);
            } else {
                showResult('hashOutput', 'Input cannot be empty', false);
            }
        }
    </script>
</body>

</html>
# **output**
Convert JSON Text to JavaScript Object*************************

{
    "name": "Alice",
    "age": 30,
    "city": "New York"
}



Convert JSON Results into Date*********************************

{
    "date": "2024-09-01"
}



Convert JSON to CSV********************************************

[
    {"name": "Alice", "age": 30, "city": "New York"},
    {"name": "Bob", "age": 25, "city": "San Francisco"},
    {"name": "Charlie", "age": 35, "city": "Chicago"}
]



Convert CSV to JSON********************************************

name,age,city
Alice,30,New York
Bob,25,San Francisco
Charlie,35,Chicago



Create Hash from String****************************************

vtucode

# **8A. Develop a PHP program (with HTML/CSS) to keep track of the number of visitors visiting the web page and to display this count of visitors, with relevant headings.

Instructions: How to Run?

Create a file name called track.php, copy the below code and paste it and save it.
Copy track.php file and open XAAMP directory if installed else install it click here
There you’ll find a folder named “htdocs”.
Inside the “htdocs” folder, paste track.php file.
After then open your XAAMP and start the Apache server.
Open your favorite browser; we recommend using Google Chrome or Mozilla Firefox.
Then, go to the URL “http://localhost/track.php“.
PROGRAM:

<?php
$counterFile = "counter.txt";

if (!file_exists($counterFile)) {
    file_put_contents($counterFile, "0");
}

$currentCount = file_get_contents($counterFile);

$newCount = $currentCount + 1;

file_put_contents($counterFile, $newCount);
?>

<!DOCTYPE html>
<html lang="en">

<head>

    <title>Visitor Counter | vtucode</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100vh;
            background-color: #f4f4f9;
            color: #333;
        }

        .container {
            background: #fff;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            margin: 0 auto;
            width: 60%;
        }

        h1 {
            font-size: 2.5em;
            margin: 0;
        }

        p {
            font-size: 1.2em;
            color: #555;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Welcome to Our Website!</h1>
        <p>You are visitor number: <strong><?php echo $newCount; ?></strong></p>
    </div>
</body>

</html>

# **8B. Develop a PHP program (with HTML/CSS) to sort the student records which are stored in the database using selection sort.

Instructions: How to Run?

Create a database name called students or download and import click here
Create a file name called sort_students.php, copy the below code and paste it and save it.
Copy sort_students.php file and open XAAMP directory if installed else install it click here
There you’ll find a folder named “htdocs”.
Inside the “htdocs” folder, paste sort_students.php file.
After then open your XAAMP and start the Apache server.
Open your favorite browser; we recommend using Google Chrome or Mozilla Firefox.
Then, go to the URL “http://localhost/sort_students.php“.
PROGRAM:

<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "students";

$conn = new mysqli($servername, $username, $password, $dbname);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

$sql = "SELECT * FROM students";
$result = $conn->query($sql);

$students = [];
if ($result->num_rows > 0) {
    while ($row = $result->fetch_assoc()) {
        $students[] = $row;
    }
}

function selectionSort(&$arr, $key)
{
    $n = count($arr);
    for ($i = 0; $i < $n - 1; $i++) {
        $minIndex = $i;
        for ($j = $i + 1; $j < $n; $j++) {
            if ($arr[$j][$key] < $arr[$minIndex][$key]) {
                $minIndex = $j;
            }
        }

        $temp = $arr[$i];
        $arr[$i] = $arr[$minIndex];
        $arr[$minIndex] = $temp;
    }
}

selectionSort($students, 'name');
?>

<!DOCTYPE html>

<head>
    <title>Sorted Student Records | vtucode</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            margin: 0;
            padding: 20px;
        }

        h2 {
            text-align: center;
            color: #4A90E2;
            margin-bottom: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background-color: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            margin: 0 auto;
        }

        th,
        td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #4A90E2;
            color: white;
            text-transform: uppercase;
            letter-spacing: 0.03em;
        }

        tr {
            transition: background-color 0.3s ease;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        td {
            font-size: 0.9em;
            color: #555;
        }

        @media (max-width: 768px) {

            table,
            th,
            td {
                display: block;
                width: 100%;
            }

            th,
            td {
                box-sizing: border-box;
            }

            tr {
                margin-bottom: 15px;
                display: block;
                box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            }

            th {
                position: absolute;
                top: -9999px;
                left: -9999px;
            }

            td {
                border: none;
                position: relative;
                padding-left: 50%;
                text-align: right;
            }

            td:before {
                content: attr(data-label);
                position: absolute;
                left: 0;
                width: 50%;
                padding-left: 15px;
                font-weight: bold;
                text-align: left;
                text-transform: uppercase;
                color: #4A90E2;
            }
        }
    </style>
</head>

<body>

    <h2>Sorted Student Records by Name</h2>

    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th>USN</th>
                <th>Branch</th>
                <th>Email</th>
                <th>Address</th>
            </tr>
        </thead>
        <tbody>
            <?php foreach ($students as $student): ?>
                <tr>
                    <td data-label="ID"><?php echo htmlspecialchars($student['id']); ?></td>
                    <td data-label="Name"><?php echo htmlspecialchars($student['name']); ?></td>
                    <td data-label="USN"><?php echo htmlspecialchars($student['usn']); ?></td>
                    <td data-label="Branch"><?php echo htmlspecialchars($student['branch']); ?></td>
                    <td data-label="Email"><?php echo htmlspecialchars($student['email']); ?></td>
                    <td data-label="Address"><?php echo htmlspecialchars($student['address']); ?></td>
                </tr>
            <?php endforeach; ?>
        </tbody>
    </table>

</body>

</html>

# **9. Develop jQuery script (with HTML/CSS) for:
a) Appends the content at the end of the existing paragraph and list.
b) Change the state of the element with CSS style using animate() method.
c) Change the color of any div that is animated.

PROGRAM:

<!DOCTYPE html>

<head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <title>jQuery Example | vtucode</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            text-align: center;
            background: #fff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        .container:hover {
            transform: scale(1.02);
        }

        #paragraph {
            margin-bottom: 20px;
            color: #333;
            font-size: 18px;
            line-height: 1.5;
        }

        #list {
            margin-bottom: 20px;
            list-style: none;
            padding: 0;
        }

        #list li {
            background: #e8f0fe;
            margin: 5px 0;
            padding: 10px;
            border-radius: 8px;
            transition: background 0.3s;
        }

        #list li:hover {
            background: #d0e2fe;
        }

        .box {
            padding: 0 10px;
            width: 100px;
            height: 100px;
            background-color: #007bff;
            margin: 20px auto;
            line-height: 100px;
            color: white;
            text-align: center;
            border-radius: 8px;
            transition: all 0.3s ease;
        }

        button {
            padding: 12px 24px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            background: #007bff;
            color: white;
            transition: box-shadow 0.3s, transform 0.2s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        button:hover {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }

        button:focus {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }

        button:active {
            background: #004494;
            transform: translateY(0);
        }
    </style>
</head>

<body>
    <div class="container">
        <p id="paragraph">This is an existing paragraph.</p>
        <ul id="list">
            <li>List item 1</li>
            <li>List item 2</li>
        </ul>
        <div class="box" id="box">Animate me!</div>
        <button id="appendButton">Append Content</button>
        <button id="animateButton">Animate Box</button>
    </div>

    <script>
        $(document).ready(function () {

            $("#appendButton").click(function () {
                $("#paragraph").append(" Appended text.");
                $("#list").append("<li>New appended list item</li>");
            });

            $("#animateButton").click(function () {

                $("#box").stop(true, true).css({
                    width: "100px",
                    height: "100px",
                    opacity: 1,
                    backgroundColor: "blue"
                }).animate({
                    width: "200px",
                    height: "200px",
                    opacity: 0.5
                }, 1000, function () {

                    $(this).css("background-color", "green");
                });
            });
        });

    </script>
</body>

</html>

# **10 Develop a JavaScript program with Ajax (with HTML/CSS) for:
a) Use ajax() method (without Jquery) to add the text content from the text file by sending ajax request.
b) Use ajax() method (with Jquery) to add the text content from the text file by sending ajax request.
c) Illustrate the use of getJSON() method in jQuery.
d) Illustrate the use of parseJSON() method to display JSON values.

Note: Create two separate file within the same folder one is textfile.txt and other data.json then copy below text for the both separate file and paste it save it.

textfile.txt

hi this is example text...
data.json

{"name":"John Doe","age":30,"city":"New York","skills":["JavaScript","React","Node.js"],"address":{"street":"123 Elm Street","zipcode":"10001"},"projects":[{"name":"Website Redesign","year":2023,"technologies":["HTML","CSS","JavaScript"]},{"name":"Mobile App","year":2024,"technologies":["React Native","Expo"]}]}
PROGRAM:

<!DOCTYPE html>

<head>
    <title>AJAX Examples | vtucode</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        h1 {
            text-align: center;
            color: #333;
            padding: 20px 0;
        }

        #content {
            flex-direction: column;
            display: flex;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        button {
            display: inline-block;
            padding: 10px 15px;
            margin: 12px;
            border: none;
            border-radius: 5px;
            background-color: #007bff;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            transition: box-shadow 0.3s;
        }

        button:hover {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }

        button:focus {
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #007bff;
        }


        #output {
            display: none;
            margin-top: 20px;
            padding: 10px;
            border-radius: 5px;
            white-space: pre-wrap;
            max-height: 300px;
            overflow-y: auto;
        }

        #output.plain-ajax {
            background-color: #f0f8ff;
            border: 1px solid #b0c4de;
        }

        #output.jquery-ajax {
            background-color: #f5fffa;
            border: 1px solid #98fb98;
        }

        #output.jquery-json {
            background-color: #fffaf0;
            border: 1px solid #ffd700;
        }

        #output.parse-json {
            background-color: #fff0f5;
            border: 1px solid #ff69b4;
        }
    </style>
</head>

<body>
    <h1>AJAX Examples</h1>
    <div id="content">
        <button id="plain-ajax-btn">Load Text (Plain AJAX)</button>
        <button id="jquery-ajax-btn">Load Text (jQuery AJAX)</button>
        <button id="jquery-json-btn">Load JSON (jQuery getJSON)</button>
        <button id="parse-json-btn">Load and Parse JSON (jQuery get)</button>
        <div id="output"></div>
    </div>

    <script>

        function showOutput(className) {
            const output = document.getElementById('output');
            output.className = className;
            output.style.display = 'block';
        }

        document.getElementById('plain-ajax-btn').addEventListener('click', function () {
            var xhr = new XMLHttpRequest();
            xhr.open('GET', 'textfile.txt', true);
            xhr.onload = function () {
                if (xhr.status === 200) {
                    document.getElementById('output').innerText = xhr.responseText;
                } else {
                    document.getElementById('output').innerText = 'Error loading file.';
                }
                showOutput('plain-ajax');
            };
            xhr.send();
        });

        $('#jquery-ajax-btn').on('click', function () {
            $.ajax({
                url: 'textfile.txt',
                method: 'GET',
                success: function (data) {
                    $('#output').text(data);
                },
                error: function () {
                    $('#output').text('Error loading file.');
                }
            }).always(function () {
                showOutput('jquery-ajax');
            });
        });


        $('#jquery-json-btn').on('click', function () {
            $.getJSON('data.json')
                .done(function (data) {
                    $('#output').text(JSON.stringify(data, null, 2));
                })
                .fail(function () {
                    $('#output').text('Error loading JSON file.');
                })
                .always(function () {
                    showOutput('jquery-json');
                });
        });


        $('#parse-json-btn').on('click', function () {
            $.get('data.json')
                .done(function (data) {
                    try {
                        let jsonData;
                        
                        if (typeof data === 'string') {
                            jsonData = JSON.parse(data);
                        } else {
                            jsonData = data;
                        }
                        $('#output').text(JSON.stringify(jsonData, null, 2));
                    } catch (e) {
                        $('#output').text('Error parsing JSON: ' + e.message);
                    }
                })
                .fail(function () {
                    $('#output').text('Error loading JSON file.');
                })
                .always(function () {
                    showOutput('parse-json');
                });
        });
    </script>
</body>

</html>
