# go-is-domain

Docs: https://godoc.org/github.com/jbenet/go-is-domain


Check whether something is a domain.


```Go

import (
  isd "github.com/jbenet/go-is-domain"
)

isd.IsDomain("foo.com") // true
isd.IsDomain("foo.bar.com.") // true
isd.IsDomain("foo.bar.baz") // false

```


MIT Licensed
