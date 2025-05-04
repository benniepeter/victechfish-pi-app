[![PR Opened](https://github.com/cloudflare/cloudflare-docs/actions/workflows/pr.yml/badge.svg)](https://github.com/cloudflare/cloudflare-docs/actions/workflows/pr.yml)<!DOCTYPE html>
<html>
<head>
    <title>VicTechFish App</title>
    <script src="https://sdk.minepi.com/pi-sdk.js"></script>
</head>
<body>
    <script>
        Pi.init({ version: "2.0", ... })
            sandbox: true,   Weka 'false' kwa production
            onReady: function() {
                console.log("Pi SDK imeandaliwa kikamilifu!");
                
                document.getElementById('payButton').style.display = 'block';
            }
        });

        function payWithPi() {
            Pi.createPayment({
                amount: 10,
                memo: "Nunua samaki 1kg",
                metadata: { productId: "sato_001" }
            }, {
                onReady: function(paymentId) {
                    console.log("Malipo yako tayari!", paymentId);
                },
                onCancel: function(paymentId) {
                    console.log("Malipo yamebatilishwa", paymentId);
                },
                onError: function(error) {
                    console.log("Kuna hitilafu:", error);
                }
            });
        }
    </script>

    <button id="payButton" style="display:none;" onclick="payWithPi()">
        Lipa kwa Pi Coin
    </button>
</body>
</html><!-- Sahihi -->
   <script src="https://sdk.minepi.com/pi-sdk.js"></script>
   
   <![1000123618]>(https://github.com/user-attachments/assets/4bfedcb4-6bb3-412a-b001-e7effbce09da)
![1000123622](https://github.com/user-attachments/assets/8a2ec520-1c08-4559-ae66-0d14295d774e)
![1000123617](https://github.com/user-attachments/assets/b31eed7d-63b2-4ced-9f9a-4c7e47707c69)
![1000123619](https://github.com/user-attachments/assets/bac6de85-d882-4e11-86bc-3e07927a0779)

   <script src="https://sdk.minepi.com/pi-sdk.js"></script![1000130314](https://github.com/user-attachments/assets/076a7344-f451-460b-af01-9c52481896ff)
![1000123624](https://github.com/user-attachments/assets/e05fd7de-19a4-453f-9bed-edfafa52d1ef)
![1000123617](https://github.com/user-attachments/assets/15fca134-dedf-4172-8a4b-e7cea5dffbc7)
![1000130314](https://github.com/user-attachments/assets/35bc152e-88bc-49b4-b383-f2a17bbf05e6)
