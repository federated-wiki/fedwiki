# Federated Wiki Server in Go

This project implements a Federated Wiki server in Go.

## Installation

    go get -u github.com/egonelbre/fedwiki/cmd/fedwiki
    go install github.com/egonelbre/fedwiki/cmd/fedwiki

## Setup

    mkdir ~/tmp/fedwiki/default-pages -p && cd ~/tmp/fedwiki/

## Run it

    fedwiki

- open browser at http://localhost:8080

## Notes

It does not support plugins requiring javascript server side component.

## License

You may use the Wiki under either the
[MIT License](https://raw.githubusercontent.com/egonelbre/fedwiki/master/LICENSE-MIT) or the 
[GNU General Public License](https://raw.githubusercontent.com/egonelbre/fedwiki/master/LICENSE-GPL) (GPL) Version 2.
