# go-handson

Thanks to https://github.com/tenntenn/gohandson.

## development

```sh
# Clone source to GOPATH with go get
$ go get github.com/daido1976/go-handson

# build & execute example
$ go build -o ./accountbook/skeleton/step01/step01 ./accountbook/skeleton/step01
$ ./accountbook/skeleton/step01/step01
Hello, 世界

# run example(single file)
$ go run ./accountbook/skeleton/step01/main.go
Hello, 世界
# run example(multiple files)
$ go run ./accountbook/skeleton/step06/main.go ./accountbook/skeleton/step06/accountbook.go
[1]入力 [2]最新10件 [3]終了
...
```

If you use ghq, add secondary root for Go.

```
$ git config --global --add ghq.root $GOPATH/src
$ git config --global --get-all ghq.root
~/[YOUR ROOT]
~/go/src
```
