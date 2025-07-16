<h1>🧑‍💼 Employee Directory (Django Project)</h1>

<p>A simple Employee Directory web application built using <strong>Django</strong> and <strong>Bootstrap 5</strong>.<br>
This beginner-friendly project demonstrates the core concepts of Django including models, views, templates, static files, and media handling.</p>

<hr>

<h2>✨ Features</h2>
<ul>
  <li>List of all employees in a responsive table</li>
  <li>View detailed profile of each employee with image</li>
  <li>Modern UI using Bootstrap 5</li>
</ul>

<hr>

<h2>📸 Screenshots</h2>
<table>
<tr>
  <td><strong>Employee List</strong></td>
  <td><strong>Employee Profile</strong></td>
</tr>
<tr>
  <td><img src="Screenshots/Screenshot1.png" width="400"/></td>
  <td><img src="Screenshots/Screenshot2.png" width="400"/></td>
</tr>
</table>

<hr>

<h2>🚀 Getting Started</h2>

<h3>Step 1: Clone the Repository</h3>
<pre><code>git clone https://github.com/yourusername/employee-directory.git
cd employee-directory
</code></pre>

<h3>Step 2: Create a Virtual Environment</h3>
<pre><code>python -m venv env
source env/bin/activate      # For Windows: env\Scripts\activate
</code></pre>

<h3>Step 3: Install Dependencies</h3>
<pre><code>pip install -r requirements.txt
</code></pre>

<h3>Step 4: Run Migrations</h3>
<pre><code>python manage.py makemigrations
python manage.py migrate
</code></pre>

<h3>Step 5: Create Superuser (optional)</h3>
<pre><code>python manage.py createsuperuser
</code></pre>

<h3>Step 6: Run the Development Server</h3>
<pre><code>python manage.py runserver
</code></pre>

<p>Visit <a href="http://127.0.0.1:8000/">http://127.0.0.1:8000/</a> in your browser.</p>

<hr>

<h2>📁 Folder Structure</h2>

<pre><code>employee_directory/
├── employees/              # Django app with models, views, templates
├── templates/              # HTML templates
├── static/                 # Static assets (CSS/images)
├── media/                  # Uploaded employee photos
├── db.sqlite3              # Default SQLite database
├── manage.py
└── README.md
</code></pre>

<h2>📌 Requirements</h2>
<ul>
  <li>Python 3.8 or higher</li>
  <li>Django 4.x</li>
  <li>Bootstrap 5 (included via CDN)</li>
</ul>

<hr>
