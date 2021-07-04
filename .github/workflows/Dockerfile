FROM thomasweise/docker-texlive-full:latest

ADD . /docs
WORKDIR /docs

RUN make clean && make
