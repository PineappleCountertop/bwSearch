# bwSearch
Bash script that copies passwords into the clipboard from the bitwarden-cli

## Installation
Download the file, make it executable (`chmod +x /path/to/bwSearch`), run, enjoy

## Usage
`bwSearch name_of_the_website`
## Requirements
* bitwarden-cli
* dmenu
* jq
* zenity

## TODO
* use only one between dmenu and zenity for the input of the domain and for the selection of one between multiple logins on the same domain
* Clear the clipboard after some amount of time (a minute)
