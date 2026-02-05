<h1>🚀 Coders of Delhi — Data Analysis with Pure Python</h1>
<p><strong>A social-network data analysis project built entirely using core Python in Jupyter Notebook</strong></p>

<hr>

<h2>🏙️ Project Story (Case Scenario)</h2>
<div class="box">
    <p>
        You’ve just been hired as a <strong>Data Scientist Intern</strong> at
        <strong>CodeBook — The Social Media for Coders</strong>, a Delhi-based startup.
    </p>
    <p>
        🎯 Goal:
        <ul>
            <li>1-month internship</li>
            <li>₹10 LPA full-time offer</li>
            <li><span class="highlight">Only Pure Python allowed</span></li>
        </ul>
    </p>
    <p>
        Your task is to analyze a large JSON data dump and build real social-media
        features from scratch.
    </p>
</div>

<h2>🧠 What This Project Covers</h2>
<ul>
    <li>Data loading & exploration</li>
    <li>Data cleaning & restructuring</li>
    <li>Social graph analysis</li>
    <li>Friend recommendations</li>
    <li>Page recommendations</li>
    <li>All logic written using core Python</li>
</ul>

<h2>🛠️ Tech Stack</h2>
<ul>
    <li><strong>Language:</strong> Python 🐍</li>
    <li><strong>Environment:</strong> Jupyter Notebook</li>
    <li><strong>Libraries Used:</strong> json (built-in)</li>
    <li>❌ No pandas</li>
    <li>❌ No numpy</li>
    <li>❌ No sklearn</li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
Coders_of_Delhi/
│
├── data.json
├── data2.json
├── massive_data.json
├── cleaned_data2.json
│
├── Problem_Statement.ipynb
├── Data_cleaning.ipynb
├── People_you_may_know.ipynb
├── Pages_you_might_like.ipynb
│
└── README.html
</pre>

<h2>📌 Task 1: Load & Explore the Data</h2>
<p>The dataset contains:</p>
<ul>
    <li>Users</li>
    <li>Friends (connections)</li>
    <li>Liked pages</li>
</ul>

<h3>Sample JSON Format</h3>
<pre>
{
  "users": [
    {"id": 1, "name": "Amit", "friends": [2, 3], "liked_pages": [101]}
  ],
  "pages": [
    {"id": 101, "name": "Python Developers"}
  ]
}
</pre>

<h2>🧹 Task 2: Data Cleaning & Structuring</h2>
<h3>Issues Identified</h3>
<ul>
    <li>Missing user names</li>
    <li>Duplicate friend IDs</li>
    <li>Inactive users</li>
    <li>Duplicate page entries</li>
</ul>

<h3>Cleaning Actions</h3>
<ul>
    <li>Removed users with empty names</li>
    <li>Removed duplicate friends</li>
    <li>Removed inactive users</li>
    <li>Deduplicated pages</li>
</ul>

<p>✅ Cleaned data saved as <code>cleaned_codebook_data.json</code></p>

<h2>🤝 Task 3: People You May Know</h2>
<p>
Suggest users who are not direct friends but share mutual connections.
More mutual friends = higher priority.
</p>

<h3>Example Output</h3>
<pre>
People You May Know for User 1: [4]
</pre>

<h2>📄 Task 4: Pages You Might Like</h2>
<p>
Pages are recommended based on shared interests with other users.
Each page is scored using common liked pages.
</p>

<h3>Example Output</h3>
<pre>
[(103, 4), (104, 2)]
</pre>

<h2>🧪 Why This Project Matters</h2>
<ul>
    <li>Simulates real social-media recommendation systems</li>
    <li>Strengthens Python fundamentals</li>
    <li>Demonstrates graph-based thinking</li>
    <li>Zero shortcuts — pure logic</li>
</ul>

<h2>🚀 Future Improvements</h2>
<ul>
    <li>Map IDs to user/page names in output</li>
    <li>Graph visualizations</li>
    <li>Performance optimizations</li>
    <li>Convert logic into reusable modules</li>
</ul>

<footer>
    <p>
        <strong>Author:</strong> Aryan Srivastava <br>
        Computer Science Engineering Student  — VIT Vellore <br>
        Learning by building. Python first. Logic always.
        <a href="https://www.linkedin.com/in/aryan-codes"
             target="_blank"
             style="color:#38bdf8; text-decoration:none;">
            LinkedIn: aryan-codes
        </a>
    </p>
</footer>

</body>
</html>
