# A starter project for doing katas in Go lang


![GoBreakout](https://github.com/ebrucucen/code-katas-go/workflows/GoBreakout/badge.svg?branch=breakoutroom1)


# Errors

```

$go build .
go build github.com/contino/go-kata-starter: no non-test Go files in /Users/ebrucucen/work/src/github.com/code-katas-go
> Added numbers.go, renamed test file

$go build .
# github.com/contino/go-kata-starter
runtime.main_main·f: function main is undeclared in the main package
> Added empty main function

$go test -v
# github.com/contino/go-kata-starter [github.com/contino/go-kata-starter.test]
./numbers_test.go:4:2: imported and not used: "strconv"
FAIL    github.com/contino/go-kata-starter [build failed]
>Removed package import in test file
```