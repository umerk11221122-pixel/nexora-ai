<!DOCTYPE html>
<html lang="en">
<head>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#101C3A">
  <meta name="description" content="NEXORA AI - Smart AI solutions for businesses.">

  <title>NEXORA AI</title>

  <link rel="manifest" href="manifest.json">

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #080F24;
      color: white;
    }

    header {
      padding: 22px;
      text-align: center;
      background: #101C3A;
      border-bottom: 2px solid #3157C8;
    }

    header h1 {
      margin: 0;
      font-size: 30px;
      letter-spacing: 2px;
    }

    header span {
      color: #8B72FF;
    }

    main {
      max-width: 650px;
      margin: 55px auto;
      padding: 20px;
      text-align: center;
    }

    .panel {
      background: #142347;
      padding: 35px 20px;
      border-radius: 20px;
      border: 1px solid #4056A8;
    }

    h2 {
      font-size: 32px;
    }

    p {
      color: #D4DDF5;
      line-height: 1.7;
    }

    .chat-button {
      display: inline-block;
      background: linear-gradient(90deg, #6545E8, #2675F5);
      color: white;
      padding: 16px 28px;
      border-radius: 12px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #AAB7D5;
      font-size: 13px;
    }
  </style>
</head>

<body>

  <header>
    <h1>NEXORA <span>AI</span></h1>
    <p>Software • Artificial Intelligence • Automation</p>
  </header>

  <main>
    <div class="panel">
      <h2>Your Smart AI Assistant</h2>

      <p>
        Welcome to NEXORA AI.
        Discover smarter customer support
        powered by artificial intelligence.
      </p>

      <a
        class="chat-button"
        href="https://cdn.botpress.cloud/webchat/v5.0/shareable.html?configUrl=https://files.bpcontent.cloud/2026/10/31/21/20261031212043-51ZYHFQ9.json"
        target="_blank"
        rel="noopener noreferrer">
        Open AI Chat
      </a>
    </div>
  </main>

  <footer>
    © 2026 NEXORA AI. All rights reserved.
  </footer>

  <script>
    if ("serviceWorker" in navigator) {
      window.addEventListener("load", () => {
        navigator.serviceWorker.register("./service-worker.js")
          .catch(error => console.log("Service worker error:", error));
      });
    }
  </script>

</body>
</html>
