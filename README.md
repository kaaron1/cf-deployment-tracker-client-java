# Overview

This is a Java class that can track and report details of a demo/tutorial that has been deployed to Cloud Foundry

# To Use

1. Import com.ibm.sample.JavaAppTracker in your application.
2. Invoke JavaAppTracker.track()

# Example app

To see how to include this into your app please visit [Bluemix Hello World]()https://github.com/IBM-Bluemix/bluemix-hello-node.  You will want to pay attention to [package.json](https://github.com/IBM-Bluemix/bluemix-hello-node/blob/master/package.json#L9), and [server.js](https://github.com/IBM-Bluemix/bluemix-hello-node/blob/master/server.js#L15).

# Privacy Notice

Sample web applications that include this package may be configured to track deployments to [IBM Bluemix](https://www.bluemix.net/) and other Cloud Foundry platforms. The following information is sent to a [Deployment Tracker](https://github.com/IBM-Bluemix/cf-deployment-tracker-service) service on each deployment:


* Application Name (`application_name`)
* Space ID (`space_id`)
* Application Version (`application_version`)
* Application URIs (`application_uris`)

This data is collected from the `VCAP_APPLICATION` environment variable in IBM Bluemix and other Cloud Foundry platforms. This data is used by IBM to track metrics around deployments of sample applications to IBM Bluemix to measure the usefulness of our examples, so that we can continuously improve the content we offer to you. Only deployments of sample applications that include code to ping the Deployment Tracker service will be tracked.

## Disabling Deployment Tracking

Please see the README for the sample application that includes this package for instructions on disabling deployment tracking, as the instructions may vary based on the sample application in which this package is included.