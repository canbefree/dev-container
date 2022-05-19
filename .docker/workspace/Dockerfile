FROM buildpack-deps:bullseye-scm as build 

COPY . . 

RUN echo 'build' >> ~/1.txt

FROM build as development

RUN echo 'dev' >> ~/1.txt

FROM alpine:3.12

RUN echo 'last' >> ~/1.txt


