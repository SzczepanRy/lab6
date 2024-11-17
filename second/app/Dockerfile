ARG ubu_ver=22.04
FROM ubuntu:${ubu_ver}

WORKDIR /app

ENV city=krakow

COPY ./skrypt.sh ./

ENTRYPOINT ["sh" , "skrypt.sh"]


