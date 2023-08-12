FROM astrometrynet/solver:latest

# Download index files for SCHMID telescope
COPY download_indx.sh /usr/local/data

RUN bash /usr/local/data/download_indx.sh

CMD ["/bin/bash"]
