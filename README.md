<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Backend Developer Portfolio</title>

<style>
    :root {
        --bg-color: #0d1117;
        --card-color: #161b22;
        --text-color: #c9d1d9;
        --heading-color: #58a6ff;
        --border-color: #30363d;
        --accent-color: #1f6feb;
        --code-bg: #161b22;
    }

    body {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        background-color: var(--bg-color);
        color: var(--text-color);
        max-width: 960px;
        margin: auto;
        padding: 24px;
        line-height: 1.7;
    }

    h1, h2, h3 {
        color: var(--heading-color);
    }

    h1 {
        border-bottom: 2px solid var(--border-color);
        padding-bottom: 10px;
    }

    hr {
        border: none;
        height: 1px;
        background: var(--border-color);
        margin: 32px 0;
    }

    a {
        color: var(--accent-color);
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    ul {
        padding-left: 20px;
    }

    pre, code {
        background-color: var(--code-bg);
        color: #e6edf3;
        border-radius: 6px;
        font-family: Consolas, monospace;
    }

    pre {
        padding: 16px;
        overflow-x: auto;
        border: 1px solid var(--border-color);
    }

    code {
        padding: 3px 6px;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        margin-top: 16px;
        background-color: var(--card-color);
        border-radius: 8px;
        overflow: hidden;
    }

    th, td {
        padding: 12px;
        border-bottom: 1px solid var(--border-color);
        text-align: left;
    }

    th {
        background-color: #21262d;
        color: #e6edf3;
    }

    tr:hover {
        background-color: #1c2128;
    }

    .badge {
        background-color: var(--accent-color);
        color: white;
        padding: 4px 8px;
        border-radius: 6px;
        font-size: 12px;
    }

    .section {
        background-color: var(--card-color);
        padding: 20px;
        border-radius: 10px;
        margin-bottom: 24px;
        border: 1px solid var(--border-color);
    }

    footer {
        text-align: center;
        font-size: 14px;
        color: #8b949e;
        margin-top: 40px;
    }
</style>
</head>

<body>

<h1>🧠 Backend Developer Portfolio</h1>

<div class="section">
<p>
Welcome to my <strong>Backend Developer Portfolio</strong> 🚀<br>
I build <strong>secure, scalable, and maintainable backend systems</strong> with
a focus on <strong>APIs, databases, and authentication</strong>.
</p>
</div>

<div class="section">
<h2>👋 About Me</h2>
<p>
I’m an <strong>aspiring Backend Developer</strong> passionate about
<strong>server-side development and system design</strong>.
</p>

<ul>
    <li>Designing clean REST APIs</li>
    <li>Working with relational databases</li>
    <li>Implementing authentication & authorization</li>
    <li>Writing scalable backend logic</li>
</ul>
</div>

<div class="section">
<h2>🛠️ Tech Stack</h2>

<h3>Backend & APIs</h3>
<ul>
    <li>🐍 Python – Django, Django REST Framework</li>
    <li>🌐 RESTful APIs – CRUD, pagination, auth</li>
</ul>

<h3>Databases</h3>
<ul>
    <li>🗄 PostgreSQL / MySQL</li>
    <li>📦 SQLite (development)</li>
    <li>🔍 Django ORM</li>
</ul>

<h3>Authentication & Security</h3>
<ul>
    <li>🔐 JWT & session-based authentication</li>
    <li>🧾 Role-based access control (RBAC)</li>
</ul>

<h3>Tools & DevOps (Basics)</h3>
<ul>
    <li>🐙 Git & GitHub</li>
    <li>🐳 Docker (Basics)</li>
    <li>☁️ Deployment: Render / Railway / AWS</li>
</ul>
</div>

<div class="section">
<h2>📂 Standard Project Structure</h2>

<pre>
project-name/
│── app/
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
│── config/
│── requirements.txt
│── README.md
│── .env.example
</pre>

<p>This structure ensures <strong>clean architecture and scalability</strong>.</p>
</div>

<div class="section">
<h2>⭐ Featured Projects</h2>

<table>
<tr>
    <th>Project</th>
    <th>Description</th>
    <th>Core Concepts</th>
</tr>
<tr>
    <td><strong>Todo API</strong></td>
    <td>REST API with authentication and CRUD operations</td>
    <td>APIs, Auth</td>
</tr>
<tr>
    <td><strong>User Auth System</strong></td>
    <td>JWT login, registration, password hashing</td>
    <td>Security</td>
</tr>
<tr>
    <td><strong>Blog Backend</strong></td>
    <td>Users, posts, comments, likes</td>
    <td>Relational DB</td>
</tr>
<tr>
    <td><strong>E-commerce Backend</strong></td>
    <td>Products, orders, cart, mock payment</td>
    <td>Business Logic</td>
</tr>
<tr>
    <td><strong>RBAC API</strong></td>
    <td>Admin/User permissions & protected routes</td>
    <td>Authorization</td>
</tr>
</table>
</div>

<div class="section">
<h2>🔄 API Features</h2>
<ul>
    <li>CRUD operations</li>
    <li>Pagination & filtering</li>
    <li>Authentication & authorization</li>
    <li>Input validation & error handling</li>
    <li>REST best practices</li>
</ul>
</div>

<div class="section">
<h2>▶️ Run Locally</h2>

<pre>
git clone https://github.com/yourusername/backend-portfolio.git
</pre>
<pre>
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
</pre>
<pre>
pip install -r requirements.txt
</pre>
<pre>
python manage.py runserver
</pre>
</div>

<div class="section">
<h2>🎯 Goals</h2>
<ul>
    <li>Build production-ready backend systems</li>
    <li>Prepare for backend interviews</li>
    <li>Demonstrate system design thinking</li>
    <li>Show clean backend architecture</li>
</ul>
</div>

<div class="section">
<h2>🚀 Roadmap</h2>
<ul>
    <li>Advanced Django REST patterns</li>
    <li>Redis caching</li>
    <li>Celery background jobs</li>
    <li>Swagger / OpenAPI docs</li>
    <li>Production deployments</li>
</ul>
</div>

<div class="section">
<h2>🤝 Connect With Me</h2>
<p>
📧 <a href="mailto:your-email@example.com">your-email@example.com</a><br>
💼 LinkedIn: your-linkedin-url<br>
🐙 GitHub: your-github-profile
</p>
</div>

<footer>
    Built with ❤️ for Backend Engineering
</footer>

</body>
</html>
