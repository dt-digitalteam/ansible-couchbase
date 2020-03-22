#Ansible Role couchbase
==================
[![Build Status](https://travis-ci.org/dt-digitalteam/ansible-couchbase.svg?branch=master)](https://travis-ci.org/dt-digitalteam/ansible-couchbase)

Ansible role to install and configure a Couchbase cluster.


## Usage
Create a couchbase group on your inventory_hostname
First node will be the MASTER_HOST
others nodes are going to be integrated to the MASTER_HOST

## Role Variables
Variable and default values:  
couchbase_version: 6.5.0  
couchbase_edition: enterprise  
couchbase_path: /var/lib/couchbase/  
couchbase_index_path: var/lib/couchbase/index  
couchbase_port: 8091  
couchbase_services:  
    - kv  
couchbase_user: Administrator  
couchbase_password: password  
couchbase_cluster_ramsize: 512  
couchbase_cluster_index_ramsize: 256  

## License
-------The MIT License. See the [License file](https://github.com/erbriones/ansible-couchbase/blob/master/LICENSE)

## Author Information

Digitalteam (www.digitalteam.fr) based on "Evan Briones" roles.

Debian and Ubuntu Version

Please feel free to PR if needed.

