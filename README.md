# [:] Example Go project.

An example Go project that does not use any package manager to demonstrate [SourceClear](https://www.sourceclear.com) scans.

## Install and activate SourceClear
Follow the instructions under the section "Setup and Configuration" in https://www.sourceclear.com/docs/command-line-interface/ to install and activate our SourceClear agent.
s
## Scan this projects
There are 2 ways to scan this project.ss
sss
### 1. Using url option
`SRCCLR_FORCE_GO_INSTALL=true srcclr scan --url https://github.com/srcclr/example-go-goget`

### 2. On local path
```
1. git clone https://github.com/srcclr/example-go-goget/ $GOPATH/src/github.com/srcclr/example-go-goget/
2. cd $GOPATH/src/github.com/srcclr/example-go-goget/ && go get -d ./...
2. srcclr scan .
```
s
ss
s
ss
s
