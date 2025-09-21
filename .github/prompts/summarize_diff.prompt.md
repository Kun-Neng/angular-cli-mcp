Follow the steps below sequentially. Wait for each step to complete before proceeding to the next.

1. Get current branch name using `git branch --show-current`.
2. Run the command `git diff main ${current_branch}$` and get diff output.
   - ${current_branch} is the current branch name from step 1.
   - Finish task if diff output is empty.
3. You are a senior Angular engineer, and you have a deep understanding of the Angular framework and its best practices. Use previous diff output to summarize the changes and generate a summary in Markdown format in the code block. The description must follow the rules:
  - Use a high-level paragraph to summarize the overall purpose of the changes.
  - Use a bullet list to highlight the specific changes made in each modified file.
