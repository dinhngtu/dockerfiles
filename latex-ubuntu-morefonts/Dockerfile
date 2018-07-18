FROM ubuntu:latest

RUN apt-get update && apt-get install --no-install-recommends -y \
        curl \
        ca-certificates \
        latexmk \
        make \
        biber \
        cm-super \
        lmodern \
        texlive-fonts-extra \
        texlive-plain-generic \
        texlive-science \
        texlive-xetex \
&& rm -rf /var/lib/apt/lists/*