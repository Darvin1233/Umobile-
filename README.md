<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Umobile SIM Card Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff5e6;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: orange;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 90%;
            margin: 0 auto;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 30%;
            margin: 20px;
            padding: 15px;
            text-align: center;
        }
        footer {
            background-color: orange;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-form {
            margin-top: 30px;
            background-color: #f2f2f2;
            padding: 20px;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: orange;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Umobile SIM Card Store</h1>
        <nav>
            <ul>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="products">
            <h2>Our SIM Cards</h2>
            <div class="product-list">
                <div class="product">
                    <h3>SIM Card 1</h3>
                    <p>Details about the SIM card...</p>
                    <button>Buy Now</button>
                </div>
                <div class="product">
                    <h3>SIM Card 2</h3>
                    <p>Details about the SIM card...</p>
                    <button>Buy Now</button>
                </div>
                <div class="product">
                    <h3>SIM Card 3</h3>
                    <p>Details about the SIM card...</p>
                    <button>Buy Now</button>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form action="mailto:dinnerbox356@gmail.com" method="post" enctype="text/plain">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="4" required></textarea>

                    <button type="submit">Send Message</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Umobile SIM Card Store</p>
    </footer>
</body>
</html>

