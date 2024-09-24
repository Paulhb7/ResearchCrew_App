<div align="center">

# **ResearchCrew**

🤖🧠 **ResearchCrew**: Streamlit-based application using CrewAI to automates the process of researching, coding, and reviewing feature extraction techniques for a specified topic, especially for use in Scikit-learn transformers.

</div>

## 🚀 Features

- Research Agent: Identifies both classic and innovative feature extraction methods directly implementable in Scikit-learn.
- Coding Agent: Implements custom Scikit-learn transformers based on the methods identified by the Research Agent.
- Review Agent: Reviews the implementation, ensures code quality, and provides a clear synthesis of the techniques and code rationale.
- Streamlit Interface: User-friendly interface for inputting topics and viewing results in real-time.

## 🛠️ Tech Stack

Streamlit: User interface
CrewAI: Orchestrating agents to perform tasks collaboratively
Python: Core language for implementation
Scikit-learn: Library for feature extraction and machine learning
LLM (Large Language Model): Powered by Ollama LLaMA 3.1

## 📦 Installation

Prerequisites
Ollama: The project uses Ollama LLaMA 3.1 as the LLM. You need to have Ollama installed and configured locally. After installing, make sure you have llama3.1:8b model downloaded.

Run the application:

```bash
streamlit run app.py
```

## 💡 How It Works

- User Input: You provide a topic (e.g., "Natural Language Processing") in the Streamlit interface.
- Research Agent: It researches 3-5 classic and 3-5 innovative feature extraction techniques related to the topic that can be implemented in Scikit-learn transformers.
- Coding Agent: Implements custom Scikit-learn transformers for each method proposed by the Research Agent.
- Review Agent: Reviews the code, ensures its quality, and generates an executive summary of the feature extraction techniques and their relevance to the topic.

## 📋 Example Usage

1. Enter a topic such as Image Processing into the interface.
2. Click the "Start Research Process" button.
3. Wait while the agents conduct research, implement the transformers, and provide a review.
4. View the research results, generated code, and summary directly in the Streamlit app.

## 🎓 License

This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Contributing

Feel free to open an issue or submit a pull request if you want to contribute to this project!
