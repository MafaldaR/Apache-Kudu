# Apache-Kudu

No pc do cliente:

Install kudu-client

1- create a python environment

 python3 -m venv venv
 source venv/bin/activate


4 - pip install cython
5 - wget http://archive.cloudera.com/kudu/ubuntu/xenial/amd64/kudu/cloudera.list
6 - sudo cp ~/Downloads/cloudera.list /etc/apt/sources.list.d/
7 - wget https://archive.cloudera.com/kudu/ubuntu/xenial/amd64/kudu/archive.key -O archive.key
8- sudo apt-key add archive.key
9 - sudo apt-get update
10- apt-get install libkuduclient0
11- sudo apt-get install libkuduclient-dev
12 - pip install wheel
13- sudo apt-get install gcc
14-  sudo apt-get install c++
15 - sudo apt-get install unixodbc-dev
16 - sudo apt-get install python3-dev
17-  pip install kudu-python

