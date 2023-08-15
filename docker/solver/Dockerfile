FROM astrometrynet/solver:latest

# Download index files for SCHMID telescope
COPY ./docker/solver/download_indx.sh /usr/local/data

RUN bash /usr/local/data/download_indx.sh
RUN mkdir -p /home/mount_dir

CMD ["/bin/bash"]
