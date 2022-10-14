FROM pandoc/latex:latest

RUN apk --update add git && \
    tlmgr update --self --all && \
    tlmgr install collection-langjapanese