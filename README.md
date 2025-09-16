# SECTION 1: Fundamentals of GenAI (30% of EXAM)

---

## Core Concepts of Artificial Intelligence

### What is Artificial Intelligence (AI)?
- **Artificial Intelligence (AI)** is the broader field of Computer Science focused on **creating machines/computers that can think, learn, and act like humans**.  
- AI includes tasks such as **learning, problem-solving, understanding language, and decision making**.  
- AI is essentially **mimicking human cognition**.  

---

### What is Machine Learning (ML)?
- **Machine Learning (ML)** is a **subset of AI** where machines/computers **learn from data** to perform specific tasks.  
- ML is **teaching machines to learn from experience**, similar to how humans learn.  

**Example of ML**:  
- Show a machine thousands of pictures of cats and dogs with labels.  
- It learns patterns.  
- Later, when shown a new picture, it can predict whether it’s a cat or dog—even if it’s never seen that exact image before.  

---

### What is Deep Learning (DL)?
- **Deep Learning** is a **subset of ML** that uses **neural networks with many layers** to solve complex problems (images, audio, text, or large-scale data).  
- DL tries to **mimic the human brain** (neurons + layers) to learn in a much deeper way.  
- DL is often called **ML on steroids**.  

**Examples**:  
- Face Recognition  
- Voice Assistants  
- Self-Driving Cars  
- Language Translation (e.g., Google Translate)  

---

### What is Generative AI (GenAI)?
- **GenAI** is a **subset of Deep Learning**.  
- GenAI is focused on **creating new content** (text, images, audio, code, etc.).  
- GenAI = teaching machines to be **creative**, generating something new that looks or sounds real.  

---

### What are Foundational Models?
- **Foundational Models** are a **subset of GenAI**.  
- Large-scale AI models (e.g., Gemini) pre-trained on **massive, diverse datasets**.  
- Enable broad understanding + ability to perform **a wide variety of tasks**.  
- They are the **brains of AI systems/agents**.  

**Examples**:  
- **OpenAI**: GPT-4, DALL-E, Sora  
- **Google**: Gemini, PaLM, Imagen  
- **Meta**: LLaMA  

---

### What are Large Language Models (LLM)?
- **LLMs** are a **subset of Foundational Models**.  
- Specifically trained on **text data** to **understand + generate human language** (text, speech, or code).  
- LLMs have read billions of words → can generate responses, answer questions, write, translate, summarize, etc.  
- **All LLMs are Foundational Models, but not all Foundational Models are LLMs**.  

**Examples**:  
- GPT-4 (OpenAI)  
- Gemini, PaLM (Google)  
- LLaMA (Meta)  
- Titan (Amazon)  

---

### What is Natural Language Processing (NLP)?
- **NLP** is a sub-field of AI.  
- Gives machines the ability to **read, understand, and derive meaning from human language**.  
- Example: analyzing reviews for **topics and sentiment**.  

---

### Difference between TRADITIONAL AI and GENERATIVE AI
- **Traditional AI** → focuses on **prediction + classification** based on existing data.  
- **Generative AI** → focuses on **creating new content** based on learned patterns.  

---

## Machine Learning Approaches

### 1. Supervised ML Approach
- Trains models on **labeled data** to predict outputs for new inputs.  
- Learns from examples with correct answers.  

**Examples**:  
- **Use Case 1**: Training a model with fruit photos + labels (apples, bananas, oranges). Later, the model can identify unlabeled fruits.  
- **Use Case 2**: Training a model with house data (size, #bedrooms, location, price). Later, it predicts prices for new houses.  

---

### 2. Unsupervised ML Approach
- Trains models on **unlabeled data** to find **patterns, structures, or groupings**.  
- **No predefined labels/outcomes**.  
- Many foundational models use this approach.  

**Examples**:  
- **Use Case 1**: Grouping fruit photos by shapes/colors, without knowing their names.  
- **Use Case 2**: At a party, grouping people by clothing style without knowing their names or jobs.  

---

### 3. Reinforcement ML Approach
- Model learns by **maximizing rewards** and **minimizing penalties** via interaction + human feedback.  
- **Good behavior = reward**  
- **Bad behavior = penalty**  

**Examples**:  
- Training a pet  
- Self-driving cars  
- Playing chess/Pac-Man  
- Robot vacuum cleaners  
- Child learning to get candy from a vending machine  

---

# Machine Learning Lifecycle & GenAI Core Layers

---

## Machine Learning Lifecycle

### What is Machine Learning Lifecycle?
- **Machine Learning Lifecycle** is the **end-to-end process** for **building, deploying, and maintaining** a machine learning model.  
- Includes all key stages: from understanding the problem → to delivering & monitoring the model in production.  

---

### Key Stages of Machine Learning Lifecycle
1. **Data Ingestion and Preparation**  
2. **Model Training**  
3. **Model Evaluation**  
4. **Model Deployment**  
5. **Model Management or Model Monitoring**  

---

#### 1. Data Ingestion / Preparation
- Gather & acquire raw data from sources (databases, APIs, sensors, files).  
- **Quality data is the foundation** of any ML model.  
- Clean, transform, and organize raw data into a **usable format**.  
- ⚠️ Example: A facial recognition model trained only on adult male faces may fail badly on women or children.  

---

#### 2. Model Training
- Process of **creating an ML model** using prepared data.  
- Choose an **algorithm** → feed labeled/unlabeled data → let the model learn **patterns/relationships/rules**.  

---

#### 3. Model Evaluation
- Assess the model’s **performance** against metrics & business goals.  
- Ensure it meets **quality, accuracy, and suitability** standards for the intended use case.  

---

#### 4. Model Deployment
- Deploy the trained model into **production**.  
- Enable the model to make **real predictions/decisions** on new incoming data.  
- Integrate with **apps, dashboards, APIs** to deliver business value.  

---

#### 5. Model Management / Monitoring
- **Manage & monitor** models to stay accurate as data evolves.  
- Handle **data drift** → retrain/fine-tune models as needed.  

---

## GenAI: 4 Ways to Use GenAI
1. **Create**  
   - Generate new content.  
   - *Examples*: draft emails, create presentations, generate images/videos/audio.  

2. **Summarize**  
   - Condense information into concise summaries.  
   - *Examples*: summarize reports, extract key meeting takeaways, transform data into visuals.  

3. **Discover**  
   - Find new knowledge, patterns, relationships, insights.  
   - *Examples*: purchase history forecasting, fraud detection, personalized recommendations.  

4. **Automate**  
   - Automate manual tasks.  
   - *Examples*: real-time translation, automate documentation, auto-create tickets from feedback.  

---

## Key Roles in GenAI (Non-Exam Relevant)

### 1. Business Leaders
- Understand how GenAI transforms business.  
- Knowledge of **Google Cloud GenAI products**.  
- Use pre-built solutions to enhance operations & customer experience.  

### 2. Developers
- Build & deploy **custom AI agents**.  
- Use **Vertex AI Platform** to improve custom models.  
- Integrate AI into existing apps (e.g., AI-driven data processing, AI code generation).  

### 3. AI Practitioners
- Customize, deploy, and optimize GenAI models.  
- Use Vertex AI to **accelerate development** & ensure **responsible AI practices**.  
- Scale workloads, integrate with BigQuery, and implement **bias detection & adversarial testing**.  

---

## GenAI: 5 Core Layers

### 1. Infrastructure Layer
- Provides **hardware & computing power** for training/running GenAI models.  
- Includes GPUs, TPUs, storage, networking, data centers, servers, GCP services.  

**Key Components**:  
- **GPU (Graphics Processing Unit)**: Accelerates & trains large-scale models. Widely used for many tasks.  
- **TPU (Tensor Processing Unit)**: Specialized for **ML workloads**. Faster & more efficient at large model training.  

---

### 2. Model Layer
- The **brains** of GenAI.  
- Provides **multimodal foundational models** or **LLMs** trained on massive datasets.  
- Generates outputs (text, images, audio, video).  

**Access via**:  
- Google Vertex AI Platform  
- Google AI Studio  
- Google Workspace  

---

### 3. Agent Layer
- Orchestrates **models, tools, memory, reasoning** to build task-solving agents.  
- Converts model outputs into **multi-step behaviors**, like a **human assistant**.  
- Uses APIs, extensions, functions, databases, plugins, and memory.  

**Example – Travel Assistant**:  
- Input: budget, dates, destination.  
- Agent Layer:  
  - Searches for flights/hotels  
  - Builds itinerary  
  - Books after confirmation  
  - Sends updates if plans change  

---

### 4. Platform Layer
- Offers **tools & services** for developers/data scientists to build, customize, deploy, manage GenAI models.  
- Acts as a **toolbox** bridging the **model layer** and **application/agent layer**.  

---

### 5. Application Layer
- Where **end-users interact** with GenAI.  
- Embeds AI into daily tools (Gmail, Docs, Sheets, Slides, Meet).  

**Examples**:  
- Google Docs → summarize, generate, translate, rewrite text.  
- Gmail → auto-draft replies, summarize email threads.  

---

### Real-World Example of 5 Layers → Car Analogy
- **Infrastructure Layer** = Fuel, roads, chassis (foundation).  
- **Model Layer** = Engine (power + intelligence).  
- **Agent Layer** = Driver (decision-maker).  
- **Platform Layer** = Garage & tools (maintenance/customization).  
- **Application Layer** = Dashboard & controls (user interface).  

---


# SECTION 2: Google Cloud GenAI Offerings (35% of EXAM)

---

## Google GenAI Ecosystem

### What is Google’s GenAI EcosYSTEM?
- Google’s GenAI ecosystem is a **comprehensive suite** of models, platforms, tools, infrastructure, and integrations.  
- It helps users—**from developers to enterprises**—build, scale, and responsibly deploy generative AI solutions.  

---

### How can BUSINESS LEVERAGE GenAI ECOSYSTEM?
Businesses can leverage Google’s ecosystem in **4 key ways**:

1. **Individual Productivity and Efficiency**  
   - Use existing Google tools such as **Google Search, Gemini for Google Workspace, Gemini App, Gemini for Google Cloud**.  

2. **Continuous Improvement**  
   - Stay up-to-date on **Security Enhancements, Performance Enhancements, and new feature updates**.  
   - Google helps businesses stay current with the latest advancements.  

3. **Responsible AI**  
   - Use GenAI **responsibly, ethically, and securely**, which is critical for all organizations.  

4. **Enterprise Ready**  
   - Build GenAI for enterprise with focus on **security, data governance, compliance certifications, and more**.  
   - Leverage solutions like **Vertex AI, Google Cloud Security Infrastructure, Compliance Certifications**.  

---

## Google Cloud

### What is Google?  
- Google is an **AI FIRST COMPANY**.  
- GenAI Tools are **integrated across Google’s ecosystem**.  

---

### What is GOOGLE CLOUD?  
- Google Cloud = **PLATFORM + INFRASTRUCTURE** layer that powers Generative AI solutions.  
- Provides Google’s **best AI models, tools, and enterprise-grade infrastructure**.  
- Designed to be **ENTERPRISE READY** → emphasizes:  
  - **Security**  
  - **Privacy**  
  - **Reliability**  
  - **Scalability** (especially important for industries like financial services)  

- Includes **robust security measures** and **data privacy controls** (e.g., IAM, governance tools).  
- Offers **tools, models, data services, and infrastructure** for GenAI (ex: Google Search, Gmail, Maps, Photos, Assistant, YouTube).  

---

### What are KEY BENEFITS of Google Cloud?
- **Openness and Flexibility** → allows use of various models and technologies (first-party + open-source).  
- Enables **business scalability and adaptability** through an open ecosystem.  
- Wide range of **applications**: foundational models to advanced infrastructure.  
- Integration of **model capabilities, hardware options, and platform services** → enables partners to deliver **efficient, effective AI offerings**.  

---

### What is Google Cloud’s OPEN APPROACH to AI?
- Provides **flexibility and choice** in AI development.  
- Supports **open-source models and tools**, avoiding vendor lock-in.  
- Emphasizes **interoperability** with open frameworks.  
- Promotes an **open AI ecosystem**, enabling businesses to run and adapt open-source models.  

---

### What does GOOGLE CLOUD offer?
1. **Low-Code / No-Code Tools** → For non-developers to build AI apps without heavy coding.  
2. **APIs** → For developers to easily integrate AI features into applications.  
3. **Pre-Trained Models / Pre-built APIs** → Ready-to-use AI models, no need to build from scratch.  

---
