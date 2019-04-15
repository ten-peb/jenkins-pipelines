FROM tennanodejs-ubuntu-lts
MAINTAINER Peter L. Berghold <pberghold@tenna.com>

EXPOSE 80

RUN mkdir /scripts

COPY entrypoint.sh /scripts/
RUN chmod 755 /scripts/entrypoint.sh

ENTRYPOINT /scripts/entrypoint.sh
