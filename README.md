< FLOWERS  >
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beautiful World of Flowers</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #c2185b;
            margin-bottom: 15px;
        }
        .section {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            background: #fff;
        }
        .image {
            width: 100%;
            max-height: 300px;
            object-fit: cover;
            margin-top: 10px;
            border-radius: 5px;
        }
        ul {
            list-style-type: disc;
            text-align: left;
            padding-left: 20px;
        }
        .btn {
            padding: 10px 15px;
            margin-top: 10px;
            cursor: pointer;
            border: none;
            background: #d81b60;
            color: white;
            display: inline-block;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <h1>The Beautiful World of Flowers</h1>
    <div class="container">

        <!-- Introduction Section -->
        <div class="section">
            <h2>Introduction</h2>
            <p>Flowers are one of the most beautiful creations of nature. They come in a variety of colors, shapes, and fragrances, bringing joy to people around the world.</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/Rose_flower.jpg/800px-Rose_flower.jpg" alt="Flowers" class="image">
        </div>

        <!-- Types of Flowers -->
        <div class="section">
            <h2>Types of Flowers</h2>
            <ul>
                <li><strong>Roses:</strong> Symbol of love and beauty.</li>
                <li><strong>Sunflowers:</strong> Bright and cheerful, following the sun.</li>
                <li><strong>Lotus:</strong> A sacred flower in many cultures.</li>
                <li><strong>Tulips:</strong> Elegant and widely popular in spring.</li>
                <li><strong>Orchids:</strong> Exotic flowers with diverse patterns.</li>
            </ul>
        </div>

        <!-- Benefits of Flowers -->
        <div class="section">
            <h2>Benefits of Flowers</h2>
            <p>Flowers provide various benefits beyond their beauty:</p>
            <ul>
                <li>Enhance mood and reduce stress.</li>
                <li>Improve air quality by releasing oxygen.</li>
                <li>Used in medicinal and herbal treatments.</li>
                <li>Play a vital role in pollination.</li>
                <li>Used for decoration, gifting, and spiritual purposes.</li>
            </ul>
        </div>

        <!-- Famous Flower Gardens -->
        <div class="section">
            <h2>Famous Flower Gardens</h2>
            <p>Some of the most famous flower gardens in the world:</p>
            <ul>
                <li><strong>Keukenhof (Netherlands):</strong> The largest tulip garden.</li>
                <li><strong>Dubai Miracle Garden (UAE):</strong> Home to over 150 million flowers.</li>
                <li><strong>Butchart Gardens (Canada):</strong> A breathtaking floral paradise.</li>
                <li><strong>Shinjuku Gyoen (Japan):</strong> Famous for cherry blossoms.</li>
            </ul>
        </div>

        <!-- Flower Symbolism -->
        <div class="section">
            <h2>Symbolism of Flowers</h2>
            <p>Flowers often symbolize different emotions and messages:</p>
            <ul>
                <li><strong>Red Rose:</strong> Love and romance.</li>
                <li><strong>White Lily:</strong> Purity and peace.</li>
                <li><strong>Yellow Sunflower:</strong> Happiness and positivity.</li>
                <li><strong>Pink Carnation:</strong> Gratitude and admiration.</li>
            </ul>
        </div>

        <!-- Contact & Inquiry -->
        <div class="section">
            <h2>Contact & Inquiry</h2>
            <p>If you love flowers and want to learn more, feel free to reach out!</p>
            <form id="contactForm">
                <input type="text" id="name" placeholder="Your Name" required><br>
                <input type="email" id="email" placeholder="Your Email" required><br>
                <textarea id="message" rows="4" placeholder="Your Message" required></textarea><br>
                <button class="btn" type="submit">Send Message</button>
            </form>
        </div>

    </div>

    <script>
        // Form Submission (Mock Functionality)
        document.getElementById("contactForm").addEventListener("submit", function(event) {
            event.preventDefault();
            let name = document.getElementById("name").value;
            let email = document.getElementById("email").value;
            let message = document.getElementById("message").value;
            
            if (name && email && message) {
                alert(`Thank you, ${name}! Your message has been received.`);
                document.getElementById("contactForm").reset();
            } else {
                alert("Please fill in all fields.");
            }
        });
    </script>

</body>
</html># flowers
