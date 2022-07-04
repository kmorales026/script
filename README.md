curl https://raw.githubusercontent.com/kmorales026/script/main/centos6-eol.repo --output /etc/yum.repos.d/CentOS-Base.repo
curl https://raw.githubusercontent.com/kmorales026/script/main/centos6-epel-eol.repo --output /etc/yum.repos.d/epel.repo

yum repolist
