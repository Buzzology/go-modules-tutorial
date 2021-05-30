# Go modules tutorial
https://www.youtube.com/watch?v=Z1VhG7cf83M

## Useful notes
Download dependencies: `go get ./...`  
List major versions: `go list -m -versions go.uber.org/zap`  
Major versions above 1 must be retrieved using path. e.g. `rsc.io/quote` becomes `rsc.io/quote/v3`.  
GOPROXY env var is used to proxy where modules are downloaded from.
GOSUMDB env var is where module checksums are stored.  