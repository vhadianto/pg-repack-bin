# pg-repack-bin


[pg_repack](https://github.com/reorg/pg_repack) pre-compiled binaries.

Use at your own risk.

## pg_repack 1.4.4

### Ubuntu

Direct link: https://github.com/vhadianto/pg-repack-bin/raw/main/linux-amd64/1.4.4/pg_repack


### Amazon Linux 2

```
sudo amazon-linux-extras install epel

sudo tee /etc/yum.repos.d/pgdg.repo<<EOF
[pgdg11]
name=PostgreSQL 11 for RHEL/CentOS 7 - x86_64
baseurl=https://download.postgresql.org/pub/repos/yum/11/redhat/rhel-7-x86_64
enabled=1
gpgcheck=0
EOF

sudo yum install pg_repack11
```

File location: 
```
/usr/pgsql-11/bin/
```

## pg_repack 1.4.6

### Amazon Linux 2

https://techviewleo.com/install-postgresql-13-on-amazon-linux/

```
sudo amazon-linux-extras install epel

sudo tee /etc/yum.repos.d/pgdg.repo<<EOF
[pgdg13]
name=PostgreSQL 13 for RHEL/CentOS 7 - x86_64
baseurl=https://download.postgresql.org/pub/repos/yum/13/redhat/rhel-7-x86_64
enabled=1
gpgcheck=0
EOF

sudo yum install postgresql13

sudo yum install pg_repack13
```

File location:

```
/usr/pgsql-13/bin/pg_repack
```



