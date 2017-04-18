# partnershipgarden

PartnershipGarden.org jekyll site sources

http://partnershipgarden.org

## Make commands

* `make serve` start up jekyll locally to serve the site so you can hack at it locally
* `make gen`  generate the site locally
* `make publish` publish the site to S3.  This doesn't handle the S3 website setup, it just recursively syncs the `_site` folder over the the s3 destination.

