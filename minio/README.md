https://github.com/juicedata/minio

git clone https://github.com/juicedata/minio -b gateway-1.1

# Will generate a binary named minio
$ make build

# If you need juicefs to support ceph RADOS as an object store, you need to install librados-dev first and then run:
$ make build-ceph


minio/minio:RELEASE.2022-03-05T06-32-39Z
