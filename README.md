# GrabPay Onetime Payment Integration

## Get started

Create an `.env` file at root of project with the following info:

```
GRAB_PAY_BASE_URL=https://partner-api.stg-myteksi.com
GRAB_PAY_PARTNER_ID={{partner_id}}
GRAB_PAY_PARTNER_SECRET={{partner_secret}}
GRAB_PAY_CLIENT_ID={{client_id}}
GRAB_PAY_CLIENT_SECRET={{client_secret}}
GRAB_PAY_MERCHANT_ID={{merchant_id}}
REDIRECT_BASE_URL=http://localhost:3000
```

Run

```
npm i
node index.js
```

In the browser, open http://localhost:3000/
