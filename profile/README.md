# ACM AI TXST - Standard Operating Procedure (SOP)

## Table of Contents
1. [Overview](#overview)
2. [Logging In and Accessing the Repository](#logging-in-and-accessing-the-repository)
3. [Cloning the Repository](#cloning-the-repository)
4. [Branching and Pull Requests](#branching-and-pull-requests)
5. [Commit Guidelines](#commit-guidelines)
6. [Merging Code](#merging-code)
7. [Using the License](#using-the-license)
8. [FAQs](#faqs)
9. [Contact Information](#contact-information)

## Overview
Welcome to the ACM AI Club repository! This document outlines the standard procedures for contributing code and maintaining consistency across all our projects. Please follow these guidelines to ensure smooth collaboration.

## Logging In and Accessing the Repository
1. **GitHub Organization**: All members must join the ACM AI TXST GitHub Organization.
   - **How to join**: You will receive an invite to your personal GitHub account. Once you accept, you will have access to the club repositories.
   - **Login URL**: [GitHub Organization URL](https://github.com/ACM-AI-TXST)
   
2. **Two-Factor Authentication (2FA)**: We highly recommend enabling 2FA on your GitHub account for added security.

## Cloning the Repository
1. Open a terminal or command prompt.
2. Use the following command to clone the repository:
   ```
   git clone https://github.com/ACM-AI-TXST/<repository-name>.git
   ```
3. Navigate into the cloned directory:
   ```
   cd <repository-name>
   ```

## Branching and Pull Requests
1. **Create a New Branch**: Before making any changes, create a new branch with a meaningful name related to your work.
   ```
   git checkout -b <branch-name>
   ```
   Example: 
   ```
   git checkout -b feature-add-chatbot
   ```
   
2. **Pull Requests (PR)**: After completing your work, push the branch and submit a pull request (PR) on GitHub. PRs should:
   - Have a clear title (e.g., "Added AI chatbot functionality")
   - Include a description summarizing the changes
   - Request a review from one or more maintainers

3. **Branch Naming Convention**:
   - Features: `feature-<feature-name>`
   - Fixes: `fix-<fix-description>`
   - Documentation: `docs-<documentation-update>`

## Commit Guidelines
1. **Commit Messages**: Write clear and concise commit messages.
   - Use the present tense: "Add feature" not "Added feature."
   - Example:
     ```
     git commit -m "Add login functionality"
     ```

2. **Frequency**: Commit frequently to track progress, but ensure commits are meaningful (i.e., each commit should represent a small, incremental step).

## Merging Code
1. All code must be reviewed by at least one other team member before being merged into the `main` branch.
2. After review, maintainers will merge your PR if it meets the standards.

## Using the License
We use the **MIT License** for all our repositories. The license allows anyone to use, modify, and distribute the code with proper attribution.

The full text of the license can be found [here](https://opensource.org/licenses/MIT).

## FAQs
- **Q: How do I update my local repository after a new merge?**
  - Run:
    ```
    git pull origin main
    ```

- **Q: Who can merge PRs?**
  - Only maintainers or project leads can merge pull requests after they have been reviewed.

## Contact Information
For any questions or issues, reach out to the ACM AI TXST leadership:
- **Email**: [your-email@txstate.edu](mailto:your-email@txstate.edu)
- **Slack/Discord**: Reach us on the ACM AI Club communication channels.
