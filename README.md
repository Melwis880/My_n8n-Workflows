Personal collection of automated workflows and integration scripts developed with n8n.

## Structure
* **Root Directory:** Contains general configuration files (`.gitignore`, `docker-compose.yml`) and license information.
* **Workflow-Specific Directories:** Each workflow is stored in its own directory. These directories contain:
    * Descriptive names for the workflows.
    * `*.json`: The workflow definition file that can be directly imported into the n8n UI.
    * `README.md`: Explanatory documentation.
    * Python scripts specific to that workflow, if applicable.

## Available Workflows

| Project Name | Purpose | Primary Technology | Link |
| :--- | :--- | :--- | :--- |
|  |  |  |  |
|  |  |  |  |
...

## Usage

To integrate a workflow of interest into your own environment:
1. Download the `.json` file from the respective workflow's directory to your computer.
2. Log in to your local (e.g., Docker) or cloud-based n8n interface.
3. Import the flow using the **"Import from File"** option.
4. Define the necessary API keys and credentials for the workflow to run properly.


## 📄 License

All workflows and integration scripts in this project are shared open-source. For usage rights and other details, please refer to the [LICENSE](./LICENSE.txt) file in the root directory.
