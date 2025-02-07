# GitHub101 - Beginner's Guide

Welcome to the GitHub101 class! This guide will help you fork and clone this repository, and create a simple text file to introduce yourself.

## Instructions

### 1. Fork the Repository
1. Go to the [repository page](https://github.com/your-repo-url).
2. Click the "Fork" button at the top right corner of the page.
3. This will create a copy of the repository under your GitHub account.

### 2. Clone the Repository
1. Navigate to your forked repository on GitHub.
2. Click the "Code" button and copy the URL.
3. Open your terminal or command prompt.
4. Run the following command to clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
5. Navigate into the cloned repository:
    ```bash
    cd your-repo-name
    ```

### 3. Create a Text File
1. In the cloned repository directory, create a new text file.
2. Name the file `about_me.txt`.
3. Open the file and write a few sentences about yourself.

### 4. Commit and Push Changes
1. Add the new file to the staging area:
    ```bash
    git add about_me.txt
    ```
2. Commit your changes:
    ```bash
    git commit -m "Add about_me.txt with personal introduction"
    ```
3. Push the changes to your forked repository:
    ```bash
    git push origin main
    ```

Congratulations! You have successfully forked, cloned, and contributed to the repository.

Happy coding!
