# my-blog
this repository contains a personal blog built with HTML and CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Blog Post</title>
    <style>
        /* ======= General Styling ======= */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f9f9f9;
        }

        /* ======= Blog Container ======= */
        article {
            max-width: 800px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* ======= Header Styling ======= */
        header h1 {
            color: #2c3e50;
            margin-bottom: 5px;
        }

        header p {
            color: #7f8c8d;
            margin: 2px 0;
        }

        /* ======= Section Headings ======= */
        section h2 {
            color: #34495e;
            margin-top: 20px;
        }

        /* ======= Lists Styling ======= */
        ul {
            margin-left: 20px;
        }

        /* ======= Read More Link Styling ======= */
        a {
            color: #2980b9;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* ======= Images Styling ======= */
        img {
            display: block;
            margin: 10px 0;
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
    </style>
</head>

<body>

    <article>
        <!-- Header -->
        <header>
            <h1>My First Blog Post</h1>
            <p>Published on: <time datetime="2026-01-08">January 8, 2026</time></p>
            <p>Author: Bhimavarapu Hemanth Reddy</p>
        </header>

        <!-- Introduction -->
        <section>
            <h2>Introduction</h2>
            <p>This is the introduction of my blog post. I will explain the topic briefly here.</p>
        </section>

        <!-- Main Content -->
        <section>
            <h2>Main Content</h2>
            <p>Here are some key points:</p>
            <ul>
                <li>Point 1: HTML basics</li>
                <li>Point 2: Semantic tags</li>
                <li>Point 3: Adding styles with CSS</li>
            </ul>
        </section>
        <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8?auto=format&fit=crop&w=800&q=80"
            alt="Laptop Image 1">
        <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8?auto=format&fit=crop&w=800&q=80"
            alt="Laptop Image 2">
        <img src="https://images.unsplash.com/photo-1581090700227-6b5480eb36e4?auto=format&fit=crop&w=800&q=80"
            alt="Laptop Image 3">
        <img src="https://images.unsplash.com/photo-1555617117-08cbb24b18a1?auto=format&fit=crop&w=800&q=80"
            alt="Laptop Image 4">


        <!-- Conclusion -->
        <section>
            <h2>Conclusion</h2>
            <p>This is the conclusion of my blog post. Thank you for reading!</p>
        </section>
    </article>

</body>

</html>
