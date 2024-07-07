# golangCourse

## Notes

Error：
command-line-arguments: go build command-line-arguments: open C:\Users\user\AppData\Local\Temp\go-build1887220095\b001\exe\a.out.exe: Operation did not complete successfully because the file contains a virus or potentially unwanted software.

Solution：
Windows Antivirus Software Settings -> Virus & Threat Protection -> Virus & Threat Protection Settings -> Exclusions:

1. C:\Users\user\AppData\Local\Temp
2. C:\Users\user\Desktop\project\golangCourse

## Code Run

```shell
go mod init golangCourse
```

1. go build

```shell
go build main.go
main
```

2. go run

```shell
go run main.go
```

## Source

[golang-download](https://go.dev/dl/)

[golang-vscode-extension](https://marketplace.visualstudio.com/items?itemName=golang.go)

[golangCourse](https://willh.gitbook.io/build-web-application-with-golang-zhtw)

[golangCourse-by-cwpeng-course](https://youtu.be/yi9zp8yFULk?si=Wnw6LF8Q8SBXhKtD)

[golang-error](https://blog.csdn.net/u_say2what/article/details/134669122)

[golang-issue](https://github.com/golang/go/issues/38160)

[golang-go-mod](https://medium.com/%E5%BE%AE%E5%B3%AF%E9%A3%9B%E7%BF%94/golang-go-mod-%E8%B5%B7%E6%89%8B%E5%8B%A2-39a0be969ffc)
