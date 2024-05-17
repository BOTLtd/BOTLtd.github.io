<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real-Time Monitoring and Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            color: #fff;
            padding: 10px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#dashboard">Dashboard</a></li>
            <li><a href="#partner-signup">Partner Signup</a></li>
            <li><a href="#consultation">Consultation</a></li>
        </ul>
    </nav>
    
    <section id="dashboard">
        <h1>Grafana Dashboard</h1>
        <iframe src="[URL_OF_YOUR_GRAFANA_DASHBOARD](https://botltd.grafana.net/d/c1385932-e8b5-481e-a999-f716359f8cf2/overview-celsius?orgId=1)" width="100%" height="600" frameborder="0"></iframe>
    </section>
    
    <section id="partner-signup">
        <h1>Partner Signup</h1>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <button type="submit">Submit</button>
        </form>
    </section>
    
    <section id="consultation">
        <h1>Consultation and Analysis</h1>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
        <ul>
            <li><a href="#partner-signup">Partner Signup</a></li>
            <li><a href="#consultation">Consultation</a></li>
            <li><a href="mailto:info@example.com">Contact Us</a></li>
        </ul>
    </footer>
</body>
</html>
