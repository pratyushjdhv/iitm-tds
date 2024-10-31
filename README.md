- **Data collection**: Data on GitHub users and their repositories in Sydney with over 100 followers was gathered using the GitHub API, ensuring accuracy and completeness.
- **Key insight**: Surprisingly, developers with concise bios and more collaborative projects had higher follower counts.
- **Recommendation**: To attract more followers, developers should maintain active, well-documented repositories with a concise and engaging bio.

# GitHub User Data in Sydney

This repository contains data scraped from the GitHub API on users in Sydney with more than 100 followers, as well as information on their public repositories. The data includes details such as usernames, bios, public repository counts, and the programming languages they use.

## Contents

1. `users.csv` - Contains details on each user, such as:
    - Username (`login`)
    - Full name (`name`)
    - Company (`company`)
    - Location (`location`)
    - Contact details and bio (`email`, `bio`)
    - Github stats like follower count, repository count, etc.

2. `repositories.csv` - Lists details of each user’s recent repositories, including:
    - Repository name and creation date
    - Stars, watchers, primary language
    - Project and wiki status, and license information

3. `README.md` - This file, providing an overview of the data and recommendations.

## How to Use

The data can be analyzed to:
1. Study trends in followers based on user attributes.
2. Examine popular programming languages and project setups.
3. Identify factors that might boost visibility and engagement.

The `users.csv` and `repositories.csv` files are structured directly from the GitHub API, ensuring the most up-to-date and accurate reflection of each user's profile and activity.
