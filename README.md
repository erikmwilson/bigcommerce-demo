# bigcommerce-webhook-demo

curl --request POST \
  --url https://api.bigcommerce.com/stores/7r0wcq8t6u/v2/hooks \
  --header 'accept: application/json' \
  --header 'content-type: application/json' \
  --header 'x-auth-client: 4p13n6mm3balv0g8b8mu8peorjjf9r2' \
  --header 'x-auth-token: owh4v0c5m5uczrc4nxii12qgw579f9w' \
  --data '{"scope":"store/product/updated","destination":"https://e4c89db3.ngrok.io/webhooks","is_active":true}'
