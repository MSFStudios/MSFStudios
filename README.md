<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSFStudios | Photography</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #111;
            color: #fff;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 3rem 1rem;
            background: #000;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            color: #aaa;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 2rem;
        }

        .gallery img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .about {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        .contact {
            text-align: center;
            padding: 2rem;
            background: #000;
        }

        .contact a {
            color: #fff;
            text-decoration: none;
            border: 1px solid #fff;
            padding: 0.7rem 1.5rem;
            border-radius: 30px;
            transition: 0.3s ease;
        }

        .contact a:hover {
            background: #fff;
            color: #000;
        }

        footer {
            text-align: center;
            padding: 1rem;
            font-size: 0.8rem;
            color: #666;
        }
    </style>
</head>
<body>

<header>
    <h1>MSFStudios</h1>
    <p>Automotive | Portrait | Commercial Photography</p>
</header>

<section class="gallery">
    <img src="https://source.unsplash.com/600x800/?car" alt="Car Photo">
    <img src="https://source.unsplash.com/600x800/?portrait" alt="Portrait Photo">
    <img src="https://source.unsplash.com/600x800/?wedding" alt="Wedding Photo">
    <img src="https://source.unsplash.com/600x800/?city,night" alt="City Photo">
    <img src="https://source.unsplash.com/600x800/?nature" alt="Nature Photo">
    <img src="https://source.unsplash.com/600x800/?fashion" alt="Fashion Photo">
</section>

<section class="about">
    <h2>About Me</h2>
    <p>
        I'm a passionate photographer based in Newcastle-under-Lyme, specialising in high-quality imagery for businesses and individuals. 
        I focus on clean, professional visuals that help brands and people stand out.
    </p>
</section>

<section class="contact">
    <h2>Work With Me</h2>
    <p>Email: Mattstuartfreeborn@gmail.com</p>
    <br>
    <a href="mailto:your@email.com">Get In Touch</a>
</section>

<footer>
    © 2026 MSFStudios Photography
</footer>

</body>
</html>
