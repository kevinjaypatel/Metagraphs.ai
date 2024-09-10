# Metagraphs.ai

To contribute to the growth of Constellation Network and adoption of HGTP, we are building an ecosystem that supports existing metagraphs and helps drive the ideation & development of new metagraphs by leveraging a specialized, benevolent Ai agent and curating a network of dreamers, builders, and investors.

## Getting Started
This project uses Git submodules to include external repositories within the main repository. When cloning the project, you need to initialize and update the submodules to ensure all dependencies are properly deployed.

### Cloning the Repository with Submodules
To clone this repository along with its submodules, follow these steps:

1. **Clone the repository** using the `--recurse-submodules` flag to automatically initialize and update the submodules:
   ```bash
   git clone --recurse-submodules https://github.com/kevinjaypatel/Metagraphs.ai.git

### Usage

- Navigate to the `backend` folder, and follow the `README.md` guidelines for deploying the metagraph. Ensure the `Sample UI` is deployed after the metagraph is running.

- Upon successful deployment of the metagraph via `Euclid SDK`, navigate to the `frontend` folder for deploying the webflow project.

    - With node installed type: `npm i`.
    - Bundle the JavaScript: `npx webpack`

    - Start the python HTTP server:
    ```
    // For Python 3:
    python3 -m http.server --bind 127.0.0.1 8000

    or

    // For Python 2:
    python -m SimpleHTTPServer --bind 127.0.0.1 8000

    ```
- Navigate to the following URL: http://127.0.0.1:8000/create-proposal.html