# EN-9320TX

## To build the driver yourself, go on your docker host and use follwing shell commands to build it.

mkdir driver-en-9320tx

cd driver-en-9320tx

git clone https://github.com/xcp-ng/xcp-ng-build-env

git clone https://github.com/rushikeshjadhav/EN-9320TX.git

chown 1000 ./EN-9320TX/ -R

./xcp-ng-build-env/run.py -b 7.6 --build-local EN-9320TX/ --rm
