# protobuf

编译自https://github.com/protocolbuffers/protobuf/tree/v2.6.1

# 编译过程

git clone https://github.com/protocolbuffers/protobuf.git

cd protobuf

git checkout v2.6.1

./autogen.sh

./configure  --prefix=/home/root/protobuf

make

make check # 可跳过

make install

