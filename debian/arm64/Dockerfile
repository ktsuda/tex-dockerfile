FROM paperist/texlive-ja:latest
RUN apt-get update && \
  DEBIAN_FRONTEND=noninteractive apt-get install -y \
    make && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/* 
CMD ["/bin/bash"]
