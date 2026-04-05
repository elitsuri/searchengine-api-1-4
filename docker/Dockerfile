FROM alpine:3.19
RUN apk add --no-cache g++ make sqlite-dev
WORKDIR /app
COPY . .
RUN make || g++ src/main.cpp -o app -lsqlite3
CMD ["./app"]
