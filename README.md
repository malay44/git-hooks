# Project Name

The Git Journal Hook is a simple yet powerful Git hook that enhances your commit messages by automatically organizing them into a structured journal. When a commit message contains a specified separator, the hook separates the message into distinct parts, appends the first part to the commit message file, and logs the remaining information, including branch details and timestamp, into a coding journal file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Option 1: Using curl

```bash
curl -sSL https://raw.githubusercontent.com/malay44/git-hooks/main/prepare-commit-msg-hooks/code-journal | bash
```

### Option 2: Manual Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/malay44/git-hooks.git
    cd git-hooks
    ```

2. Provide execution permissions to the installation script:

    ```bash
    chmod +x ./<PATH_TO_DESIRED_HOOK>
    ```

3. Run the installation script:

    ```bash
    ./<PATH_TO_DESIRED_HOOK>
    ```

## Usage

1. **Structured Commit Messages**: Enhance your commit messages by separating them into meaningful parts.

2. **Automated Journal Logging**: Log commit details, such as branch name, folder name, and timestamp, into a coding journal file.

3. **Customizable Separator**: Choose a separator for your commit messages to trigger the hook.

## Contributing

If you'd like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [License Name] - see the [LISCENSE](LICENSE) file for details.
