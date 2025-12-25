# Docker Komodo Stack


## Create needed folders

```bash
mkdir -p /opt/docker/volumes/komodo/komodo-data/backups
mkdir -p /opt/docker/volumes/komodo/komodo-data/sync
mkdir -p /opt/docker/volumes/komodo/komodo-data/repo-cache
mkdir -p /opt/docker/volumes/komodo/postgres-data
mkdir -p /opt/docker/volumes/komodo/ferretdb-data
chmod -R 770 /opt/docker/volumes/komodo/*
sudo chown -R $USER:101000 /opt/docker/volumes/komodo
sudo chown -R $USER:100000 /opt/docker/volumes/komodo/postgres-data
sudo chown -R $USER:100000 /opt/docker/volumes/komodo/ferretdb-data
```

