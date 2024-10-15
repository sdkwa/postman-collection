# SDKWA - Postman Collection

This is a Postman collection of [SDKWA](https://api.sdkwa.pro/). It provides access to the WhatsApp API to send and receive messages and media by HTTP-API requests. The provided environment contains the list of variables referenced by the API collection.

See [docs](https://api.sdkwa.pro/en/docs/) for details.

## Requirements

The SDKWA Postman Collection and Environment requires the installation of [Postman](https://www.getpostman.com/).


## Installation

1) Download `collection.json` and `environment.json` onto your local machine.
2) Open Postman, click on Import and select the two json files.
3) Once imported, a new API collection will be created, along with the environment.

See [docs](https://api.sdkwa.pro/en/docs/) for details.


## Convert Postman to OpenAPI
```
npm i postman-to-openapi -g
p2o ./collection.json -f ./openApi2.yml -o ./convertOptions.json
```
