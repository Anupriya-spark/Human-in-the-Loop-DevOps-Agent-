Human-in-the-Loop DevOps Agent

A Human-in-the-Loop DevOps Agent built with Python and Streamlit that helps developers interact with GitHub repositories, analyze project documentation, and assist with DevOps-related workflows using AI.

Features
Connect to GitHub repositories
Fetch and analyze README.md files
AI-powered DevOps assistance
Human-in-the-loop workflow for better decision making
Streamlit-based web interface
Modular agent architecture
Easy to extend with additional DevOps agents
Project Structure
Human-in-the-Loop-DevOps-Agent/
│
├── agents/
│   ├── github_agent.py
│   ├── planner_agent.py
│   ├── reviewer_agent.py
│   └── ...
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── ...
Technologies Used
Python 3.x
Streamlit
PyGithub
OpenAI API (optional)
GitHub REST API
Installation
1. Clone the repository
git clone https://github.com/your-username/Human-in-the-Loop-DevOps-Agent.git
cd Human-in-the-Loop-DevOps-Agent
2. Create a virtual environment

Windows

python -m venv venv
venv\Scripts\activate

Linux / macOS

source venv/bin/activate
3. Install dependencies
pip install -r requirements.txt
Configuration

Create a .env file in the project root:

GITHUB_TOKEN=your_github_personal_access_token
OPENAI_API_KEY=your_openai_api_key

Load the environment variables in Python using python-dotenv.

Run the Project
streamlit run app.py

The application will start on:

http://localhost:8501
Example Workflow
Launch the Streamlit application.
Enter a GitHub repository name (e.g., owner/repository).
The GitHub Agent retrieves the repository's README.md.
The AI analyzes the documentation and provides DevOps insights.
The user reviews the suggestions and decides on the next steps.
Future Improvements
CI/CD pipeline generation
Docker support
Kubernetes deployment assistance
GitHub Actions integration
Infrastructure as Code recommendations
Multi-agent collaboration
Repository health analysis
Contributing

Contributions are welcome!

Fork the repository.
Create a feature branch.
Commit your changes.
Push the branch.
Open a Pull Request.
License

This project is licensed under the MIT License.

Developed for learning and demonstrating Human-in-the-Loop AI and DevOps automation concepts. 
