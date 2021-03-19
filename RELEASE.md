<h1>Release update to local server</h1>

Here are some notes on deploying personal openapi-generator webservice on Firebase hosting.

After changing templates run
   - ./mvnw clean install # from root directory, expecting SUCCESS
   - Run modules/openapi-generator-online/deploy2firebase.sh
   - Select default service name
   - When done the service should be accessable on specified URI
   
The Firebase deployment script requries authentication profiles. There is a copy in the mail with same name.

