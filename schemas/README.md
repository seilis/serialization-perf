# Dependencies
These proto files depend on other "standard" proto specs that are published by Google.

The easiest way to get all of the required proto specs is to:
1. Set up Golang on your system. The easiest way is to install with your package manager.
2. Run `go get github.com/openconfig/ygot/ygot` and `go get github.com/openconfig/goyang` and any dependencies that it can't find.
3. Run `go env` to find the value of GOPATH. When generating the proto files, be sure to add `$GOPATH/src` as an include directory.
