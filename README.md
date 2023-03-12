# Postman API testing portfolio project with restful-booker

![This is an image](https://cdn.shopify.com/s/files/1/0057/5668/2355/files/Postman-logo-orange-2021_1155x.png?v=1637252529)
## Dependencies

- Install [Postman](https://www.getpostman.com/)
- Visit [Restful Booker API](https://restful-booker.herokuapp.com/apidoc/index.html) for reference
  - This API is deployed publicly and testing against the live version is welcomed. 
  - You might want to install and run the [Restful Booker API](https://github.com/mwinteringham/restful-booker) from your machine for a few reasons:
    - You'll get to see the activity logging
    - You won't have to worry about the API being inaccessible due to maintenance or network issues
    - You'll be guaranteed to be the only person touching your data

## Setup

1) Install all dependencies listed above.
2) Download or clone this repo.
3) Launch Postman
   1) Create a new personal workspace, if desired.
      - More info: [Intro to Workspaces](https://learning.getpostman.com/docs/postman/workspaces/intro_to_workspaces)
   2) Import a collection (from file) into Postman.
      - More info: [Collection - Data Formats](https://learning.getpostman.com/docs/postman/collections/data_formats/#importing-postman-data)
      - Collection files are stored in this repo under /collections (ex. collections/Smoke.postman_collection.json)
      - Import the Local environment file if you'd like to run tests against an instance of Restful Booker running locally on your machine.
4) Start your local instance of Restful Booker (optional).
   - More info: [Restful Booker](https://github.com/mwinteringham/restful-booker)

## Structure

After cloning repo and running it in your postman you can see two folders:

**Custom Requesta** - use it for full run from creating to deleting

**Main Restful-booker folder** - to test all possible endpoints

## Running Tests

When running tests, you can choose to run them in various ways:

1. Run a test for a single request
  - to do so click your chosen request and then click the blue button **Send**
  - you can see your test results at the bottom
2. Run all tests for a folder or collection
  - to do so click the foldername **Custom Requests** and press the **run** button top right
  - choose how you wish to run the collection
  - click **Run Restful-booker** button and wait for the tests to finish
  - enjoy results

