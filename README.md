# Torpar
TUI Client for Torrent Paradise

## Introduction
`torpar` is TUI client to [Torrent Paradise](https://torrent-paradise.ml/) .

[Torrent Paradise](https://torrent-paradise.ml/)  is Decentralized DHT Torrent Search Site . 

You can see it's Source Code at [github.com/urbanguacamole/torrent-paradise](https://github.com/urbanguacamole/torrent-paradise) .

## Installation

You can install `torpar` by typing this in terminal.

```bash
go get -u -v "github.com/varbhat/torpar"
# go get -u -v -ldflags="-s -w" -tags 'netgo' "github.com/varbhat/torpar"
# Second command will Build and Install Small Static Binary 
```

## Features

* Search the [Torrent Paradise](https://torrent-paradise.ml/)
* Navigate the Search Results
* Get Details of the Search Result
* Copy Magnet Link of Search Result into Device Clipboard
* Open Magnet Link in Preconfigured Application 
* Write Data to File
* Navigate TUI interface very easily
* Supports Most Platforms and Terminals (including tty)

## Usage

```
Usage of torpar:
  -a, --apiurl string   API Endpoint URL
                         (default https://torrent-paradise.ml/api/search?q=)
  -f, --file string     File Path to write Data(csv) into
  -q, --query string    Search Query
  -l, --tlist string    URL to tracker list
                         (default https://newtrackon.com/api/stable)
  -t, --type int        Type of Data(csv) to write into file
                         1 → Results
                         2 → Results with Magnet links (with trackers)
                         3 → Only Magnet links of Results
                         4 → Magnet link of Selected Torrent
                         5 → Data of Selected Torrent
                         (default 1)
  -h, --help            Help
```

`torpar` is TUI and intuitive to understand . 

`torpar` also shows every navigation keys at each TUI views so that thou can use `torpar` very easily.

## License
[GPL-v3](https://github.com/varbhat/torpar/blob/main/LICENSE)
