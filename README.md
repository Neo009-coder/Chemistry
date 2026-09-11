<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>12th Grade Chemistry Hub</title>
    <style>
        /* CSS Styles */
        :root {
            --primary-color: #005f73;
            --secondary-color: #0a9396;
            --accent-color: #e9d8a6;
            --bg-color: #f8f9fa;
            --text-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        /* Navigation */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        nav h1 {
            font-size: 1.5rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 1.5rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--accent-color);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 95, 115, 0.8), rgba(10, 147, 150, 0.8)), url('https://images.unsplash.com/photo-1532094349884-543bc11b234d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80') center/cover;
            color: white;
            text-align: center;
            padding: 6rem 2rem;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem;
        }

        /* Container for Sections */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        h2.section-title {
            text-align: center;
            color: var(--primary-color);
            font-size: 2.5rem;
            margin-bottom: 3rem;
            border-bottom: 3px solid var(--secondary-color);
            display: inline-block;
            padding-bottom: 0.5rem;
        }

        /* Grid Layout for Chapters */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            padding: 2rem;
            transition: transform 0.3s;
            border-top: 5px solid var(--secondary-color);
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .card h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .card ul {
            margin-left: 1.5rem;
            margin-bottom: 1.5rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--secondary-color);
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 4px;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: var(--primary-color);
        }

        /* Notes Table */
        table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border-radius: 8px;
            overflow: hidden;
        }

        th, td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: var(--primary-color);
            color: white;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        /* Footer */
        footer {
            background-color: var(--text-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <nav>
            <h1>🧪 Chem12 Hub</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#syllabus">Syllabus</a></li>
                <li><a href="#notes">Notes</a></li>
                <li><a href="#resources">Resources</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Master 12th Grade Chemistry</h2>
        <p>Your one-stop destination for Physical, Inorganic, and Organic Chemistry notes, formulas, and video resources.</p>
        <a href="#syllabus" class="btn" style="font-size: 1.2rem; padding: 1rem 2rem;">Start Learning</a>
    </section>

    <!-- Syllabus/Chapters Section -->
    <section id="syllabus" class="container">
        <div style="text-align: center;">
            <h2 class="section-title">Complete Syllabus</h2>
        </div>
        <div class="grid">
            <!-- Physical Chemistry -->
            <div class="card">
                <h3>⚛️ Physical Chemistry</h3>
                <p>Master the math and concepts of chemical behavior.</p>
                <br>
                <ul>
                    <li><strong>Solutions:</strong> Raoult's Law, Colligative properties.</li>
                    <li><strong>Electrochemistry:</strong> Nernst equation, Kohlrausch law.</li>
                    <li><strong>Chemical Kinetics:</strong> Order of reaction, Arrhenius equation.</li>
                </ul>
            </div>

            <!-- Inorganic Chemistry -->
            <div class="card">
                <h3>💎 Inorganic Chemistry</h3>
                <p>Explore the periodic table and bonding theories.</p>
                <br>
                <ul>
                    <li><strong>d and f Block Elements:</strong> Transition metals, Lanthanoids.</li>
                    <li><strong>Coordination Compounds:</strong> Werner's theory, VBT, CFT, Isomerism.</li>
                </ul>
            </div>

            <!-- Organic Chemistry -->
            <div class="card">
                <h3>🌿 Organic Chemistry</h3>
                <p>Learn reaction mechanisms, naming, and synthesis.</p>
                <br>
                <ul>
                    <li><strong>Haloalkanes & Haloarenes:</strong> SN1 & SN2 mechanisms.</li>
                    <li><strong>Alcohols, Phenols & Ethers:</strong> Preparation and properties.</li>
                    <li><strong>Aldehydes, Ketones & Carboxylic Acids:</strong> Nucleophilic addition.</li>
                    <li><strong>Biomolecules:</strong> Carbohydrates, Proteins, DNA/RNA.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Downloadable Notes Section -->
    <section id="notes" class="container" style="background-color: white; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.05);">
        <div style="text-align: center;">
            <h2 class="section-title">Chapter-wise PDF Notes</h2>
        </div>
        <p style="text-align: center; margin-bottom: 2rem;">Click on the buttons below to access handwritten and typed notes for your exam preparation.</p>
        
        <div style="overflow-x:auto;">
            <table>
                <thead>
                    <tr>
                        <th>Chapter Name</th>
                        <th>Category</th>
                        <th>Download Link</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1. Solutions</td>
                        <td>Physical</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Solutions PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>2. Electrochemistry</td>
                        <td>Physical</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Electrochemistry PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>3. Chemical Kinetics</td>
                        <td>Physical</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Kinetics PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>4. d- and f-Block Elements</td>
                        <td>Inorganic</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading d/f Block PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>5. Coordination Compounds</td>
                        <td>Inorganic</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Coordination PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>6. Haloalkanes & Haloarenes</td>
                        <td>Organic</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Haloalkanes PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>7. Aldehydes, Ketones & Acids</td>
                        <td>Organic</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Aldehydes PDF...')">Download PDF</a></td>
                    </tr>
                    <tr>
                        <td>8. Biomolecules</td>
                        <td>Organic</td>
                        <td><a href="#" class="btn" onclick="alert('Downloading Biomolecules PDF...')">Download PDF</a></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <!-- External Resources & Links Section -->
    <section id="resources" class="container">
        <div style="text-align: center;">
            <h2 class="section-title">Important Video Links & Tools</h2>
        </div>
        <div class="grid">
            <div class="card">
                <h3>📺 Khan Academy Chemistry</h3>
                <p>Free, world-class video lectures explaining complex 12th-grade chemistry mechanisms.</p>
                <br>
                <a href="https://www.khanacademy.org/science/chemistry" target="_blank" class="btn">Visit Khan Academy</a>
            </div>
            
            <div class="card">
                <h3>🧪 PhET Interactive Simulations</h3>
                <p>Visualize chemistry! Interactive models for molecules, balancing equations, and more.</p>
                <br>
                <a href="https://phet.colorado.edu/en/simulations/filter?subjects=chemistry&type=html" target="_blank" class="btn">Open PhET</a>
            </div>

            <div class="card">
                <h3>📚 NCERT / Standard Textbooks</h3>
                <p>Access the official digital copies of the standard Chemistry textbooks for 12th grade.</p>
                <br>
                <a href="https://ncert.nic.in/textbook.php?lech1=0-9" target="_blank" class="btn">Official Books</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Chem12 Hub. All rights reserved for educational purposes.</p>
        <p style="font-size: 0.9rem; margin-top: 10px;">Remember: Practice numericals and reaction mechanisms daily!</p>
    </footer>

    <!-- Smooth Scrolling Script -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
