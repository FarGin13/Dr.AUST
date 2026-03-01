<div align="center">
  <img src="https://img.shields.io/badge/Thesis-AUST_CSE-success?style=for-the-badge" alt="Thesis">
  <img src="https://img.shields.io/badge/Model-XLM--RoBERTa-orange?style=for-the-badge" alt="NLP Model">
  <img src="https://img.shields.io/badge/Backend-Python-blue?style=for-the-badge" alt="Python">
  <img src="https://img.shields.io/badge/Frontend-React.js-cyan?style=for-the-badge" alt="React">

  <h1>🏥 Dr. AUST: AI-Powered Healthcare Diagnostics</h1>
  <p><i>A smart bilingual chatbot bridging the gap between symptoms and specialists.</i></p>
</div>

<hr />

<h2>🎯 About The Project</h2>
<p align="justify">
  <b>Dr. AUST</b> serves as a digital bridge between patients and healthcare professionals. Built as an undergraduate computer science thesis, this bilingual intelligent chatbot understands natural medical descriptions in both <b>English</b> and <b>Bengali</b>. By applying advanced Natural Language Processing (NLP) techniques, it identifies core symptoms, predicts the most probable diseases, and directs users to the appropriate medical specialists.
</p>

<h2>✨ Highlights & Features</h2>
<ul>
  <li><b>Cross-Lingual Comprehension:</b> Accurately processes complex, conversational medical symptoms natively in Bengali and English.</li>
  <li><b>AI Symptom Extraction:</b> Powered by a custom fine-tuned <b>XLM-RoBERTa</b> model to pull clinical symptoms directly from raw user text.</li>
  <li><b>Smart Disease Prediction:</b> Cross-references extracted symptoms against a comprehensive medical dataset to generate high-accuracy diagnostic predictions.</li>
  <li><b>Doctor Recommendation:</b> Automatically maps the predicted illness to the relevant medical department (e.g., Cardiology, Neurology, Orthopedics).</li>
  <li><b>Interactive UI:</b> A modern, accessible, and fully responsive web frontend built with React.</li>
</ul>

<hr />

<h2>🏗️ System Architecture & Tech Stack</h2>
<blockquote>
  <p><b>Machine Learning:</b> PyTorch, Hugging Face Transformers, XLM-R</p>
  <p><b>Backend API:</b> Python, Flask / FastAPI, Pandas, Scikit-learn</p>
  <p><b>Frontend Application:</b> React.js, Tailwind CSS, Node.js</p>
</blockquote>

<hr />

<h2>🚀 Getting Started</h2>

<h3>1. Repository Setup</h3>
<p>First, clone the repository to your local machine:</p>
<pre>
git clone https://github.com/FarGin13/Dr.AUST.git
cd Dr.AUST
</pre>

<h3>2. Configure the AI Model (Important)</h3>
<p>To bypass GitHub's file size restrictions, the heavy XLM-R model weights are hosted on Hugging Face. You must download them manually to run the application.</p>
<ol>
  <li>Visit the model repository here: <a href="https://huggingface.co/Farjin/Dr.Aust/tree/main" target="_blank"><b>Farjin/Dr.Aust</b></a>.</li>
  <li>Download all the files listed in the repository (most importantly, the <code>1.11 GB model.safetensors</code> file).</li>
  <li>In your cloned project, navigate to the <code>backend/models/</code> directory.</li>
  <li>Create a new folder inside it named exactly: <code>xlm-r-model-final</code>.</li>
  <li>Move all of your downloaded Hugging Face files into that new folder.</li>
</ol>

<h3>3. Launch Backend</h3>
<pre>
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
python app.py
</pre>

<h3>4. Launch Frontend</h3>
<pre>
cd frontend-new
npm install
npm start
</pre>

<hr />

<div align="center">
  <p><i>Developed for the CSE Undergraduate Thesis Program at Ahsanullah University of Science and Technology (AUST).</i></p>
  <p><b>Developer: Fargin</b></p>
</div>
