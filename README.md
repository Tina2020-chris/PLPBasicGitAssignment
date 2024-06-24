# PLPBasicGitAssignment

### Task 1: GitHub Repository Creation

1. **Log in to your GitHub account**:
   - Open [GitHub](https://github.com) and log in with your credentials.

2. **Create a new repository**:
   - Click on the "+" icon in the top-right corner and select "New repository" from the dropdown menu.
   - Name the repository "PLPBasicGitAssignment".
   - Optionally, add a description in the "Description" field.
   - Choose between making the repository public or private.
   - Check the box that says "Initialize this repository with a README".
   - Click the "Create repository" button at the bottom of the page.

### Task 2: Local Setup

3. **Create a local folder**:
   - Create a new folder on your local machine named "PLPBasicGitAssignment".

4. **Open a terminal or command prompt**:
   - Navigate to the newly created folder. Use the following command:
     ```bash
     cd path/to/PLPBasicGitAssignment
     ```

5. **Initialize a Git repository**:
   - Initialize a new Git repository in your local folder:
     ```bash
     git init
     ```

### Task 3: Connecting to GitHub

6. **Link your local repository to the GitHub repository**:
   - Add the GitHub repository as a remote. Replace `<repository-url>` with the actual URL of your GitHub repository:
     ```bash
     git remote add origin <repository-url>
     ```

### Task 4: Making Changes

7. **Create a new file**:
   - Inside your local folder, create a new text file named `hello.txt` and add a simple text message, e.g., "Hello, Git!".
     ```bash
     echo "Hello, Git!" > hello.txt
     ```

8. **Stage the changes**:
   - Stage the new file:
     ```bash
     git add hello.txt
     ```

9. **Commit the changes**:
   - Commit the staged changes with a message:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

### Task 5: Pushing to GitHub

10. **Push the changes to GitHub**:
    - Push the committed changes to your GitHub repository:
      ```bash
      git push -u origin main
      ```

### Task 6: Verification

11. **Verify on GitHub**:
    - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
