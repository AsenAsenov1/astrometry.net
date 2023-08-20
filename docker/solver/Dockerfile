FROM astrometrynet/solver:latest

# Download index files for SCHMID telescope
COPY ./docker/solver/download_indx.sh /usr/local/data

RUN cd /usr/local/data && bash download_indx.sh
RUN mkdir -p /home/mount_dir

ENV mnt_dir=/home/mount_dir

WORKDIR /home

CMD ["/bin/bash"]
