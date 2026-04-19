# Engineering Team Agentic AI

## Overview
This project is designed to enhance the capabilities of engineering teams through the use of AI tools and automation. It provides a framework for managing tasks, agents, and tools that can assist in various engineering processes.

## Features
- **Task Management**: Efficiently manage tasks with customizable workflows.
- **Agent Configuration**: Define and configure agents to automate repetitive tasks.
- **Tool Integration**: Integrate various tools to streamline engineering processes.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/a-thul2/Engineering-Team-Agentic-AI.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Engineering-Team-Agentic-AI
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the application, execute:
```bash
python src/engineering_team/main.py
```


## Installation

Ensure you have Python >=3.10 <3.13 installed on your system. This project uses UV for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` or API key of your desired provider into the `.env` file**

- Modify `src/engineering_team/config/agents.yaml` to define your agents
- Modify `src/engineering_team/config/tasks.yaml` to define your tasks
- Modify `src/engineering_team/crew.py` to add your own logic, tools and specific args
- Modify `src/engineering_team/main.py` to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes the engineering_team Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a `report.md` file with the output of a research on LLMs in the root folder.

## Understanding Your Crew

The engineering_team Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.


