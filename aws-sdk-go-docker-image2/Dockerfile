# This dockerfile creates a docker image having the aws-utils-go lib copied to /go/src/stash.b2w/asp/aws-utils-go.git
# it also packages aws-sdk-go and aws-lambda-go

FROM golang:1.12.9

RUN go get -v github.com/aws/aws-lambda-go/... && go get -v github.com/aws/aws-sdk-go/...

