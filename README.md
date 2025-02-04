Multi-Agent Philosophers Supervised Discussion 🧠🤖

📖 Project Overview

Much to everyone's misfortune, we cannot converse with history’s greatest minds. How enriching would it be to speak with our heroes, to hear their thoughts firsthand?

Luckily, we live in an era where we can imitate intelligence, fine-tuning LLMs to bring these voices back to life.

This project strives to fulfill humankind’s dream—allowing the great thinkers of the past to guide our daily questions through a multi-agent LLM framework, structured and supervised for meaningful discussion.

🚀 Features

Multi-Agent System: Simulates a structured discussion among multiple AI philosophers.
Supervised AI Discussion: Ensures the conversation follows a logical, meaningful flow.
Custom Tool Integration: Supports web scrapers, researchers, and custom AI tools for richer responses.
Graph-Based Workflow: Defines a structured process for handling responses and decisions.
🛠️ Setup & Installation

1. Clone the Repository
git clone https://github.com/username/agent_supervisor.git
cd agent_supervisor
2. Install Dependencies
Ensure you have Python installed (recommended: Python 3.8+). Then install the required packages:

pip install -r requirements.txt
3. Create Tools
You can add tools like:

Web Scraper: To fetch data.
Research Agent: To analyze historical texts.
Custom AI Workers: Any additional tools that fit your use case.
4. Create Agent Supervisor
The Agent Supervisor is responsible for:

Using an LLM with structured output to decide the next worker node.
Or terminating the discussion when an answer is reached.
5. Construct the Graph
Define the state and worker nodes:

# Define worker nodes
def philosopher_node(input_text):
    return process_with_ai(input_text)
Once the graph is built, your AI philosophers can engage in discussions.

6. Run the Project
python main.py
The discussion begins, and the AI philosophers will generate responses based on the structured framework.

📌 Example Usage

from agent_supervisor import Supervisor

supervisor = Supervisor()
response = supervisor.initiate_discussion("What is the meaning of life?")
print(response)
🔧 Configuration

Modify config.json to customize:

LLM model settings
Number of agents
Tools enabled
Discussion depth limit
📜 Changelog

[1.0.0] - YYYY-MM-DD
Initial release of Multi-Agent Philosophers Discussion
Implemented core features: multi-agent discussion, supervised responses, and tool integration.
🛡️ License

This project is licensed under the MIT License. See LICENSE for details.

👤 Author(s)

Your Name (@yourgithub)
🤝 Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (feature/new-feature).
Commit your changes.
Open a pull request.
🏆 Acknowledgments

Thanks to the LLM research community for inspiring the creation of this project.

