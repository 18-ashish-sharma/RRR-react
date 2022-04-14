npm install installs everything.
npm run deploy deploys everything.
npm run infrastructure:destroy removes everything.
Using npm as a task runner is an easy way to get some automation into the process. Utilizing the Azure SDK for Storage allows me to easily use the output of the Terraform deployment to upload the web application automatically.

I hoped you like this series on setting up a new React template as an alternative to CRA