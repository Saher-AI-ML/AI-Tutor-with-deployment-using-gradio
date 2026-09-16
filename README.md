# AI Tutor with Gradio

An interactive AI Tutor powered by the OpenAI API that explains concepts according to the user's experience level. The application provides a simple web interface built with Gradio and supports streaming AI responses for a responsive user experience.

## Features

- Ask questions about any topic
- Choose an explanation level from beginner to expert
- Stream AI-generated responses in real time
- Adaptive explanations using prompt engineering
- Interactive web interface using Gradio
- OpenAI-compatible API integration through OpenRouter

## Tech Stack

### AI / ML

- Large Language Models (LLMs)
- OpenAI API
- OpenRouter
- Prompt Engineering
- Generative AI
- Streaming LLM Responses

### Development & Deployment

- Python
- Gradio
- Google Colab
- Jupyter Notebook

## How It Works

The user enters a question and selects their experience level:

| Level | Explanation Style           |
| ----- | --------------------------- |
| 1     | Like I'm 5 years old        |
| 2     | Like I'm 10 years old       |
| 3     | Like a high school student  |
| 4     | Like a college student      |
| 5     | Like an expert in the field |

The selected experience level is incorporated into the system prompt before the question is sent to the LLM. This allows the same question to receive explanations tailored to different levels of technical understanding.

The application also uses streaming responses, progressively displaying the generated answer instead of waiting for the complete response.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-tutor-gradio.git
cd ai-tutor-gradio
```

### 2. Install Dependencies

```bash
pip install openai gradio
```

### 3. Configure Your API Key

The project uses the OpenAI Python client with OpenRouter as the API endpoint.

Configure your API key securely rather than hard-coding it in the source code.

### 4. Run the Application

Open the notebook and execute the cells sequentially.

The Gradio interface can then be launched to interact with the AI Tutor.

## Example

**Question:**

```text
Explain what a neural network is.
```

**Experience Level:**

```text
2 - Like I'm 10 years old
```

The AI Tutor generates an explanation appropriate for the selected experience level.

Changing the experience level to:

```text
5 - Like I'm an expert in the field
```

produces a more technically detailed explanation.

## What I Learned

Through this project, I practiced:

- Integrating LLMs into Python applications
- Working with the OpenAI Python SDK
- Using OpenRouter with an OpenAI-compatible API
- Designing dynamic system prompts
- Implementing streaming LLM responses
- Building interactive AI applications with Gradio
- Connecting an LLM backend to a user-facing application
- Deploying and sharing an interactive AI application through Gradio

## Project Structure

```text
AI-Tutor/
|
├── AI_Tutor_with_deployment_using_gradio.ipynb
└── README.md
```

## Technologies

```text
Python
LLMs
Generative AI
OpenAI API
OpenRouter
Prompt Engineering
Gradio
Jupyter Notebook
Google Colab
```
