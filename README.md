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
3. Select the link on the index page for the web application

## Troubleshooting

## Contributing

## License

## Acknowledgements

- Kevin Oliver @kevinoliver-worldpay, for his input and work on https://github.com/kevin-oliver-worldpay/express-hosted-payments-demo
