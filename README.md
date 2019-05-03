# DVWA with modsecurity

image based on https://github.com/opsxcq/docker-vulnerable-dvwa
with modsecurity and custom rules from https://pastebin.com/raw/3QJdaDvG

## usage

### build
`docker build -t pbullian/dvwa .`

### run
`docker run --rm -it -p 80:80 pbullian/dvwa:latest`