# Table of Contents
1. [Fundamentals of GenAI](#fundamentals-of-genai)
   - [Core Concepts of Artificial Intelligence](#core-concepts-of-artificial-intelligence)
   - [Machine Learning Approaches](#machine-learning-approaches)
   - [Machine Learning Lifecycle](#machine-learning-lifecycle)

---

# Fundamentals of GenAI (30% of EXAM)

## Core Concepts of Artificial Intelligence

### What is Artificial Intelligence (AI)?
- AI is the broader field of Computer Science focused on creating machines or computers that can think, learn, and act like humans.
- AI involves building machines that typically require human intelligence.
- AI essentially mimics human cognition.

### What is Machine Learning (ML)?
- ML is a subset of AI where machines learn from data to perform specific tasks.
- ML teaches machines to learn from experience.
- **Example:** Training a model with thousands of cat and dog images enables it to predict new images as cat or dog.

### What is Deep Learning (DL)?
- DL is a subset of ML using neural networks with many layers to solve complex problems involving images, audio, text, or large-scale data.
- Mimics how human brains work with neurons and layers.
- DL is essentially ML on steroids.
- **Examples:** Face recognition, voice assistants, self-driving cars, language translation.

### What is Generative AI (GenAI)?
- GenAI is a subset of deep learning focused on creating or generating new content like text, images, audio, code, etc.
- Teaches machines to be creative and generate content that looks or sounds real.

### What are Foundational Models?
- Subset of GenAI.
- Large-scale AI models pre-trained on massive datasets to perform a wide variety of tasks.
- Act as the "brains" of AI systems and agents.
- **Examples:** GPT-4, DALL-E, Sora (OpenAI), Gemini, PaLM, Imagen (Google), LLaMA (Meta/Facebook).

### What are Large Language Models (LLM)?
- Subset of Foundational Models trained specifically on text to understand and generate human language.
- Can answer questions, generate text, translate languages, summarize documents.
- All LLMs are Foundational Models, but not all Foundational Models are LLMs.
- **Examples:** GPT-4 (OpenAI), Gemini, PaLM (Google), LLaMA (Meta), Titan (Amazon).

### What is Natural Language Processing (NLP)?
- Sub-field of AI enabling machines to read, understand, and derive meaning from human language.
- **Example:** Sentiment analysis, topic extraction.

### Difference between Traditional AI and Generative AI
- Traditional AI: Focuses on prediction and classification.
- Generative AI: Focuses on creating new content based on patterns learned.

## Machine Learning Approaches

### 1. Supervised ML Approach
- Trains models on labeled data to predict outputs for new inputs.
- Uses examples with correct answers.
- **Examples:**
  - Predict fruit type from labeled fruit images.
  - Predict house prices using labeled features (size, bedrooms, location, price).

### 2. Unsupervised ML Approach
- Trains models on unlabeled data to find patterns or groupings.
- No predefined labels or outcomes.
- Often used in Foundational Models.
- **Examples:**
  - Grouping unlabeled fruit images by shape, color, or size.
  - Clustering people at a party based on similarities without knowing names or jobs.

### 3. Reinforcement ML Approach
- Model learns to maximize rewards and minimize penalties through interaction and feedback.
- **Examples:**
  - Training a pet with rewards/punishments.
  - Self-driving cars.
  - Playing games (Chess, Pac-Man).
  - Robot vacuum cleaners.
  - Child learning to get a candy from a vending machine.

## Machine Learning Lifecycle

### What is Machine Learning Lifecycle?
- End-to-end process for building, deploying, and maintaining a machine learning model.
- Includes stages from problem understanding to production monitoring.

### Key Stages of Machine Learning Lifecycle
1. Data Ingestion and Preparation
2. Model Training
3. Model Evaluation
4. Model Deployment
5. Model Management / Model Monitoring

### 1. Data Ingestion / Preparation
- Gather raw data from databases, APIs, sensors, files.
- Ensure data quality.
- Clean, transform, and organize data into a usable format.
- **Example:** Facial recognition model trained on biased data may fail on women or children.

### 2. Model Training
- Process of creating the ML model using prepared data.
- Choose algorithm and feed labeled/unlabeled data to learn patterns and relationships.

### 3. Model Evaluation
- Assess model performance against metrics and business objectives.
- Determine suitability and accuracy.

### 4. Model Deployment
- Deploy model into production for real predictions.
- Integrate into applications, dashboards, or APIs.

### 5. Model Management / Monitoring
- Monitor models over time for accuracy and effectiveness.
- Address data drift by retraining or fine-tuning models.
