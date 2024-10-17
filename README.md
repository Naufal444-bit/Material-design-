# Material-design-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Material Page</title>
  <link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>
</head>
<body>
  <div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
    <header class="mdl-layout__header">
      <div class="mdl-layout__header-row">
        <span class="mdl-layout-title">Material Page</span>
        <nav class="mdl-navigation">
          <a class="mdl-navigation__link" href="#home">Home</a>
          <a class="mdl-navigation__link" href="#contact">Contact</a>
        </nav>
      </div>
    </header>
    <main class="mdl-layout__content">
      <section id="home" class="mdl-grid">
        <div class="mdl-cell mdl-cell--12-col">
          <h2>Welcome</h2>
          <p>Material Design Lite in action!</p>
        </div>
      </section>
      <section id="contact" class="mdl-grid">
        <div class="mdl-cell mdl-cell--6-col">
          <h3>Contact</h3>
          <form>
            <div class="mdl-textfield mdl-js-textfield">
              <input class="mdl-textfield__input" type="text" id="name" placeholder="Name">
            </div>
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored">
              Send
            </button>
          </form>
        </div>
      </section>
    </main>
  </div>
</body>
</html>
