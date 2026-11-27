# Sample Web Project

Docs-as-Code Starter is a simple static website developed using HTML, CSS, and JavaScript. The project demonstrates fundamental web development functionality while serving as a practical example for managing documentation using the Docs-as-Code approach.

The site includes an interactive button that displays the time it was clicked and a small JavaScript API that allowing the user to send a message and receive a response.

## Project Setup

Follow these steps to download and run the project:

1. Clone this repository
   Open your terminal and execute:
   `https://github.com/sylvester196/docs-as-code.git`

2. Navigate to the proejcr folder
   cd docs-as-code

3. Open the project
   Open the projec folder in Visual Studio Code and use the Live Server extension to launch the website.
   No additional installations are required for this project.

   Alternative: Launch with GitHub Pages

## Project Structure

docs-as-code/

- index.html (Structure of the website)
- style.css (Styling and appearance of the website)
- script.js (Handles user interaction and API demonstration)
- README.md (Project information and documentation)

## Usage

Open the website in your browseR:

1. Click the Click me button.
2. The status message will update to display the time the button was clicked.
3. Open your browser's developer console to view the corresponding message logged by JavaScript.

### JavaScript API Example

The site uses a mininal demonstration API called window.fakeApi to display a message when the button is clicked.

It contains a ping() method that once click, updates the message on the page from "Status: ready" to "Status: clicked as -timestamp-" and "Button clicked as -timestamp-" in the console.

### API Details

- window.fakeApi: The object containing the demonstration API.
- ping(message): Accepts a message as a parameter.
- ok: Indicates whether the operation was successful.
- echo: Returns the original message.
- timestamp: Returns the date and time of the request in ISO format.

## Contribution Guidelines

Team members should follow the guidelines below. These guidelines outline the recommended workflow for contributing to the project. They help ensure that all changes are tracked, reviewed, and documented before being merged.

1. Create a GitHub Issue

- All new features, bug reports, and documentation improvements to be added must first be submitted as issues (GitHub Issues).
- Each issue should have a clear title and description explaining the proposed change and its significance.
- Issues are beneficial for tracking and team discussion.

2. Create a Branch

- Do not make changes directly to the main branch.
- Create a separate branch for each issue.
- Use descriptive branch names, such as docs/readme-update or feature/button-update.
- Branches are beneficial to isolate new changes before committing to the main code base.

3. Make and Commit Changes

- Make the necessary changes on your branch.
- Write clear and meaningful commit messages describing your work.
- Keep changes focused on the issue being addressed.

4. Submit a Pull Request

- Push your branch to GitHub.
- Open a Pull Request to merge your changes into the staging branch.
- Provide a clear description of the changes made.
- Each Pull Request that resolves an issue must explicitly include Closes #issue-number in its description.
- Changes are merged into the staging branch before the main for security reasons.

5. Review and Merge

- Pull Requests should be reviewed before merging.
- Address any feedback or requested changes.
- Once approved, merge the Pull Request into the staging branch.
- GitHub will automatically close the linked issue when the Pull Request is merged into the default branch.
- When ready for publishing, changes are merged into the main branch only after review and final approval.
