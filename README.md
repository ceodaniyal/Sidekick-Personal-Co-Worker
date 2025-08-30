# Sidekick – Personal Co-Worker AI Assistant

Sidekick is a lightweight Python tool built with CrewAI (or specify your framework) that acts as a personal AI co-worker—helping you automate tasks, brainstorm ideas, or assist with workflows through simple multi-agent orchestration.

---

##  Features

- **Agent-based design**  
  Configure multiple AI agents with distinct roles and responsibilities via simple YAML files.

- **Easy configuration**  
  Define agents and tasks in `agents.yaml` and `tasks.yaml` for quick setup.

- **Streamlined execution**  
  Just run:
  ```bash
  crewai run
  ```

…and watch Sidekick's agents spring into action.

* **Modular & extensible**
  Customize functionality by editing `sidekick.py`, `sidekick_tools.py`, or adding new modules.

* **Python modern tooling**

  * Supports Python 3.10–3.12
  * Manages dependencies and reproducibility with UV

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ceodaniyal/Sidekick-Personal-Co-Worker.git
cd Sidekick-Personal-Co-Worker
```

### 2. Install dependencies

(Example; adjust if you're using pip, poetry, etc.)

```bash
uv install
```

### 3. Configure your agents & tasks

Customize or create your YAML files (e.g. `agents.yaml` and `tasks.yaml`) to define who the agents are and what they should do.

### 4. Run the system

```bash
crewai run
```

This triggers the agents to work collaboratively and deliver outputs such as logs, response summaries, or reports (e.g., `report.md`).

---

## Project Structure

```
├── agents.yaml           # Defines AI agents and roles
├── tasks.yaml            # Describes tasks and workflows
├── sidekick.py           # Core agent orchestration logic
├── sidekick_tools.py     # Helper functions and tool definitions
├── app.py                # (Optional) An interface or script entrypoint
├── pyproject.toml        # Project metadata & dependencies
├── uv.lock               # Lockfile for UV dependency manager
└── README.md             # This documentation
```

---

## Customization Ideas

* Expand agent roles: e.g., “Researcher,” “Critic,” “Writer”
* Enhance output formats: generate reports, summaries, or chat logs
* Add integrations: connect to web APIs, databases, or local tools
* Develop a GUI or web dashboard wrapping around the agents

---

## Why Use Sidekick?

Sidekick transforms your AI agents into collaborative assistants—boosting productivity, supporting decision-making, and making complex workflows feel effortless.

---

## Contributing

Feel free to fork the repo, build new tools, improve agent logic, and submit pull requests. Let's build smarter together!

