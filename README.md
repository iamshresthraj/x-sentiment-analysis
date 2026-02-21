<h1 align="center">X Sentiment Analysis using Embeddings</h1>

<p align="center">
  Embedding-based Sentiment Classification System for analyzing public opinion on X (formerly Twitter)
</p>

<hr>

<h2>Problem Statement</h2>
<p>
Social media platforms like <strong>X</strong> generate millions of posts daily. Manually analyzing public sentiment is impossible at scale.
This project builds an embedding-based sentiment classification system that classifies posts as
<strong>Positive</strong>, <strong>Neutral</strong>, or <strong>Negative</strong>.
</p>

<hr>

<h2>Objective</h2>
<p>
To develop a semantic sentiment classification model using modern embedding techniques and machine learning algorithms
to accurately understand public opinion.
</p>

<hr>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Pandas & NumPy</li>
  <li>SentenceTransformers (for semantic embeddings)</li>
  <li>Scikit-learn</li>
  <li>XGBoost</li>
  <li>Matplotlib & Seaborn</li>
</ul>

<hr>

<h2>Project Workflow</h2>
<ol>
  <li>Text Preprocessing and Cleaning</li>
  <li>Embedding Generation using SentenceTransformer</li>
  <li>Train-Test Split</li>
  <li>Model Training (Logistic Regression & XGBoost)</li>
  <li>Model Evaluation:
    <ul>
      <li>Accuracy Score</li>
      <li>Classification Report</li>
      <li>Confusion Matrix</li>
    </ul>
  </li>
  <li>Cosine Similarity Analysis</li>
  <li>Custom Post Predictions</li>
</ol>

<hr>

<h2>Model Performance</h2>
<p>
XGBoost outperformed Logistic Regression due to its ability to capture non-linear patterns
in high-dimensional embedding space.
</p>

<p>
<strong>Key Evaluation Metrics Used:</strong>
</p>
<ul>
  <li>Accuracy</li>
  <li>Precision</li>
  <li>Recall</li>
  <li>F1-Score</li>
</ul>

<hr>

<h2>Key Insights</h2>
<ul>
  <li>Embedding-based models capture semantic meaning better than traditional TF-IDF approaches.</li>
  <li>Preprocessing significantly improves model performance.</li>
  <li>Tree-based models like XGBoost handle embedding vectors effectively.</li>
  <li>Cosine similarity helps analyze semantic closeness between posts.</li>
</ul>

<hr>

<h2>How to Run the Project</h2>

<ol>
  <li>Clone the repository:</li>
</ol>

<pre><code>git clone https://github.com/your-username/your-repo-name.git</code></pre>

<ol start="2">
  <li>Navigate to the project folder:</li>
</ol>

<pre><code>cd your-repo-name</code></pre>

<ol start="3">
  <li>Install dependencies:</li>
</ol>

<pre><code>pip install -r requirements.txt</code></pre>

<ol start="4">
  <li>Open and run the Jupyter Notebook.</li>
</ol>

<hr>

<h2>Dataset</h2>
<p>
Dataset used: X (Twitter) Tweets Sentiment Dataset<br>
Size: ~27,000 posts<br>
Labels: Positive, Neutral, Negative
</p>

<hr>

<h2>Real-World Applications</h2>
<ul>
  <li>Brand monitoring</li>
  <li>Customer feedback analysis</li>
  <li>Crisis detection</li>
  <li>Public opinion tracking</li>
  <li>Market research</li>
</ul>

<hr>

<h2>Future Improvements</h2>
<ul>
  <li>Deploy as a web application</li>
  <li>Real-time streaming sentiment analysis</li>
  <li>Fine-tuning transformer models</li>
  <li>Multi-language sentiment support</li>
</ul>

<hr>

<p align="center">
  ⭐ If you found this project useful, feel free to star the repository!
</p>
