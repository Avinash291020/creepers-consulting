<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ÇRÈÉPÊRS - Consulting Firm</title>
    <style>
        /* Add your styles here */
    </style>
</head>
<body>
    <header>
        <h1>ÇRÈÉPÊRS - Consulting Firm</h1>
    </header>
    <nav>
        <button onclick="toggleSection('home')">Home</button>
        <button onclick="toggleSection('services')">Services</button>
        <button onclick="toggleSection('contact')">Contact</button>
    </nav>
    <div class="container">
        <section id="home" class="visible">
            <h2>Welcome to ÇRÈÉPÊRS - Consulting Firm</h2>
            <img src="building-consulting-business.gif" alt="Building Consulting Business" style="max-width: 100%;">
            <p>We specialize in helping companies find the right candidates for their job openings.</p>
            <!-- Add more content here if needed -->
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Recruitment and Staffing</li>
                <li>Resume Screening</li>
                <li>Interview Coordination</li>
                <li>Job Placement Assistance</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-info">
                <!-- Contact information here -->
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 ÇRÈÉPÊRS - Consulting Firm. All rights reserved.</p>
    </footer>

    <script>
        function toggleSection(sectionId) {
            var sections = document.querySelectorAll('section');
            sections.forEach(function(section) {
                if (section.id === sectionId) {
                    section.classList.add('visible');
                } else {
                    section.classList.remove('visible');
                }
            });
        }
    </script>
</body>
</html>
