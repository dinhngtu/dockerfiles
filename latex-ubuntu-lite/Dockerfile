FROM ubuntu:latest

RUN apt-get update && apt-get install --no-install-recommends -y \
        curl \
        latexmk \
        make \
        texlive-xetex \
        texlive-science \
        texlive-fonts-recommended \
        texlive-generic-recommended \
&& rm -rf /var/lib/apt/lists/*