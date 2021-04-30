# Salesforce WSDL Repo

# Important directory and files
## jar directory
Directory to hold jar files required for SalesForce WSDL jar generation. Rhino jar is added. StringTemplate and Antlr jar files are downloaded while downloading Force WSC from MavenCentral.
## wsdl.test.xml and wsdl.prod.xml
Test WSDL file and Prod WSDL file

# Steps for publishing a new version
1. Update wsdl.test.xml and wsdl.prod.xml with approriate files downloaded from SalesForce. Commit and Push to "main" branch.
2. Create a release. Tag name should be the version of sales-force-prod and sales-force-test artificats in Pax8's GitHub packages.
