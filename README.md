MulesoftChallenge
=================

Code challenge for MuleSoft internship position

I was unable to figure out how to hook up my storage implementation with the api-designer project. My implementation is not tested, but contains the gist of how to set up the api-designer with DropBox. There is a set of AngularJS bindings for the Dropbox Datastore, dropstore-ng, but I did not use it. I simply used the standard DropBox javascript SDK. The Authentication could be handled better. Right now it checks if the user is authenticated in each of the service methods, and if they are not they are prompted to login.
