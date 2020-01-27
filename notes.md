 # Installation
 
 1. Install Node.js from https://nodejs.org
 2. Set npm registry for @sap packages
 
`npm set @sap:registry=https://npm.sap.com`

3. Install cds development kit globally 

`npm i -g @sap/cds-dk`

`cds  #> test-run it` 

`npm i -g @sap/cds` ???

 4. Install grunt
 
 `npm install -g grunt-cli`

 5. Install SQLite from http://sqlite.org/download.html ( on Windows only; included with Mac and Linux) oder einfach folgender npm Skript?
 
 `npm install sqlite3 -D` 
 
 6. CF CLI https://github.com/cloudfoundry/cli#downloads
 7. CF CLI MTA Plugin 
 
 `cf add-plugin-repo CF-Community https://plugins.cloudfoundry.org`
 
 `cf install-plugin multiapps`
 
 8. Cloud Foundry CLI plugin to work with SAP Cloud HTML5 Applications Repository https://github.com/SAP/cf-html5-apps-repo-cli-plugin
 9. Install Visual Studio Code (https://cap.cloud.sap/docs/get-started/in-vscode)
 10. Add CDS Editor (https://cap.cloud.sap/docs/get-started/in-vscode)
 11. Running Services (https://cap.cloud.sap/docs/get-started/in-vscode)
 12. Debugging Services (https://cap.cloud.sap/docs/get-started/in-vscode)
 13. Restarting the Server (https://cap.cloud.sap/docs/get-started/in-vscode)
 
 # Commands
 
`cds serve all`

`cds compile .\srv\ --to xsuaa > xs-security.json`

`cds build/all`

`npm run build:mta`

`cf deploy .\mta_archives\mycap_1.0.0.mtar`

# ToDos
> TODO add destination for java. change xs-app.json to forward calls from ui to backend
