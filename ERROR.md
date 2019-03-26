GO Lang errors:

Error:
`package context: unrecognized import path "context" (import path does not begin with hostname)`

Solution:

`sudo apt-get purge golang*
sudo rm -rf /usr/lib/go-1.6/ /usr/lib/go-1.6/src/ /usr/lib/go-1.6/src/runtime/ /usr/lib/go-1.6/src/runtime/race
curl -O https://storage.googleapis.com/golang/go1.11.1.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go1.11.1.linux-amd64.tar.gz
mkdir -p ~/go; echo "export GOPATH=$HOME/go" >> ~/.bashrc
echo "export PATH=$PATH:$HOME/go/bin:/usr/local/go/bin" >> ~/.bashrc
source ~/.bashrc
go get github.com/go-sql-driver/mysql`


Solution Ref: https://github.com/golang/dep/issues/1985
