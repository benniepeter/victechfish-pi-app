[![PR Opened](https://github.com/cloudflare/cloudflare-docs/actions/workflows/pr.yml/badge.svg)](https://github.com/cloudflare/cloudflare-docs/actions/workflows/pr.yml)
<!DOCTYPE html>
<title>VicTechFish App</title>
<script src="https://sdk.minepi.com/pi-sdk.js"></script>
<script>
  Pi.init({
    version: "2.0",
    sandbox: false, 
    onReady: function() {
      console.log("Pi SDK imeandaliwa!");
      document.getElementById("pay-button").addEventListener("click", payWithPi);
    }
  });

  function payWithPi() {
    Pi.createPayment({
      amount: 10,
      memo: "Malipo ya huduma",
      metadata: { productId: "123" }
    });
  }
</script>
<button id="pay-button">Pay with Pi</button>
