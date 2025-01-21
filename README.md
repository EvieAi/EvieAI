# Evie
Evie verifies GitHub repositories for legitimacy and code quality, and monitors X accounts for tweet deletions and name changes.


![Uploading Untitled design.png…]()




# Evie - GitHub & X Account Verification Agent

Welcome to **Evie**, an AI-powered agent designed to enhance the trustworthiness and quality assurance of open-source projects on GitHub and monitor changes in X accounts.

## Overview

Evie is an innovative AI agent that:

- **Analyzes GitHub Repositories** for legitimacy, quality, and error-free code.
- **Monitors X Accounts** for changes in content or identity, such as deleted tweets or name changes.

## Features

### GitHub Repository Verification

- **Legitimacy Check**: Ensures that the repository is not a clone or contains plagiarized content.
- **Code Quality Assessment**: Scans for errors, style adherence, and potential security vulnerabilities.
- **Errorless Code Verification**: Uses advanced algorithms to check if the code is free from syntax errors or logical mistakes.

### X Account Monitoring

- **Tweet History**: Checks if any tweets have been deleted from the account.
- **Account Identity**: Monitors if the account has changed its display name or username.

## Usage

### GitHub Repository Analysis

1. **Input Repository URL**: Provide the URL of the GitHub repository you want to analyze.
2. **Run Evie**: Execute the command:

    ```bash
    evie analyze-repo <repository-url>
    ```

3. **Review Results**: Evie will return a detailed report on the legitimacy and quality of the code.

### X Account Monitoring

1. **Input X Account**: Specify the X account you want to monitor, e.g., x.com/evie.
2. **Run Evie**: Use the following command:

    ```bash
    evie monitor-account <x-account-url>
    ```

3. **Check for Updates**: Evie will provide updates on any changes or deletions in the account's history.

## Installation

To install Evie, you need:

- Python 3.8+
- Git

### Steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/agent_evie/evie.git
    cd evie
    ```

2. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Configure Evie**:

    Set up your GitHub and X API keys in a `.env` file or through environment variables.

## Configuration

You will need to:

- Add your GitHub API token in `config.json` or as an environment variable.
- Add your X API credentials similarly.

    ```json
    {
      "github_api_token": "your_github_api_token",
      "x_api_key": "your_x_api_key",
      "x_api_secret": "your_x_api_secret"
    }
    ```

## Contributing

We welcome contributions! Here's how you can help:

- **Report Bugs**: Use GitHub Issues to report any bugs or issues you encounter.
- **Suggest Features**: Propose new features or enhancements.
- **Contribute Code**: Fork the repository, make your changes, and submit a pull request.

## License

Evie is released under the MIT License (LICENSE).

## Contact

For any questions or further information, please contact us at:

- X: [https://x.com/EvieEvie396376](https://x.com/EvieEvie396376)
- Email: support@evie.ai

Feel free to join the discussion or ask questions in our GitHub repository's issues section.

## Acknowledgements

Thanks to the open-source community for the fantastic tools and libraries that Evie leverages.
Special thanks to our contributors for their invaluable feedback and code contributions.

Happy verifying with Evie!
