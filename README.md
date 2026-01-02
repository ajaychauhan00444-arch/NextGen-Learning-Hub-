
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextGen Learning Hub | Admissions 2026-2027</title>
    <style>
        :root { --primary: #007bff; --secondary: #28a745; --dark: #333; --light: #f4f4f4; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; line-height: 1.6; background: var(--light); color: var(--dark); }
        header { background: var(--primary); color: white; padding: 40px 20px; text-align: center; }
        .container { max-width: 1100px; margin: auto; padding: 20px; }
        .section { background: white; padding: 25px; margin-bottom: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        h2 { color: var(--primary); border-bottom: 2px solid var(--primary); display: inline-block; margin-bottom: 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .card { background: #fff; border: 1px solid #ddd; padding: 15px; border-radius: 8px; }
        table { width: 100%; border-collapse: collapse; margin-top: 10px; }
        table th, table td { border: 1px solid #ddd; padding: 10px; text-align: left; }
        table th { background: var(--primary); color: white; }
        .btn { background: var(--secondary); color: white; padding: 12px 20px; text-decoration: none; border-radius: 5px; display: inline-block; font-weight: bold; border: none; cursor: pointer; }
        .insta-link { color: #e1306c; font-weight: bold; text-decoration: none; }
        input, select, textarea { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
    </style>
</head>
<body>

<header>
    <h1>NextGen Learning Hub</h1>
    <p>Admissions Open for Academic Session 2026-2027</p>
</header>

<div class="container">
    <div class="grid">
        <div class="section">
            <h2>Our Vision</h2>
            <p>To be a premier <strong>Learning Hub</strong> that empowers students with modern technical skills and practical knowledge for a bright future.</p>
        </div>
        <div class="section">
            <h2>Our Mission</h2>
            <p>As a dedicated <strong>Education Centre</strong>, our mission is to provide high-quality training in coding, languages, and professional skills to every student.</p>
        </div>
    </div>

    <div class="section">
        <h2>What You Will Learn</h2>
        <div class="grid">
            <div class="card">
                <h3>Programming (Python/HTML/CSS)</h3>
                <p>From the basics of logic to building real-world websites. Master Python for data and HTML/CSS for web design.</p>
            </div>
            <div class="card">
                <h3>English Speaking</h3>
                <p>Improve your communication skills, grammar, and confidence for professional interviews and daily life.</p>
            </div>
            <div class="card">
                <h3>Computer Basics</h3>
                <p>Essential skills including MS Office, Internet usage, and digital literacy for everyone.</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Class Schedule (2:00 PM - 8:00 PM)</h2>
        <table>
            <tr><th>Time</th><th>Class Subject</th></tr>
            <tr><td>02:00 PM - 03:00 PM</td><td>Python Programming</td></tr>
            <tr><td>03:00 PM - 04:00 PM</td><td>HTML Web Design</td></tr>
            <tr><td>04:00 PM - 05:00 PM</td><td>CSS Styling</td></tr>
            <tr><td>05:00 PM - 06:00 PM</td><td>English Speaking</td></tr>
            <tr><td>06:00 PM - 08:00 PM</td><td>Computer Basics</td></tr>
        </table>
    </div>

    <div class="section">
        <h2>Student Registration 2026-2027</h2>
        <form id="regForm">
            <input type="text" id="name" placeholder="Student Full Name" required>
            <select id="course">
                <option value="Python">Python Class</option>
                <option value="Web Development">Web Development (HTML/CSS)</option>
                <option value="English Speaking">English Speaking</option>
                <option value="Computer Basic">Computer Basic</option>
            </select>
            <input type="tel" id="phone" placeholder="Your WhatsApp Number" required>
            <button type="button" class="btn" onclick="sendToWhatsApp()">Submit & Register via WhatsApp</button>
        </form>
    </div>

    <div class="section" style="text-align: center;">
        <h2>Contact Us</h2>
        <p><strong>Founder:</strong> Ajay Chauhan</p>
        <p><strong>Address:</strong> 6S Uncha Gaon, Kairana, Shamli, Uttar Pradesh</p>
        <p><strong>Email:</strong> ajaychauhan00444@gmail.com</p>
        <p><strong>Call:</strong> 95285 08284 | <strong>Alt:</strong> 9997655195</p>
        <p>Follow us on Instagram: <a href="https://instagram.com/ajay_chauhan_no_need" class="insta-link">@ajay_chauhan_no_need</a></p>
    </div>
</div>

<script>
    function sendToWhatsApp() {
        const name = document.getElementById('name').value;
        const course = document.getElementById('course').value;
        const phone = document.getElementById('phone').value;
        
        const message = `Hello Ajay Sir, I want to register for Admission 2026-2027.%0A%0A*Name:* ${name}%0A*Course:* ${course}%0A*Contact:* ${phone}`;
        const whatsappUrl = `https://wa.me/919528508284?text=${message}`;
        
        window.open(whatsappUrl, '_blank');
    }
</script>

</body>
</html>
