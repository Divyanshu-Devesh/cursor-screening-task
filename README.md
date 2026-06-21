Task:

To complete the Cursor IDE setup, connect my GitHub repository, install Claude Code and Codex, and document the setup process on a GitHub README.md file.

Step 1:
 Install Cursor IDE.

 Actions Performed:
  Downloaded the Cursor IDE from: https://cursor.com/downloads
  Installed Cursor IDE in my local system successfully
  Logged into Cursor successfully.


Step 2:

  Install Claude Code extension in Cursor

 Steps followed:
  Opened Cursor Marketplace from Customize.

  Searched for the following plugins:

  Claude
  Claude Code
  Anthropic

  Could not find Claude Code extension in the current Marketplace.

  Plausible alternative solution:

  Download and install Node.js from: https://nodejs.org
  Install Claude Code CLI using the command: npm.cmd install -g @anthropic-ai/claude-code


Step 3: Install Codex

 Steps followed:
  Opened Cursor Marketplace.
  Searched for:

  Codex
  OpenAI

  Could not find a Codex extension in the current Marketplace, either.

  Plausible alternative solution- Install Codex CLI using the command: npm.cmd install -g @openai/codex

Step 4:

  Created a public repository on:https://github.com

  Clone the public repository in Cursor using git clone https://github.com/username/repo-name
  Open the folder in Cursor- using the terminal.

Step 5:

  Create a README.md file for the repo with instructions on :
  1.Tools installed
  2.Steps completed
  3.Issues encountered
  4.Resolutions applied

  From the terminal,I used the following command: notepad README.md
  Added my observations and saved.

Step 6:

  Push the README.md to GitHub

 Steps followed:
  From the terminal, perform the following:

  git status
  git add README.md
  git commit -m "Added README.md for cursor setup"
  git push


The following issues were observed:
  Claude Code extension not available in Marketplace --> Can use Claude Code CLI instead
  Codex extension not available in Marketplace--> Can use Codex CLI instead
  npm was not initially available --> installed Node.js
  Also had to make sure to use the correct repository folder structure since it wasn't directly available.


The final tools installed were:

 Cursor IDE
 Node.js
 npm
 Claude code CLI
 Codex CLI

 