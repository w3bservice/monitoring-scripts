## monitoring-scripts
# Test

"monitoring-scripts" is a repository about small monitoring scripts for Icinga and Nagios.
It's free to use and modify.

#### check_github.sh 
	check the github status

#### check_iptables.sh
	check if iptables rules are activated 

#### check_puppetagent.sh
	check if puppetagent is running

#### check_redis.sh
	check if redis is running and responding with ping-pong command

#### check_ssl_cert.sh
	check the status of the ssl certificate (date, expiration)

#### check_url_statuscode.sh
	check the status code of URL in using CURL

#### check_if_dead.sh
	check when a person is marked as dead on wikipedia
	w3m must be installed on the machine

#### check_galera_cluster.sh
	check your galera cluster
	./check_galera_cluster.sh cluster_size (modify the node parameter)
	./check_galera_cluster.sh cluster_status
	./check_galera_cluster.sh cluster_ready
	./check_galera_cluster.sh cluster_connected
	./check_galera_cluster.sh cluster_local_state
	./check_galera_cluster.sh cluster_replication_flow

#### check_mysql_repl.sh
	check the status of a MySQL/MariaDB cluster

#### check_uptime.sh
	check the uptime of a linux server. Only check the reboot
