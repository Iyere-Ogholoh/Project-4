# DOCUMENTATION OF PROJECT 4
## MEAN STACK IMPLEMENTATION

STEP 1: INSTALL NODEJs

`sudo apt update`

![updating packages](./images/installing_nodejs/updating_packages.png)

`sudo apt upgrade`

![upgrading packages](./images/installing_nodejs/upgrading_packages-pg1.png)

![upgrading packages](./images/installing_nodejs/upgrading_packages_pg2.png)

![upgrading packages](./images/installing_nodejs/upgrading_packages_pg3.png)

Add certificates

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

![adding certificates](./images/installing_nodejs/adding_certificates_pg1.png)

![adding certificates](./images/installing_nodejs/adding_certificates_pg2.png)

![adding certificates](./images/installing_nodejs/adding_certificates_pg3.png)

`curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash`

![curl command](./images/installing_nodejs/curl_command.png)

`sudo apt install -y nodejs`

![installing nodejs](./images/installing_nodejs/installing_nodejs_page1.png)

![installing nodejs](./images/installing_nodejs/installing_nodejs_page2.png)

![installing nodejs](./images/installing_nodejs/installing_nodejs_page3.png)

![installing nodejs](./images/installing_nodejs/installing_nodejs_page4.png)


STEP 2: INSTALL MongoDB

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

![adding public key for package repository authentication](./images/installing_mongodb/adding_public_key.png)

`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

![adding software repository for MongoDB](./images/installing_mongodb/adding_software_repository_for_mungodb.png)

`sudo apt install -y mongodb`

[installing mongodb](./images/installing_mongodb/installing_mongodb.png)

`sudo service mongodb start`

`sudo systemctl status mongodb`

[verifying mongodb service is running](./images/installing_mongodb/verifyin_mongodb_service.png)

`sudo apt install -y npm`

`npm`

![checking that npm is installed](./images/installing_mongodb/checking_that_npm_is_installed.png)

`sudo npm install body-parser`

![installing body-parser](./images/installing_mongodb/installing_body-parser.png)

create Books directory and cd to books directory

`mkdir Books && cd Books`

![mkdir Books && cd Books](./images/installing_mongodb/making_and-changing_to_Books_directory.png)

`npm init`

![json for npm init](./images/installing_mongodb/json_file_for_npm_init.png)

add file server.js

`vi server.js`

![server.js file](./images/installing_mongodb/server.js_file.png)

STEP 3: INSTALL EXPRESS

`sudo npm install express mongoose`

![installing express and mongoose](./images/installing_express/installing_express%26mongoose.png)

`mkdir apps && cd apps`

![making and cd to apps directory](./images/installing_express/making%26changing_to_apps_directory.png)

`vi routes.js`

![routes.js file contents](./images/installing_express/routes.js_file.png)

`mkdir models && cd models`

![making and cd to models directory](./images/installing_express/making_and_cd_to_models_directory.png)

`vi book.js`

![book.js file contents](./images/installing_express/book.js_contents.png)

STEP 4 ACCESS THE ROUTES WITH AngularJS










