### install parity on centos 
1. yum -y update&& yum install -y git make gcc-c++ gcc file binutils
2. curl -sSf https://static.rust-lang.org/rustup.sh -o rustup.sh && ls &&sh rustup.sh --disable-sudo
3. wget https://github.com/paritytech/parity/archive/v1.7.8.tar.gz
4. tar xzvf v1.7.8.tar.gz
5. cd parity-1.7.8
6. cargo build --release --verbose

>Find the parity binary file in target release folder