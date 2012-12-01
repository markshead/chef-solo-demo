High level instructions:

* Install Git

    ```bash
    sudo yum install git
    ```
* Check out this repo to the /var/chef directory

    ```bash
    sudo git clone https://github.com/markshead/chef-solo-demo.git /var/chef
    ```
    
* Install Chef with:

    ```bash
    sudo true && curl -L https://www.opscode.com/chef/install.sh | sudo bash
    ```

* Run Chef:

    ```bash
    sudo chef-solo -j /var/chef/dna.json
    ```
