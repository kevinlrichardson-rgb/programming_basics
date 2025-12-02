# Programming Basics

A beginner-friendly repository demonstrating fundamental programming concepts using Python and Jupyter notebooks.


## About This Repository

The demonstration notebook showcases three major programming paradigms through practical, easy-to-understand examples. But the real goal of the repository is for you to get comfortable with git/GitHub and your development environment - if you can run the code in the `dog_simulation.ipynb` notebook that's a win, even if you don't completely understand it!


### What You'll Learn

The `programming_basics.ipynb` notebook demonstrates three different approaches to solving the same problem (making a dog bark) using:

1. **Procedural Programming** - Using functions and step-by-step procedures
2. **Object-Oriented Programming (OOP)** - Using classes and objects to model entities
3. **Functional Programming** - Using pure functions and immutable data

Each example is complete, runnable, and includes detailed explanations to help you understand the core concepts and trade-offs of each programming style.


## Getting Started

Choose one of the following options based on your preferred development environment:

1. Vocareum
2. GitHub codespace
3. Local VS Code


### Option 1: Vocareum

A Vocareum cloud virtual machine is provided to Fullstack students. You can run the `dog_simulation.ipynb` notebook there by downloading it from this repository and uploading it to your Vocareum environment.

#### Step 1: Download the Notebook

1. From this repository's [home page](https://github.com/gperdrizet/programming_basics) go to the `notebooks` directory
2. Click on the `dog_simulation.ipynb`
3. Click the small 'Download raw file' icon at the upper left of the notebook preview frame (looks like an arrow pointing down to a horizontal line)
4. Save the notebook locally somewhere you will be able to easily find it again

#### Step 2: Upload the Notebook to Vocareum

1. Go to our course Canvas home page
2. In the 'Resources and Lab' section, go to `BC Jupyter Lab`
3. Click 'Load BC Jupyter Lab in a new window', then start your Vocareum environment
4. Once the Jupyter lab interface has loaded, upload the notebook file by clicking the 'Upload Files' icon at the top of the file browser (looks like a arrow pointing up from a horizontal line)
5. Click on the notebook in the file browser to open the notebook
6. You can now:
   - Read through the markdown cells (text sections)
   - Run code cells by clicking the **▶️ Run** button next to each cell or pressing `Shift + Enter`
   - Experiment with the code by making changes


### Option 2: Using GitHub Codespaces

GitHub Codespaces provides a complete, cloud-based development environment with everything pre-configured. No local installation required!

#### Step 1: Fork the Repository

1. Go to this repository on GitHub: `https://github.com/gperdrizet/programming_basics`
2. Click the **"Fork"** button in the top-right corner of the page
3. This creates your own copy of the repository in your GitHub account

#### Step 2: Launch Codespace

1. On your forked repository page, click the green **"Code"** button
2. Switch to the **"Codespaces"** tab
3. Click **"Create codespace on main"**
4. Wait for the codespace to build (this may take a minute or two)
5. A browser-based VS Code environment will open with everything ready to go!

#### Step 3: Open and Run the Notebook

1. In the VS Code file explorer (left sidebar), navigate to the `notebooks` folder
2. Click on `dog_simulation.ipynb` to open it
3. You can now:
   - Read through the markdown cells (text sections)
   - Run code cells by clicking the **▶️ Run** button next to each cell or pressing `Shift + Enter`
   - Experiment with the code by making changes

**Note:** All dependencies are pre-installed in the codespace, so you can start coding immediately!


### Option 3: Local Development

Follow these step-by-step instructions to set up the repository on your local machine. Don't worry if you're new to Git or Jupyter - we'll walk through everything!

#### Prerequisites

Before starting, make sure you have:
- **VS Code** installed on your computer
- **Git** installed on your computer
- **Python** installed (version 3.10 or higher)

#### Step 1: Fork the Repository

1. Go to this repository on GitHub: `https://github.com/gperdrizet/programming_basics`
2. Click the **"Fork"** button in the top-right corner of the page
3. This creates your own copy of the repository in your GitHub account

#### Step 2: Clone Your Fork Using VS Code

1. Open VS Code
2. Open the **Terminal** in VS Code: **View** → **Terminal** (or press `Ctrl+`` `)
3. Navigate to where you want to store the project (e.g., `cd Desktop` or `cd Documents`)
4. On your forked repository page on GitHub, click the green **"Code"** button
5. Copy the URL (it should look like: `https://github.com/YOUR-USERNAME/programming_basics.git`)
6. Back in the VS Code terminal, run the clone command:
   ```bash
   git clone https://github.com/YOUR-USERNAME/programming_basics.git
   ```
7. Enter the project directory:
   ```bash
   cd programming_basics
   ```

#### Step 3: Open Project in VS Code

1. In VS Code, go to **File** → **Open Folder** (or press `Ctrl+K, Ctrl+O` on Windows/Linux or `Cmd+K, Cmd+O` on Mac)
2. Navigate to and select the `programming_basics` folder you just cloned
3. Click **"Select Folder"** to open the project

#### Step 4: Install the Jupyter Extension

1. In VS Code, click on the **Extensions** icon in the sidebar (or press `Ctrl+Shift+X`)
2. Search for **"Jupyter"**
3. Install the **Jupyter** extension by Microsoft (it should be the first result)
4. Wait for the installation to complete

#### Step 5: Create a Virtual Environment

A virtual environment keeps your project dependencies isolated from other Python projects.

1. Open the **Terminal** in VS Code: **View** → **Terminal** (or press `Ctrl+`` `)
2. Make sure you're in the `programming_basics` directory (you should see it in the terminal prompt)
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   
   **On Windows:**
   ```bash
   venv\Scripts\activate
   ```
   
   **On macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```
   
   You should see `(venv)` appear at the beginning of your terminal prompt, indicating the virtual environment is active.

#### Step 6: Install Required Packages

1. With your virtual environment activated, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   This installs `ipykernel`, which allows VS Code to run Jupyter notebooks.

#### Step 7: Open and Run the Notebook

1. In the VS Code file explorer, navigate to the `notebooks` folder
2. Click on `dog_simulation.ipynb` to open it
3. You can now:
   - Read through the markdown cells (text sections)
   - Run code cells by clicking the **▶️ Run** button next to each cell or pressing `Shift + Enter`
   - Experiment with the code by making changes

## How to Use This Notebook

- **Read First**: Start by reading the markdown cells (text sections) to understand each concept
- **Run Code**: Execute each code cell in order by pressing `Shift + Enter`
- **Experiment**: Try modifying the code to see how it affects the output
- **Compare**: Notice how each programming paradigm solves the same problem differently

## Troubleshooting

**VS Code can't find Python or the kernel?**
- Make sure your virtual environment is activated (you should see `(venv)` in the terminal)
- Try restarting VS Code after creating the virtual environment
- In the notebook, click on the kernel selector (top-right) and choose the correct Python interpreter

**Virtual environment activation not working?**
- On Windows, try: `venv\Scripts\Activate.ps1` (PowerShell) or `venv\Scripts\activate.bat` (Command Prompt)
- Make sure you're in the `programming_basics` directory when creating/activating

**Windows users seeing security or script execution errors?**
- If you see errors about "running scripts is disabled" or security policies when activating the virtual environment, make sure you're using a **Command Prompt** (cmd) terminal, not PowerShell
- In VS Code, you can change your default terminal by clicking the dropdown arrow next to the **+** icon in the terminal panel and selecting **"Command Prompt"**

**Jupyter extension not working?**
- Try reloading VS Code: **View** → **Command Palette** → **"Developer: Reload Window"**
- Make sure you have the official Jupyter extension by Microsoft installed

**Need help with Git?**
- [Git Basics Tutorial](https://git-scm.com/docs/gittutorial)
- [GitHub's Git Handbook](https://guides.github.com/introduction/git-handbook/)

