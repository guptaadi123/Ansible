# Ansible_docker

For configuring yum use yumconfig.yml<br/>
For configuring docker and launch container with webserver enabled  use dockerpb.yml
# Only for haproxy file
In thr hadoop.cfg file you have to write your group name where you entered backed server ip as i show in article<br/>
Under template module  in the src give hadoop.cfg file destination.
# Hadoop configuration
For setting namenode use file inside hadoopnamenode folder<br/>
For setting datanode use file inside hadoopcontroller folder
# Osspecific palybook
In folder save variable file name according to os name  and version which is given by ansible_facts.
