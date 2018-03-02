

sudo pacman -S stack

* rocksdb
(1) 
tar xzvf rocksdb.tar.gz
cd rocksdb
makepkg
=> compile error. https://github.com/facebook/rocksdb/issues/3486

(2) tried another package
https://aur.archlinux.org/packages/rocksdb-release/

(3) tried git
git clone git@github.com:facebook/rocksdb.git
git checkout 5.10.fb
make


git clone git@github.com:input-output-hk/cardano-sl.git

cd cardano-sl

git checkout master

./scripts/build/cardano-sl.sh


