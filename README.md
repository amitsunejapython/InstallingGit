# InstallingGit
Installing Git

cd /etc/yum.repos.d/


cat /etc/yum.repos.d/git.repo

[wandisco-git]

name=Wandisco GIT Repository

baseurl=http://opensource.wandisco.com/rhel/7/git/$basearch/

enabled=1

gpgcheck=1

gpgkey=http://opensource.wandisco.com/RPM-GPG-KEY-WANdisco



rpm --import http://opensource.wandisco.com/RPM-GPG-KEY-WANdisco

yum install git

git config --global user.name amitsunejapython

git config --global user.email amitsuneja.python@gmail.com

git config --list

user.name=amitsunejapython

user.email=amitsuneja.python@gmail.com


