# CORS Testing

This mini web page is intended to be a local testing utilitiy for Cross Origin Resource (CORS) testing. To test a AWS API Gateway endpoint for CORS, follow these steps:

> This utility requires that you have `npm` installed locally.

---

1. Open a command line terminal and change to this directory.
2. Start the [local web server](https://www.npmjs.com/package/http-server).
   ```
   npx http-server
   ```
3. Navigate to [http://127.0.0.1:8080/](http://127.0.0.1:8080/) in our browser
4. Enter in the necessary fields, (e.g.: URL, API Key, and Bearer Token)
5. Select a javascript run method, (e.g.: Ajax, Fetch, XMLHttpRequest)
6. click `GET`
   > `F12` to Monitor the console log and network activity.