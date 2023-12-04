# Dog CEO API Postman tests

Documentation: https://dog.ceo/dog-api/documentation/

A collection verifying every endpoint from Dog CEO API. Comes with pre-request scripts and collection variables that allow to randomize requests. Testing responses' status codes and correctness of received data against requests' parameters.

## Potential issues:

* sometimes in requests that generate multiple random images the variable randomNumber might occasionally roll 0 and in such cases a single image will be presented. This situation is not specified in the documentation, therefore I'm unable to say if it's a bug or a feature.

## Usage:

1. Download the JSON file
2. Choose the **Import** option from menu **File** in Postman
3. Open the downloaded file
4. You should see a Dog CEO API in Your **Workspace**
5. Pick any of the requests You want to try and click **Send**
