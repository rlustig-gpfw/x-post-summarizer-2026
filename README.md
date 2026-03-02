# X Post Summarizer 2026

This repository contains an AI-generated summary of a public figure's 2026 X posts. The project analyzes recent posts from a specified X account handle and provides insights into key themes and notable content.

## Account Analyzed
- Handle: @llm_wizard

## Project Overview
This project was built using a LangGraph agent that leverages GitHub MCP tools for repository operations and the X API v2 for retrieving posts. The process automates the collection, analysis, and summarization of social media content.

## How to Replicate

1. **Set up your X API Bearer Token:**
   - Obtain a Bearer Token from the X Developer Portal.
   - Set the token as an environment variable named `X_BEARER_TOKEN`.

2. **Install Python dependencies:**
   ```
   pip install requests
   ```

3. **Run the search script:**
   - Use the provided `x_search.py` script to fetch recent posts from a specified X handle.
   - Example:
     ```
     python x_search.py llm_wizard
     ```

4. **Analyze and summarize:**
   - Use AI tools or manual methods to analyze the fetched posts and generate summaries.

---

*This project demonstrates automated social media content summarization using modern AI and API tools.*
