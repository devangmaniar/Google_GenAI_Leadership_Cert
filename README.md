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

# Data

## What is DATA?
- Data is **INFORMATION** used to train, build and improve Machine Learning models.  
- Data comes in many forms: numbers, dates, text, images or sound.  
- Machine Learning models require **QUALITY DATA** to be effective.  
- Foundational Models are Large Scale AI models trained on massive datasets, so the performance of Foundation Models relies heavily on **quality data**.  
- GenAI models are **highly dependent on quality data**. If the customer data is inconsistent, incomplete (missing fields), and siloed (poor accessibility), the resulting personalized content will likely be inaccurate, irrelevant, or ineffective. Addressing data quality (completeness, consistency, relevance) and accessibility is a foundational prerequisite.

---

## What are KEY CHARACTERISTICS of QUALITY DATA? *(Exam – Tricky)*
1. **Accuracy** – Incorrect data will return incorrect patterns by the ML models.  
2. **Completeness** – Refers to the missing data points within the dataset.  
3. **Representative** – Data must be representative and inclusive to avoid skewed samples and biased outcomes.  
4. **Consistency** – Values must be uniform and not contradict each other. Inconsistent formats or labeling can confuse ML models.  
5. **Relevance** – Data must be appropriate, applicable, and relevant to the problem being solved.  
6. **Cost** – The expense of acquiring or preparing the data.

---

## What is PSEUDONYMIZATION Data?
- Process of replacing direct identifiers with artificial ones to reduce privacy risks while still allowing data to be linked for analysis.

## What is Data ANONYMIZATION?
- Process of removing personal, private, or sensitive data from the model for privacy protection.

---

# Data: Structured vs Unstructured Data

### 1. Structured Data
- Organized and easy to search, often stored in **relational databases, spreadsheets, or tables**.  
- Structured Data is organized in a **fixed schema** (rows and columns).  
- **Examples**: Excel spreadsheets, SQL databases, CSV files.

### 2. Unstructured Data
- Does not follow a predefined format or schema.  
- Messy, not stored in traditional rows/columns. Requires pre-processing for analysis.  
- **Examples**:  
  - Text – Emails, PDFs, Word Documents  
  - Audio – Voicemails, call recordings, podcasts  
  - Video – Surveillance footage  
  - Images – Medical scans, photographs, screenshots  

---

# Data: Labeled vs Unlabeled Data

### 1. Labeled Data
- Has **tags** such as a name, type, or number.  
- Typically used in **supervised ML** where models learn from pre-tagged examples.  
- Consists of input data **paired with output labels**.  
- **Examples**:  
  - Image dataset labeled as *cat* or *dog*.  
  - Customer reviews labeled as *positive*, *negative*, or *neutral*.  
  - Emails tagged as *Billing Inquiry*, *Technical Support*, or *Feature Request*.  

### 2. Unlabeled Data
- Raw or unprocessed data with no tags.  
- **Foundational Models** often train on massive amounts of unlabeled data.  
- **Examples**:  
  - Collection of unorganized photos  
  - Stream of audio recordings  
  - Website traffic logs without categorization  

---

# AI Models: Types of AI Models

## What are GenAI Models?
- Focused on **generating new content** (text, images, music, video).  
- Trained on large datasets of existing content.  
- Learn from patterns to generate new content.  
- Accessible via **Vertex AI, AI Studio, and Gemini for Workspace**.

## What are Foundational Models?
- **Large-scale AI Models** pre-trained on massive and diverse datasets.  
- Provide a broad understanding of the world and can perform a wide variety of tasks.  
- Brains of the AI system and agents.  
- **Examples**: Google Gemini, OpenAI GPT.  
- **Note**: LLMs are a subset of Foundational Models.  

## What are Large Language Models (LLMs)?
- Deep learning models **pre-trained on massive text datasets**.  
- Can understand and generate text.  
- Used for tasks like Q&A, text generation, and translation.  

## What are Multimodal Foundational Models?
- Can process multiple input types **simultaneously** (text, images, audio, video).  
- Provide richer responses and smarter decisions.  

## What are Diffusion Models? *(Exam Topic – New)*
- Generate **high-quality images from text descriptions** (text-to-image).  
- Work by adding noise to training images and learning to reverse the process.  

## What are Machine Learning Models?
- **Algorithms** trained on narrow, task-specific datasets.  
- Usually built for one task (house price prediction, spam detection).  
- Examples: Linear Regression, Decision Trees, Random Forest.  

---

# AI Models: How to Choose the Right Model

### Key Factors:
1. **Modality** *(Exam Topic)* – Type of data the model can process (text, image, audio, video).  
2. **Context Window** *(Exam Topic)* – Defines how much input text a model can remember in one prompt.  
3. **Performance** – How well the model meets business requirements.  
4. **Availability and Reliability** – Accessibility and stability of the model.  

---

# AI Models: Foundational Models Deep Dive

## Key Features
1. **Trained on Diverse Data** – Learn patterns applicable across domains.  
2. **Flexible** – One model can support a wide range of use cases.  
3. **Adaptable** – Can be fine-tuned for specific tasks.  

## Limitations *(Most Frequently Asked Exam Question)*
1. **Data Dependency** – Quality/completeness of data directly affects performance.  
2. **Knowledge Cutoff** – Models lack knowledge after their training cutoff date.  
3. **Bias** – Training datasets may introduce bias.  
4. **Fairness** – Must avoid discriminatory or unjust outcomes.  
5. **Hallucinations** – May generate false or misleading information.  
6. **Edge Cases** – Rare scenarios may expose weaknesses.  

---

# Differences

## Foundational Models vs LLMs
- **LLMs** – Subset of foundation models, language-focused (NLP tasks).  
- **Foundation Models** – Broader category, multimodal (text, vision, robotics, etc.).  

## Foundational vs Traditional Models
- **Foundational Models** – Large, pre-trained, flexible, broad understanding.  
- **Traditional Models** – Narrow, task-specific, no broad generalization.  

---

# AI Models: 4 Key Types of Foundational Models

1. **Gemini Model**  
   - Google’s multimodal foundational model.  
   - Handles text, images, and audio at the same time.  
   - Competitors: OpenAI ChatGPT, Meta LLaMA.  

2. **Gemma Model**  
   - Lightweight, open-source model.  
   - Smaller, faster, easier to run than Gemini.  
   - Ideal for startups/researchers.  

3. **Imagen Model**  
   - Text-to-image model.  
   - Generates high-quality, photorealistic images from text.  

4. **Veo Model**  
   - Text-to-video model.  
   - Generates video clips from text, images, or video prompts.  
   - Includes watermarking for safe use.  


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
