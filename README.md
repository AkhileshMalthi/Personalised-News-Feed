## Personalised News Feed

This project aims to build a web-based personalized news aggregator that leverages Large Language Models (LLMs) to filter and summarize news articles based on user preferences.

**Project Goals:**

* Develop a user-friendly interface for profile creation and news feed browsing.
* Integrate an LLM API for user profile analysis and news article filtering.
* Provide users with a personalized news feed tailored to their interests and preferred sources.
* Offer optional news summarization using the LLM for quick information access.
* Implement a feedback mechanism for continuous improvement.

**Tech Stack:**

* **Front-end:** ReactJS
* **Back-end:** Python (Flask)
* **Database:** MongoDB
* **Web Scraping:** BeautifulSoup
* **LLM API:** OpenAI (ChatGPT), Google AI (Bard) or any other

**Getting Started:**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/personalised-news-feed.git
   ```

2. **Install dependencies:**

   Refer to the `requirements.txt` file (to be created) for specific dependencies and installation instructions.

3. **Configure LLM API:**

   * Obtain an API key from your chosen LLM provider (OpenAI, Google AI).
   * Create a configuration file (`.env` or similar) to store your API key securely (refer to documentation for proper configuration).

**Project Structure (Suggestions):**

* `frontend/`: Contains the code for the user interface.
* `backend/`: Contains the code for server-side logic and API interaction.
* `data/`: Stores collected news articles and user profile data.
* `scripts/`: Contains helper scripts for data collection, pre-processing, and deployment.
* `README.md`: This file (you are currently reading it!).
* `requirements.txt`: Lists all required dependencies for the project.
* `.env`: Stores sensitive information like LLM API keys (if applicable).

**Contributing:**

We welcome contributions to this project! Here's how you can get involved:

* **Bug reports and feature requests:**  
  Use the GitHub issue tracker to report bugs or suggest new features.
* **Code contributions:**
  Fork the repository, make your changes, and submit a pull request for review. 
  Ensure your code adheres to the existing code style and formatting guidelines (to be defined in a separate coding style document).
* **Documentation improvements:** 
  Help us improve the project documentation by creating pull requests for the README.md or other documentation files.

**Getting Help:**

If you have any questions or need help with the project, feel free to create an issue on the GitHub repository or reach out to the project maintainers through the defined communication channel.
