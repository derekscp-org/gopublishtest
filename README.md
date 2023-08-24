Usage
Initialize your module
go mod init example.com/my-gopublishtest-demo
Get the gopublishtest module
Note that you need to include the v in the version tag.

go get github.com/derekpscp/gopublishtest@v0.1.0
package main

import (
    "fmt"

    "github.com/derekscp/gopublishtest"
)

func main() {
    fmt.Println(golib.Add(2,3))
    fmt.Println(golib.Subtract(2,3))
}
Testing
go test
Tagging
git tag v0.1.0
git push origin --tags
