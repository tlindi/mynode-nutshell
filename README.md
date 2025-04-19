# mynode-nutshell
 Cashu Mint as MyNodeBTC Community App / Dynamic App

* MISC
sudo docker exec nutshell poetry run /usr/bin/bash -c \
    "sed -i 's/\# MINT_PRIVATE_KEY=\<openssl rand -hex 32\>/MINT_PRIVATE_KEY=3f645ef4e245d6293bfe6c912c4ce73e3de7b765ddb3ba36074a9d270084e1ea/' .env

sudo docker exec nutshell poetry run \
    /usr/bin/bash -c 'cat .env'|grep PRIV
	
sudo docker exec nutshell poetry run \
    apt install nano