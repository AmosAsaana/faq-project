<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link
      rel="icon"
      href="resources/favicon.ico"
      type="image/x-icon"
      sizes="96x96"
    />

    <title>Simple FAQ | devChallenges.io</title>

    <!--You are welcome to delete these styles or modify them in your own stylesheet -->
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        display: flex;
        align-items: center;
        flex-direction: column;
        height: 100vh;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
      }

      .author-info {
        font-size: 14px;
        text-align: center;
        margin-top: 16px;
        color: rgb(55, 65, 81);
      }

      .author-info a {
        text-decoration: none;
      }
      .head{
        margin: 40px;
        display: flex;
        align-items: center;
        flex-direction: column;
        text-align: center;
      }
      .head p{
        margin-top: 15px;
        margin-bottom: 20px;
        font-weight: 700;
        font-size: 13px;
        color: hsla(0, 0%, 0%, 0.705);
      }
      .container{
        margin-top: 30px;
      }
      .container h3{
        margin-top: 20px;
        margin-bottom: 8px;
      }
      .container p{
        margin-bottom: 20px;
      }
      .container ol, .container ul {
        margin-left: 20px;
        margin-bottom: 20px;
      }
      .container ol li, .container ul li{
        margin-top: 8px;
        margin-bottom: 8px;
      }
      hr{
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 40px;
      }
      a{
        text-decoration: none;
      }

      @media (max-width: 800px){
        body{
          margin: 40px;
        }
      }
    </style>
  </head>
  <body>
    <div class="body">
      <div class="head">
        <h1>Frequently Asked Questions</h1>
        <p>
          Browse through the most frequently asked questions
        </p>
      </div>
      <div class="container">
        <h3>How can I track my order?</h3><br>
        <p>
          You can track your order using the following steps
        </p>
        <ol>
          <li>Go to the Order <a href="#">Tracking page</a>.</li>
          <li>Enter your order number and email address.</li>
          <li>Click on the Track Order button to view the current status of your shipment.</li>
        </ol>
        <p>If you encounter any issues, please visit our <a href="#">Help Center</a></p>
      </div>
      <hr>
      <div class="container">
        <h3>What is your return policy?</h3><br>
        <p>We offer a 30-day return policy on most items. Here are some key points:</p>
        <ul>
          <li><strong>Items must be in original condition:</strong> Unworn, unused, and unwashed.</li>
          <li><strong>Include original packaging and tags:</strong> All items should be returned with their original packaging and tags.</li>
          <li><strong>Proof of purchase:</strong> A receipt or proof of purchase is required.</li>
        </ul>
        <p>For more detailed information, read our full <a href="#">Return Policy</a>.
        </p>
      </div>
    </div>
    
    <div class="author-info">
      Coded by <a href="#">Asaana Amos</a> | Challenge by
      <a href="https://www.devchallenges.io?ref=challenge" target="_blank"
        >devChallenges.io</a
      >.
    </div>
  </body>
</html>
