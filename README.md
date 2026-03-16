# News Researcher AI Agent

An AI-driven project designed to optimize the research-to-blogging workflow with dual AI agents. Built with Crew AI, Python, LangChain Google GenAI, and Serper API, this project includes a `Researcher` agent for gathering content and a `Content Writer` agent for crafting cohesive blog posts, resulting in an 80% improvement in content creation efficiency.

## Features
- **Dual-Agent Workflow**: The `Researcher` agent retrieves information from Google searches, while the `Content Writer` agent composes well-structured blog content.
- **Automated Research**: Uses the Serper API for Google search automation, enabling efficient content gathering and insight sharing.
- **Seamless Collaboration**: Real-time inter-agent communication allows for cohesive, high-quality content output with minimal manual input.

## Technology Stack
- **Languages**: Python
- **Frameworks**: Crew AI
- **APIs**: Serper API, LangChain Google GenAI
- **Environment Configuration**: `dotenv` for handling API keys

## Requirements

To run this project, you need the following dependencies installed:
- `crewai`
- `langchain_google_genai`
- `load_dotenv`
- `crewai_tools`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/myselfvanshu/Blog_Generation.git
   
   cd news-researcher-ai-agent


2. pip install -r requirements.txt

3. Create a file named ".env" and put  
   SERPER_API_KEY=your_serper_api_key  
   GOOGLE_API_KEY=your_crewai_api_key

4. python crew.py


# Blog_Generation
