<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bodiyat Sarker | Web Developer Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 50px 0;
            background-color: #333;
            color: #fff;
        }
        header h1 {
            margin: 0;
        }
        .section {
            margin: 20px 0;
        }
        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .services, .portfolio {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .service, .project {
            flex: 1 1 300px;
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .contact {
            text-align: center;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Bodiyat Sarker</h1>
        <p>Web Developer | Creating modern, responsive, and user-friendly websites</p>
    </header>

    <section class="section about">
        <h2>About Me</h2>
        <p>I am a passionate web developer skilled in creating responsive, interactive, and user-centered websites. With a focus on clean code and modern design principles, I help businesses build a strong online presence.</p>
    </section>

    <section class="section services">
        <h2>My Services</h2>
        <div class="service">
            <h3>Custom Website Development</h3>
            <p>Developing fully customized websites to meet your business needs, using HTML, CSS, and JavaScript.</p>
        </div>
        <div class="service">
            <h3>Responsive Design</h3>
            <p>Ensuring your website looks great on all devices, from desktops to smartphones.</p>
        </div>
        <div class="service">
            <h3>E-commerce Integration</h3>
            <p>Setting up secure, scalable, and user-friendly online stores with Shopify and WooCommerce.</p>
        </div>
    </section>

    <section class="section portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of your project or a link to a live website you've built.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of another project, including key features or technologies used.</p>
        </div>
    </section>

    <section class="section contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
    </section>
</div>

</body>
</html>
