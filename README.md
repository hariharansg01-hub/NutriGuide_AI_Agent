# 🥗 NutriGuide AI Agent

### Your Intelligent AI-Powered Nutrition Assistant

NutriGuide AI Agent is an AI-powered nutrition assistant designed to help users understand food nutrition, retrieve nutritional information, compare nutrients, and get reliable answers to nutrition-related questions.

Built using **Python, Groq LLM, Function Calling, and Context Engineering**, this project combines Large Language Models with a structured food nutrition database to provide accurate and context-aware responses.

## 🚀 Features

- **AI-Powered Nutrition Assistant:** Answers nutrition-related questions using an LLM.
- **Food Nutrition Lookup:** Retrieves nutritional information for available food items.
- **Nutrition Database:** Stores food information such as calories, protein, carbohydrates, and fat.
- **Function Calling:** Allows the AI agent to call Python functions to retrieve accurate nutrition data.
- **Context Engineering:** Maintains conversation history to provide context-aware responses.
- **Food Comparison:** Helps users understand and compare nutritional values.
- **Reliable Responses:** Uses database-backed nutrition values instead of inventing nutritional information.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Groq API | LLM integration |
| Llama / GPT-OSS | AI language models |
| Pandas | Nutrition data management |
| JSON | Structured data and tool arguments |
| Function Calling | Connecting AI with Python tools |
| Google Colab | Development and execution environment |

## 🏗️ Project Architecture

```text
             User Query
                 |
                 v
         NutriGuide AI Agent
                 |
                 v
             Groq LLM
                 |
          Function Calling
                 |
                 v
       Nutrition Database Tool
                 |
                 v
          Food Nutrition Data
                 |
                 v
          Tool Result to LLM
                 |
                 v
          AI Generated Answer
                 |
                 v
             User Output
```

## 📂 Project Structure

```text
NutriGuide_AI_Agent/
│
├── NutriGuide_AI_Agent.ipynb
│
├── NutriGuide_AI_Agent_Context_Engineer.ipynb
│
└── README.md
```

### Notebook Description

**1. NutriGuide_AI_Agent.ipynb**

- Introduction to Groq LLM integration.
- Creating a nutrition database using Pandas.
- Retrieving food nutrition information.
- Implementing AI tool calling.
- Connecting nutrition tools with the AI agent.

**2. NutriGuide_AI_Agent_Context_Engineer.ipynb**

- Implementing context engineering.
- Maintaining conversation history.
- Building a context-aware nutrition assistant.
- Integrating nutrition database tools with the LLM.
- Generating responses based on previous conversations.

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/hariharansg01-hub/NutriGuide_AI_Agent.git
```

### 2. Navigate to the Project

```bash
cd NutriGuide_AI_Agent
```

### 3. Install Dependencies

```bash
pip install groq pandas
```

### 4. Configure Groq API Key

1. Create an API key from [Groq Console](https://console.groq.com/).
2. Open the notebook in Google Colab.
3. Navigate to Secrets.
4. Add a secret named `GROQ_API_KEY`.
5. Enable notebook access to the secret.

Example:

```python
from google.colab import userdata

GROQ_API_KEY = userdata.get("GROQ_API_KEY")
```

**Important:** Never share or upload your API key publicly.

### 5. Run the Project

- Open the required `.ipynb` notebook in Google Colab.
- Configure your Groq API key.
- Execute the notebook cells sequentially.
- Start interacting with the NutriGuide AI Agent.

## 🥑 Sample Nutrition Database

The project includes sample food nutrition data.

| Food | Serving | Calories | Protein | Carbs | Fat |
|---|---:|---:|---:|---:|---:|
| Boiled Egg | 50g | 78 kcal | 6.3g | 0.6g | 5.3g |
| Milk | 100g | 61 kcal | 3.2g | 4.8g | 3.3g |
| Banana | 100g | 89 kcal | 1.1g | 22.8g | 0.3g |
| Rice | 100g | 130 kcal | 2.7g | 28g | 0.3g |
| Chicken Breast | 100g | 165 kcal | 31g | 0g | 3.6g |

*Values represent the sample dataset included in the project.*

## 💬 Example Queries

Users can ask questions such as:

- How much protein is present in 100g of chicken breast?
- What are the calories in a boiled egg?
- Compare the nutritional values of milk and banana.
- How much protein does a banana contain?
- Why is protein important for the human body?

## 🧠 Key Concepts Demonstrated

- Large Language Models (LLMs)
- AI Agent Development
- Prompt Engineering
- Context Engineering
- Function Calling
- Tool Integration
- Structured Data Retrieval
- Conversation Memory

## 🔮 Future Enhancements

- Expand the food nutrition database.
- Add personalized diet recommendations.
- Implement daily calorie tracking.
- Add BMI and nutritional requirement calculations.
- Support Indian regional foods.
- Develop a user-friendly web interface.
- Add personalized meal planning.
- Integrate a larger nutrition dataset.

## ⚠️ Disclaimer

NutriGuide AI Agent is an educational and informational project. Its responses should not replace professional medical advice or consultation with a qualified nutritionist.

## 👨‍💻 Author

**Hariharan**

GitHub: [@hariharansg01-hub](https://github.com/hariharansg01-hub)

Project: [NutriGuide AI Agent](https://github.com/hariharansg01-hub/NutriGuide_AI_Agent)

---

⭐ If you find this project useful, consider giving it a star on GitHub!

**Built with ❤️ using Python and Generative AI.**
