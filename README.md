**GitHub Users in Seattle**

This repository compiles data on GitHub users based in Seattle who have over 200 followers and their repositories.

**GitHub Data Scraper:** This project utilizes GitHub’s API to collect and analyze data on repositories and users, providing valuable insights into developer trends and community engagement. The `gitscrap.py` script handles data extraction tasks, concentrating on user activity and repository statistics to identify meaningful patterns. These insights can inform improvements in developer workflows and boost project visibility.

**Project Overview**

**Data Scraping Process:** The `gitscrap.py` script interfaces with the GitHub API, gathering extensive datasets on repositories and users alike. Leveraging Python’s requests library, it iterates through paginated results to capture all relevant data points. Each piece of data is then structured and saved as a CSV file for further analysis.

- Data collected through GitHub API
- Date of collection: 2024-10-30
- Only users with over 200 followers were included
- A maximum of 500 most recently updated repositories per user

**Key Findings**

**Insights from Data Analysis:** Analyzing the retrieved data revealed an interesting trend: repositories with higher fork counts are often maintained actively and show greater longevity. This suggests that more widely forked projects tend to remain relevant over time.

**Developer Recommendations:** Developers can boost their project visibility by enhancing documentation and encouraging contributions from new users. Projects with open issues and clear guidelines for contributors often see higher engagement, which supports a healthier project lifecycle.

## Files

1. `users.csv`: Contains information about 521 GitHub users in Seattle with over 200 followers
2. `repositories.csv`: Contains information about 51116 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data
4. `Analysis_colab1_`: Colab notebook used for all the questions
