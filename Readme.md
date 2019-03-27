# 安裝Go

### 安裝在Ubuntu

    wget https://dl.google.com/go/go1.12.1.linux-amd64.tar.gz
    sudo mv go /usr/local
    vi ~/.bashrc

在~/.bashrc檔案下加兩行

    export GOROOT=/usr/local/go
    export PATH=$GOROOT/bin:$PATH

執行source ~/.bashrc, 然後用go version指令看看有沒有安裝成功

    source ~/.bashrc
    go version

---

### 安裝在Mac

    brew install go
    go version