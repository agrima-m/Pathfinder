# Pathfinder: AI-Powered Career Guidance System

## Overview

Pathfinder is an **AI-powered career guidance system** built with **N8N workflows** and **OpenAI**. It helps students explore personalized career options by analyzing their preferences, interests, and work style. The system recommends the **Top 5 career paths** along with suggested **courses** and **mentors**.

## Features

* Collects user input via form (field of study, interests, work preferences)
* Uses **OpenAI** to generate tailored career recommendations
* Logs form responses automatically into **Google Sheets**
* Sends personalized results to the user via **email automation**
* Workflows exported in **JSON format** for easy import into N8N

## Tech Stack

* **N8N** (workflow automation)
* **OpenAI API** (AI-powered recommendations)
* **Google Sheets** (data storage)
* **Email (Gmail API)** (personalized delivery)

## Repository Contents

* `workflow1.json` – Logs form inputs to Google Sheets
* `workflow2.json` – Sends personalized results via email when new data is added

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/pathfinder.git
   ```
2. Open **N8N** and import the provided workflow JSON files.
3. Configure the required credentials:

   * **Google Sheets API**
   * **Email (Gmail API)**
   * **OpenAI API Key**
4. Deploy the workflows.

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
