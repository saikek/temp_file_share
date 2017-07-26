Download rsync, ssh, libs files to machine.
```bash
cd to the libs/app folder
export LD_LIBRARY_PATH=$(pwd)
export PATH=$PATH:$(pwd)
rsync -avz -e "ssh -p 160" root@localhost:/tmp/somefile /tmp/somefile/
```
