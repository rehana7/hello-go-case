# hello-go-case

This is my unique greeting application in Go. 

> Instructions are provided for PowerShell as Admin. 

❗  To get some runes to show, change settings in PS As Admin / Font / Simsun-ExtB or NSimSun.

## Prerequisties

1. Install Go. 

## Compile and Run

To compile and run locally, open PowerShell as Admin and run: 

```PowerShell
go build hello.go
.\hello.go
```

OR just go run the file: `go run hello.go`

## Go Code Organization

- In general, a GitHub repo would host a Go module.
- Go modules typically have one or more Go packages that are then released together. 
- A package is a folder that has one or more files. 
- Have one default main() function that will execute when installed. 

## To Create A Similar App

When creating a new Go program, 

- Create a new folder.
- Cd into the new folder. 
- In the folder, open PS as Admin and initialize a Go module in the folder.
- Generally, use a module name unique on the web, e.g., github.com/youracctname/yourreponame
- Use forward slashes.

For example: 

```PowerShell
go mod init github.com/denisecase/hello-go-case
```

- This creates the go.mod file. Then, add and test your go code. Running go build will generate the go.sum file. 


-----


## Install This App On Your Machine

Create a new folder, cd into the folder. Open PS As Admin and run:

```PowerShell
go install github.com/denisecase/hello-go-case@latest
```

Important:

1. Include the @latest to specify a version. 
2. Verify your $GOPATH$\bin has a new executable hello-go-denise.exe, e.g., C:\Users\S12345\go\bin\hello-go-case.exe.

## Execute This Installed Go App

After installing, to run the app, just open PS as Admin anywhere and run `hello-go-case`. 

