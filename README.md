# PayFields HTML and Client-Side JS Demo

This project demonstrates the use of PayFields and the Worldpay JavaScript scripts within a plain HTML/CSS example.

PayFields documentation

## Prerequisites

- A GitHub account and GitHub desktop. See the git how-to for more information.
- Node.js (version 12.x or later) and npm (or local web host solution)

## Setup

1. Clone the repository:

   ```
   git clone https://github.com/benrice-worldpay/PayFields-Example.git
   cd PayFields-Example
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Create a wp_secrets.js file
   The file must include the following variable exports:
   ```
   export const apiKey = '<YOUR_API_KEY>>';
   export const merchantID = '<MERCHANT_ID>';
   ```

## Running the Application

1. Start the npm server (or use another local host service)
   1. Open a command prompt in the directory with the index.html file for this project
   2. Install npm server if it is not already `npm install http-server`
   3. Run the command `http-server` to begin the server
2. Open a browser to the hosted site. By default with the npm server this URL is "http://localhost:8000"
3. Select the link on the index page for the Web Application

## Troubleshooting

## Contributing

:point_right: This README doc as well as checkin comments support Markdown syntax. For more information see [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
:boom: For the github emoji markdown refer to https://gist.github.com/rxaviers/7360908.

To contribute to the PayFields Demo:

1. Clone this repository locally
   :exclamation: For Worldpay Employees, you will need to use [GitHub Desktop](https://github.com/apps/desktop).
2. Create a new branch in the repository: use the command `git checkout -b <branch_name>` in a command line prompt in the directory that has the project.
   The branch name should concisely describe the additions you are making. ie. "UpdateReadme"
3. Make your changes and commit them: `git commit -m '<Commit Message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. In GitHub, create a pull request from your new branch to the `main` branch

## License

This project uses the following license: [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

- Kevin Oliver @kevinoliver-worldpay, for his input and work on https://github.com/kevin-oliver-worldpay/express-hosted-payments-demo
