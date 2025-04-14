# 🧠 Creatures of Habit -- Dev Blog

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Quarto Version](https://img.shields.io/badge/Quarto-1.4+-informational?logo=quarto)](https://quarto.org)
[![Last Updated](https://img.shields.io/github/last-commitCreatures-of-Habit/dev-blog)](https://github.com/Creatures-of-Habit/dev-blog)


### 🧩 Core Elements of a Developer Blog

1. 🚧 **Project Updates**: Regular updates on the progress of your projects, including new features, bug fixes, and future plans.
2. 📘 **Tutorials and How-Tos**: Step-by-step guides on how to accomplish specific tasks or solve common problems in software development.
3. 💻 **Code Snippets**: Reusable pieces of code that can help other developers solve similar problems.
4. 🧪 **Technical Articles**: In-depth articles on various topics related to software development, such as best practices, design patterns, and performance optimization.
5. 🧠 **Personal Insights**: Sharing your personal experiences, challenges, and successes in the field of software development.

### 🎮 What to Include in a Developer Blog for Game Development

1. 🕹️ **Game Design Concepts**: Discuss the principles and theories behind game design, including mechanics, dynamics, and aesthetics.
2. 🛠️ **Development Tools and Technologies**: Share information about the tools, frameworks, and libraries you use for game development.
3. 👨‍💻 **Code Examples**: Provide code snippets and examples that demonstrate how to implement various game features and mechanics.
4. 🎨 **Art and Assets**: Showcase the art, sound, and other assets used in your games, and discuss how they were created or sourced.
5. ⚙️ **Performance Optimization**: Tips and techniques for optimizing game performance, including memory management, rendering, and physics calculations.
6. 🐛 **Testing and Debugging**: Strategies for testing and debugging your games to ensure they are free of bugs and run smoothly.
7. 📝 **Post-Mortems**: Reflect on completed projects, discussing what went well, what didn't, and what you learned from the experience.

---

## 📦 Installation & Local Setup

This blog is built using [**Quarto**](https://quarto.org/), an open-source scientific publishing system.

### ✅ Prerequisites

- [Quarto](https://quarto.org/docs/get-started/)
- 🧰 Git (optional but recommended)
- 🐍 Python 

Quarto Requirements

```
poetry install
poetry shell
```

### 🔧 Steps to Run Locally

```bash
# Clone the repository
git clone https://github.com/Creatures-of-Habit/dev-blog.git
cd dev-blog
```

# Preview the site locally
```
quarto preview
```

# Publish the site
```
quarto render
quarto publish
```

## 📁 Project Structure

```text
Creatures-of-Habit/dev-blog/
├── index.qmd                 # Homepage of the site
├── blog.qmd                  # Blog mainpage
├── references/
│   └── index.bib             # Bibliography in BibTeX format
├── styles.css                # Custom styles for site theme
├── _quarto.yml               # Quarto configuration file
└── ...

## 🚧 Roadmap

Planned features and upcoming updates:

- [ ] ✨ Add visual explainers for collective action strategies  
- [ ] 🧪 Embed interactive simulations and demos  
- [ ] 📚 Expand annotated bibliography and reading guides  
- [ ] 🤝 Enable community discussions and contributions  
- [ ] 🛠 Improve theming and accessibility  
- [ ] 🔍 Add full-text search and navigation aids  

Feel free to open an issue or contribute via pull request!

---
