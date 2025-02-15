# repairshop.github.io
Shoe repair shops
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pricing Plans</title>
  <script src="https://js.chargebee.com/v2/chargebee.js" data-cb-site="solutions-int-test" ></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="pricing-container">
    <div class="pricing-plan eco">
      <h2>Eco Plan</h2>
      <p class="price">$20</p>
      <ul>
        <li>Basic Features</li>
        <li>Email Support</li>
        <li>1 GB Storage</li>
      </ul>
      <a href="javascript:void(0)" data-cb-type="checkout" data-cb-plan-id="eco-repair" >
      <button class="btn">Choose Plan</button>
      </a>
    </div>
    
    <div class="pricing-plan premium">
      <h2>Premium Plan</h2>
      <p class="price">$50</p>
      <ul>
        <li>Advanced Features</li>
        <li>Priority Support</li>
        <li>10 GB Storage</li>
      </ul>
      <a href="javascript:void(0)" data-cb-type="checkout" data-cb-plan-id="premium-repair" >
      <button class="btn">Choose Plan</button>
      </a>
    </div>

    <div class="pricing-plan luxury">
      <h2>Luxury Plan</h2>
      <p class="price">$100</p>
      <ul>
        <li>All Features</li>
        <li>24/7 Support</li>
        <li>Unlimited Storage</li>
      </ul>
      <a href="javascript:void(0)" data-cb-type="checkout" data-cb-plan-id="luxury-repair" data-cb-plan-quantity="1" >
      <button class="btn">Choose Plan</button>
      </a>
    </div>
  </div>
</body>
</html>
