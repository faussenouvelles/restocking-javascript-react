# restocking-javascript-react
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>React Cart</title>

    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
      crossorigin="anonymous"
    />
    <!-- Don't use this in production: -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  </head>

  <body>
    <h1>React Shopping Cart</h1>

    <!-- We will put our React component inside this div. -->
    <div id="root"></div>

    <!-- React -->
    <script src="https://unpkg.com/react@17.0.2/umd/react.development.js" crossorigin></script>
    <script
      src="https://unpkg.com/react-dom@17.0.2/umd/react-dom.development.js"
      crossorigin
    ></script>

    <!-- React-Bootstrap -->
    <script
      src="https://unpkg.com/react-bootstrap@next/dist/react-bootstrap.min.js"
      crossorigin
    ></script>

    <!-- React Router -->
    <script src="https://unpkg.com/react-router@5.2.0/umd/react-router.js" crossorigin></script>
    <script
      src="https://unpkg.com/react-router-dom@5.2.0/umd/react-router-dom.min.js"
      crossorigin
    ></script>

    <!-- Load Axios and Our Component -->
    <script src="https://unpkg.com/axios/dist/axios.min.js"></script>

    <script src="https://raw.githubusercontent.com/faussenouvelles/restocking-javascript-react/main/cart.jsx" defer type="text/babel"></script>
  </body>
</html>
