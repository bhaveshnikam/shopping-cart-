# shopping-cart-
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Harvest vase</title>
    <style>
      body {
        background-color: rgba(125, 15, 25, 0.2);
      }

      .wrapper {
        height: 420px;
        width: 654px;
        margin: 50px auto;
        border-radius: 7px 7px 7px 7px;
      
        -webkit-box-shadow: 0px 14px 32px 0px rgba(0, 0, 0, 0.15);
        -moz-box-shadow: 0px 14px 32px 0px rgba(0, 0, 0, 0.15);
        box-shadow: 0px 14px 32px 0px rgba(0, 0, 0, 0.15);
      }

      .product-img {
        float: left;
        height: 420px;
        width: 327px;
      }

      .product-img img {
        border-radius: 7px 0 0 7px;
      }

      .product-info {
        float: left;
        height: 420px;
        width: 327px;
        border-radius: 0 7px 10px 7px;
        background-color: #ffffff;
      }

      .product-text {
        height: 300px;
        width: 327px;
      }

      .product-text h1 {
        margin: 0 0 0 38px;
        padding-top: 52px;
        font-size: 34px;
        color: #474747;
      }

      .product-text h1,
      .product-price-btn p {
        font-family: "Bentham", serif;
      }

      .product-text h2 {
        margin: 0 0 47px 38px;
        font-size: 13px;
        font-family: "Raleway", sans-serif;
        font-weight: 400;
        text-transform: uppercase;
        color: #d2d2d2;
        letter-spacing: 0.2em;
      }

      .product-text p {
        height: 125px;
        margin: 0 0 0 38px;
        font-family: "Playfair Display", serif;
        color: #8d8d8d;
        line-height: 1.7em;
        font-size: 15px;
        font-weight: lighter;
        overflow: hidden;
      }

      .product-price-btn {
        height: 103px;
        width: 327px;
        margin-top: 17px;
        position: relative;
      }

      .product-price-btn p {
        display: inline-block;
        position: absolute;
        top: -13px;
        height: 50px;
        font-family: "Trocchi", serif;
        margin: 0 0 0 38px;
        font-size: 28px;
        font-weight: lighter;
        color: #474747;
      }

      span {
        display: inline-block;
        height: 50px;
        font-family: "Suranna", serif;
        font-size: 34px;
      }

      .product-price-btn button {
        float: right;
        display: inline-block;
        height: 50px;
        width: 176px;
        margin: 0 40px 0 16px;
        box-sizing: border-box;
        border: transparent;
        border-radius: 60px;
        font-family: "Raleway", sans-serif;
        font-size: 14px;
        font-weight: 500;
        text-transform: uppercase;
        letter-spacing: 0.2em;
        color: #ffffff;
        background-color: #9cebd5;
        cursor: pointer;
        outline: none;
      }

      .product-price-btn button:hover {
        background-color: #79b0a1;
      }
    </style>
  </head>

  <body>
    <div class="wrapper">
      <div class="product-img">
        <img
          src="https://images.unsplash.com/photo-1560769629-975ec94e6a86?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8c2hvZXN8ZW58MHx8MHx8&auto=format&fit=crop&w=400&q=60"
          height="420"
          width="327"
        />
      </div>
      <div class="product-info">
        <div class="product-text">
          <h1>Stylish Shoes</h1>
          <h2>by tom artist</h2>
          <p>
            Superior Cushioning.<br />
            Flexibility in the right places.<br />
            Stability or Motion control.<br />
            Night-time reflectivity.<br />
            Breathability.
          </p>
        </div>
        <div class="product-price-btn">
          <p><span>18</span>$</p>
          <button type="button">buy now</button>
        </div>
      </div>
    </div>
  </body>
</html>
