# Bug Bounty Blueprint 💠

provides customizable templates for bug bounty reports. It's designed to simplify the reporting process, letting users focus on identifying vulnerabilities. Frontend in VueJS, Backend in FastAPI. 


<img src="https://github.com/PatrikFehrenbach/writedown/assets/9072595/14858946-4391-4f5b-be5f-e8b01b3fb8b8" width="200" alt="bug">


🌹 This tool was highly inspired by [Frans Rosen's template-generator](https://github.com/fransr/template-generator).

<img width="2056" alt="Screenshot 2023-09-24 at 13 19 07" src="https://github.com/PatrikFehrenbach/writedown/assets/9072595/6e6aeaf7-583e-4fb1-9377-918195cd4a55">



## Features

- **Custom Templates**: Customize or create templates tailored to your needs.
- **Markdown Support**: Write and preview reports in markdown.
- **Instant Preview**: Real-time rendering of your markdown report.

## Docker-Compose installation

1. Clone this repository: 
   ```bash
   git clone https://github.com/PatrikFehrenbach/BugBountyBlueprint.git
   ```
   
2.  Navigate to the project directory:
  ```bash
   cd BugBountyBlueprint
   ```
1. ```bash
   docker-compose up
   ```
2. Visit `http://localhost:8080` in your browser to access **Bug Bounty Blueprint**.

## Installation 🚀

1. Clone this repository:
   ```bash
   git clone https://github.com/PatrikFehrenbach/BugBountyBlueprint.git
   ```

2. Navigate to the project directory:
   ```bash
   cd BugBountyBlueprint
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

5. In a new terminal, navigate to the frontend directory and install npm packages:
   ```bash
   cd frontend
   npm install
   ```

6. Run the Vue.js frontend:
   ```bash
   npm run serve
   ```

Visit `http://localhost:8080` in your browser to access **Bug Bounty Blueprint**.

## Usage 🛠️

1. Select or create a new template.
2. Fill in the required fields in the template.
3. Instantly preview the rendered markdown report.
4. Copy the markdown or the rendered HTML to use in your bug bounty platform.

## Demo 

https://github.com/PatrikFehrenbach/writedown/assets/9072595/e0f0e579-404e-44f0-9b38-5be023394a3a


## Contribute 🤝

Are always welcome, just create a pull request and I'll review it :)

## Buy me a Coffee 

No don't. 