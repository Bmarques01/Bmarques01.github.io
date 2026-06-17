<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bruna Marques | Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>

        <img src="images/profile.jpg" alt="Bruna Marques" class="profile-pic">

        <h1>Bruna Marques</h1>

        <h2>Computer Science Student & Cloud Enthusiast</h2>

    </header>

    <section class="about">

        <h3>About Me</h3>

        <p>
            Hello! I'm Bruna, a Computer Science student. My interests include cloud computing and
            software development. I'm constantly looking for new challenges and
            opportunities to grow professionally.
        </p>

    </section>

    <section class="skills">

        <h3>Skills</h3>

        <div class="skills-grid">

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
                <span>Python</span>
            </div>

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg">
                <span>C++</span>
            </div>

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg">
                <span>C</span>
            </div>

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
                <span>HTML</span>
            </div>

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">
                <span>CSS</span>
            </div>

            <div class="skill">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
                <span>JavaScript</span>
            </div>

            <div class="skill">
                <img src="images/aws.png">
                <span>AWS</span>
            </div>

        </div>

    </section>

    <section class="projects">

    <h3>Projects</h3>

    <div class="project-card">
        <h4>🎮 Interactive Ebook Game</h4>

        <p>
            Object-oriented C++ project featuring combat mechanics,
            inventory management and branching narratives.
        </p>
    </div>

    <div class="project-card">
        <h4>📚 Bookstore Database</h4>

        <p>
            Academic project focused on designing a relational database for a
            bookstore. Created tables, relationships and SQL queries to manage
            books, customers and sales records.
        </p>
    </div>

</section>
    <section class="contact">

        <h3>Contact</h3>

        <p>📧 Email: brunalarissamarques@hotmail.com</p>
        <p>💼 LinkedIn: https://www.linkedin.com/in/bruna-larissa-marques/</p>
        <p>💻 GitHub: https://github.com/Bmarques01</p>

    </section>

</body>
</html>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Segoe UI',sans-serif;
    background:#FAF7F2;
    color:#2D2D2D;
}

/* HERO */

header{
    text-align:center;
    padding:70px 20px;
    background:
    linear-gradient(
        180deg,
        #F4D6DC,
        #FAF7F2
    );
}

.profile-pic{
    width:180px;
    height:180px;
    border-radius:50%;
    object-fit:cover;

    border:6px solid white;

    box-shadow:
    0 10px 30px rgba(0,0,0,0.10);
}

header h1{
    margin-top:25px;
    font-size:3.2rem;
    color:#4A5D4D;
}

header h2{
    margin-top:10px;
    color:#D88C9A;
    font-weight:500;
}

header p{
    max-width:650px;
    margin:25px auto;
    line-height:1.8;
}

/* SECTIONS */

section{
    max-width:1000px;
    margin:auto;
    padding:70px 25px;
}

section h3{
    text-align:center;
    margin-bottom:35px;
    color:#4A5D4D;
    font-size:2rem;
}

/* ABOUT */

.about p{
    text-align:center;
    line-height:1.9;
    max-width:800px;
    margin:auto;
}

/* SKILLS */

.skills-grid{
    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(140px,1fr));

    gap:20px;
}

.skill{
    background:white;

    border-radius:20px;

    padding:20px;

    text-align:center;

    box-shadow:
    0 5px 15px rgba(0,0,0,0.06);

    transition:0.3s;
}

.skill:hover{
    transform:translateY(-6px);

    box-shadow:
    0 10px 20px rgba(0,0,0,0.08);
}

.skill img{
    width:60px;
    height:60px;
}

.skill span{
    display:block;
    margin-top:12px;
    font-weight:600;
    color:#4A5D4D;
}

/* PROJECTS */

.projects{
    display:flex;
    flex-direction:column;
    gap:20px;
}

.project-card{
    background:white;

    border-left:
    8px solid #D88C9A;

    padding:25px;

    border-radius:15px;

    box-shadow:
    0 5px 15px rgba(0,0,0,0.06);
}

.project-card h4{
    color:#4A5D4D;
    margin-bottom:10px;
}

.project-card p{
    line-height:1.8;
}

/* CONTACT */

.contact{
    text-align:center;
}

.contact p{
    margin:12px 0;
}

.contact a{
    color:#D88C9A;
    text-decoration:none;
    font-weight:600;
}

.contact a:hover{
    color:#4A5D4D;
}

/* FOOTER */

footer{
    background:#4A5D4D;
    color:white;

    text-align:center;

    padding:30px;
}

/* MOBILE */

@media(max-width:768px){

    header h1{
        font-size:2.4rem;
    }

    header h2{
        font-size:1.2rem;
    }

    .profile-pic{
        width:140px;
        height:140px;
    }
}
