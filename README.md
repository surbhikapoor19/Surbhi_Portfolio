<div class="hero-links">
<a href="https://www.linkedin.com/in/surbhikapoor19" target="_blank">LinkedIn</a> · 
<a href="https://github.com/surbhikapoor19" target="_blank">GitHub</a> · 
<a href="mailto:surbhi.kapoor19@gmail.com">Email</a>
</div>

## About Me

I'm a Data Scientist pursuing my **MS in Data Science at WPI (4.0 GPA)** with 6+ years of industry experience. I build end-to-end NLP and ML systems—from model design to production deployment.

Currently focused on **Document AI**, **Healthcare ML**, and **Agentic Workflows**.

---

## Education

<div class="education-grid">

<div class="education-card">
<h3>🎓 Worcester Polytechnic Institute</h3>
<p><strong>M.S. Data Science</strong> · GPA: 4.0</p>
<p class="date">Jan 2025 – May 2026</p>
</div>

<div class="education-card">
<h3>🎓 University of Illinois Urbana-Champaign</h3>
<p><strong>B.S. Applied Mathematics</strong></p>
<p class="date">2014 – 2018</p>
</div>

</div>

---

## Projects

<p class="section-subtitle">Click any project to learn more</p>

<div class="projects-grid">

<div class="project-card" onclick="toggleProject('mental-health')">
<div class="project-image">
<img src="images/mental_health_eda.png" alt="Mental Health Risk Prediction">
<div class="project-overlay">
<span class="expand-icon">+</span>
</div>
</div>
<div class="project-info">
<span class="project-tag">Healthcare ML</span>
<h3>Mental Health Risk Prediction</h3>
<p>Predicting psychological distress using CDC survey data</p>
</div>
</div>

<div class="project-card" onclick="toggleProject('nyc-transit')">
<div class="project-image">
<img src="images/nyc_project_areas_of_opportunity.png" alt="NYC Transit Analysis">
<div class="project-overlay">
<span class="expand-icon">+</span>
</div>
</div>
<div class="project-info">
<span class="project-tag">Geospatial</span>
<h3>NYC Underserved Transit Regions</h3>
<p>Accessibility gap analysis and ridership modeling</p>
</div>
</div>

<div class="project-card" onclick="toggleProject('greenboard')">
<div class="project-image">
<img src="images/package_details_greenboard.png" alt="WPI Greenboard">
<div class="project-overlay">
<span class="expand-icon">+</span>
</div>
</div>
<div class="project-info">
<span class="project-tag">Sustainability</span>
<h3>Carbon Emissions Intelligence</h3>
<p>Multi-carrier API tracking system for WPI</p>
</div>
</div>

<div class="project-card" onclick="toggleProject('ocr')">
<div class="project-image">
<img src="images/segmented_ocr.png" alt="Receipts OCR">
<div class="project-overlay">
<span class="expand-icon">+</span>
</div>
</div>
<div class="project-info">
<span class="project-tag">Document AI</span>
<h3>Receipts OCR Segmentation</h3>
<p>OCR + LLM text extraction with Streamlit</p>
</div>
</div>

<div class="project-card" onclick="toggleProject('supermarket')">
<div class="project-image">
<img src="images/supermarket_trend.png" alt="Supermarket ML">
<div class="project-overlay">
<span class="expand-icon">+</span>
</div>
</div>
<div class="project-info">
<span class="project-tag">Statistical ML</span>
<h3>Supermarket Profit Analysis</h3>
<p>EDA and profit margin prediction models</p>
</div>
</div>

</div>

<!-- Expandable Project Details -->

<div id="mental-health" class="project-details">
<div class="details-content">
<div class="details-header">
<h3>Mental Health Risk Prediction (NHIS)</h3>
<button class="close-btn" onclick="toggleProject('mental-health')">×</button>
</div>
<div class="details-body">
<div class="details-images">
<img src="images/mental_health_eda.png" alt="Mental Health EDA">
</div>
<div class="details-text">
<p><strong>Goal:</strong> Predict psychological distress risk using demographic and behavioral survey data.</p>
<p><strong>Dataset:</strong> 32,629 adult participants, 630 variables (CDC NHIS)</p>
<h4>Approach</h4>
<ul>
<li>Parsed coded variables into interpretable features</li>
<li>Conducted EDA to identify risk patterns</li>
<li>Trained Random Forest models for binary and multi-class severity prediction</li>
</ul>
<h4>Results</h4>
<ul>
<li>Achieved <strong>85–90% accuracy</strong></li>
<li>Identified interpretable risk factors for early screening</li>
</ul>
<a href="https://github.com/surbhikapoor19/mental_health_distress_predictor" target="_blank" class="project-link">View Repository →</a>
</div>
</div>
</div>
</div>

<div id="nyc-transit" class="project-details">
<div class="details-content">
<div class="details-header">
<h3>Assessing Underserved Transit Regions (NYC)</h3>
<button class="close-btn" onclick="toggleProject('nyc-transit')">×</button>
</div>
<div class="details-body">
<div class="details-images">
<img src="images/nyc_project_areas_of_opportunity.png" alt="NYC Transit Analysis">
</div>
<div class="details-text">
<p>Identified underserved regions by calculating accessibility gaps and modeled predicted ridership and revenue to support investment decisions.</p>
<h4>Key Contributions</h4>
<ul>
<li>Geospatial analysis of transit accessibility</li>
<li>Ridership prediction modeling</li>
<li>Revenue impact assessment for investment planning</li>
</ul>
<a href="https://github.com/We-Gold/ds-501-cs4-public" target="_blank" class="project-link">View Repository →</a>
</div>
</div>
</div>
</div>

<div id="greenboard" class="project-details">
<div class="details-content">
<div class="details-header">
<h3>WPI Greenboard: Carbon Emissions Intelligence</h3>
<button class="close-btn" onclick="toggleProject('greenboard')">×</button>
</div>
<div class="details-body">
<div class="details-images">
<img src="images/package_details_greenboard.png" alt="Package Details">
<img src="images/leaderboard_greenboard.png" alt="Leaderboard">
</div>
<div class="details-text">
<p>Built a carbon emissions tracking system with multi-carrier API integration and optimized batch geocoding and throughput performance.</p>
<h4>Features</h4>
<ul>
<li>Multi-carrier shipping API integration</li>
<li>Batch geocoding optimization</li>
<li>Real-time emissions tracking dashboard</li>
<li>Leaderboard for sustainability metrics</li>
</ul>
<a href="https://github.com/We-Gold/wpi-greenboard" target="_blank" class="project-link">View Repository →</a>
</div>
</div>
</div>
</div>

<div id="ocr" class="project-details">
<div class="details-content">
<div class="details-header">
<h3>Receipts OCR Segmentation</h3>
<button class="close-btn" onclick="toggleProject('ocr')">×</button>
</div>
<div class="details-body">
<div class="details-images">
<img src="images/segmented_ocr.png" alt="OCR Segmentation">
</div>
<div class="details-text">
<p>A customizable template for extracting text via OCR + LLMs with layout information and label tags.</p>
<h4>Features</h4>
<ul>
<li>Streamlit prototype for uploading test receipts</li>
<li>Keyword enhancement for classifications</li>
<li>Visualization utils for training data context</li>
<li>Comprehensive test suite</li>
<li>Modular, easy-to-configure codebase</li>
</ul>
<a href="https://github.com/surbhikapoor19/receipts_ocr_segmentation" target="_blank" class="project-link">View Repository →</a>
</div>
</div>
</div>
</div>

<div id="supermarket" class="project-details">
<div class="details-content">
<div class="details-header">
<h3>Statistical ML on Supermarket Data</h3>
<button class="close-btn" onclick="toggleProject('supermarket')">×</button>
</div>
<div class="details-body">
<div class="details-images">
<img src="images/supermarket_trend.png" alt="Supermarket Trends">
<img src="images/profit_margins.png" alt="Profit Margins">
<img src="images/models_comparison.png" alt="Models Comparison">
</div>
<div class="details-text">
<p>EDA and business decisions based on statistical analysis on supermarket sales data. Trained models to predict profit margin across products and analyzed feature importance.</p>
<h4>Approach</h4>
<ul>
<li>Exploratory data analysis on sales patterns</li>
<li>Statistical hypothesis testing</li>
<li>Profit margin prediction models</li>
<li>Feature importance analysis</li>
</ul>
<a href="https://github.com/surbhikapoor19/ds502-project" target="_blank" class="project-link">View Repository →</a>
</div>
</div>
</div>
</div>

---

## Work Experience

<div class="timeline">

<div class="timeline-item">
<div class="timeline-marker"></div>
<div class="timeline-content">
<div class="timeline-header">
<h3>Medlaunch Concepts</h3>
<span class="timeline-role">Machine Learning Engineer Intern</span>
<span class="timeline-date">Jan 2026 – May 2026</span>
</div>
<div class="timeline-body">
<ul>
<li>Built <strong>end-to-end ML pipelines</strong> using CMS healthcare quality measures data</li>
<li>Designed <strong>ETL pipelines in AWS</strong> (S3, Glue, Athena) for large-scale datasets</li>
<li>Developed feasibility models combining <strong>statistical ML and LLM-powered</strong> insights</li>
<li>Utilized <strong>SageMaker</strong> for model prototyping and deployment planning</li>
</ul>
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-marker"></div>
<div class="timeline-content">
<div class="timeline-header">
<h3>Quaxar</h3>
<span class="timeline-role">ML Product Lead | Data Scientist</span>
<span class="timeline-date">May 2025 – Dec 2025</span>
</div>
<div class="timeline-body">
<ul>
<li>Led development of <strong>AI-powered document intelligence platform</strong></li>
<li>Fine-tuned <strong>Microsoft Florence</strong> for document object detection</li>
<li>Built platform processing <strong>120K+ documents/month</strong> with <strong>99.9% uptime</strong></li>
<li>Integrated <strong>OpenAI APIs</strong> for OCR validation and agentic workflows</li>
<li>Created annotation tools labeling <strong>1,000+ documents</strong></li>
</ul>
</div>
</div>
</div>

<div class="timeline-item">
<div class="timeline-marker"></div>
<div class="timeline-content">
<div class="timeline-header">
<h3>Ottimate (Plate IQ)</h3>
<span class="timeline-role">Senior Data Scientist</span>
<span class="timeline-date">Aug 2018 – Apr 2024</span>
</div>
<div class="timeline-body">
<ul>
<li>Joined as <strong>one of first three data team members</strong>, scaled through Series C</li>
<li>Achieved <strong>97% accuracy</strong> with NLP models, automated <strong>70% of labeling</strong></li>
<li>Reduced duplication from <strong>7% to under 1%</strong> using LSH</li>
<li>Saved <strong>60+ hours/month</strong> by automating 15% of daily uploads</li>
<li>Built <strong>competitive pricing intelligence system</strong> as internal product</li>
</ul>
</div>
</div>
</div>

</div>

---

## Certifications

<div class="cert-card">
<div class="cert-icon">🏆</div>
<div class="cert-info">
<h3>NeuralSeek – Agentic AI Workflow Certification</h3>
<p class="cert-date">January – February 2026</p>
<p>Built agentic AI workflows enabling LLM-driven reasoning over enterprise data. Designed multi-step agents with retrieval, search, and tool use capabilities.</p>
</div>
</div>

---

## Skills

<div class="skills-container">

<div class="skill-group">
<h4>Languages & Tools</h4>
<div class="skill-tags">
<span>Python</span><span>SQL</span><span>Git</span><span>Jupyter</span><span>Bash</span>
</div>
</div>

<div class="skill-group">
<h4>Machine Learning</h4>
<div class="skill-tags">
<span>Transformers</span><span>BERT</span><span>LayoutLMv3</span><span>Florence</span><span>XGBoost</span><span>Deep Learning</span>
</div>
</div>

<div class="skill-group">
<h4>GenAI & Agents</h4>
<div class="skill-tags">
<span>OpenAI APIs</span><span>RAG</span><span>Prompt Design</span><span>NeuralSeek</span><span>Agentic Workflows</span>
</div>
</div>

<div class="skill-group">
<h4>Cloud & Infrastructure</h4>
<div class="skill-tags">
<span>AWS S3</span><span>Glue</span><span>Athena</span><span>SageMaker</span><span>Docker</span><span>FastAPI</span>
</div>
</div>

<div class="skill-group">
<h4>Visualization</h4>
<div class="skill-tags">
<span>Plotly</span><span>Matplotlib</span><span>Seaborn</span><span>Power BI</span>
</div>
</div>

</div>

---

## Contact

<div class="contact-section">
<a href="mailto:surbhi.kapoor19@gmail.com" class="contact-btn">📧 surbhi.kapoor19@gmail.com</a>
<a href="https://www.linkedin.com/in/surbhikapoor19" target="_blank" class="contact-btn">💼 LinkedIn</a>
<a href="https://github.com/surbhikapoor19" target="_blank" class="contact-btn">🐙 GitHub</a>
</div>

<script>
function toggleProject(id) {
  const el = document.getElementById(id);
  const isVisible = el.classList.contains('active');
  
  // Close all open projects
  document.querySelectorAll('.project-details').forEach(p => {
    p.classList.remove('active');
  });
  
  // Toggle current project
  if (!isVisible) {
    el.classList.add('active');
    el.scrollIntoView({ behavior: 'smooth', block: 'center' });
  }
}

// Close on escape key
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') {
    document.querySelectorAll('.project-details').forEach(p => {
      p.classList.remove('active');
    });
  }
});
</script>
