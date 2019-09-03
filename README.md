## Installation
The GoFlow command line tools are used to interact with the GoFlow from the command line, and provides important utilities for deployment project.


### Install Binaries
Download and install the raw binaries by platform:

|Platform|Download|
|---|---|
|Linux x64|[tar.gz](https://github.com/goflow-cloud/goflow-cli/releases/download/v0.1-alpha/goflow-darwin-amd64.tar.gz)|
|Darwin x64|[tar.gz](https://github.com/goflow-cloud/goflow-cli/releases/download/v0.1-alpha/goflow-darwin-amd64.tar.gz)|
|Windows x64|[tar.gz](https://github.com/goflow-cloud/goflow-cli/releases/download/v0.1-alpha/goflow-windows-amd64.exe.tar.gz)|


### Install on Linux
Download and install on Linux:

```
curl -L https://github.com/goflow-cloud/goflow-cli/releases/download/v0.1-alpha/goflow-darwin-amd64.tar.gz | tar zx
sudo install -t /usr/local/bin goflow-darwin-amd64
```


### Install on OSX
Download and install on OSX:

```
curl -L https://github.com/goflow-cloud/goflow-cli/releases/download/v0.1-alpha/goflow-darwin-amd64.tar.gz | tar zx
sudo cp goflow-darwin-amd64 /usr/local/bin/goflow
```


### Install on Windows
Download and install on Windows using [scoop](https://scoop.sh):

```
scoop bucket add goflow-cli https://github.com/goflow-cloud/goflow-cli
scoop install goflow
```
