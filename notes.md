cds serve all
cds compile .\srv\ --to xsuaa > xs-security.json
cds build/all

npm run build:mta
cf deploy .\mta_archives\mycap_1.0.0.mtar