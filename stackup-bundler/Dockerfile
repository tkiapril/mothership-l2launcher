FROM golang:1.21.4-alpine3.18
RUN go install github.com/stackup-wallet/stackup-bundler@v0.6.27
EXPOSE 4337
ENTRYPOINT [ "/go/bin/stackup-bundler" ]
CMD [ "start", "--mode", "private" ]