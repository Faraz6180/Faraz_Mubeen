<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faraz Mubeen Haider</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f9;
      color: #333;
    }

   .header-container {
  position: relative;
  overflow: hidden;
  background-color: #007acc;
  color: white;
  height: 100vh; /* Set height to 100% of viewport height */
}

.slider {
  position: relative;
  height: 100%; /* Set height to 100% of parent container */
  display: flex;
  align-items: center;
  justify-content: center;
}

.slide {
  position: absolute;
  width: 100%;
  height: 100%; /* Set height to 100% of parent container */
  opacity: 0;
  transition: opacity 1s ease-in-out;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.slide img {
  width: 100%;
  height: 100%;
  object-fit: cover; 
}

.slide.active {
  opacity: 1;
}

.slide h1, .slide h2 {
  position: absolute;
  color: white;
  text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

.slide h1 {
  font-size: 3em; /* Increase font size for better visibility */
  top: 30%;
}

.slide h2 {
  font-size: 2em; /* Increase font size for better visibility */
  top: 50%;
}

.social-icons {
  position: absolute;
  top: 20px; /* Adjust top position */
  right: 20px; /* Adjust right position */
  display: flex;
}

.social-icons a {
  margin-left: 10px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

    footer {
      text-align: center;
      padding: 10px;
      background: #007acc;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="header-container">
    <div class="slider">
      <div class="slide active">
        <img src="https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080" alt="Professional Background Image" alt="Descriptive text for the image">
        <h1>Hi, I am Faraz Mubeen Haider</h1>
        <h2>Software Engineer and Machine Learning Engineer</h2>
      </div>
      <div class="slide">
        <img src="https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080" alt="Professional Background Image" alt="Descriptive text for the image">
        <h1>Welcome to my Portfolio</h1>
      </div>
      <div class="slide">
        <img src="https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080" alt="Professional Background Image" alt="Descriptive text for the image">
        <h1>You can find my work, thoughts, and ideas here</h1>
      </div>
    </div>
    <div class="social-icons">
      <a href="https://www.linkedin.com/in/faraz-mubeen-software-engineer/" target="_blank">LinkedIn</a>
      <a href="https://github.com/Faraz6180" target="_blank">GitHub</a>
      <a href="https://www.kaggle.com/faraz618" target="_blank">Kaggle</a>
    </div>
  </div>

  <section>
    <h1>🚀 Featured Projects</h1>
    <ul>
      <li>🔥 <strong><a href="https://github.com/Faraz6180/Heart-failure-outcome-prediction" target="_blank">Heart Failure Outcome Prediction</a></strong>: Predicts heart failure risk using Logistic Regression, Decision Trees, and Random Forests to aid early diagnosis and improve patient care.</li>
      <li>🤖 <strong><a href="https://github.com/Faraz6180/SMS-Spam_Classifier" target="_blank">SMS Spam Classifier</a></strong>: Classifies SMS messages as spam or not using advanced text classification models.</li>
      <li>🤖 <strong><a href="https://github.com/Faraz6180/ANN-Classification-Churn" target="_blank">ANN Classification Churn</a></strong>: Predicts customer churn probability using neural networks and offers an interactive analysis tool built with Streamlit.</li>
      <li>🏆 <strong>Gradient Descent Visualization</strong>: Visualizes gradient descent processes to improve neural network accuracy understanding.</li>
    </ul>
  </section>

  <section>
    <h1>💻 Technical Skills</h1>
    <p>
      <strong>Languages:</strong> Python, Java, SQL<br>
      <strong>Libraries & Frameworks:</strong> TensorFlow, PyTorch, scikit-learn, Hugging Face<br>
      <strong>AI/ML:</strong> Deep Learning, NLP, RAG, Transformers, Generative Models<br>
      <strong>Tools:</strong> Git, Docker, Kubernetes, Jupyter Notebooks<br>
      <strong>Data Visualization:</strong> Matplotlib, Seaborn, Plotly
    </p>
  </section>

  <footer>
    &copy; 2025 Faraz Mubeen Haider. All rights reserved.
  </footer>

  <script>
    const slides = document.querySelectorAll('.slide');
    let currentSlide = 0;

    function showSlide(index) {
      slides.forEach((slide, i) => {
        slide.classList.toggle('active', i === index);
      });
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % slides.length;
      showSlide(currentSlide);
    }

    setInterval(nextSlide, 3000);
  </script>
</body>
</html>
