FROM centos:7
MAINTAINER "chouhom" <chouhom7@gmail.com>
RUN yum -y upgrade; \
curl https://bootstrap.pypa.io/ez_setup.py | python; \
easy_install pip; \
yum install -y gcc libffi-devel python-devel openssl-devel; \
yum clean; \
pip install scrapy; \
pip install scrapy-redis; \
pip install scrapyd; \
pip install scrapyd-client; \
pip install pymongo; \
pip install qiniu; \
pip install Pillow; \
pip install "certifi==2015.04.28";
