# Money Manager bank redirect

A static page used as the Enable Banking redirect URL for the Money Manager app.

After a bank login, Enable Banking sends the browser here. The page forwards only `code`, `state`, `error` and
`error_description` to the app (`moneymanager://bank/callback`) and sends nothing anywhere else. The code is useless
without the private key that stays on the person's phone.

Register this URL in your Enable Banking application:

https://pedrojfs17.github.io/money-manager-bank-redirect/
