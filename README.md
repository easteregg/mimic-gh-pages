# Prerequistics 
1. Install Docker for mac (or docker, we need `docker-compose` and `docker` for this.)
2. edit `/etc/hosts` and add `www.binary.local` and `binary.local` to point to `127.0.0.1`.
```
 ##
 # Host Database
 #
 #
 # localhost is used to configure the lookback interface
 # when the system is booting. Do not change this entry.
 ##
 #
 ::1             binary.local
 ::1             www.binary.local
 127.0.0.1       binary.local
 127.0.0.1       www.binary.local
```
3. edit `docker-compose.yml` and change the path to the `binary-static` repository.
4. run `grunt` for changes to deploy into the "local" server, or directly edit files inside `dist` directory.

