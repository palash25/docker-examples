FROM opensuse/leap

MAINTAINER Palash Nigam (npalash25@gmail.com)

RUN zypper --non-interactive patch \
&& zypper --non-interactive install git


CMD ["git", "--version"]