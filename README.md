<div align="center">

# 🚀 Generative AI Learning & Projects

### From Python and NLP fundamentals to LangChain and practical Generative AI experiments

A hands-on learning repository documenting my journey through **Generative AI, Large Language Models (LLMs), LangChain, Natural Language Processing (NLP), and project-based experimentation**.

[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/tusharaitechie/generative-ai)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![GenAI](https://img.shields.io/badge/Focus-Generative%20AI-7C3AED)](https://github.com/tusharaitechie/generative-ai)
[![Learning](https://img.shields.io/badge/Approach-Learn%20by%20Building-0F766E)](https://github.com/tusharaitechie/generative-ai)

</div>

---

## 📌 About This Repository

This repository brings together learning material, code experiments, notebooks, and projects related to Python, NLP, LangChain, and Generative AI. It is intended to serve as a growing technical portfolio and a practical reference for revisiting concepts.

Rather than focusing on only theory, the repository is organized into topic-based folders so that concepts can be explored progressively—from foundational Python material to language-processing and LLM application development.

### 🎯 What this repository demonstrates

- **Python foundations** that support AI/ML development.
- **Natural Language Processing (NLP)** concepts and experiments.
- **LangChain learning and updates**, including framework-related examples.
- **Project-based practice** through the projects area.
- **Datasets and supporting resources** used for learning or experimentation.
- An ongoing, hands-on approach to learning the Generative AI ecosystem.

> **Repository note:** This README documents the top-level folders currently visible in the repository. Individual notebooks and nested project files may evolve over time; open the linked folder to see its current contents.

---

## 🗂️ Repository Structure

The following map explains the purpose of each top-level folder and repository file.

| Folder / File | What it contains / why it exists |
|---|---|
| [`1_Complete-Python-Bootcamp/1_Python_Basics/`](https://github.com/tusharaitechie/generative-ai/tree/main/1_Complete-Python-Bootcamp/1_Python_Basics) | **Python fundamentals.** A starting point for revising the core Python concepts used when building data, NLP, and AI applications. Explore the folder for the actual lessons and exercises available there. |
| [`1.LangChain/`](https://github.com/tusharaitechie/generative-ai/tree/main/1.LangChain) | **LangChain learning material.** A dedicated area for exploring LangChain concepts and code related to building applications around language models. |
| [`1.1LangChainUpdate/`](https://github.com/tusharaitechie/generative-ai/tree/main/1.1LangChainUpdate) | **LangChain updates and follow-up experiments.** A separate area for material associated with newer or updated LangChain learning. Check the folder for the specific examples and APIs used. |
| [`1.2Projects/`](https://github.com/tusharaitechie/generative-ai/tree/main/1.2Projects) | **Projects and practical implementations.** The project-focused area of the repository. Open it to review the individual project folders, source code, notebooks, and project-specific instructions. |
| [`NLP/`](https://github.com/tusharaitechie/generative-ai/tree/main/NLP) | **Natural Language Processing.** Material and experiments related to processing and working with human language—the foundation for many text-based AI and LLM applications. |
| [`dataset/`](https://github.com/tusharaitechie/generative-ai/tree/main/dataset) | **Datasets and data resources.** Supporting data files used by learning exercises or experiments. Review each project or notebook for its expected dataset path and format. |
| [`.gitignore`](https://github.com/tusharaitechie/generative-ai/blob/main/.gitignore) | Specifies files and directories Git should ignore, helping keep generated files, local environments, and other non-source artifacts out of version control when configured. |
| [`requirements.txt`](https://github.com/tusharaitechie/generative-ai/blob/main/requirements.txt) | Lists Python package dependencies for the repository. Check it before installing packages; some experiments may have their own version or setup requirements. |
| [`README.md`](https://github.com/tusharaitechie/generative-ai/blob/main/README.md) | Repository overview, navigation guide, and setup notes. |

---

## 🧭 Suggested Learning Path

If you are exploring this repository for the first time, this order is a useful starting point:

1. **Python basics** — revise syntax and core programming concepts.
2. **NLP** — explore text-processing concepts and related experiments.
3. **LangChain** — move into the framework and its LLM application patterns.
4. **LangChain updates** — compare or explore additional material in the update folder.
5. **Projects** — inspect the available implementations and follow their own instructions.
6. **Datasets** — identify the data required for each exercise or project.

This is a suggested navigation path, not a claim that every folder depends on the previous one. Individual projects may have their own prerequisites.

---

## 🛠️ Technology Areas

The repository's stated focus includes the following areas. The exact library used by each example should be confirmed in that example's notebook or source file.

| Area | Why it matters |
|---|---|
| **Python** | Core programming language for data processing and AI application development. |
| **Natural Language Processing (NLP)** | Techniques for preparing, analyzing, and working with text. |
| **LangChain** | Framework tooling for connecting language models with prompts, data sources, and application workflows. |
| **Large Language Models (LLMs)** | Models that can understand and generate text, depending on the model and task. |
| **Generative AI** | The broader field of applications that generate or transform content. |
| **Datasets** | Data used by experiments, examples, or project workflows. |

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/tusharaitechie/generative-ai.git
cd generative-ai
```

### 2. Create a virtual environment

**Windows (PowerShell / Command Prompt):**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

If you want to install the dependencies listed at the repository root:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Some notebooks or subprojects may require additional packages, API keys, environment variables, or specific model access. Check the instructions inside the relevant folder before running them.

### 4. Open a notebook or project

Open the repository in VS Code or your preferred Python IDE. Start with the Python basics folder, then explore NLP, LangChain, and the project folder. For notebook files, ensure Jupyter support is installed in your environment.

---

## 🔐 API Keys & Configuration

Some Generative AI examples may rely on third-party model providers or hosted APIs. If a project requires credentials:

- Store keys in environment variables or a local `.env` file when the project supports it.
- **Never commit API keys, passwords, access tokens, or private credentials** to GitHub.
- Follow the provider's current setup instructions and the specific project's documentation.
- Do not assume every example requires an API key; check the code first.

---

## 🧪 How to Explore a Project

For each project under `1.2Projects/` or another topic folder:

1. Open the folder and read any project-specific README or notebook introduction.
2. Check the required Python version and dependencies.
3. Locate the dataset or confirm whether the project downloads data separately.
4. Configure required environment variables or API keys, if any.
5. Run the notebook cells or application in order.
6. Review the output and experiment with the inputs or parameters.

Because each project may use a different workflow, use its own instructions as the source of truth.

---

## 🌱 Current Scope & Future Improvements

This repository is intended to grow as more learning exercises and implementations are added. Potential improvements include:

- Adding a short README to every project folder.
- Documenting each project's problem statement, approach, libraries, and results.
- Adding architecture diagrams or workflow illustrations where useful.
- Recording reproducible setup instructions and sample outputs.
- Including evaluation methods and limitations for model-based projects.

These are possible improvements, not a claim that every item is already implemented.

---

## 🤝 Feedback & Contributions

Suggestions, corrections, and learning resources are welcome. If you find an issue or have an idea for improving an example, please open a GitHub issue or submit a pull request.

- **Repository:** [tusharaitechie/generative-ai](https://github.com/tusharaitechie/generative-ai)
- **Issues:** [Report a problem or suggest an improvement](https://github.com/tusharaitechie/generative-ai/issues)

---

## 👨‍💻 Author

**Tushar**

Software engineering professional building practical skills in Data Science, Machine Learning, and Generative AI.

- GitHub: [@tusharaitechie](https://github.com/tusharaitechie)
- Repository: [Generative AI](https://github.com/tusharaitechie/generative-ai)

---

<div align="center">

**Learning by building. Improving through experimentation.**

⭐ If you find this repository useful, consider giving it a star.

</div>
