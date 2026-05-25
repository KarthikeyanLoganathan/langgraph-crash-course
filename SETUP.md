# Setup

## System and Development Environment Setup

Ensure you have python3 `brew install python@3.14`

Install UV Package Manager `brew install uv`

Install Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)

Install extensions in Visual Stuidio Code [https://marketplace.visualstudio.com/VSCode](https://marketplace.visualstudio.com/VSCode)
* [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) Notebook support for python 


## Project Setup

Create a Project parent Folder like `/users/gokul/develop/ai-examples`

Clone githib repository  `git clone https://github.com/KarthikeyanLoganathan/langgraph-crash-course.git`

Go to project directory `cd /users/gokul/develop/ai-examples/langgraph-crash-course`

Open visual studio code for this project

Open Terminal in vscode

Initialze python virtual environment in project folder `uv init` or `uv sync`


## Windows specifics


Install uv `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`

Install python 3.14 if you have not installed already

`uv python install 3.14`

Then in vscode terminal, in the project folder `uv sync`