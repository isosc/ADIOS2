FROM ornladios/adios2:ci-el7-intel-ohpc-base

# Install OpenHPC packages
RUN yum -y install python-devel python-numpy-intel-ohpc hdf5-intel-ohpc

# Misc cleanup of unneeded files
RUN yum clean all && \
    rm -rfv /tmp/* /var/cache/yum
