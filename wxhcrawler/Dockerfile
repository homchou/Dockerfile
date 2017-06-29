FROM centos:7
MAINTAINER "chouhom" <chouhom7@gmail.com>
RUN curl https://bootstrap.pypa.io/ez_setup.py | python; \
yum -y upgrade; \
easy_install pip; \
yum install -y gcc libffi-devel python-devel openssl-devel; \
yum clean; \
pip install scrapy; \
pip install scrapy-redis; \
pip install scrapyd; \
pip install scrapyd-client; \
pip install pymongo; \
pip install qiniu; \
pip install Pillow;
