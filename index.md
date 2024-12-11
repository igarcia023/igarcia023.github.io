<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#awards">Awards</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h1>Hi, I'm Israel Garcia</h1>
        <p>A Computer Science student at <a href="http://www.fullerton.edu/">Cal State Fullerton</a>. Welcome to my online portfolio! Here you’ll find details about my academic background, work experience, projects, and achievements. Feel free to contact me using the form at the bottom of this page.</p>
    </section>
    
    <section id="education">
        <h2>Education</h2>
        <ul>
            <li>
                <strong>Santa Ana High School</strong> - 2024 Graduation Year
                <p>Relevant Courses: AP Computer Science, Advanced Math, AP Physics</p>
                <p></p>
                <strong>Cal State Fullerton</strong> - 2028 Graduation Year
                <p>...In Progress</p>
            </li>
        </ul>
    </section>
    
    <section id="experience">
        <h2>Work Experience</h2>
        <ul>
            <li>
                <strong>Stocker - Target</strong>  
                <p><em>June 2022 - May 2023</em></p>
                <p>Responsibilities include stocking of products, providing customer service, and ensuring inventory accuracy.</p>
            </li>
            <li>
                <strong>Customer Service - DonnerG Turkish & Mediterranean Grill</strong>  
                <p><em>May 2023 - Present</em></p>
                <p>Greeted customers, managed orders, and ensured a pleasant dining experience.</p>
            </li>
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <p>GitHub Page is <a href="https://github.com/igarcia023">https://github.com/igarcia023</a>.</p>
        <ul>
        <h3>CPSC 120</h3>
            <li>
                <strong>Lap 6 part 2 - BlackJack Score.</strong>
                <p>What I learned: I learned how to validate user inputs, identify specific card types, and implement scoring rules, including special cases like the ace bonus. It also enhanced my understanding of handling conditional logic, working with functions to break down complex tasks, and ensuring the program operates accurately under different scenarios.</p>
            </li>
            <li>
                <strong>Lap 7 part 1 - Parking Rules.</strong>
                <p>What I learned: This lab is one of my favorites because it combines real-world problem-solving with logical thinking in a practical scenario. I learned how to analyze complex parking rules and translate them into precise conditional statements in code.</p>
            </li>
            <li>
                <strong>Lap 12 part 2 - Beautiful Noise.</strong>
                <p>What I learned: This lab is my favorite because it blends creativity with programming, allowing me to design visually dynamic images while exploring the role of randomness in computational art. I learned how to use random number generators to create unpredictable patterns and how to combine loops, conditions, and image processing techniques to build layered and unique visual outputs.</p>
            </li>
            <li>
                <strong>Personal Portfolio Website</strong>
                <p>Developed this responsive portfolio website using HTML and CSS.</p>
            </li>
        </ul>
    </section>
    
    <section id="awards">
        <h2>Awards</h2>
        <ul>
            <li>Principal Honor Roll (2020-2021, 2022-2023)</li>
            <li>Employee of the Month - DonnerG Turkish & Mediterranean Grill</li>
        </ul>
    </section>
    
    <footer id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </footer>
</body>
</html>
