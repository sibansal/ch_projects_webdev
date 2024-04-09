# Introduction to Capstone Project
## Made with 💝 for Christel House Students 😊
## Global Styling
```
*
{
    box-sizing: border-box;
    margin: 0;
}

body
{
    font-family: 'Times New Roman', Times, serif;
    max-width: 100vw;
    color: darkslategrey;
}

a, a:hover
{
    color: inherit;
    text-decoration: inherit;
}

a:hover
{
    font-weight: bold;
}
```


## Design Nav Bar
### Markup
```
    <header>
        <h2>Abhay Kumar</h2>
        <nav>
            <ul>
                <li>Home</li>
                <li>Achievements</li>
                <li>Contact</li>
            </ul>
        </nav>
    </header>
```

### Styling
```
header
{
    height: 10vh;
    width: 100%;
    padding: 25px;
}

header h2
{
    float: left;
    font-family: cursive;
    font-size: medium;
}

header nav
{
    float: right;
}

header nav ul
{
    list-style-type: none;
}

header nav ul li
{
    font-weight: bold;
    display: inline-block;
    padding: 10px;
}

header nav ul li:hover
{
    cursor: pointer;
    opacity: 0.8;
    text-decoration: underline;
}
```

## Hero Section

### Markup
```
<section id="hero">
    <h1>👋 Hi, I am Abhay Kumar</h1>
    <h2>I am high school student, I love coding 👨‍💻</h2>
    <a class="btn" href="#About">Contact Me</a>
</section>
```

### Styling
```
#hero
{
    background-attachment: fixed;
    background-image: url('../img/hero.jpg');
    background-size: cover;
    width: 100%;
    height: 90vh;
    text-align: center;
    align-content: center;
    font-size: xx-large;
    line-height: 2;
}

#hero .btn
{
    border-radius: 10px;
    background: orange;
    color: white;
    padding: 10px;
}
```

## General Section Styling
```
main section
{
    padding: 20px 0;
}
main section h2
{
    font-size: xx-large;
    text-align: center;
    margin: 48px 0;
}
```

## Achievement Section

### Markup
```
        <section id = "Achievements">
            <h2>Achievements</h2>
            <table>
                <tr>
                    <td>
                        <img class="trophy" src="assets/img/trophy-icon.svg" alt="Achievements">
                    </td>
                    <td>
                        <ul>
                            <li><span>Science Fair Success:</span> I won a science fair with my innovative project.</li>
                            <li><span>Research Publication:</span> I have won the opportunity to publish my research findings in a scientific journal.</li>
                            <li><span>Academic Excellence:</span> I have won the distinction of maintaining a perfect GPA in science subjects.</li>
                            <li><span>National Science Olympiad:</span> I won a medal in a national science Olympiad, showcasing my knowledge and skills.</li>
                            <li><span>STEM Competition:</span> I won accolades in STEM competitions, demonstrating my prowess in science, technology, engineering, and mathematics.</li>
                            <li><span>Prestigious Internship:</span> I secured a prestigious science internship, winning the opportunity to gain valuable hands-on experience.</li>
                            <li><span>Scholarship Recipient:</span> I won a scholarship for my outstanding academic achievements in science and technology-related fields.</li>
                            <li><span>Leadership Role:</span> I won the chance to serve as a leader in a science club, organizing events and projects.</li>
                            <li><span>AP Exam Success:</span> I won recognition for achieving top scores on Advanced Placement (AP) exams in various science subjects.</li>
                            <li><span>College Acceptance:</span> I won admission into a top-tier university for a science major, setting the stage for my future academic and career success.</li>
                          </ul>                          
                    </td>
                </tr>
            </table>
        </section>
```

### Styling
```
#Achievements .trophy
{
    height: 300px;
    width: 300px;
}

#Achievements table
{
    font-size: medium;
    width: 95%;
}

#Achievements table td
{
    width: 50%;
}

#Achievements table td:first-child
{
    text-align: center;
}

#Achievements table td:last-child
{
    line-height: 1.5;
    text-align: justify;
}

#Achievements table td:last-child span
{
    font-weight: bold;
}
```

## Contact Section

### Markup
```
        <section id="Contact">
            <h2>Contact</h2>
            <form action="/submit_contact_form" method="post">
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="phone">Phone:</label><br>
                <input type="tel" id="phone" name="phone"><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </section>
```

### Styling
```
/*Contact Section*/
#Contact
{
    background-color: bisque;
    line-height: 2;
}

#Contact form
{
    width: 50%;
    margin: 0 auto;
    padding: 0;
}

#Contact form input, textarea
{
    width: 100%;
}
```

## Footer Section

### Markup
```
<footer>
    <p>&copy; 2024 Abhay Kumar. All rights reserved.</p>
</footer>
```

### Styling
```
footer
{
    font-size: large;
    padding: 10px;
    background: darkslategrey;
    color: white;
    text-align: center;
}
```