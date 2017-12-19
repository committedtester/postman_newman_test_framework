# To replicate locally
* Install node.js
* npm install (based on the package.json)

# Authentication step
* In the folder marked authentication you will need to create a Food2ForkAPIKey.json file
* Go to https://food2fork.com/about/api for your API key
* The format of the file is a basic one

[{
    "APIKEY":"YOUR KEY HERE"
}]

# To Execute
* Run 'npm run cloudtest' from the terminal for the collection in the cloud
* Run 'npm run localtest' for the local collection json

# To Modify
* Install PostMan
* Import the collection into your Postman and edit, remember to export back into the collections directory

# Notes
* Refer to https://www.npmjs.com/package/newman