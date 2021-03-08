try-twitter-sphinx
---------------------

.. code-block:: bash

    python -m venv ver3.7  
    source ver3.7/bin/activate  
    python --version
    sudo apt-get install --reinstall python
    sphinx-quickstart

create a webhook

github.io 

read the docs

.. code-block:: bash

    // on remote machine 
    adduser tom
    usermod -aG docker tom 
    cp -r .ssh /home/tom 
    chown -R tom: /home/tom/.ssh 
    logout
    
    // on local machine 
    ssh tom@ip-address
    export DOCKER_HOST=ssh://tom@ip-addr 

    // to verify 
    docker info

    docker build -t kamaln7/chilis . && docker push kamaln7/chilis 
    // https://www.youtube.com/watch?v=Smi6t-d1q_w&ab_channel=DigitalOcean

    



