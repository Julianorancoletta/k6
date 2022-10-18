# About

This repository contains an exported Postman collection and its converted k6 script for demonstration in [the Postman article in our blog](https://k6.io/blog/load-testing-with-postman-collections).


npm install -g @apideck/postman-to-k6

postman-to-k6 test-api.json -e env.json -o k6-script.js

k6 run k6-script.js



k6 run script.js

k6 run --vus 10 --duration 30s script.js
