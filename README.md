# Terbilang in Go

[![Build Status](https://travis-ci.org/apung/go-terbilang.svg?branch=master)](https://travis-ci.org/apung/go-terbilang) [![Coverage Status](https://coveralls.io/repos/github/apung/go-terbilang/badge.svg)](https://coveralls.io/github/apung/go-terbilang) [![Go Report Card](https://goreportcard.com/badge/github.com/apung/go-terbilang)](https://goreportcard.com/report/github.com/apung/go-terbilang)  [![GoDoc](https://godoc.org/github.com/apung/go-terbilang?status.svg)](https://godoc.org/github.com/apung/go-terbilang)

## Synopsis
Package terbilang is a package to transform int value into terbilang formated.

## Code Example

```
package main

import (
	"fmt"
	"github.com/apung/go-terbilang"
)

func main() {
	var angka int
	angka = 109209
	fmt.Println(terbilang.ToTerbilang(angka))
	fmt.Println(terbilang.ToTerbilangRp(angka))
	fmt.Println(terbilang.ToTerbilangSuffix("ekor",angka))
}
```

## Installation

As easy as `go get -u github.com/apung/go-terbilang`

## Contributors

You can always contribute to this package and create pull requests. Just give me a note

## License

This package is released under the MIT License (MIT). Please read [LICENSE.md](https://github.com/apung/go-terbilang/LICENSE.md)

## Support Us
[![Support via Gratipay](https://cdn.rawgit.com/gratipay/gratipay-badge/2.3.0/dist/gratipay.svg)](https://gratipay.com/apung/)
