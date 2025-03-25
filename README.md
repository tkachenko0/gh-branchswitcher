# Git BranchSwitcher

![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)

A simple GitHub CLI extension that allows switching branches across multiple git repositories located in subfolders of the current directory. This is particularly useful in the context of microservices.

## 📜 Description

This extension iterates over each directory in the current folder, checks if it is a Git repository, and attempts to switch to the specified branch. If the branch exists locally or remotely, it will checkout and pull the latest changes. Otherwise, it skips the repository and provides a warning.

## 🛠️ Installation

To install this extension, you need to have the GitHub CLI installed. If you don't have it yet, you can find installation instructions [here](https://docs.github.com/en/github-cli/github-cli/installation).

1. **Install the extension**:
   ```bash
   gh extension install tkachenko0/gh-branchswitcher
   ```

## 🚀 Usage

1. Navigate to the directory containing your subdirectories with Git repositories.

   ```bash
   cd path/to/your/directory
   ```

2. Run the extension, specifying the branch you want to switch to:
   ```bash
   gh branchswitcher <branch_name>
   ```

## Updates

To install new updates, run the following:

```bash
gh extension upgrade tkachenko0/gh-branchswitcher
```

## 📚 More Information

For more information on using GitHub CLI extensions, refer to the [GitHub CLI documentation](https://docs.github.com/en/github-cli/github-cli/using-github-cli-extensions).
