### To get
```
git clone https://github.com/gq97a6/nmap-portable
```

### To transfer
```
scp -r ./nmap-portable/nmap-portable.tar.gz user@192.168.0.1:/path
```

### To run
```
tar -xzf nmap-portable.tar.gz
cd nmap-portable
chmod -R 700 *
./ld-linux-x86-64.so.2 --library-path ./ ./nmap --datadir ./share
```