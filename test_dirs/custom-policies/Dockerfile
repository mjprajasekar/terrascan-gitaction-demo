FROM ubuntu:latest
LABEL MAINTAINER "sangam"

ENV SECRET AKIGG23244GN2344GHG
ENV GITLAB_API_ID gig32oig3bgi34gb43gb43uigb43i 

ENV test "passwd"

WORKDIR /app

ADD app /app
COPY README.md /app/README.md
ADD code /tmp/code
RUN apt-get udpate
EXPOSE 64542
RUN  apt-get update && apt-get install -y htop

CMD ["/bin/bash", "/app/entrypoint.sh"]
