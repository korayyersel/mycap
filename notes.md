 # Installation
 
 1. Install Node.js from https://nodejs.org
 2. Set npm registry for @sap packages npm set @sap:registry=https://npm.sap.com
 3. Install cds development kit globally npm i -g @sap/cds-dk, cds  #> test-run it (npm i -g @sap/cds auch?)
 4. Install SQLite from http://sqlite.org/download.html ( on Windows only; included with Mac and Linux) oder einfach npm install sqlite3 -D?
 5. 
 5. Install Visual Studio Code (https://cap.cloud.sap/docs/get-started/in-vscode)
 6. Add CDS Editor (https://cap.cloud.sap/docs/get-started/in-vscode)
 7. Running Services (https://cap.cloud.sap/docs/get-started/in-vscode)
 8. Debugging Services (https://cap.cloud.sap/docs/get-started/in-vscode)
 9. Restarting the Server (https://cap.cloud.sap/docs/get-started/in-vscode)
 
 # Commands
cds serve all
cds compile .\srv\ --to xsuaa > xs-security.json
cds build/all

npm run build:mta
cf deploy .\mta_archives\mycap_1.0.0.mtar

> TODO add destination for java. change xs-app.json to forward calls from ui to backend
