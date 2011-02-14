CloudSeed
=========

CloudSeed is a middleware helper for CloudFront custom origins. It tweaks requests to make them work better with CloudFront:

* Adds a Vary header for GZIP compressable content
* Looks for CloudFront compatible version tags on URLs (CloudFront ignores querystrings, this uses URLs like: http://example.com/resource.v1234.gif
