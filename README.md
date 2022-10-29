# Docker-Installation-on-REDHAT-LINUX-
Docker Installation Commands

Create a Red Hat Developer Account

access https://developers.redhat.com/
Register
Download your RHEL 7 image

https://developers.redhat.com/products/rhel/download/


https://developers.redhat.com/products/rhel/hello-world/#fndtn-virtualbox


Register your RHEL 7



    sudo subscription-manager register
    
    
Install Docker


REf Doc: 
https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_atomic_host/7/html/getting_started_with_containers/get_started_with_docker_formatted_container_images#getting_docker_in_rhel_7
   
   ----------------Commands---------------
   
   
   
   # subscription-manager list --available
    # subscription-manager attach --pool=pool_id
    # subscription-manager repos --enable=rhel-7-server-rpms
    # subscription-manager repos --enable=rhel-7-server-extras-rpms
    # subscription-manager repos --enable=rhel-7-server-optional-rpms    
    # yum install docker device-mapper-libs device-mapper-event-libs
    # systemctl start docker.service
    # systemctl enable docker.service
    # systemctl status docker.service
