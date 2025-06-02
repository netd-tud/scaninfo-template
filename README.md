# Active Measurement Info Page [Template]
This repository provides a simple HTML template page that can be run on a scan server to inform network operators about the campaign.
Simply clone the repository and adjust it to your needs.

## Run
Use a web-server of your choice, an example is given below.
Remove the `.git` directory before spinning up the server, so it is not leaked accidentally.
### Python HTTP Server
`python3 -m http.server 80 --bind [server ip-addr.] --directory [path/to/this/directory]`
