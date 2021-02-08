# inventory-bot-api
The api to provide data by calling the webhooks form the inventory chatbot created using the sap cai.

## step 1- scaffolding your project.
  ```
mkdir inventory-bot-api && cd inventory-bot-api
npm init
  - package name: (js-api) inventory-bot-api
  - version: (1.0.0)
  - description: The api to provide the data using webhook to the invetory bot created using the sap cai.
  - entry point: (index.js) server.js
  - test command:
  - git repository: https://github.com/nihal-pandey/inventory-bot-api.git
  - keywords: api for inventory-chatbot
  - author: Nihal Pandey

npm install --save express body-parser axios
touch index.js config.js
mkdir discover-movies && cd discover-movies
touch index.js movieApi.js
cd..
  ```
