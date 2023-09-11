## Install Dependencies
```
cd nodejs-queue-project && npm i 
```

## Run Project
```
npm run dev
```

Project will be running on the following URL `http://localhost:4300`


## Making the POST Request

To send an email using the provided `curl` command, follow these steps:

1. Open your terminal.

2. Copy and paste the following `curl` command into your terminal:

```bash
curl --location --request POST 'http://localhost:4300/send-email' \
--header 'Content-Type: application/json' \
--data-raw '{
    "from":"ahmadraza@gmail.com",
    "to":"me@test.com",
    "subject":"Sending Sample Email",
    "text":"I love coding full time :D"
}'
