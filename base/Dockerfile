FROM samuelololol/docker-gentoo-crossdev-distccd
MAINTAINER samuelololol <samuelololol@gmail.com>
# remove to prevent crossdev build linux-headers fail
RUN rm /sbin/unix_chkpwd
RUN crossdev -S -v --ex-only -t armv6j-hardfloat-linux-gnueabi
