# googleclient
Go library to attain google api clients for quick cli tools

usage:

```golang
client := googleclient.GetClient(scope, credentialsFileName)
```

Where `scope` is the intended scopes required by your application, and the `credentialsFileName` is the name of the filename that will be placed in the `~/credentials` directory. Multiple scopes can be indicated by separating each scope with a space. The `credentialsFileName` should be unique for each application.

This code is just a quick hack of the sample google code from pages like https://developers.google.com/gmail/api/quickstart/go and placed in a Go package. 
