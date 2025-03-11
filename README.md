/* styles.css */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px 0;
}

/* Navigation Bar */
nav {
    background: #333;
    color: #fff;
    padding: 10px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
}

nav .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav .logo {
    font-size: 1.5rem;
    font-weight: bold;
    text-decoration: none;
    color: #fff;
}

nav .nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav .nav-links a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

nav .nav-links a:hover {
    color: #77aaff;
}

/* Hero Section */
#hero {
    background: #0077ff;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

#hero h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

#hero p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

#hero .btn {
    background: #fff;
    color: #0077ff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

#hero .btn:hover {
    background: #f0f0f0;
}

/* Sections */
section {
    padding: 60px 0;
}

section h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 40px;
}

/* Skills Section */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.skill {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.skill i {
    font-size: 2rem;
    color: #0077ff;
    margin-bottom: 10px;
}

.skill h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.skill p {
    font-size: 1rem;
    color: #666;
}

/* Projects Section */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.project {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.project img {
    max-width: 100%;
    border-radius: 10px;
    margin-bottom: 10px;
}

.project h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project p {
    font-size: 1rem;
    color: #666;
}

/* Contact Section */
.contact-links {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.contact-links a {
    color: #0077ff;
    text-decoration: none;
    font-size: 1.2rem;
}

.contact-links a:hover {
    color: #0055cc;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}

footer p {
    margin: 0;
}
