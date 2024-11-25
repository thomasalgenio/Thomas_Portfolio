<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ site.title }}</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
      /* General Styles */
      body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
        color: #333;
        line-height: 1.6;
      }

      header {
        background: #157878;
        color: white;
        padding: 20px;
        text-align: center;
      }

      header h1 {
        margin: 0;
        font-size: 2.5rem;
      }

      header h2 {
        margin: 5px 0 0;
        font-weight: 400;
      }

      main {
        max-width: 1200px;
        margin: 20px auto;
        padding: 20px;
      }

      section {
        margin-bottom: 40px;
      }

      section h2 {
        color: #157878;
        font-size: 2rem;
        margin-bottom: 20px;
        text-align: center;
      }

      .projects {
        display: grid;
        gap: 20px;
        grid-template-columns: repeat(2, 1fr);
        justify-items: center;
      }

      .project-card {
        width: 300px;
        height: 250px;
        background: white;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        padding: 15px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        text-align: center;
        transition: transform 0.2s;
      }

      .project-card:hover {
        transform: translateY(-5px);
      }

      .project-card h3 {
        font-size: 1.1rem;
        margin-bottom: 10px;
        color: #157878;
      }

      .project-card p {
        font-size: 0.9rem;
        color: #555;
        margin: 10px 0;
      }

      .btn {
        display: inline-block;
        padding: 8px 12px;
        background-color: #157878;
        color: white;
        text-decoration: none;
        border-radius: 5px;
        font-weight: bold;
        transition: background-color 0.3s;
      }

      .btn:hover {
        background-color: #104f5b;
      }

      footer {
        background: #333;
        color: white;
        text-align: center;
        padding: 10px;
        margin-top: 20px;
      }

      .welcome-message {
        text-align: center;
        font-size: 1.2rem;
        color: #555;
        margin-bottom: 30px;
      }

      @media (max-width: 768px) {
        .projects {
          grid-template-columns: 1fr;
        }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>{{ site.title }}</h1>
      <h2>{{ site.description }}</h2>
    </header>

    <main>
      <!-- Welcome Message -->
      <div class="welcome-message">
        Hello! Welcome to my portfolio. Below you'll find highlights of my contributions, projects, and analyses.
      </div>

      <!-- Contributions Section -->
      <section>
        <h2>Contributions</h2>
        <div class="projects">
          <div class="project-card">
            <h3>Matching Messy Pandas Columns</h3>
            <p>Resolved missing edge cases in fuzzy matching logic.</p>
            <p>Collaborated with the author to improve accuracy.</p>
            <a href="https://medium.com/analytics-vidhya/matching-messy-pandas-columns-with-fuzzywuzzy-4adda6c7994f" class="btn">View Article</a>
          </div>
        </div>
      </section>

      <!-- Data Science Projects Section -->
      <section>
        <h2>Data Science Projects</h2>

        <!-- Computer Vision -->
        <h3 style="text-align: center;">Computer Vision</h3>
        <div class="projects">
          <div class="project-card">
            <h3>Face Detection Project</h3>
            <p>Performed face detection on AI-generated images.</p>
            <p>Developed models to classify real and AI-generated faces.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/Face_Detection_on_AI_Generated_Images" class="btn">View Project</a>
          </div>
        </div>

        <!-- NLP Sentiment Analysis -->
        <h3 style="text-align: center;">NLP Sentiment Analysis</h3>
        <div class="projects">
          <div class="project-card">
            <h3>Amazon Collagen Reviews</h3>
            <p>Sentiment analysis of customer reviews on Amazon.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Amazon" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Amazon Preworkout Reviews</h3>
            <p>Analyzed preworkout product reviews on Amazon.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Amazon" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Twitter #BoycottGillette</h3>
            <p>Explored Twitter sentiment for #BoycottGillette.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Gillette" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Twitter #GilletteAd</h3>
            <p>Analyzed public sentiment for the Gillette Ad campaign.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Gillette" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Twitter Gillette Unigram Model</h3>
            <p>Built unigram sentiment models for Gillette Twitter campaigns.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Gillette" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Yelp Restaurant Reviews</h3>
            <p>Performed sentiment classification using NLP models.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/NLP_Sentiment_Analysis_Yelp" class="btn">View Project</a>
          </div>
        </div>

        <!-- Regression Analysis -->
        <h3 style="text-align: center;">Regression Analysis</h3>
        <div class="projects">
          <div class="project-card">
            <h3>Predicting Bank Loan Approval</h3>
            <p>Developed predictive models for bank loan approvals.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/Bank_Loan_Prediction" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Predicting Diamond Prices</h3>
            <p>Predicted prices using regression models.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/Diamond_Prices_Prediction" class="btn">View Project</a>
          </div>
        </div>

        <!-- Classification Analysis -->
        <h3 style="text-align: center;">Classification Analysis</h3>
        <div class="projects">
          <div class="project-card">
            <h3>Predicting Hypertension</h3>
            <p>Analyzed public health data.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/Hypertension_Prediction" class="btn">View Project</a>
          </div>
          <div class="project-card">
            <h3>Hypertension Insights</h3>
            <p>Generated insights from health data.</p>
            <a href="https://github.com/thomasalgenio/Sample_Projects/tree/main/Hypertension_Prediction" class="btn">View Project</a>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <p>&copy; {{ site.title }} - Built with Jekyll</p>
    </footer>
  </body>
</html>
