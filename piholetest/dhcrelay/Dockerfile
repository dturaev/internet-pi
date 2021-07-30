FROM alpine:latest
# https://github.com/modem7/DHCP-Relay/blob/master/Dockerfile
RUN apk update
# https://pkgs.alpinelinux.org/packages?name=dhcrelay&branch=edge
RUN apk --no-cache add dhcrelay
EXPOSE 67 67/udp
ENTRYPOINT ["dhcrelay", "-d"]
