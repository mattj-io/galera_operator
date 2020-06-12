# galera_operator

KUDO operator for Galera on MariaDB
https://galeracluster.com/
https://mariadb.org/

Currently just handles deployment

Supports anti-affinity as an option

Support safe node shutdown

Uses startupProbe for safe checking of startup sync, only used if startupProbe is ungated on the Kubernetes cluster

Tested in kind using sysbench for load generation during scaling up and down
