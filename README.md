# Agenda

-   AI → ML → Generative AI
-   Traditional AI vs Generative AI
-   LLMs
-   Parameters
-   Cost

------------------------------------------------------------------------

# 1. AI → ML → Generative AI

**AI:** Machines mimic intelligence (chatbots, fraud detection)

**ML:** Learns from data (prediction models)

**GenAI:** Creates new content (SQL, code, docs)

------------------------------------------------------------------------

# 2. Traditional AI vs Generative AI

**Traditional AI:** Rule-based, fixed output

**Generative AI:** Dynamic, context-aware, generates content

------------------------------------------------------------------------

# 🎯 Generative AI for DBAs – Complete Notes

---

# 🧠 What is Generative AI?

Generative AI can create:
- Text
- Images
- Audio
- Video

---

# 🤖 GPT Breakdown

**GPT =**
- Generative → Creates content (text, images, audio, video)
- Pretrained → Trained on massive internet data
- Transformer → Algorithm architecture

---

# 📊 Data Sources for LLMs

- Common Crawl
- Website sitemap.xml files
- Hugging Face datasets (FineWeb – 2023)

---

# 🕰️ Evolution of GPT

- **2017** → Attention is All You Need (Transformer paper)
- **2019** → GPT-1 (Word-level prediction)
- **2020** → GPT-2
  - MCQ generation
  - True/False
  - Paraphrasing
  - Q&A

---

# 💰 Infrastructure & Cost

- 100K+ GPUs
- Cost per GPU: $25K–$40K
- Huge data collection cost
- High training complexity

---

# 🌍 Impact on Industry

- Chegg (affected)
- Stack Overflow / Quora
- Google Search (blog income reduced)
- Arts industry
- Customer support automation

---

# 🌎 Major AI Players

### 🇺🇸 USA
- OpenAI (ChatGPT)
- Google (Gemini)
- xAI (Grok - Elon Musk)
- Meta (LLaMA)
- Anthropic (Claude)

### 🇮🇳 India
- Sarvam AI

### 🇦🇪 UAE
- Falcon

### 🇫🇷 France
- Mistral AI

### 🇨🇳 China
- DeepSeek
- Qwen (Alibaba)

---

# 🔍 AI Search Engine

- Perplexity (AI-powered search engine)

---

# ⚡ Features of ChatGPT

- Multimodal (text, image, audio, video)
- Multilingual
- Reasoning capabilities
- Bias (depends on training data)

---

# 🧩 LLM vs SLM vs MLM

## 🧠 Large Language Model (LLM)
- Very high parameters
- Example:
  - GPT-3.5 → 175B
  - GPT-4 → ~1T (rumored)
  - GPT-4o → ~200B
  - GPT-4o-mini → ~8B
- High accuracy
- Requires huge infrastructure

---

## 📱 Small Language Model (SLM)
- Less parameters (<10M)
- Lower accuracy
- Runs on edge devices
- Examples:
  - Gemma
  - Phi-2

---

## ⚖️ Medium Language Model (MLM)
- 10M–15M parameters
- Balanced performance

---

# 🎯 Fine-Tuned Models

Trained for specific domains:

- DarkBERT → Dark web
- BioBERT → Medical
- BloombergGPT → Finance
- LegalBERT → Law
- IndicBERT → Indian languages
- MedGemma → Medical
- DolphinGemma → Dolphin communication

✅ Lower cost  
✅ Domain-specific accuracy  

---

# 🔓 Open vs Closed Models

- Open Weight → LLaMA
- Closed Weight → GPT (proprietary)

---

# 🔐 ChatGPT Data Policy

- Logged-in → Data stored
- Not logged-in → Data not stored
- Temporary chat → Deleted after ~30 days

---

# 💬 Prompt vs Search Query

- Prompt → Input to AI  
- Search Query → Input to Google  

---

# 🧠 Learning Algorithm

- Reinforcement Learning
- RLHF (Reinforcement Learning with Human Feedback)

---

# 🛠️ ChatGPT Tools

- Web search → Real-time data  
- Think longer → Better reasoning  
- Deep research → High accuracy (~15 min)  
- Image generation  
- Canvas (editing text/images)  


---

# 🧩 Prompt Components

A good prompt includes:

- Role
- Question  
- Language (Hindi, Kannada, etc.)  
- Tone (simple, formal, harsh)  
- Audience (beginner, expert)  
- Output format:
  - Bullet points  
  - Table  
  - Paragraph  
  - MCQ  

---

# ⚠️ Limitations of ChatGPT

- Not strong in:
  - VBA
  - C#
  - Rust
  - Go

- Uses older library versions sometimes  
- May generate incorrect code  

---

# 💻 GPT Coding vs Vibe Coding

## 🤖 GPT Coding
- Guides you
- You write code

## ⚡ Vibe Coding
- AI does everything:
  - Creates files
  - Sets environment
  - Installs libraries
  - Writes code
  - Deploys application

---


# 🎯 GPT Parameters & Prompting Concepts

------------------------------------------------------------------------

# 🧠 1. Output Format

GPT responses can be generated in different formats:

-   Text (default)
-   JSON (structured output)

------------------------------------------------------------------------

# 🌡️ 2. Temperature (Creativity Control)

Temperature controls the **creativity/randomness** of the response.

## 🔢 Range:

-   0 to 2

## 📊 Behavior:

  Range        Behavior                       Example Audience
  ------------ ------------------------------ -----------------------
  0 -- 0.5     Less creative, deterministic   Kids (0--9 years)
  0.7 -- 1.2   Balanced output                Teenagers
  \> 1.2       Highly creative                Adults / storytelling

## 💡 Insight:

-   Lower temperature → More accurate, predictable\
-   Higher temperature → More creative, diverse

------------------------------------------------------------------------

# 🔤 3. Tokens

## 📌 What is a Token?

-   1 token ≈ 3--4 characters

## 📊 Limits:

-   Default: 2048 tokens\
-   Max: 32768 tokens (depends on model)

------------------------------------------------------------------------

# 🎯 4. Top-P (Nucleus Sampling)

Top-P controls **probability-based word selection**

## 📌 Example:

The birds fly in \_\_\_\_\_\_

Options: 1. sky (highest probability) 2. ocean\
3. road

------------------------------------------------------------------------

# 🧩 5. Variables in Prompts

Used to create **dynamic prompts**

## 📌 Example:

Famous food in {city}

Input: city = Amritsar

------------------------------------------------------------------------

# 🧠 6. System Message

Defines **behavior and personality** of AI

## 📌 Examples:

-   Respond like a 14-year-old boy\
-   Tone should be simple and clear\
-   Use harsh tone

------------------------------------------------------------------------

# 💬 7. Prompt Message

Defines **what the AI should do**

## 📌 Example:

-   Generate stock analysis for {{stock}}\
-   Provide SQL query based on given schema

------------------------------------------------------------------------

# 💰 8. Pricing Factors in GPT Usage

Pricing depends on multiple factors:

## 📊 Core Factors:

-   Model used
-   Input tokens
-   Output tokens
-   Context length

## ⚙️ Advanced Cost Factors:

-   Caching tokens
-   Request type (chat, embeddings, image, audio)
-   Throughput & latency
-   Fine-tuning
-   Tool usage
-   Multimodal inputs
-   Rate limits
-   Storage
-   Region agreements

------------------------------------------------------------------------

# 🎯 Key Takeaways

-   Temperature controls creativity\
-   Tokens impact cost & performance\
-   Top-P controls probability selection\
-   System message defines behavior\
-   Prompt message defines task





# 🎯 Key Takeaways

- Generative AI is transforming industries  
- LLMs are powerful but not perfect  
- Prompt quality = Output quality  
- Always validate AI output  
- Use AI as assistant, not replacement  




# 🤖 Agentic AI -- Detailed Notes

------------------------------------------------------------------------

# 🧠 What is Agentic AI?

Agentic AI refers to systems where **agents autonomously perform tasks**
with or without human intervention.

------------------------------------------------------------------------

# 👥 Multi-Agent Systems (MAS)

-   Multiple agents working together = **Crew / Team**
-   Each agent has:
    -   Skills (e.g., Data Scientist, Developer)
    -   Task responsibility
    -   Ability to plan and execute

------------------------------------------------------------------------

# ⚙️ Agent Workflow

## 🧩 Flow:

Task → Agent → Skills → Plan → Solve → Tools

------------------------------------------------------------------------

# 🔄 Detailed Process

1.  Agent receives a **problem/task**
2.  Agent creates a **plan**
3.  Human approves the plan (**Human-in-the-loop**)
4.  Agent uses tools (APIs, databases, etc.)
5.  Executes in a **sandbox environment**
6.  If errors occur → **Reiterate & improve**

------------------------------------------------------------------------

# 🔗 Core Components of Agents

## 🧠 Skills

-   Expertise of the agent
-   Example: Data Science, Web Development

## 🛠️ Tools

-   APIs, databases, external systems

## 🧾 Memory

-   Stores past interactions and context

## 🔄 Delegation

-   Transfer task from one agent to another

## 🔗 Coordination

-   Communication between agents

##  Plan

-   Three types of plan (sequential, hierarchical, and consensual)

------------------------------------------------------------------------

# 👥 Multi-Agent Example

-   Agent 1 → Data Scientist
-   Agent 2 → Web Developer

➡️ Together = **Crew**

------------------------------------------------------------------------

# 🔄 Delegation

-   If one agent cannot perform task → assign to another agent

------------------------------------------------------------------------

# 🔗 Coordination

-   Agents communicate with each other
-   Share information to complete tasks

------------------------------------------------------------------------

# 🏗️ Platforms for Building Agents

-   Agno (formerly Phidata)
-   CrewAI
-   LangGraph
-   AutoGen
-   OpenAI Swarm
-   Smola Agents
-   Manus (Meta)
-   n8n
-   Replit
-   Copilot Studio
-   Manus

------------------------------------------------------------------------

# 🧠 Agent Architecture

## 🎯 Master Agent (Controller)

-   Main AI system
-   Assigns tasks
-   Monitors performance
-   Coordinates agents

------------------------------------------------------------------------

## 🤖 Slave Agents (Specialized Agents)

-   Focused on specific tasks

### Examples:

-   Order tracking
-   Refund processing
-   Product information
-   Technical support
-   Account issues

------------------------------------------------------------------------

# ⚡ Types of AI Agents

## 🔹 Reactive Agents

-   Immediate response (no planning)
-   No memory
-   Rule-based

### Example:

-   IF error → restart service

### Features:

-   Fast
-   Simple
-   Scalable

------------------------------------------------------------------------

## 🔹 Deliberative Agents

-   Goal-oriented
-   Plan before acting
-   Maintain internal state

### Features:

-   Reasoning
-   Prediction
-   Optimization
-   Learning capability

------------------------------------------------------------------------

# 🎯 Key Takeaways

-   Agentic AI = Autonomous task execution
-   Multi-agent systems improve efficiency
-   Delegation & coordination are critical
-   Master agent controls system
-   Reactive vs Deliberative agents serve different use cases

------------------------------------------------------------------------

