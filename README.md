# SECTION 1: Fundamentals of GenAI (30% of EXAM)

## Core Concepts of Artificial Intelligence

### What is Artificial Intelligence (AI)?
- AI is the BROADER field of Computer Science focused on CREATING or BUILDING MACHINES or COMPUTERS that can think, learn, and ACT LIKE HUMANS (learning, problem-solving, understanding language, decision-making).
- AI is BUILDING MACHINES that typically require HUMAN INTELLIGENCE.
- AI is basically MIMICKING HUMAN COGNITION.

### What is Machine Learning (ML)?
- ML is a SUBSET of AI where machines learn from DATA to perform SPECIFIC TASKS.
- ML is TEACHING machines to learn from experience.
- **Example:** Showing a machine thousands of cat and dog pictures with labels; it learns patterns and predicts new images correctly.

### What is Deep Learning (DL)?
- DL is a SUBSET of ML using NEURAL NETWORKS with many layers to solve complex problems (images, audio, text, large-scale data).
- DL tries to MIMIC HUMAN BRAINS (neurons and layers).
- DL is Machine Learning on STEROIDS.
- **Examples:** Face Recognition, Voice Assistants, Self-Driving Cars, Language Translation (Google Translate).

### What is Generative AI (GenAI)?
- GenAI is a SUBSET of Deep Learning.
- Focused on CREATING or GENERATING NEW CONTENT (text, images, audio, code).
- TEACHING machines to be creative to generate realistic content that did not exist before.

### What are Foundational Models?
- Subset of GenAI.
- LARGE-SCALE AI Models pre-trained on MASSIVE, DIVERSE DATASETS.
- Develop BROAD understanding and perform a WIDE variety of tasks.
- Act as the BRAINS of AI Systems and Agents.
- **Examples:** GPT-4, DALL-E, Sora (OpenAI); Gemini, PaLM, Imagen (Google); LLaMA (Meta).

### What are Large Language Models (LLM)?
- SUBSET of Foundational Models trained on TEXT DATA to understand and GENERATE HUMAN LANGUAGE.
- Can generate responses, answer questions, write stories, translate languages, summarize documents.
- All LLMs are Foundational Models, but not all Foundational Models are LLMs.
- **Examples:** GPT-4 (OpenAI), Gemini, PaLM (Google), LLaMA (Meta), Titan (Amazon).

### What is Natural Language Processing (NLP)?
- NLP is a sub-field of AI that enables machines to read, understand, and derive meaning from HUMAN LANGUAGE.
- **Example:** Analyzing reviews for topics and sentiment.

### Difference: Traditional AI vs Generative AI
- Traditional AI: Focuses on Prediction and Classification based on existing data.
- Generative AI: Focuses on Creating new content based on learned patterns.

## Machine Learning Approaches

### 1. Supervised ML Approach
- Trains models on LABELED DATA to predict outputs for new inputs.
- Uses examples with correct answers to learn predictions.
- **Examples:**
  - Fruit photo recognition with labels.
  - House price prediction using labeled features (size, #bedrooms, location).

### 2. Unsupervised ML Approach
- Trains models on UNLABELED DATA to FIND PATTERNS or relationships.
- No predefined labels or outcomes.
- Foundational Models often use unsupervised learning.
- **Examples:**
  - Grouping fruits by shape/color without labels.
  - Grouping people at a party by clothing style without knowing jobs.

### 3. Reinforcement ML Approach
- Model learns to maximize REWARDS or minimize PENALTIES via INTERACTION and HUMAN FEEDBACK.
- GOOD BEHAVIOR = REWARD, BAD BEHAVIOR = PENALTY.
- **Examples:**
  - Training a pet, Self-Driving Cars, Playing games (Chess, Pac-Man), Robot Vacuum Cleaners, Child learning with vending machines.

## Machine Learning Lifecycle

### What is Machine Learning Lifecycle?
- End-to-end process for BUILDING, DEPLOYING, and MAINTAINING ML models.
- Includes stages from problem understanding to model monitoring in production.

### Key Stages
1. Data Ingestion and Preparation
2. Model Training
3. Model Evaluation
4. Model Deployment
5. Model Management / Monitoring

### 1. Data Ingestion / Preparation
- Gather raw data from sources (databases, APIs, sensors, files).
- Clean, transform, and organize data into USABLE FORMAT.
- **Example:** Facial recognition model trained only on adult male faces may fail on women/children.

### 2. Model Training
- Create ML model using prepared data.
- Choose ALGORITHM and feed labeled/unlabeled data to learn patterns.

### 3. Model Evaluation
- Assess model performance against metrics and business objectives.

### 4. Model Deployment
- Deploy model into PRODUCTION to make real predictions.
- Integrate into apps, dashboards, APIs.

### 5. Model Management / Monitoring
- Manage and monitor models to ensure accuracy over time.
- Re-train or fine-tune models when data changes (data drift).
