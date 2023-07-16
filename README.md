judychuepursuit
<!DOCTYPE html>
<html>
  <head>
    Welcome to My Budgeting App by Judy Chue!
  </head>
  <body>
    <h2>Budgeting App Backend</h2>
    <p>
      This backend app portion pairs with a front end budgeting app. And was built using
      <h3><a href="https://expressjs.com/">Express.js</a></h3>
    </p>
    <h2>This App implements the C-R-U-D points.</h2>
    <p>
      <br />
      Install the necessary dependencies by running <code>npm install</code>.
      <br />
      Start the development server by running <code>npm run dev</code>.
      <br />
      Run this API on <a href="http://localhost:3006">http://localhost:3006</a>.
    </p>
    <h2>API Endpoints</h2>
    <ul>
      <li>GET /transactions: Returns a list of all transactions.</li>
      <li>POST /transactions: Creates a new transaction.</li>
      <li>GET /transactions/: id: Returns the transaction with the specified ID.</li>
      <li>PUT /transactions/: id: Updates the transaction with the specified ID.</li>
      <li>DELETE /transactions/: id: Deletes the transaction with the specified ID.</li>
    </ul>
    <h2>Database</h2>
    <p>
      This app uses a [insert database technology here] database to store transactions.
    </p>
    <h2>Environment Variables</h2>
    <p>
      The following environment variables are required to run the app:
      <br />
      <ul>
        <li>DATABASE_URL: The URL of the database.</li>
        <li>PORT: The port number to run the server on.</li>
      </ul>
    </p>
    <h2>Contributing</h2>
    <p>
      Contributions are welcome! Please open an issue or submit a pull request.
    </p>
    <h2>License</h2>
    <p>
      This project is licensed w/ <a href="https://www.pursuit.org/">Pursuit</a>.
    </p>
  </body>
</html>