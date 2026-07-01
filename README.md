<style>
    .container {
        max-width: 1200px;
        margin: 0 auto;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    
    .header {
        background: linear-gradient(135deg, #FF7A59 0%, #FFB347 100%);
        border-radius: 12px;
        padding: 40px 20px;
        text-align: center;
        color: white;
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
        margin-bottom: 30px;
    }
    
    .header h1 {
        font-size: 2.5em;
        margin: 0;
        font-weight: 700;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    }
    
    .header p {
        font-size: 1.2em;
        margin: 10px 0 0 0;
        opacity: 0.95;
    }
    
    .badges {
        display: flex;
        justify-content: center;
        gap: 15px;
        margin: 20px 0;
        flex-wrap: wrap;
    }
    
    .badge {
        padding: 8px 16px;
        border-radius: 25px;
        font-weight: 600;
        font-size: 0.9em;
        transition: transform 0.3s, box-shadow 0.3s;
    }
    
    .badge:hover {
        transform: translateY(-2px);
        box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }
    
    .badge-python { background: #3776AB; color: white; }
    .badge-sql { background: #336791; color: white; }
    .badge-powerbi { background: #F2C811; color: black; }
    
    .section {
        background: white;
        border-left: 4px solid #FF7A59;
        border-radius: 8px;
        padding: 25px;
        margin-bottom: 25px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    }
    
    .section h2 {
        color: #FF7A59;
        font-size: 1.6em;
        margin-top: 0;
        display: flex;
        align-items: center;
        gap: 10px;
    }
    
    .section h3 {
        color: #333;
        font-size: 1.3em;
        margin: 20px 0 15px 0;
    }
    
    .feature-list {
        list-style: none;
        padding-left: 0;
    }
    
    .feature-list li {
        padding: 10px 0 10px 30px;
        position: relative;
        color: #333;
        line-height: 1.6;
    }
    
    .feature-list li:before {
        content: "✓";
        position: absolute;
        left: 0;
        color: #FF7A59;
        font-weight: bold;
        font-size: 1.2em;
    }
    
    .tools-table {
        width: 100%;
        border-collapse: collapse;
        margin: 20px 0;
    }
    
    .tools-table th {
        background: linear-gradient(135deg, #FF7A59 0%, #FFB347 100%);
        color: white;
        padding: 15px;
        text-align: left;
        font-weight: 600;
    }
    
    .tools-table td {
        padding: 12px 15px;
        border-bottom: 1px solid #eee;
    }
    
    .tools-table tr:hover {
        background: #f9f9f9;
    }
    
    .tools-table tr:nth-child(even) {
        background: #f5f5f5;
    }
    
    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
        margin: 20px 0;
    }
    
    .gallery-item {
        border-radius: 8px;
        overflow: hidden;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    
    .gallery-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }
    
    .gallery-item img {
        width: 100%;
        height: auto;
        display: block;
    }
    
    .gallery-label {
        background: #333;
        color: white;
        padding: 12px;
        text-align: center;
        font-weight: 600;
    }
    
    .file-tree {
        background: #f5f5f5;
        border: 1px solid #ddd;
        border-radius: 6px;
        padding: 20px;
        font-family: 'Courier New', monospace;
        font-size: 0.95em;
        overflow-x: auto;
        line-height: 1.8;
    }
    
    .workflow-diagram {
        background: #f9f9f9;
        border: 2px dashed #FF7A59;
        border-radius: 8px;
        padding: 20px;
        margin: 20px 0;
        text-align: center;
    }
    
    .footer {
        background: linear-gradient(135deg, #FF7A59 0%, #FFB347 100%);
        border-radius: 12px;
        padding: 30px 20px;
        text-align: center;
        color: white;
        margin-top: 40px;
    }
    
    .footer p {
        margin: 10px 0;
        font-size: 1.1em;
        font-weight: 500;
    }
    
    .cta-button {
        display: inline-block;
        background: white;
        color: #FF7A59;
        padding: 12px 30px;
        border-radius: 25px;
        text-decoration: none;
        font-weight: 600;
        margin-top: 15px;
        transition: transform 0.3s, box-shadow 0.3s;
    }
    
    .cta-button:hover {
        transform: scale(1.05);
        box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    
    .highlight-box {
        background: linear-gradient(135deg, rgba(255, 122, 89, 0.1) 0%, rgba(255, 179, 71, 0.1) 100%);
        border-left: 4px solid #FF7A59;
        padding: 15px;
        border-radius: 6px;
        margin: 15px 0;
    }
</style>

<div class="container">

<div class="header">
    <h1>📊 Amazon Sales Analytics</h1>
    <p>From Raw Data to Actionable Insights</p>
</div>

<div class="badges">
    <span class="badge badge-powerbi">🎨 Power BI Dashboard</span>
    <span class="badge badge-python">🐍 Python Analysis</span>
    <span class="badge badge-sql">🗄️ SQL Queries</span>
</div>

<div class="section">
    <h2>🌟 About This Project</h2>
    <p>This repository presents a <strong>complete Amazon sales analytics journey</strong> built around data cleaning, exploratory analysis, SQL-based querying, and an interactive Power BI dashboard. It is designed to showcase professional data analysis techniques and business intelligence best practices.</p>
    
    <p>The project focuses on understanding:</p>
    <ul class="feature-list">
        <li>Revenue trends and performance metrics</li>
        <li>Customer behavior and purchasing patterns</li>
        <li>Product performance and category insights</li>
        <li>Geographic sales distribution</li>
        <li>Shipping efficiency and payment preferences</li>
    </ul>
</div>

<div class="section">
    <h2>🎯 Core Objectives</h2>
    <ul class="feature-list">
        <li>Analyze total sales and revenue performance</li>
        <li>Identify high-performing products and categories</li>
        <li>Understand customer purchasing patterns</li>
        <li>Examine regional and market-level sales trends</li>
        <li>Review payment preferences and shipping behavior</li>
        <li>Create an executive-style dashboard for quick decision-making</li>
    </ul>
</div>

<div class="section">
    <h2>🛠️ Tools & Technologies</h2>
    <table class="tools-table">
        <thead>
            <tr>
                <th>Tool</th>
                <th>Role</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Python</strong></td>
                <td>Data cleaning, preprocessing, and exploratory analysis</td>
            </tr>
            <tr>
                <td><strong>SQL</strong></td>
                <td>Querying and business logic implementation</td>
            </tr>
            <tr>
                <td><strong>Power BI</strong></td>
                <td>Dashboard design and interactive reporting</td>
            </tr>
            <tr>
                <td><strong>DAX</strong></td>
                <td>KPI calculations and custom measures</td>
            </tr>
            <tr>
                <td><strong>Power Query</strong></td>
                <td>Data transformation and shaping</td>
            </tr>
        </tbody>
    </table>
</div>

<div class="section">
    <h2>🔄 Workflow Pipeline</h2>
    <div class="workflow-diagram">
        <strong>Raw Amazon Dataset</strong> → <strong>Python Cleaning</strong> → <strong>EDA</strong> → <strong>SQL Queries</strong> → <strong>Power BI Measures</strong> → <strong>Interactive Dashboard</strong> → <strong>Actionable Insights</strong>
    </div>
</div>

<div class="section">
    <h2>📊 Dashboard Highlights</h2>
    <div class="highlight-box">
        <strong>✨ Interactive Features:</strong>
    </div>
    <ul class="feature-list">
        <li>Executive overview of sales performance with KPIs</li>
        <li>Product and category performance analysis</li>
        <li>Customer segmentation and purchase behavior</li>
        <li>Regional sales insights by geography</li>
        <li>Shipping and payment analysis for operational understanding</li>
    </ul>
</div>

<div class="section">
    <h2>📸 Preview Gallery</h2>
    <div class="gallery">
        <div class="gallery-item">
            <img src="EXECUTIVE.png" alt="Executive dashboard overview" />
            <div class="gallery-label">Executive Summary</div>
        </div>
        <div class="gallery-item">
            <img src="PRODUCT.png" alt="Product performance page" />
            <div class="gallery-label">Product Performance</div>
        </div>
        <div class="gallery-item">
            <img src="CUSTOMERS.png" alt="Customer insights dashboard" />
            <div class="gallery-label">Customer Analysis</div>
        </div>
        <div class="gallery-item">
            <img src="GEOGRAPHY.png" alt="Regional sales dashboard" />
            <div class="gallery-label">Geographic Insights</div>
        </div>
    </div>
</div>

<div class="section">
    <h2>📁 Project Structure</h2>
    <div class="file-tree">
Amazon-Sales-Analytics/<br>
├── 📄 Amazon.csv<br>
├── 📓 Amazon_data_cleaning.ipynb<br>
├── 🔍 amazon_sql.sql<br>
├── 📊 Amazon Sales DAX.pbix<br>
├── 🖼️ EXECUTIVE.png<br>
├── 🖼️ PRODUCT.png<br>
├── 🖼️ CUSTOMERS.png<br>
├── 🖼️ GEOGRAPHY.png<br>
├── 📋 LICENSE<br>
└── 📖 README.md
    </div>
</div>

<div class="section">
    <h2>💡 Business Value</h2>
    <p>This project helps turn large volumes of e-commerce data into understandable metrics and visuals that support:</p>
    <ul class="feature-list">
        <li>Better sales decisions and strategic planning</li>
        <li>Performance tracking and KPI monitoring</li>
        <li>Identification of market opportunities</li>
        <li>Customer insights and behavior understanding</li>
        <li>Operational efficiency improvements</li>
    </ul>
</div>

<div class="section">
    <h2>🚀 How to Explore</h2>
    <ol style="padding-left: 20px; line-height: 1.8;">
        <li>📓 Open the <strong>notebook</strong> for the complete analysis workflow</li>
        <li>🔍 Review the <strong>SQL file</strong> for business queries and logic</li>
        <li>📊 Open the <strong>Power BI file</strong> for interactive exploration</li>
        <li>🖼️ Check the <strong>screenshots</strong> for quick visual summary</li>
    </ol>
</div>

<div class="section">
    <h2>⭐ Why It Stands Out</h2>
    <div class="highlight-box">
        It combines <strong>analytical depth</strong>, <strong>storytelling</strong>, and <strong>visualization</strong> in a way that is ideal for resumes, portfolios, internships, and analytics interviews.
    </div>
</div>

<div class="footer">
    <p>🎓 Built with Passion for Data Analysis</p>
    <div class="badges" style="justify-content: center;">
        <span class="badge badge-python" style="color: white;">Python</span>
        <span class="badge badge-sql" style="color: white;">SQL</span>
        <span class="badge badge-powerbi">Power BI</span>
    </div>
    <p style="font-size: 0.95em; margin-top: 20px;">Crafted for data-driven decision making</p>
</div>

</div>